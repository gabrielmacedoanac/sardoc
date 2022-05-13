---
title: SAR Doc
tags: 
  - projeto
  - anac 
  - flatdata  
  - markdown 
  - git 
  - opensource 
  - knowledgegraph 
  - normas
hide:
  - navigation
---

## Plotly

Ver também: 

- https://chart-studio.plotly.com/~jackp/17434/drone-flight-paths-in-plotly-and-python
- https://dash.gallery/dash-turbine-maintenance/
- https://dash.gallery/dash-nlp/
- https://github.com/plotly/dash-pivottable

<iframe id="igraph1" scrolling="no" style="border:none;" seamless="seamless" src="https://plotly.com/~tim.lichtenberg/686.embed" height="525" width="100%"></iframe>
<iframe id="igraph2" scrolling="no" style="border:none;" seamless="seamless" src="https://plotly.com/~chris/1638.embed" height="525" width="100%"></iframe>

### Acidentes na aviação
<iframe id="igraph3" scrolling="no" style="border:none;" seamless="seamless" src="https://plotly.com/~s3370523/28.embed" height="525" width="100%"></iframe>


## Vega-lite

```vegalite
{
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "description": "An interactive visualization of connections among major U.S. airports in 2008. Based on a U.S. airports example by Mike Bostock.",
  "layer": [
    {
      "mark": {
        "type": "geoshape",
        "fill": "#ddd",
        "stroke": "#fff",
        "strokeWidth": 1
      },
      "data": {
        "url": "https://vega.github.io/vega-tutorials/airports/data/us-10m.json",
        "format": {"type": "topojson", "feature": "states"}
      }
    },
    {
      "mark": {"type": "rule", "color": "#000", "opacity": 0.35},
      "data": {"url": "https://vega.github.io/vega-tutorials/airports/data/flights-airport.csv"},
      "transform": [
        {"filter": {"param": "org", "empty": false}},
        {
          "lookup": "origin",
          "from": {
            "data": {"url": "https://vega.github.io/vega-tutorials/airports/data/airports.csv"},
            "key": "iata",
            "fields": ["latitude", "longitude"]
          }
        },
        {
          "lookup": "destination",
          "from": {
            "data": {"url": "https://vega.github.io/vega-tutorials/airports/data/airports.csv"},
            "key": "iata",
            "fields": ["latitude", "longitude"]
          },
          "as": ["lat2", "lon2"]
        }
      ],
      "encoding": {
        "latitude": {"field": "latitude"},
        "longitude": {"field": "longitude"},
        "latitude2": {"field": "lat2"},
        "longitude2": {"field": "lon2"}
      }
    },
    {
      "mark": {"type": "circle"},
      "data": {"url": "https://vega.github.io/vega-tutorials/airports/data/flights-airport.csv"},
      "transform": [
        {"aggregate": [{"op": "count", "as": "routes"}], "groupby": ["origin"]},
        {
          "lookup": "origin",
          "from": {
            "data": {"url": "https://vega.github.io/vega-tutorials/airports/data/airports.csv"},
            "key": "iata",
            "fields": ["state", "latitude", "longitude"]
          }
        },
        {"filter": "datum.state !== 'PR' && datum.state !== 'VI'"}
      ],
      "params": [{
        "name": "org",
        "select": {
          "type": "point",
          "on": "mouseover",
          "nearest": true,
          "fields": ["origin"]
        }
      }],
      "encoding": {
        "latitude": {"field": "latitude"},
        "longitude": {"field": "longitude"},
        "size": {
          "field": "routes",
          "type": "quantitative",
          "scale": {"rangeMax": 1000},
          "legend": null
        },
        "order": {
          "field": "routes",
          "sort": "descending"
        }
      }
    }
  ],
  "projection": {"type": "albersUsa"},
  "width": 900,
  "height": 500
}
```

