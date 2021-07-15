---
title: "Aviação Aeroagrícola"
description: "Tema relacionado à aviação aeroagrícola"
hide:
  - navigation
  - toc
disqus: ""
---

## Pesquisa de Normativos utilizando tabela em JS

<script src="https://bossanova.uk/jspreadsheet/v4/jexcel.js"></script>
<script src="https://jsuites.net/v4/jsuites.js"></script>
<link rel="stylesheet" href="https://jsuites.net/v4/jsuites.css" type="text/css" />
<link rel="stylesheet" href="https://bossanova.uk/jspreadsheet/v4/jexcel.css" type="text/css" />

<div id="spreadsheet"></div>

<button id='download'>[Exportar tabela acima como arquivo CSV :fontawesome-solid-paper-plane:](){ .md-button .md-button--primary }</button>
 
<script>
var mySpreadsheet = jspreadsheet(document.getElementById('spreadsheet'), {
        data:[
            {
                name:'Paulo',
                id:'3',
                age:'40',
                gender:'Male'
            },
            {
                name:'Cosme Sergio',
                id:'4',
                age:'48',
                gender:'Male'
            },
            {
                name:'Jorgina Santos',
                id:'5',
                age:'32',
                gender:'Female'
            },
        ],
        columns: [
            {
                type:'text',
                width:'300',
                name:'id'
            },
            {
                type:'text',
                width:'200',
                name:'name'
            },
            {
                type:'text',
                width:'100',
                name:'age'
            },
            {
                type:'hidden',
                name:'gender'
            },
         ]
    });
 
document.getElementById('download').onclick = function () {
    mySpreadsheet.download();
}
</script>

<div id="spreadsheet2"></div>

<script>
    jexcel(document.getElementById('spreadsheet2'), {
        search:true,
        pagination:10,
        url:"https://sistemas.anac.gov.br/dadosabertos/regulamentacao/rbha-e-rbac/rbac.json",
        columns: [
            {
                type:'text',
                width:'300',
                title:'Ementa',
                name: 'ementa'
            },
            {
                type:'text',
                width:'100',
                name:'norma'
            },
            {
                type:'hidden',
                width:'100',
                name:'tornada_sem_efeito'
            },
             {
                type:'hidden',
                width:'100',
                name:'alterada'
            },
            {
                type:'text',
                width:'100',
                name:'data'
            },
            {
                type:'hidden',
                width:'100',
                name:'outros'
            },
            {
                type:'text',
                width:'100',
                name:'tipo_normatico'
            },
            {
                type:'hidden',
                width:'100',
                name:'publicacao'
            },
            {
                type:'hidden',
                width:'100',
                name:'revogada'
            },
            {
                type:'text',
                width:'100',
                name:'em_vigor'
            },
            {
                type:'text',
                width:'300',
                title:'Anexos',
                name:'anexos'
            }
         ]
    });
document.getElementById('download').onclick = function () {
    mySpreadsheet.download();
}
</script>
