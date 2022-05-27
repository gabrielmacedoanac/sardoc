---
title: Flat Data - Instruções
tags: 
  - projeto
  - anac 
  - flatdata  
  - git 
  - normas
hide:
  - navigation
#  - toc
---

**Apresentação**

O Flat Data evita a complexidade de muitas ferramentas de ETL em favor de algo simples e flexível o suficiente para muitas cargas de trabalho, sem requerer que a infraestrutura seja mantida pelos usuários.[^1]

A ferramenta entrega várias funcionalidades para explorar os dados, tais como:

- Filtragem múltipla
- Ordenação
- Cabeçalhos e colunas fixas
- Diferenças entre versões específicas que alteraram os dados

## Bases disponíveis

Os dados abertos da ANAC podem ser pesquisados e exibidos de forma versionada.
Abra o [visualizador _Flat Viewer_ em tela cheia](https://flatgithub.com/gabrielmacedoanac/flat-data-anac?filename=regulamentos.tsv).

**Tabelas disponíveis**

**Regulamentos (RBAC, IS, Resoluções, Portarias, Decisões...)**:
- [Todos os regulamentos](https://flatgithub.com/gabrielmacedoanac/flat-data-anac?filename=regulamentos.tsv)
- RBAC
- IS

**Produtos aeronáticos (Aeronaves, Drones, Motores...)**:
- Aeronaves
- Drones
- Motores

**Profissionais credenciados**:
- Profissionais de Aeronavegabilidade
- 


## Tutorial

### Opções disponíveis no topo da ferramenta

![](https://user-images.githubusercontent.com/83769557/170712636-bdd38347-2853-45ef-a0e6-1d0585db816e.png)

**Repository**

![](https://user-images.githubusercontent.com/83769557/170711558-c477f10e-c288-49f3-8c5e-937e0471c915.png)

Indica o local onde estão armazenados as tabelas de dados, o controle de versão e as automações para tratamento das informações. É adequado para o acesso aos dados brutos e granulados.

**Data file**

![](https://user-images.githubusercontent.com/83769557/170711993-c499f736-e220-4aaa-baa4-c64ab243c3f9.png)

Indica as tabelas de dados disponíveis. Use para selecionar o conjunto de dados que você quer pesquisar.

**Commit**

![](https://user-images.githubusercontent.com/83769557/170712391-88b1538b-274a-4668-a475-1a91e9cbbb31.png)

Indica as versões das tabelas de dados. Use para acessar o histórico dos dados.

![](https://user-images.githubusercontent.com/83769557/170712765-b2077234-a3ec-4081-ad05-f7e71ce12604.png)

Selecione uma versão para voltar no histórico:

![](https://user-images.githubusercontent.com/83769557/170713235-1fcdb35d-0c5f-46a8-8bad-9c43141a7b4f.png)


**Data source**

![](https://user-images.githubusercontent.com/83769557/170713913-9926154c-40eb-4bce-be09-8c2127b45e2c.png)

Indica a fonte primária das tabelas de dados. Use para acessar a fonte original de onde os dados foram coletados.


### Opções disponíveis no rodapé da ferramenta

![](https://user-images.githubusercontent.com/83769557/170714452-20df6297-021a-4167-87c9-e3a32da80e9a.png)

**Navegação sobre os dados alterados**

![](https://user-images.githubusercontent.com/83769557/170714625-ce15fb5d-36b1-4088-b6b6-8d430ff06545.png)

Utilize as setas para navegar sobre as alterações nos dados históricos das tabelas. Por padrão são exibidas as alterações entre o dado mais atual (ou o conjunto selecionado) e o imediatamente anterior.

```
Changes: 
+113  rows
[*]72 rows
-60   rows

Showing 94.767 rows
```

Isso quer dizer, por exemplo, que a tabela **drones** passou pelas seguintes alterações:

```
Alterações: 
+113  linhas novas
[*]72 linhas alteradas
-60   linhas removidas

Exibindo 94.767 linhas
```

Linha nova:

![](https://user-images.githubusercontent.com/83769557/170716984-69cc8d67-deb7-4ebb-888b-ba8c1139237e.png)

Linha alterada:

![](https://user-images.githubusercontent.com/83769557/170716742-3306c6b1-5acc-4d39-8346-0bee89904524.png)

Linha removida:

![](https://user-images.githubusercontent.com/83769557/170716802-e19922eb-0aa0-4717-8a09-cb4b47803507.png)

**Exportação dos dados**

Escolhe entre os formatos CSV ou JSON para exportar a visualização atual dos dados. O arquivo final considera os filtros aplicados na visualização.

![](https://user-images.githubusercontent.com/83769557/170715447-ba345e71-498b-4945-b177-84c4337a3b69.png)
