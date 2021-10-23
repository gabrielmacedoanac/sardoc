---
variable: "**variavel da página no bloco YAML. Pode ser uma gerência dona de um processo, um artefato usado, um grupo de trabalho, etc.**"
hide:
  - navigation
---

## Tabelas

Opções de tabelas:

Apenas HTML
* https://www.w3schools.com/howto/howto_js_filter_table.asp

## Usando Javascript externo
  
### Antigas
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
<iframe title="Knowledge Graph ANAC - Kumu.io" src="https://embed.kumu.io/afa1fffb10177f3cf7eb39d236802fdf" width="100%" class="wide max-h-[35rem]" style="height: 90vh;"></iframe>

## Teste [GraphCommns](https://graphcommons.com/graphs/56d77bb0-8668-4e0a-ac80-374b9d79afa1)

* Acesse em tela cheia em: https://graphcommons.com/graphs/56d77bb0-8668-4e0a-ac80-374b9d79afa1
<iframe src="https://graphcommons.com/graphs/56d77bb0-8668-4e0a-ac80-374b9d79afa1/embed?show=Graph&fitgraph=true" frameborder="1" width="100%" class="wide max-h-[35rem]" style="height: 90vh;" allowfullscreen></iframe>

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

## Firebase Google

<!-- The core Firebase JS SDK is always required and must be listed first -->
<script src="https://www.gstatic.com/firebasejs/8.7.1/firebase-app.js"></script>

<!-- TODO: Add SDKs for Firebase products that you want to use
     https://firebase.google.com/docs/web/setup#available-libraries -->
<script src="https://www.gstatic.com/firebasejs/8.7.1/firebase-analytics.js"></script>

<script>
  // Your web app's Firebase configuration
  // For Firebase JS SDK v7.20.0 and later, measurementId is optional
  var firebaseConfig = {
    apiKey: "AIzaSyCSnQCo2mO9n_SN62p6X4zVB46rSI9CWJw",
    authDomain: "anac-3c50e.firebaseapp.com",
    projectId: "anac-3c50e",
    storageBucket: "anac-3c50e.appspot.com",
    messagingSenderId: "921061949871",
    appId: "1:921061949871:web:a3756643bced9b1986af5a",
    measurementId: "G-V7P0PR3LM2"
  };
  // Initialize Firebase
  firebase.initializeApp(firebaseConfig);
  firebase.analytics();
</script>
