---
variable: "**variavel da página no bloco YAML. Pode ser uma gerência dona de um processo, um artefato usado, um grupo de trabalho, etc.**"
hide:
  - navigation
---

## Tabela com filtro instantâneo dinâmico e paginação

- https://bossanova.uk/jspreadsheet/v4/examples/datatables

<script src="https://bossanova.uk/jspreadsheet/v4/jexcel.js"></script>
<script src="https://jsuites.net/v4/jsuites.js"></script>
<link rel="stylesheet" href="https://jsuites.net/v4/jsuites.css" type="text/css" />
<link rel="stylesheet" href="https://bossanova.uk/jspreadsheet/v4/jexcel.css" type="text/css" />

<div id="spreadsheet1"></div>

<script>
var data = [
    ['Jazz', 'Honda', '2019-02-12', '', true, '$ 2.000,00', '#777700'],
    ['Civic', 'Honda', '2018-07-11', '', true, '$ 4.000,01', '#007777'],
];

jspreadsheet(document.getElementById('spreadsheet1'), {
    data:data,
    columns: [
        { type: 'text', title:'Car', width:120 },
        { type: 'dropdown', title:'Make', width:200, source:[ "Alfa Romeo", "Audi", "Bmw" ] },
        { type: 'calendar', title:'Available', width:200 },
        { type: 'image', title:'Photo', width:120 },
        { type: 'checkbox', title:'Stock', width:80 },
        { type: 'numeric', title:'Price', width:100, mask:'$ #.##,00', decimal:',' },
        { type: 'color', width:100, render:'square', }
     ]
});
</script>

<div id="spreadsheet2"></div>
 
<script>
var data3 = [
    [1, 'Morning'],
    [2, 'Morning'],
    [3, 'Afternoon'],
    [3, 'Evening'],
];
 
jspreadsheet(document.getElementById('spreadsheet2'), {
    data:data3,
    columns: [
        {
            type:'dropdown',
            title:'Category',
            width:'300',
            source:[
                { id:'1', name:'Paulo', image:'imag1.png', title:'Admin', group:'Secretary' },
                { id:'2', name:'Cosme Sergio', image:'img2.jpg', title:'Teacher', group:'Docent' },
                { id:'3', name:'Rose Mary', image:'img3.png', title:'Teacher', group:'Docent' },
                { id:'4', name:'Fernanda', image:'img3.png', title:'Admin', group:'Secretary' },
                { id:'5', name:'Roger', image:'img3.png', title:'Teacher', group:'Docent' },
            ]
        },
        {
            type:'dropdown',
            title:'Working hours',
            width:'200',
            source:['Morning','Afternoon','Evening'],
            options: { type:'picker' },
        },
    ]
});
</script>

<div id="spreadsheet4"></div>

<script>
var data1 = [
    [ '=B1', '1', 'New products section', '2019-02-12', '80', '=PROGRESS(E1, "darkgreen")' ],
    [ '=B2', '1', 'API integration', '2019-03-01', '100', '=PROGRESS(E2, "darkgreen")' ],
    [ '=B3', '7359', 'Deck', '2018-11-10', '30', '=PROGRESS(E3, "darkgreen")' ],
    [ '=B4', '1', 'Prototype', '2019-01-12', '0', '=PROGRESS(E4, "darkgreen")' ],
];
 
var mySpreadsheet = jspreadsheet(document.getElementById('spreadsheet4'), {
    data:data1,
    columns: [
        { type: 'text', width: '60px', title: 'Photo', readOnly:true },
        { type: 'dropdown', width: '140px', title: 'Name', },
        { type: 'text', width: '200px', title: 'Task' },
        { type: 'calendar', width: '100px', title: 'When' },
        { type: 'text', width: '50px', title: '%' },
        { type: 'text', width: '200px', title: 'Progress', stripHTML: false },
    ],
    allowComments:true,
    updateTable: function(instance, cell, col, row, val, label, cellName) {
        if (col == 0) {
            if (instance.jexcel.options.data[row][col+1]) {
                cell.innerHTML = '<img src="/templates/default/img/' + instance.jexcel.options.data[row][col+1] + '.jpg" style="width:16px;border-radius:16px">';
            } else {
                cell.innerHTML = '<img src="/templates/default/img/nophoto.jpg" style="width:16px;border-radius:16px">';
            }
        }
 
        if (col == 5 && ! val) {
            instance.jexcel.setValue('F'+(row+1), '=PROGRESS(E' + (row + 1) + ', "darkgreen")');
        }
    }
});
</script>
 
<div id="spreadsheet5"></div>
 
<script>
jspreadsheet(document.getElementById('spreadsheet5'), {
    csv:'https://github.com/gabrielmacedoanac/sardoc/blob/main/docs/demo.csv',
    csvHeaders:true,
    search:true,
    pagination:10,
    columns: [
        { type:'text', width:300 },
        { type:'text', width:200 },
        { type:'text', width:100 },
        { type:'text', width:100 },
        { type:'text', width:100 },
     ]
});
</script>


**[[Germano esteve aqui]]!!** *De novo!*

# Início

