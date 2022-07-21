---
title: Flat Data
hide:
  - navigation
  - toc
---

- [_Flat Data_  - tela cheia](https://flatgithub.com/gabrielmacedoanac/flat-data-anac?filename=regulamentos.tsv)
- [_Flat Data_ - instruções](/sardoc/Ferramentas/flat-data/instrucoes-flat-data/)

<iframe title="Flatgithub ANAC - #flatdata" src="https://flatgithub.com/gabrielmacedoanac/flat-data-anac?filename=regulamentos.tsv" width="100%" class="wide max-h-[35rem]" style="height: 90vh;"></iframe>

Buscas integradas às bases de dados da ANAC usando Flat Data. Bases atualizadas de segunda a sexta, entre 05h e 08h da manhã.

O Flat Data evita a complexidade de muitas ferramentas de manipulação de dados (ETL) em favor de algo simples e flexível o suficiente para muitas cargas de trabalho, mas que não requer que a infraestrutura seja mantida num servidor próprio do usuário. Trata-se de uma ação automática e periódica no GitHub que busca e transforma dados, posteriormente exibindo uma interface comum de consulta para todas as bases de dados selecionadas um endpoint HTTP (url) ou um banco de dados SQL. Por exemplo, bases nos formatos: .csv, .tsv, .json, sql, .xlsx e outras.

> O _Flat Data_ visa simplificar as tarefas diárias de aquisição e limpeza de dados. Ele é executado no GitHub Actions, portanto, não há infraestrutura para provisionar e monitorar. Cada fluxo de trabalho em _Flat Data_ busca os dados que você especifica e, opcionalmente, executa um script de pós-processamento nos dados buscados. Os dados resultantes são confirmados em seu repositório se os novos dados forem diferentes, com uma mensagem de confirmação resumindo as alterações. Fluxos de trabalho em _Flat Data_ geralmente são executados com um temporizador periódico, mas podem ser acionados por uma variedade de estímulos, como alterações em seu código ou acionadores manuais. É isso! Sem gráficos complicados de dependência de trabalho ou orquestradores. Sem dependências, bibliotecas ou gerenciadores de pacotes. Nenhum novo modelo mental para aprender e incorporar. Apenas dados perenes, diretamente no seu repositório.[^1]

[^1]: https://githubnext.com/projects/flat-data

