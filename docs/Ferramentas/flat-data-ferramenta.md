---
title: Flat Data
tags: 
  - projeto
  - anac 
  - flatdata  
  - git 
  - normas
hide:
#  - navigation
  - toc
---

O Flat Data evita a complexidade de muitas ferramentas de ETL em favor de algo simples e flexível o suficiente para muitas cargas de trabalho, sem requerer que a infraestrutura seja mantida pelos usuários.[^1]

A ferramenta entrega várias funcionalidades para explorar os dados, tais como:

- Filtragem múltipla
- Ordenação
- Cabeçalhos e colunas fixas
- Diferenças entre versões específicas que alteraram os dados

## Flat Data ANAC

Os dados abertos da ANAC podem ser pesquisados e exibidos de forma versionada.
Abra o [visualizador _Flat Viewer_ em tela cheia](https://flatgithub.com/gabrielmacedoanac/flat-data-anac?filename=regulamentos.tsv).

### Tabelas disponíveis

#### Regulamentos (RBAC, IS, Resoluções, Portarias, Decisões...)
- [Todos os regulamentos](https://flatgithub.com/gabrielmacedoanac/flat-data-anac?filename=regulamentos.tsv)
- RBAC
- IS


#### Produtos aeronáticos (Aeronaves, Drones, Motores...)
- Aeronaves
- Drones
- Motores

#### Profissionais credenciados
- Profissionais de Aeronavegabilidade
- 

<iframe title="Flatgithub ANAC - #flatdata" src="https://flatgithub.com/gabrielmacedoanac/flat-data-anac?filename=regulamentos.tsv" width="100%" class="wide max-h-[35rem]" style="height: 90vh;"></iframe>

[^1]: https://githubnext.com/projects/flat-data