Para a documentação completa visite [mkdocs.org](https://www.mkdocs.org).

- [Portaria de organização interna da ANAC](https://www.anac.gov.br/assuntos/legislacao/legislacao-1/boletim-de-pessoal/2020/53/bps-no-53-de-31-de-dezembro-de-2020.pdf)

## Comandos

* `mkdocs new [dir-name]` - Cria um novo projeto.
* `mkdocs serve` - Inicia o _live-reloading_ servidor de documentos.
* `mkdocs build` - Produz a *build* do site.
* `mkdocs -h` - Imprime a mensagem de ajuda e saída.

## Layout do projeto

    mkdocs.yml    # O arquivo de configuração.
    docs/
        index.md  # A página inicial de documentação.
        ...       # Outras páginas, imagens e arquivos.


## Teste [Kumu.io](https://kumu.io/anac/anac)

* Acesse em tela cheia em: https://kumu.io/anac/anac
<iframe title="Knowledge Graph ANAC - Kumu.io" src="https://embed.kumu.io/afa1fffb10177f3cf7eb39d236802fdf" width="940" height="600" frameborder="1"></iframe>


## Tabelas aninhadas

### Modelo 1

```markdown
=== "Tab 1"
    Markdown **content**.

    Multiple paragraphs.

=== "Tab 2"
    More Markdown **content**.

    - list item a
    - list item b
```

=== "Tab 1"
    Markdown **content**.

    Multiple paragraphs.

=== "Tab 2"
    More Markdown **content**.

    - list item a
    - list item b

### Modelo 2

???+ note "Open styled details"

    ??? danger "Nested details!"
        And more content again.

### Modelo 3

=== "Tab 1"
    Markdown **content**.

    Multiple paragraphs.

=== "Tab 2"
    More Markdown **content**.

    - list item a
    - list item b

===! "Tab A"
    Different tab set.

=== "Tab B"
    ```
    More content.
    ```

## Incorporação de outros recursos

### Mermaid

```mermaid
graph TD
   A[Hard] -->|Text| B(Round)
   B --> C{Decision}
   C -->|One| D[Result 1]
   C -->|Two| E[Result 2]
```

```
mermaid
graph TB
    c1-->a2
    subgraph one
    a1-->a2
    end
    subgraph two
    b1-->b2
    end
    subgraph three
    c1-->c2
    end
```

## Modelos de conteúdos em blocos

!!! Note "Nota"
    Teste de \!\!\! nota

!!! Abstract "Resumo"
    Abstract

!!! Info "Informação"
    Informação
    
!!! tip "Dica"
    Dica

!!! Success "Sucesso"
    Sucesso

!!! Question "Pergunta"
    Pergunta

!!! Warning "Atenção"
    Atenção: serviço indisponível para essa aeronave. Entre em contato com a ANAC ou selecione o serviço de Certidão da Aeronave para obter mais informações.

!!! Failure "Falha"
    Falha

!!! Danger "Perigo"
    Perigo

!!! Bug "Bug"
    Bug

!!! Quote "Comentário"
    Comentário

!!! Example "Exemplo"
    Exemplo

## Exemplos de barra de progresso

Barra de progresso

[=0% "0%"]
[=5% "5%"]
[=25% "25%"]
[=45% "45%"]
[=65% "65%"]
[=85% "85%"]
[=100% "100%"]

[== 80%]

!!! example "Progress Bar Example"

=== "Output"
  [=0% "0%"]
  [=5% "5%"]
  [=25% "25%"]
  [=100% "100%"]

=== "Markdown"
```
    [=0% "0%"]
    [=5% "5%"]
    [=25% "25%"]
    [=100% "100%"]
```

Though progress bars are rendered as block items, it accepts attr_list's inline format. markdown.extensions.attr_list must be enabled for the following to work.

!!! example "Progress Bar with Attributes"

=== "Output"
    [=85% "85%"]{: .candystripe}
    [=100% "100%"]{: .candystripe .candystripe-animate}

    [=0%]{: .thin}
    [=5%]{: .thin}
    [=100%]{: .thin}

=== "Markdown"
```
    [=85% "85%"]{: .candystripe}
    [=100% "100%"]{: .candystripe .candystripe-animate}

    [=0%]{: .thin}
    [=5%]{: .thin}
    [=100%]{: .thin}
```

## Lista de tarefas

- [x] marcada 1
- [ ] não marcada 1
- [x] Comunicação de Venda
- [ ] Comunicação de Venda

## Botões

1. [Assine a nossa lista de e-mail](#){ .md-button }
1. [Responda ao nosso formulário](#){ .md-button .md-button--primary }
```
1. [Envie :smile:](#smile){ .md-button .md-button--primary }
```

## Teste de Jinja2 com varíaveis

Exibição da variável marcada no arquivo YAML no topo da página: 

* Variável do YAML da página: {{ page.meta.variable }}

```
\\* Navigation: \{\{ \navigation.* \}\}
\\* GIT: \{\{ git.* \}\}
\\* INFO: \{\{ macros_info() \}\}
\\{\{ macros_info() \}\}
```
