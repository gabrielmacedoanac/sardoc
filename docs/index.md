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

 - **HTML5** puro e bibliotecas em **Javascript**
 - **Flatgithub** #flatdata para integração contínua (automatizada)

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

## Fórum (projeto A3)

 - **Discourse**

## Evolução do processo de Policy File (projeto A6)

 - Banco de Policy Files

## Próximos passos

1. Validação com outros usuários
1. Solicitação de ferramenta - contrato STI para **Elastic Search**