```vegalite
{
  "description": "A simple bar chart with embedded data.",
  "data": {
    "values": [
      {"a": "A", "b": 28}, {"a": "B", "b": 55}, {"a": "C", "b": 43},
      {"a": "D", "b": 91}, {"a": "E", "b": 81}, {"a": "F", "b": 53},
      {"a": "G", "b": 19}, {"a": "H", "b": 87}, {"a": "I", "b": 52}
    ]
  },
  "mark": {"type": "bar", "tooltip": true},
  "encoding": {
    "x": {"field": "a", "type": "nominal", "axis": {"labelAngle": 0}},
    "y": {"field": "b", "type": "quantitative"}
  }
}
```


```vegalite
{
    "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
    "height": 300,
    "data": {
      "url": "https://raw.githubusercontent.com/timvink/mkdocs-charts-plugin/main/docs/assets/charts/data/us-10m.json",
      "format": {
        "type": "topojson",
        "feature": "counties"
      }
    },
    "transform": [{
      "lookup": "id",
      "from": {
        "data": {
          "url": "https://raw.githubusercontent.com/timvink/mkdocs-charts-plugin/main/docs/assets/charts/data/unemployment.tsv"
        },
        "key": "id",
        "fields": ["rate"]
      }
    }],
    "projection": {
      "type": "albersUsa"
    },
    "mark": {"type": "geoshape", "tooltip": true},
    "encoding": {
      "color": {
        "field": "rate",
        "type": "quantitative"
      }
    }
  }
```

```vegalite
{
  "$schema": "https://vega.github.io/schema/vega-lite/v4.json",
  "config": {
    "view": {
      "continuousHeight": 300,
      "continuousWidth": 400
    }
  },
  "data": {
    "url": "https://vega.github.io/vega-datasets/data/cars.json"
  },
  "encoding": {
    "color": {
      "field": "Origin",
      "type": "nominal"
    },
    "x": {
      "field": "Horsepower",
      "type": "quantitative"
    },
    "y": {
      "field": "Miles_per_Gallon",
      "type": "quantitative"
    }
  },
  "mark": "point"
}
```

```vegalite
{
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "description": "Stock prices of four large companies as a small multiples of area charts.",
  "transform": [{"filter": "datum.symbol !== 'GOOG'"}],
  "width": 300,
  "height": 40,
  "data": {"url": "data/stocks.csv"},
  "mark": "area",
  "encoding": {
    "x": {
      "field": "date",
      "type": "temporal",
      "title": "Time",
      "axis": {"grid": false}
    },
    "y": {
      "field": "price",
      "type": "quantitative",
      "title": "Price",
      "axis": {"grid": false}
    },
    "color": {
      "field": "symbol",
      "type": "nominal",
      "legend": null
    },
    "row": {
      "field": "symbol",
      "type": "nominal",
      "title": "Symbol"
    }
  }
}
```



```vegalite
{
  "schema-url": "https://raw.githubusercontent.com/timvink/mkdocs-charts-plugin/main/docs/assets/charts/data/basic_bar_chart.json"
}
```



## JSON-LD e Schema.org

Abra `arquivo.md` e adicione os metadados. Isso permite que você coloque metadados no topo dos arquivos markdown na sintaxe YAML. Esses metadados devem estar entre 3 hífens acima e abaixo. [Fonte: 1](https://software.ac.uk/resources/guides/adding-schema-dot-org)

```
---
layout: tutorial
schemadotorg:
 "@context": http://schema.org/
 "@type": CreativeWork
 about: "This is a training material about schema.org"
 audience:
   - "@type": Audience
     name: WebMaster
 genre: "Tutorial"
 name: "Adding schema.org to your website"
 author: ["Fred Dibnah", "Niall Beard"]
 contributor:
   - "@type": Person
     name: "Frank Spencer"
 description: "In order to establish higher search results for online resources"
 keywords: ["schemaorg", "TeSS"]
 license: CC-BY 4.0
 version: 1.0
---
```

### Meu tutorial incrível

Este é o meu tutorial. É ótimo porque

- É grátis
- Está nas Páginas do Github
- Tem schema.org




# Projeto Setorial: Gestão de normativos de aeronavegabilidade (out/2021)

##  Entregas

 - **A1 = Prototipação de Base de dados + Busca + interfaces**;
 - A2 = Levantamento e padronização de fontes de dados - Projeto piloto (GTNI);
 - **A3 = Implementação de fórum com integração das informações do SEAM (desejável)**;
 - A4 = Interface eletrônica para a promoção de busca a material acadêmico;
 - A5 = Repositório de discussões técnicas (informais);
 - **A6 = Proposta de evolução do processo de Policy File**.

## Problema

**Como melhorar a recuperação de informações de normativos de aeronavegabilidade?**

## Conceitos

 - Recuperação de informações (bases de dados e interfaces)

```
[ Dado -> Conector -> Dado ]
```
```
[ Ferramenta de busca ]
```

 - Controle e versionamento de dados para processo colaborativo gerenciável

```
GIT
```

 - Envolvimento dos especialista do domínio

```
Servidores da SAR
```

## Dados conectados

1. Preparar os Stakeholders: formar os usuários para criar e manter os dados conectados
1. Selecionar o conjunto de dados: definir quais dados serão publicados e conectá-los para reuso
1. Modelar os dados: representar os dados e relações
1. Nomear bons URIs
1. Padronizar vocabulário para publicação
1. Preparar interface para humanos e máquinas
1. Reconhecer a função social: comprometimento do publicador ao longo do tempo

Fonte: _Adaptado de_ MARTINS (2018)[1] - https://repositorio.unb.br/handle/10482/34816

## Recuperação de informações (entrega A1)

### Tabelas

 - **HTML5**, bibliotecas em **Javascript** e sistemas dedicados (Datasette)
#### Teste Datasette

<iframe src="https://glitch.com/embed/#!/embed/wool-fringe-avatar?path=regulamentos.csv&previewSize=100" width="100%" class="wide max-h-[35rem]" style="height: 90vh;"></iframe>

#### Teste Flatgithub

 - **Flatgithub** #flatdata para integração contínua (automatizada)

 <iframe title="Flatgithub ANAC - #flatdata" src="https://flatgithub.com/gabrielmacedoanac/flat-data-anac" width="100%" class="wide max-h-[35rem]" style="height: 90vh;"></iframe>

### Grafos

**Visualização de grafos interativos** para a descoberta de informações.

 - **Kumu.io**
 - **GraphCommons**

#### Teste [Kumu.io](https://kumu.io/anac/anac)

* Acesse em tela cheia em: https://kumu.io/anac/anac
<iframe title="Knowledge Graph ANAC - Kumu.io" src="https://embed.kumu.io/afa1fffb10177f3cf7eb39d236802fdf" width="100%" class="wide max-h-[35rem]" style="height: 90vh;"></iframe>

#### Teste [GraphCommns](https://graphcommons.com/graphs/56d77bb0-8668-4e0a-ac80-374b9d79afa1)

* Acesse em tela cheia em: https://graphcommons.com/graphs/56d77bb0-8668-4e0a-ac80-374b9d79afa1
<iframe src="https://graphcommons.com/graphs/56d77bb0-8668-4e0a-ac80-374b9d79afa1/embed?show=Graph&fitgraph=true" frameborder="1" width="100%" class="wide max-h-[35rem]" style="height: 90vh;" allowfullscreen></iframe>

### Sites estáticos

 - **MkDocs**
 - **WikiANAC**

## Fórum (entrega A3 mar/2022)

 - **Discourse**
   - Imagem:
 ![discourseANAC](https://i.imgur.com/BnOIbU2.png)
   - Iframe:
<iframe src="https://homologacao-discourse.anac.gov.br" frameborder="1" width="100%" class="wide max-h-[35rem]" style="height: 90vh;" allowfullscreen></iframe>

## Evolução do processo de Policy File (entrega A6)

 - Banco de Policy Files

## Próximos passos

1. Validação com outros usuários
1. Solicitação de ferramenta - contrato STI para **Elastic Search**

 - **Meilisearch** (protótipo entregue em mar/2022 - alternativa ao Elastic Search)
 ![Meilisearch](https://i.imgur.com/syqwr7k.png)
