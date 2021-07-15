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
        data:[
  {
    "ementa": "Sistemas de oxigênio dos lavatórios.", 
    "norma": "RBAC-E 111 EMD 00", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "16/03/2012", 
    "outros": "", 
    "tipo_normatico": "RBAC-E", 
    "publicacao": "", 
    "revogada": "", 
    "em_vigor": "", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-e-111@@download/arquivo_norma/RBAC-E111EMD00.pdf"
  }, 
  {
    "ementa": "Requisitos de aeronavegabilidade: aeronaves de asas rotativas categoria normal. ", 
    "norma": "RBAC 027 EMD 46", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "13/06/2013", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "", 
    "revogada": "", 
    "em_vigor": "", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-027@@download/arquivo_norma/RBAC27EMD46.pdf"
  }, 
  {
    "ementa": "Requisitos de aeronavegabilidade: aeronaves de asas rotativas categoria transporte. ", 
    "norma": "RBAC 029 EMD 53", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "13/06/2013", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "", 
    "revogada": "", 
    "em_vigor": "", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-029@@download/arquivo_norma/RBAC29EMD53.pdf"
  }, 
  {
    "ementa": "Requisitos de aeronavegabilidade: balões livres tripulados.", 
    "norma": "RBAC 031 EMD 07", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "16/10/2015", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "", 
    "revogada": "", 
    "em_vigor": "", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-031@@download/arquivo_norma/RBAC31EMD07.pdf"
  }, 
  {
    "ementa": "Requisitos de aeronavegabilidade: motores aeronáuticos. ", 
    "norma": "RBAC 033 EMD 28", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "22/04/2009", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "", 
    "revogada": "", 
    "em_vigor": "", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-033@@download/arquivo_norma/RBAC 33.pdf"
  }, 
  {
    "ementa": "Diretrizes de aeronavegabilidade ", 
    "norma": "RBAC 039 EMD 00", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "02/03/2011", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "", 
    "revogada": "", 
    "em_vigor": "", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-039@@download/arquivo_norma/RBAC 39.pdf"
  }, 
  {
    "ementa": "Certificação operacional de aeroportos.", 
    "norma": "RBAC 139 EMD 05", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "17/12/2015", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "", 
    "revogada": "", 
    "em_vigor": "", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-139@@download/arquivo_norma/RBAC139EMD05.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-139@@download/anexo_norma/Perguntas e Respostas RBAC139_EMD05.pdf"
  }, 
  {
    "ementa": "Requisitos de aeronavegabilidade: aviões categoria transporte", 
    "norma": "RBAC 025 EMD 136", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "07/02/2014", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "", 
    "revogada": "", 
    "em_vigor": "", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-025@@download/arquivo_norma/BAC25EMD136.pdf"
  }, 
  {
    "ementa": "Operações de transporte aéreo público com aviões com configuração máxima certificada de assentos para passageiros de mais 19 assentos ou capacidade máxima de carga paga acima de 3.400 kg.", 
    "norma": "RBAC 121 EMD 12", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "11/02/2021", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "12/02/2021", 
    "revogada": "", 
    "em_vigor": "Em vigor em 1º de abril de 2021. Exceto o parágrafo 121.645(e), que entrará em vigor em 26 de maio de 2021.", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-121@@download/arquivo_norma/RBAC121EMD12.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-121@@download/anexo_norma/PA2020-1031 - CEF RBAC 121.pdf"
  }, 
  {
    "ementa": "Programa Nacional de Instrução em Segurança da Aviação Civil Contra Atos de Interferência Ilícita - PNIAVSEC.", 
    "norma": "RBAC 110 EMD 00", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "17/07/2015", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "", 
    "revogada": "", 
    "em_vigor": "", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-110@@download/arquivo_norma/RBAC110EMD00.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-110@@download/anexo_norma/CEF RBAC nº 110.pdf"
  }, 
  {
    "ementa": "Programa de prevenção do risco associado ao uso indevido de substâncias psicoativas na aviação civil.", 
    "norma": "RBAC 120 EMD 03", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "11/02/2021", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "12/02/2021", 
    "revogada": "", 
    "em_vigor": "Em vigor em 1º de março de 2021.", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-120@@download/arquivo_norma/RBAC120EMD03.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-120@@download/anexo_norma/CEF RBAC 120.pdf"
  }, 
  {
    "ementa": "Requisitos de aeronavegabilidade: aviões categoria normal.", 
    "norma": "RBAC 023 EMD 64", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "07/08/2019", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "07/08/2019", 
    "revogada": "", 
    "em_vigor": "", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-023@@download/arquivo_norma/RBAC23EMD64.pdf"
  }, 
  {
    "ementa": "Licenças, habilitações e regras gerais para despachante operacional de voo e mecânico de manutenção aeronáutica", 
    "norma": "RBAC 65 EMD 00", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "25/05/2018", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "25/05/2018", 
    "revogada": "", 
    "em_vigor": "", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-65@@download/arquivo_norma/RBAC65EMD00.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-65@@download/anexo_norma/PA2018-3159 - CEF RBAC nº 65.pdf"
  }, 
  {
    "ementa": "Helipontos.", 
    "norma": "RBAC 155 EMD 00", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "25/05/2018", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "25/05/2018", 
    "revogada": "", 
    "em_vigor": "Em vigor em 21 de novembro de 2018.", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-155@@download/arquivo_norma/RBAC155EMD00.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-155@@download/anexo_norma/CEF RBAC 155 e Perguntas e Respostas.zip"
  }, 
  {
    "ementa": "Operação Aerodesportiva em Aeronaves sem Certificado de Aeronavegabilidade.", 
    "norma": "RBAC 103 EMD 00", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "08/06/2018", 
    "outros": "Retificado no Diário Oficial da União de 20 de junho de 2018, Seção 1, página 54.", 
    "tipo_normatico": "RBAC", 
    "publicacao": "08/06/2018", 
    "revogada": "", 
    "em_vigor": "", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-103@@download/arquivo_norma/RBAC103_EMD00 - Retificado.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-103@@download/anexo_norma/CEF RBAC 103.pdf"
  }, 
  {
    "ementa": "Credenciamento de pessoas.\r\n", 
    "norma": "RBAC 183 EMD 01", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "08/06/2018", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "08/06/2018", 
    "revogada": "", 
    "em_vigor": "", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-183@@download/arquivo_norma/RBAC183_EMD01.pdf"
  }, 
  {
    "ementa": "Requisitos de Aeronavegabilidade: Hélices.", 
    "norma": "RBAC 035 EMD 10", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "07/08/2019", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "07/08/2019", 
    "revogada": "", 
    "em_vigor": "", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-035@@download/arquivo_norma/RBAC35EMD10.pdf"
  }, 
  {
    "ementa": "Operação de empresas estrangeiras que têm por objetivo o transporte aéreo público no Brasil (Operations of foreign air carriers within Brazil engaged in common carriage).", 
    "norma": "RBAC 129 EMD 01", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "31/08/2018", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "31/08/2018.", 
    "revogada": "", 
    "em_vigor": "", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-129@@download/arquivo_norma/RBAC129EMD01.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-129@@download/anexo_norma/CEF RBAC nº 129.pdf"
  }, 
  {
    "ementa": "Marcas de Identificação, de Nacionalidade e de Matrícula.", 
    "norma": "RBAC 45  EMD 04", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "24/06/2020", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "24/06/2020", 
    "revogada": "", 
    "em_vigor": "Em vigor em 1º de julho de 2020.", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-045@@download/arquivo_norma/RBAC45EMD04.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-045@@download/anexo_norma/CEF RBAC 45.pdf"
  }, 
  {
    "ementa": "Segurança da aviação civil contra atos de interferência ilícita – Operador de aeródromo.", 
    "norma": "RBAC 107 EMD 04", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "07/06/2021", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "14/06/2021", 
    "revogada": "", 
    "em_vigor": "Em vigor em 1º de julho de 2021.", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-107@@download/arquivo_norma/RBAC107EMD04 - versão em vigor de 01.07 a 01.08.2021.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-107@@download/anexo_norma/Anexos RBAC 107.zip"
  }, 
  {
    "ementa": "Segurança da aviação civil contra atos de interferência ilícita - Operador aéreo.", 
    "norma": "RBAC 108 EMD 04", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "07/06/2021", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "14/06/2021", 
    "revogada": "", 
    "em_vigor": "Em vigor em 1º de julho de 2021.", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-108@@download/arquivo_norma/RBAC108EMD04 - versão em vigor de 01.07 a 01.08.2021.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-108@@download/anexo_norma/Anexos.zip"
  }, 
  {
    "ementa": "Regras Gerais para petição de emissão, alteração, revogação e isenção de cumprimento de regra.", 
    "norma": "RBAC 11 EMD 03", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "24/03/2020", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "24/03/2020", 
    "revogada": "", 
    "em_vigor": "Em vigor em 1º de abril de 2020.", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-011@@download/arquivo_norma/RBAC11EMD03.pdf"
  }, 
  {
    "ementa": "Requisitos para drenagem de combustível e emissões de escapamento de aviões com motores a turbina.", 
    "norma": "RBAC 034 EMD 06", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "18/12/2018", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "18/12/2018", 
    "revogada": "", 
    "em_vigor": "Em vigor em 17 de fevereiro de 2019.", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-034@@download/arquivo_norma/RBAC34EMD06.pdf"
  }, 
  {
    "ementa": "Requisitos para emissões de CO2 de aviões.", 
    "norma": "RBAC 038 EMD 00", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "18/12/2018", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "18/12/2018", 
    "revogada": "", 
    "em_vigor": "Em vigor em 17 de fevereiro de 2019.", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-038@@download/arquivo_norma/RBAC38EMD00.pdf"
  }, 
  {
    "ementa": "Certificação e Requisitos Operacionais: Centros de treinamento de aviação civil.", 
    "norma": "RBAC 142 EMD 03", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "11/02/2021", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "12/02/2021", 
    "revogada": "", 
    "em_vigor": "Em vigor em 1º de março de 2021.", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-142@@download/arquivo_norma/RBAC142EMD03.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-142@@download/anexo_norma/CEF RBAC 142 EMD 02.pdf"
  }, 
  {
    "ementa": "Organizações de manutenção de produto aeronáutico.", 
    "norma": "RBAC 145 EMD 07", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "23/02/2021", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "26/02/2021", 
    "revogada": "", 
    "em_vigor": "Em vigor em 1º de junho de 2021.", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-145@@download/arquivo_norma/RBAC145EMD07.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-145@@download/anexo_norma/CEF RBAC nº 145.pdf"
  }, 
  {
    "ementa": "Requisitos para gerenciamento de risco de fadiga humana.", 
    "norma": "RBAC 117 EMD 00", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "19/03/2019", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "19/03/2019", 
    "revogada": "", 
    "em_vigor": "", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-117@@download/arquivo_norma/RBAC117EMD00.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-117@@download/anexo_norma/ CEF RBAC nº 117.pdf"
  }, 
  {
    "ementa": "Requisitos para operações especiais de aviação pública.", 
    "norma": "RBAC 90 EMD 00", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "12/04/2019", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "12/04/2019", 
    "revogada": "", 
    "em_vigor": "Em vigor em 11 de julho de 2019.", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-90@@download/arquivo_norma/RBAC90EMD00.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-90@@download/anexo_norma/ CEF RBAC nº 90.pdf"
  }, 
  {
    "ementa": "Salto de paraquedas.", 
    "norma": "RBAC 105 EMD 02", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "12/04/2019", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "12/04/2019", 
    "revogada": "", 
    "em_vigor": "Em vigor em 11 de julho de 2019.", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-105@@download/arquivo_norma/RBAC105EMD02.pdf"
  }, 
  {
    "ementa": "Operação de aeronaves de asas rotativas com cargas externas.", 
    "norma": "RBAC 133 EMD 02", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "12/04/2019", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "12/04/2019", 
    "revogada": "", 
    "em_vigor": "Em vigor em 11 de julho de 2019.", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-133@@download/arquivo_norma/RBAC133EMD02.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-133@@download/anexo_norma/CEF RBAC-133.pdf"
  }, 
  {
    "ementa": "Transporte de artigos perigosos em aeronaves civis.", 
    "norma": "RBAC 175 EMD 03", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "11/02/2021", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "12/02/2021", 
    "revogada": "", 
    "em_vigor": "Em vigor em 1º de abril de 2021.", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-175@@download/arquivo_norma/RBAC175EMD03.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-175@@download/anexo_norma/CEF RBAC 175.pdf"
  }, 
  {
    "ementa": "Certificação e requisitos operacionais: Centros de Instrução de Aviação Civil.", 
    "norma": "RBAC 141 EMD 01", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "06/03/2020", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "06/03/2020", 
    "revogada": "", 
    "em_vigor": "Em vigor em 1º de abril de 2020.", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-141@@download/arquivo_norma/RBAC141EMD01.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-141@@download/anexo_norma/CEF RBAC 141.pdf"
  }, 
  {
    "ementa": "Licenças, habilitações e certificados para pilotos.", 
    "norma": "RBAC 61 EMD 13", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "19/03/2020", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "20/03/2020", 
    "revogada": "", 
    "em_vigor": "Em vigor em 1º de abril de 2020.", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-61@@download/arquivo_norma/RBAC61EMD13.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-61@@download/anexo_norma/ CEF RBAC 61.pdf"
  }, 
  {
    "ementa": "Aeródromos - Operação, manutenção e resposta à emergência.", 
    "norma": "RBAC 153 EMD 06", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "09/03/2021", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "15/03/2021", 
    "revogada": "", 
    "em_vigor": "Em vigor em 1º de abril de 2021.", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-153@@download/arquivo_norma/RBAC153EMD06.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-153@@download/anexo_norma/Anexos RBAC 153.zip"
  }, 
  {
    "ementa": "Certificação e requisitos operacionais: operações aeroagrícolas.", 
    "norma": "RBAC 137 EMD 04", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "12/05/2020", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "15/05/2020", 
    "revogada": "", 
    "em_vigor": "Em vigor em 1º de junho de 2020.", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-137@@download/arquivo_norma/RBAC137EMD04.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-137@@download/anexo_norma/CEF RBAC 137.pdf"
  }, 
  {
    "ementa": "Operações de transporte aéreo público com aviões com configuração máxima certificada de assentos para passageiros de até 19 assentos e capacidade máxima de carga paga de até 3.400 kg (7.500 lb), ou helicópteros.", 
    "norma": "RBAC 135 EMD 10", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "11/02/2021", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "12/02/2021", 
    "revogada": "", 
    "em_vigor": "Em vigor em 1º de abril de 2021.", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-135@@download/arquivo_norma/RBAC135EMD10.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-135@@download/anexo_norma/ CEF RBAC nº 135.pdf"
  }, 
  {
    "ementa": "Definições, regras de redação e unidades de medida para uso nos normativos da ANAC.", 
    "norma": "RBAC 01 EMD 08", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "11/02/2021", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "12/01/2021", 
    "revogada": "", 
    "em_vigor": "Em vigor em 1º de abril de 2021.", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-01@@download/arquivo_norma/RBAC01EMD08.pdf"
  }, 
  {
    "ementa": "Certificação: Operadores de Transporte Aéreo Público.", 
    "norma": "RBAC 119 EMD 08", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "11/02/2021", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "12/02/2021", 
    "revogada": "", 
    "em_vigor": "Em vigor em 1º de março de 2021.", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-119@@download/arquivo_norma/RBAC119EMD08.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-119@@download/anexo_norma/CEF RBAC 119.pdf"
  }, 
  {
    "ementa": "Requisitos para concessão de certificados médicos aeronáuticos, para o cadastro e credenciamento de médicos, credenciamento de clínicas e para o convênio com entidades públicas.", 
    "norma": "RBAC 67 EMD 04", 
    "tornada_sem_efeito": "", 
    "alterada": "Retificado no DOU de 29/04/2020.", 
    "data": "20/03/2020", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "20/03/2020", 
    "revogada": "", 
    "em_vigor": "Em vigor em 1º de abril de 2020.", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-067@@download/arquivo_norma/RBAC67EMD04.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-067@@download/anexo_norma/CEF RBAC 67.pdf"
  }, 
  {
    "ementa": "Requisitos para qualificação e uso de dispositivos de treinamento para simulação de voo.", 
    "norma": "RBAC 60 EMD 00", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "20/03/2020", 
    "outros": "Retificado no Diário Oficial da União de 24 de março de 2020, Seção 1, página 66.", 
    "tipo_normatico": "RBAC", 
    "publicacao": "20/03/2020", 
    "revogada": "", 
    "em_vigor": "Em vigor em 1º de abril de 2020.", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-60@@download/arquivo_norma/RBAC60EMD00.pdf"
  }, 
  {
    "ementa": "Certificação e requisitos operacionais: voos panorâmicos.", 
    "norma": "RBAC 136 EMD 00", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "24/06/2020", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "24/06/2020", 
    "revogada": "", 
    "em_vigor": "Em vigor em 1º de julho de 2020.", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-136@@download/arquivo_norma/RBAC136EMD00.pdf"
  }, 
  {
    "ementa": "Planos de Zoneamento de Ruído de Aeródromos  - PZR", 
    "norma": "RBAC 161 EMD 03", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "23/02/2021", 
    "outros": "Retificado no Diário Oficial da União de 1º de abril de 2021, Seção 1 (Edição Extra), páginas 28 e 29.", 
    "tipo_normatico": "RBAC", 
    "publicacao": "26/02/2021", 
    "revogada": "", 
    "em_vigor": "Em vigor em 1º de abril de 2021.", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-161@@download/arquivo_norma/RBAC161EMD03 - Retificado.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-161@@download/anexo_norma/CEF RBAC nº 161.pdf"
  }, 
  {
    "ementa": "Manutenção, manutenção preventiva, reconstrução e alteração.", 
    "norma": "RBAC 43 EMD 05", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "09/03/2021", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "15/03/2021", 
    "revogada": "", 
    "em_vigor": "Em vigor em 26 de maio de 2021.", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-43-emd-05@@download/arquivo_norma/RBAC43EMD05.pdf"
  }, 
  {
    "ementa": "Operações de transporte aéreo público com aviões com configuração máxima certificada de assentos para passageiros de até 19 assentos e capacidade máxima de carga paga de até 3.400 kg (7.500 lb), ou helicópteros.", 
    "norma": "RBAC 135 EMD 11", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "09/03/2021", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "15/03/2021", 
    "revogada": "", 
    "em_vigor": "Em vigor em 26 de maio de 2021.", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-135-emd-11@@download/arquivo_norma/RBAC135EMD11.pdf"
  }, 
  {
    "ementa": "Manutenção, manutenção preventiva, reconstrução e alteração.", 
    "norma": "RBAC 43 EMD 04", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "02/08/2019", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "07/08/2019", 
    "revogada": "", 
    "em_vigor": "", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-43@@download/arquivo_norma/RBAC43EMD04.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-43@@download/anexo_norma/CEF RBAC nº 43.pdf"
  }, 
  {
    "ementa": "Requisitos de ruído para aeronave.", 
    "norma": "RBAC 36", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "08/04/2021", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "12/04/2021", 
    "revogada": "", 
    "em_vigor": "Em vigor em 3 de maio de 2021.", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-36@@download/arquivo_norma/RBAC36EMD31.pdf"
  }, 
  {
    "ementa": "Requisitos gerais para aeronaves não tripuladas de uso civil", 
    "norma": "RBAC-E 94 EMD 01", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "01/06/2021", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "07/06/2021", 
    "revogada": "", 
    "em_vigor": "Em vigor em 1º de julho de 2021.", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-e-94-emd-01@@download/arquivo_norma/RBACE94EMD01.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-e-94-emd-01@@download/anexo_norma/CEF RBAC-E 94.pdf"
  }, 
  {
    "ementa": "Certificação de Produto e Artigo Aeronáuticos.", 
    "norma": "RBAC 21 EMD 08", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "14/06/2021", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "14/06/2021", 
    "revogada": "", 
    "em_vigor": "Em vigor em 1º de julho de 2021.", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-21-emd-08@@download/arquivo_norma/RBAC21EMD08.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-21-emd-08@@download/anexo_norma/CEF RBAC 21.pdf"
  }, 
  {
    "ementa": "Aeronavegabilidade continuada e melhorias na segurança para aviões categoria transporte.", 
    "norma": "RBAC 26 EMD 03", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "14/06/2021", 
    "outros": "", 
    "tipo_normatico": "CE/SC", 
    "publicacao": "14/06/2021.", 
    "revogada": "", 
    "em_vigor": "Em vigor em 1º de julho de 2021.", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-26-emd-03@@download/arquivo_norma/RBAC26EMD03.pdf"
  }, 
  {
    "ementa": "Requisitos gerais de operação para aeronaves civis.", 
    "norma": "RBAC 91 EMD 03", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "14/06/2021", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "14/06/2021", 
    "revogada": "", 
    "em_vigor": "Em vigor em 1º de julho de 2021.", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-91-emd-03@@download/arquivo_norma/RBAC91EMD03.pdf"
  }, 
  {
    "ementa": "Operações de transporte aéreo público com aviões com configuração máxima certificada de assentos para passageiros de mais 19 assentos ou capacidade máxima de carga paga acima de 3.400 kg.", 
    "norma": "RBAC 121 EMD 14", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "14/06/2021", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "14/06/2021", 
    "revogada": "", 
    "em_vigor": "Em vigor em 1º de julho de 2021.", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-121-emd-14@@download/arquivo_norma/RBAC121EMD14.pdf"
  }, 
  {
    "ementa": "Projeto de Aeródromos.", 
    "norma": "RBAC 154 EMD 07", 
    "tornada_sem_efeito": "", 
    "alterada": "", 
    "data": "16/06/2021", 
    "outros": "", 
    "tipo_normatico": "RBAC", 
    "publicacao": "16/06/2021.", 
    "revogada": "", 
    "em_vigor": "Em vigor em 1º de julho de 2021.", 
    "anexos": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-154-emd-07@@download/arquivo_norma/RBAC154EMD07.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-154-emd-07@@download/anexo_norma/Perguntas e Respostas  RBAC nº 154  Emenda nº 07.pdf"
  }
],
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


## Importado do KUMU depois do tratamento

<div id="spreadsheet2"></div>

<script>
    jexcel(document.getElementById('spreadsheet2'), {
        search:true,
        pagination:10,
        data:[
    {
      "_id": "elem-041mtsiM",
      "attributes": {
        "label": "Eduardo Américo Campos Filho",
        "element type": "Person",
        "rdf:type": "foaf:Person"
      }
    },
    {
      "_id": "elem-0hw9igRX",
      "attributes": {
        "label": "Juliana",
        "element type": "Person",
        "description": "dfdwawfafafa\nsadfasf\n\n[juliana](link.com)"
      }
    },
    {
      "_id": "elem-0msXVyQY",
      "attributes": {
        "label": "Certificação de Produtos e Isenção de requisitos/Certificação de Produtos e Isenção de requisitos",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-1I8Ol8yF",
      "attributes": {
        "label": "10. Obter certificado de aeronavegabilidade",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-1soEBRQX",
      "attributes": {
        "label": "Áureo de Morais Vasconcelos",
        "element type": "Person",
        "rdf:type": "foaf:Person"
      }
    },
    {
      "_id": "elem-1u4pJmIT",
      "attributes": {
        "label": "Fabiano dos Santos Nascimento Silva",
        "rdf:type": "foaf:Person",
        "element type": "Person"
      }
    },
    {
      "_id": "elem-1zCrWpDu",
      "attributes": {
        "label": "FDH/CHOPP/Processo normativo",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-2T7iZnJu",
      "attributes": {
        "label": "Pedro Henrique Leite Paludo",
        "element type": "Person",
        "rdf:type": "foaf:Person"
      }
    },
    {
      "_id": "elem-2dh2tl8u",
      "attributes": {
        "label": "1.3. Gerência Técnica de Auditoria e Inspeção (GTAI)",
        "description": "---\n### 1.3. Gerência Técnica de Auditoria e Inspeção (GTAI)\n> Gerente: [[Pedro Henrique Leite Paludo]]\n\nCompetências:\n\n* Certificação e vigilância continuada de organizações de produção\n* Dentro do processo de certificação de produto aeronáutico, inspeção necessária à verificação da conformidade de produto, de processo, de espécime de ensaio e de instalação associada\n* Certificação de aeronavegabilidade associada com as atividades inerentes à certificação de produto aeronáutico e aviação experimental\n* Inspeção para emissão de certificado de exportação de produto aeronáutico, incluindo aeronave usada\n* Orientação, supervisão e monitoramento de pessoas credenciadas, em sua área de atuação.",
        "rdf:type": "org:OrganizationUnit",
        "element type": "Organization"
      }
    },
    {
      "_id": "elem-2lX4v5O1",
      "attributes": {
        "label": "Conhecimentos",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-2p9rvn90",
      "attributes": {
        "label": "SITACA/Processo de Certificação de oficinas",
        "description": "Sistema Integrado de Atendimento e Controle de Solicitações AIR145",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-2q3yMydE",
      "attributes": {
        "label": "16. Obter mudança de categoria de registro de aeronave",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-2qFDRjjW",
      "attributes": {
        "label": "4. Gerência Técnica de Processo Normativo (GTPN)",
        "description": "---\n### 4. Gerência Técnica de Processo Normativo (GTPN)\n> Gerente: [[Marco Aurelio Bonilauri Santin]]\n\nCompetências:\n\n* Coordenação, condução e suporte ao desenvolvimento de normativos\n* Coordenação, condução e suporte a atividades de articulação com outras entidades, nacionais ou estrangeiras, com vistas ao estabelecimento de acordos, ao intercâmbio de informações, à internalização de informações e ao desenvolvimento de normativos\n* Coordenação e suporte ao desenvolvimento de interpretações de requisitos\n* Gerenciamento do banco de dados com as interpretações e os meios alternativos de demonstração de cumprimento de requisito\n* Suporte à definição da base de certificação e atividades correlatas\n* Coordenação e suporte à elaboração de respostas a demandas especiais",
        "rdf:type": "org:OrganizationUnit",
        "skos:preflabel": "GTPN",
        "element type": "Organization"
      }
    },
    {
      "_id": "elem-2uQlxY5v",
      "attributes": {
        "label": "FDH/CHOPP - Programas de certificação/Programas de certificação",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-2xDxDudY",
      "attributes": {
        "label": "Rafael Ximenes Borges",
        "rdf:type": "foaf:Person",
        "element type": "Person"
      }
    },
    {
      "_id": "elem-2zdl3qvH",
      "attributes": {
        "label": "01. Auditorias de Supervisão Remotas na SAR",
        "description": "SEI nº 00058.018244/2020-35 (Projeto setorial)\nSEI nº [00058.034120/2020-05](https://sei.anac.gov.br/sei/modulos/pesquisa/md_pesq_processo_exibir.php?iI3OtHvPArITY997V09rhsSkbDKbaYSycOHqqF2xsM0IaDkkEyJpus7kCPb435VNEAb16AAxmJKUdrsNWVIqQ6MPmvkM2XpDeTTGOM4Ylp-M6h8ZEkyW96XmIqStCSBm) (Setorial)",
        "vigente": "Não",
        "rdf:type": "foaf:Project",
        "skos:preflabel": "Auditorias de Supervisão Remotas na SAR",
        "element type": "Project"
      }
    },
    {
      "_id": "elem-2zzPJAAx",
      "attributes": {
        "label": "HST/Certificação suplementar de tipo",
        "description": "Dados de projeto de aprovação de grandes modificações e grandes alterações em produto aeronáutico.Controle de processos de certificação suplementar de tipo",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-3Aep8vSA",
      "attributes": {
        "label": "Certificação de Produtos e Isenção de requisitos/Certificação de Produtos e Isenção de requisitos",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-3H8njZ5F",
      "attributes": {
        "label": "Planilha Organizations/Planilha Organizations",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-3gVWrnWK",
      "attributes": {
        "label": "Mário Igawa",
        "rdf:type": "foaf:Person",
        "element type": "Person"
      }
    },
    {
      "_id": "elem-45DF8fPJ",
      "attributes": {
        "label": "28. Transferir propriedade de aeronave para pessoa jurídica",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-4J409s3K",
      "attributes": {
        "label": "20. Obter validação de Certificado Suplementar de Tipo (CST/STC) estrangeiro",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-4XXXBr5F",
      "attributes": {
        "label": "8. Obter Certidão de Propriedade e Ônus Reais",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-4fAACjQf",
      "attributes": {
        "label": "LIVRO RAB/LIVRO RAB",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-4hVX0VL1",
      "attributes": {
        "label": "Seth Emanuel Couto Melo Filho",
        "rdf:type": "foaf:Person",
        "element type": "Person"
      }
    },
    {
      "_id": "elem-4k1e8Fa3",
      "attributes": {
        "label": "CRP_AERONAVE",
        "element type": "Database",
        "description": "Base integrada de aeronaves (replicada)",
        "status": "Bad"
      }
    },
    {
      "_id": "elem-4khbkla9",
      "attributes": {
        "label": "Jose Jaétis Rosário",
        "element type": "Person",
        "rdf:type": "foaf:Person"
      }
    },
    {
      "_id": "elem-56ZwRH2e",
      "attributes": {
        "label": "20. Obter validação de Certificado Suplementar de Tipo (CST/STC) estrangeiro",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-579IurfL",
      "attributes": {
        "label": "Planilha Organizations/Planilha Organizations",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-5Hu3eHsM",
      "attributes": {
        "label": "1.2. Gerência de Engenharia de Produto (GCEN)",
        "element type": "Organization",
        "description": "---\n### 1.2. Gerência de Engenharia de Produto (GCEN)\n> Gerente: [[Nelson Eisaku Nagamine]]\n\nCompetências:\n\n* Certificação de projeto de produto aeronáutico, provendo parecer especializado nas áreas de aeronáutica, desempenho em voo e qualidade de voo resistência estrutural em aeronaves sistemas de aeronaves (hidráulicos, pneumáticos, eletroeletrônicos, software embarcado, integração inter-sistemas, etc)\n* propulsão de aeronaves\n* fator humano relacionado a projeto de aeronave\n* proteção do ocupante da aeronave\n* proteção ambiental (ruído e emissões)\n* outros aspectos técnicos considerados essenciais à segurança de voo\n* Orientação, supervisão e monitoramento de pessoas credenciadas, em sua área de atuação.",
        "rdf:type": "org:OrganizationUnit"
      }
    },
    {
      "_id": "elem-5RAb7bNv",
      "attributes": {
        "label": "2.2. Gerência de Coordenação de Vigilância Continuada (GCVC)",
        "description": "---\n### 2.2. Gerência de Coordenação de Vigilância Continuada (GCVC)\n> Gerente: [[Henri Salvatore Bigatti]]\n\nCompetências:\n\n* Planejamento das atividades de certificação e vigilância continuada na área de competência da Gerência-Geral de Aeronavegabilidade Continuada\n* Coordenação das atividades de certificação e de vigilância continuada na área de competência da Gerência-Geral de Aeronavegabilidade Continuada, pelo estabelecimento de processos, buscando maior eficiência\n* Padronização e coordenação técnica das atividades de certificação e de vigilância continuada na área de competência da Gerência-Geral de Aeronavegabilidade Continuada\n* Realização de auditorias periódicas no âmbito das gerências e gerências técnicas da GGAC\n* Monitoramento, através de indicadores de produtividade e desempenho, da execução das atividades de certificação e de vigilância continuada na área de competência da Gerência-Geral de Aeronavegabilidade Continuada.",
        "element type": "Organization",
        "rdf:type": "org:OrganizationUnit",
        "skos:preflabel": "GCVC"
      }
    },
    {
      "_id": "elem-5aQHFDPL",
      "attributes": {
        "label": "FDH/CHOPP/Organizações de projetos",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-5taoaq8m",
      "attributes": {
        "label": "21. Obter validação de grande modificação ao projeto de tipo de produto aeronáutico estrangeiro",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-60EJnEXx",
      "attributes": {
        "label": "11. Mapeamento de Riscos dos Processos Organizacionais da SAR",
        "rdf:type": "foaf:Project",
        "element type": "Project"
      }
    },
    {
      "_id": "elem-64puzcCs",
      "attributes": {
        "label": "Henri Salvatore Bigatti",
        "rdf:type": "foaf:Person",
        "element type": "Person"
      }
    },
    {
      "_id": "elem-6AcTDwuT",
      "attributes": {
        "label": "13. Otimização do Processo de Emissão de DA",
        "element type": "Project",
        "rdf:type": "foaf:Project"
      }
    },
    {
      "_id": "elem-6GEZZriT",
      "attributes": {
        "label": "4. Propostas de melhorias ao processo de conformidade",
        "element type": "Project",
        "rdf:type": "foaf:Project"
      }
    },
    {
      "_id": "elem-79ZqrhMx",
      "attributes": {
        "label": "Lawrence Josuá Fernandes Costa",
        "element type": "Person",
        "rdf:type": "foaf:Person"
      }
    },
    {
      "_id": "elem-79pi3lgp",
      "attributes": {
        "label": "2.1. Gerência de Engenharia de Manutenção (GAEM)",
        "description": "---\n### 2.1. Gerência de Engenharia de Manutenção (GAEM)\n\n> Gerente: [[Eduardo Américo Campos Filho]]\n\nCompetências:\n\n* Gestão dos recursos humanos necessários para a execução das atividades da Gerência-Geral de Aeronavegabilidade Continuada, pelas Gerências Técnicas de Aeronavegabilidade\n* Padronização da execução das atividades administrativas da Gerência-Geral, pelas Gerências Técnicas de Aeronavegabilidade, incluindo auditorias periódicas.",
        "rdf:type": "org:OrganizationUnit",
        "skos:preflabel": "GAEM",
        "element type": "Organization"
      }
    },
    {
      "_id": "elem-7ZIcgCNM",
      "attributes": {
        "label": "3. Gerência Técnica do Registro Aeronáutico Brasileiro (GTRAB)",
        "element type": "Organization",
        "description": "---\n### 3. Gerência Técnica do Registro Aeronáutico Brasileiro (GTRAB)\n> Gerente: [[Luciana Ferreira da Silva]]\n\nCompetências:\n\n* Administrar o Registro Aeronáutico Brasileiro\n* Emitir, suspender ou extinguir certificado de matrícula\n* Emitir, suspender ou extinguir certificado de aeronavegabilidade\n* Conceder meio alternativo de demonstração de cumprimento a requisito em sua área de atuação.",
        "rdf:type": "org:OrganizationUnit",
        "skos:preflabel": "GTRAB"
      }
    },
    {
      "_id": "elem-7nRz6C0x",
      "attributes": {
        "label": "Julio Giampa Scheibel",
        "rdf:type": "foaf:Person",
        "element type": "Person"
      }
    },
    {
      "_id": "elem-8NPUbqlE",
      "attributes": {
        "label": "Intranet SAR",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-8oX6TAbT",
      "attributes": {
        "label": "3. Avaliação do relatório JATR-Joint Authorities Technical Review (B737MAX)",
        "element type": "Project",
        "rdf:type": "foaf:Project",
        "description": "SEI nº"
      }
    },
    {
      "_id": "elem-8w5TVpGa",
      "attributes": {
        "label": "8. Reestruturação da Gestão do Conhecimento na SAR",
        "rdf:type": "foaf:Project",
        "element type": "Project"
      }
    },
    {
      "_id": "elem-9b0JZFhi",
      "attributes": {
        "label": "Rogério Possi Júnior",
        "rdf:type": "foaf:Person",
        "element type": "Person"
      }
    },
    {
      "_id": "elem-A3aARm2L",
      "attributes": {
        "label": "18. Obter um Certificado de Marca Experimental",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-ATpSIWeP",
      "attributes": {
        "label": "Mário Igawa",
        "element type": "Person",
        "rdf:type": "foaf:Person"
      }
    },
    {
      "_id": "elem-AdA2Z4og",
      "attributes": {
        "label": "RDS - Report de dificuldade em serviço",
        "description": "Registro de Dificuldade em Serviço de Operações de Aeronaves",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-Ax9SU0gl",
      "attributes": {
        "label": "Luciana Ferreira da Silva",
        "rdf:type": "foaf:Person",
        "element type": "Person"
      }
    },
    {
      "_id": "elem-BCb0NO22",
      "attributes": {
        "label": "2. Credenciar-se como Profissional de Aeronavegabilidade, Fabricação ou Projeto",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-BHy73uIV",
      "attributes": {
        "label": "Curador não identificado",
        "tags": [
          "Quality control"
        ],
        "description": "Elemento exclusivo para identificar bases de dados sem curadores designados pela superintendência.",
        "element type": "Person",
        "status": "Bad",
        "rdf:type": "foaf:Person"
      }
    },
    {
      "_id": "elem-BJJ8MW48",
      "attributes": {
        "label": "Jose Jaétis Rosário",
        "rdf:type": "foaf:Person",
        "element type": "Person"
      }
    },
    {
      "_id": "elem-Bld8wmdB",
      "attributes": {
        "label": "5. Gerência Técnica de Gestão do Conhecimento de Aeronavegabilidade (GTGC)",
        "description": "---\n### 5. Gerência Técnica de Gestão do Conhecimento de Aeronavegabilidade (GTGC)\n> Gerente: [[Henrique Shimanuki Muta]]\n\nPara assuntos de credenciamento de pessoas, contatar a ACP – Assessoria de Credenciamento de Profissionais\nE-mail: [credenciamento.sar@anac.gov.br](mailto:credenciamento.sar@anac.gov.br) \n\nCompetências:\n\n* Coordenação e estabelecimento de ações estratégicas, no que tange à aquisição, preservação e disseminação de conhecimentos de interesse da Superintendência\n* Planejamento, coordenação e controle da formação dos servidores alocados na Superintendência, observando procedimentos e orientações estabelecidos pela Superintendência de Gestão de Pessoas\n* Administração dos registros de capacitação\n* Administração do sistema de credenciamento de pessoas, no âmbito da Superintendência",
        "rdf:type": "org:OrganizationUnit",
        "skos:preflabel": "GTGC",
        "element type": "Organization"
      }
    },
    {
      "_id": "elem-BwNojshI",
      "attributes": {
        "label": "SCPRAB/Processos administrativos relacionados a aeronaves",
        "description": "Sistema Consulta Processual do RAB\nRelaciona todos todos os processos administrativos que têm relação com a aeronave.",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-C4w40WGe",
      "attributes": {
        "label": "Marco Aurelio Bonilauri Santin",
        "element type": "Person",
        "rdf:type": "foaf:Person"
      }
    },
    {
      "_id": "elem-CDekidd2",
      "attributes": {
        "label": "7. Treinamento recorrente do efetivo da GGCP",
        "element type": "Project",
        "rdf:type": "foaf:Project"
      }
    },
    {
      "_id": "elem-CH5cTJoC",
      "attributes": {
        "label": "SITACA/Processo de Certificação de oficinas",
        "description": "Sistema Integrado de Atendimento e Controle de Solicitações AIR145",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-CMHdROnY",
      "attributes": {
        "label": "29. Validar projeto aeronáutico certificado no exterior",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-CfvIiSOy",
      "attributes": {
        "label": "Letícia Paraguassu",
        "element type": "Person",
        "rdf:type": "foaf:Person"
      }
    },
    {
      "_id": "elem-Cl6Hpimp",
      "attributes": {
        "label": "22. Obter validação de nível de segurança de produto aeronáutico",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-D2qV8lLQ",
      "attributes": {
        "label": "Controle de certificados temporários/Controle de certificados temporários",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-DHaVeC3W",
      "attributes": {
        "label": "Rafael Ximenes Borges",
        "element type": "Person",
        "rdf:type": "foaf:Person"
      }
    },
    {
      "_id": "elem-DUuXWUeW",
      "attributes": {
        "label": "28. Transferir propriedade de aeronave para pessoa jurídica",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-DVeV8uNO",
      "attributes": {
        "label": "7. Treinamento recorrente do efetivo da GGCP",
        "rdf:type": "foaf:Project",
        "element type": "Project"
      }
    },
    {
      "_id": "elem-DbWwHiHF",
      "attributes": {
        "label": "Henrique Shimanuki Muta",
        "element type": "Person",
        "rdf:type": "foaf:Person"
      }
    },
    {
      "_id": "elem-EASiB9b2",
      "attributes": {
        "label": "Camila Akemi",
        "element type": "Person",
        "description": "Camila é funcionária da [GTPA](GTPA)"
      }
    },
    {
      "_id": "elem-EEMHA4x8",
      "attributes": {
        "label": "Competências",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-EV0dGcx1",
      "attributes": {
        "label": "6. Obter autorização especial de voo - AEV",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-Etw9gkp2",
      "attributes": {
        "label": "Mateus Frois Santa Catarina",
        "rdf:type": "foaf:Person",
        "element type": "Person"
      }
    },
    {
      "_id": "elem-Ev2cjHmo",
      "attributes": {
        "label": "12. Obter Certificado de Autorização de Voo Experimental",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-FKvz7t32",
      "attributes": {
        "label": "2.2. Gerência de Coordenação de Vigilância Continuada (GCVC)",
        "description": "---\n### 2.2. Gerência de Coordenação de Vigilância Continuada (GCVC)\n> Gerente: [[Henri Salvatore Bigatti]]\n\nCompetências:\n\n* Planejamento das atividades de certificação e vigilância continuada na área de competência da Gerência-Geral de Aeronavegabilidade Continuada\n* Coordenação das atividades de certificação e de vigilância continuada na área de competência da Gerência-Geral de Aeronavegabilidade Continuada, pelo estabelecimento de processos, buscando maior eficiência\n* Padronização e coordenação técnica das atividades de certificação e de vigilância continuada na área de competência da Gerência-Geral de Aeronavegabilidade Continuada\n* Realização de auditorias periódicas no âmbito das gerências e gerências técnicas da GGAC\n* Monitoramento, através de indicadores de produtividade e desempenho, da execução das atividades de certificação e de vigilância continuada na área de competência da Gerência-Geral de Aeronavegabilidade Continuada.",
        "rdf:type": "org:OrganizationUnit",
        "skos:preflabel": "GCVC",
        "element type": "Organization"
      }
    },
    {
      "_id": "elem-FzsZtzvs",
      "attributes": {
        "label": "Pedro Henrique Leite Paludo",
        "rdf:type": "foaf:Person",
        "element type": "Person"
      }
    },
    {
      "_id": "elem-GD5nl9yn",
      "attributes": {
        "label": "ANAC",
        "description": "# National Civil Aviation Agency (ANAC), Brazil.\n\n[Acesse na íntegra a Portaria de Organização Interna](https://www.anac.gov.br/assuntos/legislacao/legislacao-1/boletim-de-pessoal/2017/19/bps-no-19-de-12-de-maio-de-2017.pdf)\n\nFonte: https://www.anac.gov.br/acesso-a-informacao/institucional/gerencias e demais documentos abertos publicados nos canais oficiais do órgão.\n\n## Selecionar grupo de elementos\n\n* [Pessoas](=[\"element type\"=\"Person\"]) - azul claro\n* [Estrutura Organizacional](=[\"element type\"=\"Organization\"]) - azul escuro\n* [Serviços](=[\"element type\"=\"Service\"]) - verde claro\n* [Projetos](=[\"element type\"=\"Project\"]) - verde escuro\n* [Bases de dados](=[\"element type\"=\"Database\"]) - rosa\n* [Caixa de ferramentas](=[\"element type\"=\"#Tools\"]) - vermelho\n\n## Lista de elementos em exibição no grafo (padrão = todos)\n\n### Pessoas (_Person_)\n[[list/person]]\n\n### Estrutura Organizacional (_Organization_)\n[[list/organization]]\n\n### Serviços (_Service_)\n[[list/service]]\n\n### Projetos (_Project_)\n[[list/project]]\n\n### Bases de dados (_Database_)\n[[list/database]]\n\n## XML do Governo Federal\n* https://estruturaorganizacional.dados.gov.br/id/unidade-organizacional/86144\nThis XML file does not appear to have any style information associated with it. The document tree is shown below.\n\n~~~xml\n<resultadoConsultarUnidadeResumida>\n<servico>\n<codigoErro>0</codigoErro>\n<data>2020-08-12</data>\n<ipRequisitante>xxx.xxx.xxx.xxx</ipRequisitante>\n<mensagem>Processamento sem erros</mensagem>\n<versaoServico>3.7.1</versaoServico>\n</servico>\n<unidade>\n<codigoEsfera>https://estruturaorganizacional.dados.gov.br/id/esfera/federal</codigoEsfera>\n<codigoNaturezaJuridica>https://estruturaorganizacional.dados.gov.br/id/natureza-juridica/autarquia</codigoNaturezaJuridica>\n<codigoOrgaoEntidade>https://estruturaorganizacional.dados.gov.br/id/unidade-organizacional/86144</codigoOrgaoEntidade>\n<codigoPoder>https://estruturaorganizacional.dados.gov.br/id/poder/executivo</codigoPoder>\n<codigoSubNaturezaJuridica>https://estruturaorganizacional.dados.gov.br/id/subnatureza-juridica/autarquia-especial---agencia-reguladora</codigoSubNaturezaJuridica>\n<codigoTipoUnidade>https://estruturaorganizacional.dados.gov.br/id/tipo-unidade/entidade</codigoTipoUnidade>\n<codigoUnidade>https://estruturaorganizacional.dados.gov.br/id/unidade-organizacional/86144</codigoUnidade>\n<codigoUnidadePai>https://estruturaorganizacional.dados.gov.br/id/unidade-organizacional/2846</codigoUnidadePai>\n<dataInicialVersaoConsulta>2020-08-06</dataInicialVersaoConsulta>\n<nivelNormatizacao>LEI_DECRETO</nivelNormatizacao>\n<nome>Agência Nacional de Aviação Civil</nome>\n<sigla>ANAC</sigla>\n<versaoConsulta>110.4.0</versaoConsulta>\n</unidade>\n</resultadoConsultarUnidadeResumida>\n~~~",
        "uorg-xml": "https://estruturaorganizacional.dados.gov.br/id/unidade-organizacional/86144",
        "rdf:type": "org:Organization",
        "skos:altlabel": "ANAC",
        "skos:preflabel": "Agência Nacional de Aviação Civil",
        "element type": "Organization"
      }
    },
    {
      "_id": "elem-GT7q9K3E",
      "attributes": {
        "label": "Áureo de Morais Vasconcelos",
        "rdf:type": "foaf:Person",
        "element type": "Person"
      }
    },
    {
      "_id": "elem-Gsa88UZH",
      "attributes": {
        "label": "EDIAM/Declaração de Inspeção Anual de Manutenção Eletrônica",
        "description": "Declaração de Inspeção Anual de Manutenção Eletrônica de Aeronaves é prevista no RBAC 91, recentemente a IAM foi substítuida pelo CVA e portal EDIAM está em processo de migração para o portal ECVA - Certificado de Verificação de Aeronavegabilidade Eletrônico.",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-H1GJH15H",
      "attributes": {
        "label": "Seletores e Operadores para filtros",
        "description": "## Seletores\n\nFonte: \n- https://docs.kumu.io/guides/selector-reference.html\n- https://docs.kumu.io/guides/selectors.html\n\n**Seletor**",
        "element type": "#Tools"
      }
    },
    {
      "_id": "elem-H8nOI1FC",
      "attributes": {
        "label": "Vinícius Costa e Silva",
        "element type": "Person",
        "rdf:type": "foaf:Person"
      }
    },
    {
      "_id": "elem-HTO9JmCE",
      "attributes": {
        "label": "1. Gerência-Geral de Certificação de Produto Aeronáutico (GGCP)",
        "description": "---\n### 1. Gerência-Geral de Certificação de Produto Aeronáutico (GGCP)\n> Gerente: [[Mário Igawa]]\n\nCompetências:\n\n* Emitir, suspender e extinguir certificado de tipo, certificado suplementar de tipo, certificado de organização de produção e certificado de produto aeronáutico aprovado, incluindo as respectivas especificações técnicas e suas revisões, como aplicável\n* Emitir, suspender e extinguir certificado de autorização de voo experimental\n* Emitir, suspender e extinguir autorização especial de voo, com os propósitos de entrega ou exportação de aeronave a seu comprador, voo de produção, voo de demonstração para comprador, e voo com peso superior ao peso máximo de decolagem aprovado\n* Emitir, suspender ou extinguir aprovação de aeronavegabilidade para exportação\n* Emitir, suspender e extinguir outros atestados, aprovações e autorizações relativas às atividades em seu âmbito de atuação\n* Conceder meio alternativo de demonstração de cumprimento a requisito em sua área de atuação.",
        "rdf:type": "org:OrganizationUnit",
        "element type": "Organization"
      }
    },
    {
      "_id": "elem-HYPmmfdW",
      "attributes": {
        "label": "Daniel Dias da Silva",
        "element type": "Person",
        "tags": [
          "Estruturas e interiores"
        ],
        "rdf:type": "foaf:Person"
      }
    },
    {
      "_id": "elem-HZbFlLvm",
      "attributes": {
        "label": "Lawrence Josuá Fernandes Costa",
        "rdf:type": "foaf:Person",
        "element type": "Person"
      }
    },
    {
      "_id": "elem-I5IP86bY",
      "attributes": {
        "label": "2.1.3. Gerência Técnica de Aeronavegabilidade de Brasília (GTAR/DF)",
        "element type": "Organization",
        "description": "---\n### 2.1.3. Gerência Técnica de Aeronavegabilidade de Brasília (GTAR/DF)\n> Gerente: Paulo Sérgio Degrazia Dellamora\n\nCompetências da GTAR/SP, RJ e SF\n\n* Execução de inspeção, de vistoria, de auditoria ou de atividade necessária para certificação e vigilância continuada, nas áreas de competência da Gerência-Geral de Aeronavegabilidade Continuada\n* Avaliação e aprovação ou aceitação de documentos e processos relacionados às atividades de manutenção das empresas aéreas, organizações de manutenção aeronáutica, aviação geral e aeronaves civis\n* Realização de exame prático visando à habilitação de mecânico de manutenção aeronáutica e execução de atividades relacionadas com o credenciamento de examinadores de mecânico de manutenção\n* Orientação, supervisão e monitoramento de pessoas credenciadas, em sua área de atuação.",
        "rdf:type": "org:OrganizationUnit",
        "skos:preflabel": "GTAR/DF"
      }
    },
    {
      "_id": "elem-I5pGv1xR",
      "attributes": {
        "label": "11. Obter Certificado de Aeronavegabilidade Especial para Aeronave Leve Esportiva",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-IgRZwaxA",
      "attributes": {
        "label": "Antonio José Parente",
        "rdf:type": "foaf:Person",
        "element type": "Person"
      }
    },
    {
      "_id": "elem-IrcYbG14",
      "attributes": {
        "label": "Seth Emanuel Couto Melo Filho",
        "element type": "Person",
        "rdf:type": "foaf:Person"
      }
    },
    {
      "_id": "elem-IsW4KT5T",
      "attributes": {
        "label": "02. Supervisão de PCA utilizando avaliação de risco",
        "description": "SEI nº 00058.028167/2020-21 (Projeto Setorial)\nSEI nº 00058.034119/2020-72 (GTPL)",
        "rdf:type": "foaf:Project",
        "skos:preflabel": "Supervisão de PCA utilizando avaliação de risco",
        "element type": "Project"
      }
    },
    {
      "_id": "elem-J4Ac1QjC",
      "attributes": {
        "label": "5. Obter Atestado de Produto Aeronáutico Aprovado",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-JW5klVvF",
      "attributes": {
        "label": "Willer A. da Silva Cruz",
        "rdf:type": "foaf:Person",
        "element type": "Person"
      }
    },
    {
      "_id": "elem-JcDTeBnO",
      "attributes": {
        "label": "Carlos Eduardo Pessanha Couto",
        "tags": [
          "Sistema de qualidade",
          "Motor a reação",
          "Motor convencional",
          "Sistema de Gerenciamento de Segurança Operacional"
        ],
        "description": "Servidor efetivo da [[GTGC]]\n\nFormado na área de Gestão\n\nExperiência profissional: mecânico de motores, boroscopoia.",
        "status": "Bad",
        "rdf:type": "foaf:Person",
        "element type": "Person"
      }
    },
    {
      "_id": "elem-Jnb9Hei3",
      "attributes": {
        "label": "2. Gerência-Geral de Aeronavegabilidade Continuada (GGAC)",
        "element type": "Organization",
        "description": "---\n### 2. Gerência-Geral de Aeronavegabilidade Continuada (GGAC)\n> Gerente: [[Hélio Tarquínio Júnior]]\n\nCompetências:\n\n* Emitir, suspender e extinguir certificado de organização de manutenção e as respectivas especificações e suas revisões\n* Emitir parecer e aprovar as atividades de manutenção das empresas de transporte aéreo\n* Emitir, suspender e extinguir certificado de aeronavegabilidade, padrão ou especial, em sua área de atuação aprovar ou aceitar, suspender e extinguir documentos inerentes aos processos de sua competência, incluindo Programa de Manutenção e Manual Geral de Manutenção\n* Emitir, suspender e extinguir outros atestados, aprovações e autorizações relativas às atividades em seu âmbito de atuação\n* Conceder meio alternativo de demonstração de cumprimento a requisito em sua área de atuação.",
        "rdf:type": "org:OrganizationUnit",
        "skos:preflabel": "GGAC"
      }
    },
    {
      "_id": "elem-K5OHQR6g",
      "attributes": {
        "label": "23. Obter vistoria técnica em aeronave",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-KGCTM8W3",
      "attributes": {
        "label": "Nelson Eisaku Nagamine",
        "element type": "Person",
        "rdf:type": "foaf:Person"
      }
    },
    {
      "_id": "elem-KK82w1VS",
      "attributes": {
        "label": "23. Obter vistoria técnica em aeronave",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-KPVv0bsD",
      "attributes": {
        "label": "17. Obter Parecer Técnico sobre requisitos de Aeronavegabilidade",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-KUM3dqLJ",
      "attributes": {
        "label": "15. Obter Emenda a um Certificado Suplementar de Tipo (CST) de Produto Aeronáutico",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-LCn4kQIP",
      "attributes": {
        "label": "15. Revisão das Resoluções nº 293/2013 e 309/2014",
        "element type": "Project",
        "rdf:type": "foaf:Project"
      }
    },
    {
      "_id": "elem-LSkMjNDA",
      "attributes": {
        "label": "FDH/CHOPP/Produtos",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-M02XKNsE",
      "attributes": {
        "label": "Letícia Paraguassu",
        "rdf:type": "foaf:Person",
        "element type": "Person"
      }
    },
    {
      "_id": "elem-MayMOEo0",
      "attributes": {
        "label": "14. RAB Digital",
        "element type": "Project",
        "rdf:type": "foaf:Project"
      }
    },
    {
      "_id": "elem-MqTTLKR4",
      "attributes": {
        "label": "19. Obter um Certificado de Organização da Produção (COP) com Registro de Limitação da Produção (RLP)",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-MxFkHzoU",
      "attributes": {
        "label": "6. Gerência Técnica de Planejamento (GTPL)",
        "description": "---\n### 6. Gerência Técnica de Planejamento\n> Gerente: [[Mariana de Sousa Rosa Vieira]]\n\nCompetências da GTPL\n\nI - Propor e acompanhar o planejamento financeiro da SAR.\nII - Propor ao Superintendente de Aeronavegabilidade a metodologia de acompanhamento de metas institucionais e demais indicadores que suportem o alcance dos objetivos da SAR.\nIII - Estabelecer a metodologia e aplicabilidade da gestão de riscos dos processos.\nIV - Monitorar a execução do processo de manifestação de usuários.\nV - Estabelecer a política de capacitação e desenvolvimento dos colaboradores da SAR, em consonância com o disposto pela Superintendência de Gestão de Pessoas.\nVI - Promover a melhoria contínua dos processos de trabalho da SAR.\nVII - Estabelecer e aprimorar metodologia para desenvolvimento de sistemas atrelados a melhorias de processos.\nVIII - Estabelecer e aprimorar continuamente a metodologia de gerenciamento dos projetos setoriais.\nIX - Estabelecer e aprimorar continuamente a metodologia para o planejamento e gestão do orçamento da SAR.\n\nFonte: [Portaria de Organização Interna (POI) nº 3.881, de 29 de dezembro de 2020](https://www.anac.gov.br/assuntos/legislacao/legislacao-1/boletim-de-pessoal/2020/53/bps-no-53-de-31-de-dezembro-de-2020.pdf)",
        "data de início": "10/16/2020",
        "fonte da informação": "DOU",
        "fonte da informação-url": "https://www.in.gov.br/en/web/dou/-/resolucao-n-581-de-21-de-agosto-de-2020-273916813",
        "vigente": "Sim",
        "rdf:type": "org:OrganizationUnit",
        "skos:preflabel": "GTPL",
        "element type": "Organization"
      }
    },
    {
      "_id": "elem-MxJfia8J",
      "attributes": {
        "label": "12. Obter Certificado de Autorização de Voo Experimental",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-N2bWYF8z",
      "attributes": {
        "label": "9. Obter certificação de organização de manutenção de produto aeronáutico doméstica",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-NSiFmTmM",
      "attributes": {
        "label": "Henrique Shimanuki Muta",
        "rdf:type": "foaf:Person",
        "element type": "Person"
      }
    },
    {
      "_id": "elem-NmgEzBRr",
      "attributes": {
        "label": "3. Avaliação do relatório JATR-Joint Authorities Technical Review (B737MAX)",
        "description": "SEI nº",
        "rdf:type": "foaf:Project",
        "element type": "Project"
      }
    },
    {
      "_id": "elem-O3q6blzk",
      "attributes": {
        "label": "Rogério Possi Júnior",
        "element type": "Person",
        "rdf:type": "foaf:Person"
      }
    },
    {
      "_id": "elem-O4OHWP74",
      "attributes": {
        "label": "Nelson Eisaku Nagamine",
        "rdf:type": "foaf:Person",
        "element type": "Person"
      }
    },
    {
      "_id": "elem-O6KMBKrS",
      "attributes": {
        "label": "1. Autorização de Fabricação de Embalagem para Transporte Aéreo de Produtos Perigosos",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-OLEuMx5N",
      "attributes": {
        "label": "Navegação",
        "element type": "#Tools",
        "description": "## Dicas de navegação no grafo\n\n    Scroll \npara aumentar e diminuir o zoom\n\n    Clique e arraste \n\nmover-se\n\n    Pressione \\ \n\npara ajustar o zoom ao mapa\n\n    Pressione tab \n\npara ocultar / mostrar esta barra lateral\n\n    Clique nos elementos \n\npara ver informações detalhadas\n\n    Click em um elemento e pressione 1 \n\npara focar em suas conexões\n\n     Pare o cursor sobre os elementos \n\npara mostrar suas conexões\n\n    Pressione S\n\npara ativar a barra de pesquisa"
      }
    },
    {
      "_id": "elem-P50G9DTc",
      "attributes": {
        "label": "Carlos Eduardo Pessanha Couto",
        "element type": "Person",
        "tags": [
          "Sistema de qualidade",
          "Motor a reação",
          "Motor convencional",
          "Sistema de Gerenciamento de Segurança Operacional"
        ],
        "description": "Servidor efetivo da [[GTGC]]\n\nFormado na área de Gestão\n\nExperiência profissional: mecânico de motores, boroscopoia.",
        "status": "Bad",
        "rdf:type": "foaf:Person"
      }
    },
    {
      "_id": "elem-PIXDUMsO",
      "attributes": {
        "label": "Curador não identificado",
        "tags": [
          "Quality control"
        ],
        "description": "Elemento exclusivo para identificar bases de dados sem curadores designados pela superintendência.",
        "status": "Bad",
        "rdf:type": "foaf:Person",
        "element type": "Person"
      }
    },
    {
      "_id": "elem-PIzc4EKH",
      "attributes": {
        "label": "1. Autorização de Fabricação de Embalagem para Transporte Aéreo de Produtos Perigosos",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-PSPRRA2S",
      "attributes": {
        "label": "26. Solicitar cancelamento de matrícula de aeronaves",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-Q37be8pi",
      "attributes": {
        "label": "AERONAVE/RRAB",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-Q6wnZTfA",
      "attributes": {
        "label": "5. Gerência Técnica de Gestão do Conhecimento de Aeronavegabilidade (GTGC)",
        "element type": "Organization",
        "description": "---\n### 5. Gerência Técnica de Gestão do Conhecimento de Aeronavegabilidade (GTGC)\n> Gerente: [[Henrique Shimanuki Muta]]\n\nPara assuntos de credenciamento de pessoas, contatar a ACP – Assessoria de Credenciamento de Profissionais\nE-mail: [credenciamento.sar@anac.gov.br](mailto:credenciamento.sar@anac.gov.br) \n\nCompetências:\n\n* Coordenação e estabelecimento de ações estratégicas, no que tange à aquisição, preservação e disseminação de conhecimentos de interesse da Superintendência\n* Planejamento, coordenação e controle da formação dos servidores alocados na Superintendência, observando procedimentos e orientações estabelecidos pela Superintendência de Gestão de Pessoas\n* Administração dos registros de capacitação\n* Administração do sistema de credenciamento de pessoas, no âmbito da Superintendência",
        "rdf:type": "org:OrganizationUnit",
        "skos:preflabel": "GTGC"
      }
    },
    {
      "_id": "elem-QAZFc6ON",
      "attributes": {
        "label": "EAEV",
        "description": "automatizar a solicitação e emissão de autorizações de especiais de voo que constam no MPR-100  capítulo 10 feita por empresas aéreas e de manutenção com o objetivo de transladar ou efetuar voos de teste em aeronaves com certificado de aeronavegabilidade inválida.",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-QD3KHlKW",
      "attributes": {
        "label": "Modelo Markdown",
        "description": "Fonte: https://docs.kumu.io/guides/markdown.html (inglês)\n\n# Markdown\n\nO Markdown é uma maneira fácil e poderosa de formatar suas descrições e campos de texto longo usando uma sintaxe simples e natural.\n\n\n## O básico\n\n```\n_itálico_ e **negrito**\n```\n_itálico_ e **negrito**\n\n```\nUm link embutido: [Kumu](http://launch.kumupowered.com)\n```\nUm link embutido: [Kumu](http://launch.kumupowered.com)\n```\nUm link gerado automaticamente: http://launch.kumupowered.com\n```\nUm link gerado automaticamente: http://launch.kumupowered.com\n\n```\nE-mail: [email-Anac@anac.gov.br](mailto:email-Anac@anac.gov.br)\n```\nE-mail: [email-Anac@anac.gov.br](mailto:email-Anac@anac.gov.br)\n\n\n## Listas\n```\n* Milk\n* Cookies\n* Marshmallows\n```\nAparece:\n* Milk\n* Cookies\n* Marshmallows\n\n```\n 1. California\n 1. Texas\n 1. New York\n```\n\nAparece:\n1. California\n1. Texas\n1. New York\n\n\n## Imagens\n\n```\n![texto descritivo para cegos](imagem-url)\n```\n\nSubstitua _texto para cegos_ por uma legenda da imagem que os assistentes de leitores de tela possam ler e substitua _imagem-url_ por um link para sua imagem.\n\n\n## Vídeos\n\n```\n![texto descritivo para cegos](https://www.youtube.com/embed/iORN_mRpkMI)\n```\nVeja o código de incorporação (_embed_) do vídeo que deseja incorporar e pegue o URL. Exemplo acima com o YouTube.\n\nAparece:\n\n![](https://www.youtube.com/embed/iORN_mRpkMI)\n\n\n## Cabeçalhos\n\n```\n# Título 1\n## Título 2\n### Título 3\n#### Título 4\n##### Título 5\n###### Título 6\n```\n\nAparece:\n# Título 1\n## Título 2\n### Título 3\n#### Título 4\n##### Título 5\n###### Título 6\n\n\n## Citações em bloco\n\n```\n> Adicione o texto da citação aqui\n```\n\nAparece:\n\n> Adicione o texto da citação aqui\n\n\n## Tabelas\n\n```\nUm",
        "element type": "#Tools"
      }
    },
    {
      "_id": "elem-QJ5H2QP3",
      "attributes": {
        "label": "6. Gerência Técnica de Planejamento e Acompanhamento (GTPA)",
        "description": "---\n### 6. Gerência Técnica de Planejamento e Acompanhamento (GTPA)\n> Gerente: [[Lawrence Josuá Fernandes Costa]]\n\nPara assuntos de julgamento de primeira instância, contatar o Setor Julgamento em Primeira Instância – JPI\nE-mail: [julgamentoAI.SAR@anac.gov.br](mailto:julgamentoAI.SAR@anac.gov.br )\n\nCompetências:\n\n* Desenvolvimento e coordenação de atividades de planejamento\n* Acompanhamento e supervisão, junto às demais unidades da Superintendência, do cumprimento do planejamento e dos planos de trabalho estabelecidos\n* Atuação como Área Local de Gestão de Processos - ALGP da SAR, no que diz respeito ao mapeamento de processos e suporte à aprovação de manual de procedimentos\n* Assessoramento, análise e guarda dos processos administrativos instaurados por autos de infração visando emissão de decisões de primeira instância, relativos à área de competência da Superintendência.",
        "data de fim": "2020-10-15",
        "data de início": "06/14/2016",
        "vigente": "Não",
        "rdf:type": "org:OrganizationUnit",
        "skos:preflabel": "GTPA",
        "element type": "Organization"
      }
    },
    {
      "_id": "elem-QRLglCS2",
      "attributes": {
        "label": "6. Obter autorização especial de voo - AEV",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-QWc80C3n",
      "attributes": {
        "label": "Willer A. da Silva Cruz",
        "element type": "Person",
        "rdf:type": "foaf:Person"
      }
    },
    {
      "_id": "elem-Qcotv8al",
      "attributes": {
        "label": "Modelo Markdown",
        "element type": "#Tools",
        "description": "Fonte: https://docs.kumu.io/guides/markdown.html (inglês)\n\n# Markdown\n\nO Markdown é uma maneira fácil e poderosa de formatar suas descrições e campos de texto longo usando uma sintaxe simples e natural.\n\n\n## O básico\n\n```\n_itálico_ e **negrito**\n```\n_itálico_ e **negrito**\n\n```\nUm link embutido: [Kumu](http://launch.kumupowered.com)\n```\nUm link embutido: [Kumu](http://launch.kumupowered.com)\n```\nUm link gerado automaticamente: http://launch.kumupowered.com\n```\nUm link gerado automaticamente: http://launch.kumupowered.com\n\n```\nE-mail: [email-Anac@anac.gov.br](mailto:email-Anac@anac.gov.br)\n```\nE-mail: [email-Anac@anac.gov.br](mailto:email-Anac@anac.gov.br)\n\n\n## Listas\n```\n* Milk\n* Cookies\n* Marshmallows\n```\nAparece:\n* Milk\n* Cookies\n* Marshmallows\n\n```\n 1. California\n 1. Texas\n 1. New York\n```\n\nAparece:\n1. California\n1. Texas\n1. New York\n\n\n## Imagens\n\n```\n![texto descritivo para cegos](imagem-url)\n```\n\nSubstitua _texto para cegos_ por uma legenda da imagem que os assistentes de leitores de tela possam ler e substitua _imagem-url_ por um link para sua imagem.\n\n\n## Vídeos\n\n```\n![texto descritivo para cegos](https://www.youtube.com/embed/iORN_mRpkMI)\n```\nVeja o código de incorporação (_embed_) do vídeo que deseja incorporar e pegue o URL. Exemplo acima com o YouTube.\n\nAparece:\n\n![](https://www.youtube.com/embed/iORN_mRpkMI)\n\n\n## Cabeçalhos\n\n```\n# Título 1\n## Título 2\n### Título 3\n#### Título 4\n##### Título 5\n###### Título 6\n```\n\nAparece:\n# Título 1\n## Título 2\n### Título 3\n#### Título 4\n##### Título 5\n###### Título 6\n\n\n## Citações em bloco\n\n```\n> Adicione o texto da citação aqui\n```\n\nAparece:\n\n> Adicione o texto da citação aqui\n\n\n## Tabelas\n\n```\nUm"
      }
    },
    {
      "_id": "elem-QzdSUHvC",
      "attributes": {
        "label": "2. Gerência-Geral de Aeronavegabilidade Continuada (GGAC)",
        "description": "---\n### 2. Gerência-Geral de Aeronavegabilidade Continuada (GGAC)\n> Gerente: [[Hélio Tarquínio Júnior]]\n\nCompetências:\n\n* Emitir, suspender e extinguir certificado de organização de manutenção e as respectivas especificações e suas revisões\n* Emitir parecer e aprovar as atividades de manutenção das empresas de transporte aéreo\n* Emitir, suspender e extinguir certificado de aeronavegabilidade, padrão ou especial, em sua área de atuação aprovar ou aceitar, suspender e extinguir documentos inerentes aos processos de sua competência, incluindo Programa de Manutenção e Manual Geral de Manutenção\n* Emitir, suspender e extinguir outros atestados, aprovações e autorizações relativas às atividades em seu âmbito de atuação\n* Conceder meio alternativo de demonstração de cumprimento a requisito em sua área de atuação.",
        "rdf:type": "org:OrganizationUnit",
        "skos:preflabel": "GGAC",
        "element type": "Organization"
      }
    },
    {
      "_id": "elem-REyXKaVW",
      "attributes": {
        "label": "Daniel Dias da Silva",
        "tags": [
          "Estruturas e interiores"
        ],
        "rdf:type": "foaf:Person",
        "element type": "Person"
      }
    },
    {
      "_id": "elem-RmSB2vpi",
      "attributes": {
        "label": "Paulo Sérgio Degrazia Dellamora",
        "element type": "Person",
        "rdf:type": "foaf:Person"
      }
    },
    {
      "_id": "elem-S6xD6yik",
      "attributes": {
        "label": "Rosemberg Andre da Silva",
        "element type": "Person",
        "rdf:type": "foaf:Person"
      }
    },
    {
      "_id": "elem-SCl1vxLa",
      "attributes": {
        "label": "Marco Aurelio Bonilauri Santin",
        "rdf:type": "foaf:Person",
        "element type": "Person"
      }
    },
    {
      "_id": "elem-SoLpWH3a",
      "attributes": {
        "label": "Henri Salvatore Bigatti",
        "element type": "Person",
        "rdf:type": "foaf:Person"
      }
    },
    {
      "_id": "elem-T98wNZly",
      "attributes": {
        "label": "FDH/CHOPP/Produtos",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-TOwNVoQR",
      "attributes": {
        "label": "24. Realizar Emenda a Certificado de Organização de Manutenção de Produto Aeronáutico ou às suas Especificações Operativas",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-TmnCRJAO",
      "attributes": {
        "label": "FDH/CHOPP/Manuais de voo",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-Tn32YPjI",
      "attributes": {
        "label": "13. Obter Certificado de Tipo",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-UJK7Dtoe",
      "attributes": {
        "label": "Edson Souza de Jesus Filho",
        "rdf:type": "foaf:Person",
        "element type": "Person"
      }
    },
    {
      "_id": "elem-UuNJF4qP",
      "attributes": {
        "label": "Planilha SIGA/Planilha SIGA",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-VegmAZds",
      "attributes": {
        "label": "Maria Clara Costa Teixeira",
        "element type": "Person",
        "rdf:type": "foaf:Person"
      }
    },
    {
      "_id": "elem-W7GDqyLN",
      "attributes": {
        "label": "Paulo Sérgio Degrazia Dellamora",
        "rdf:type": "foaf:Person",
        "element type": "Person"
      }
    },
    {
      "_id": "elem-WVOmZm7u",
      "attributes": {
        "label": "Controle de certificados temporários/Controle de certificados temporários",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-Wl6a3IzV",
      "attributes": {
        "label": "PQs",
        "element type": "Audit",
        "status": "Bad",
        "description": "| PQ NO. | PROTOCOL QUESTION                                                                                                                                                                                                                                                                                                                                                                                                                                                 | GUIDANCE FOR REVIEW OF EVIDENCE                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | ICAO REFERENCES                                                                                                                                                                                                                                                                                                   | CE   | SHARED<br>PQ | PRIMARY RESP<br>DEPARTMENT | SHARED RESP<br>DEPARTMENT | RESP<br>UNIT                 | LINKED<br>PROCESS                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | NOTES                                              |\n| ------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---- | ------------ | -------------------------- | ------------------------- | ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------- |\n| 5.001  | Has the State promulgated airworthiness regulations to transpose the airworthiness-related provisions of Annexes 6, 7, 8, 16 and 19?                                                                                                                                                                                                                                                                                                                              | 1) Title and content.<br>2) Date of promulgation and last amendment.<br>3) Verify for:<br>\\-Annex 6, Part I<br>\\-Annex 6, Part II<br>\\-Annex 6, Part III<br>\\-Annex 7-Annex 8<br>\\-Annex 16, Volume I<br>\\-Annex 16, Volume II<br>\\-Annex 19                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | CC<br>Art. 12<br>GM<br>Doc 9734<br>Part A, C2 & C3<br>Doc 9760<br>Part II, 3.2                                                                                                                                                                                                                                    | CE-2 | Não          | SAR                        | n/a                       | GTPN                         | MPR 301<br>Processo Normativo na SAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | n/a                                                |\n| 5.003  | Has the State promulgated a national code of airworthiness, or adopted and promulgated the code of airworthiness from another State, or specified in its regulations the type certificates/related airworthiness codes from identified States of Design as basis for acceptance?                                                                                                                                                                                  | Review<br>\\-national code of airworthinessor<br>\\-adopted code of airworthiness from another Stateor<br>\\-regulations specifying type certificates/related airworthiness codes from identified States of Design as basis for acceptance.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | STD<br>A8<br>Foreword & Part I<br>(Definitions)                                                                                                                                                                                                                                                                   | CE-2 | SIM          | Poder Legislativo          | SAR                       | GTPN                         | \\[1\\] - Law 7565/1986<br>\\[2\\] - Law 11182/2005<br>\\[3\\] - Law 7565/1986 (art. 66 to 71)<br>\\[4\\] - Law 7565/1986 (art. 114)<br>\\[5\\] - Resolution Nº30/2008                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | n/a                                                |\n| 5.005  | Has the State implemented procedures for the amendment of its enabling regulations and national standards?                                                                                                                                                                                                                                                                                                                                                        | 1) Documented evidence of effective implementation of procedures for the amendment of regulations.<br>2) Amendments of regulations effected in a timely manner whenever an amendment to<br>Annexes 6, Parts I, II, and III, 7, 8 and 16 are received.<br>3) Verify the action taken by the State after receipt of the last amendments.<br>4) The development of these procedures is addressed in LEG PQ 1.009.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | CC<br>Art. 37<br>GM<br>Doc 9734<br>Part A, C3                                                                                                                                                                                                                                                                     | CE-2 | Não          | SAR                        | n/a                       | GTPN                         | \\[1\\] MPR/SAR-301-R00<br>\\[2\\] MPR/SAR-501-R00<br>Acordos e Relacionamento com a ICAO                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | n/a                                                |\n| 5.007  | Has the State implemented procedures for identifying and notifying differences, if any, to ICAO?                                                                                                                                                                                                                                                                                                                                                                  | \\* Documented evidence of effective implementation.<br>\\* The development of these procedures is addressed in LEG PQ 1.025.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | CC<br>Art. 37 & 38<br>GM<br>Doc 9734<br>Part A, C3                                                                                                                                                                                                                                                                | CE-2 | Não          | SAR                        | n/a                       | GTPN                         | \\[1\\] MPR/SAR-301-R00<br>\\[2\\] MPR/SAR-501-R00                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | n/a                                                |\n| 5.009  | If the State has adopted airworthiness regulations from another State/organization, has it implemented procedures for ensuring that its regulations are amended as needed subsequent to an Annex amendment or an amendment by the originating State/organization?                                                                                                                                                                                                 | 1) Verify regulatory framework.<br>2) Confirm implementation of the procedures when:<br>a) amendments are made by the originating State/organization.<br>b) airworthiness-related Annexes are amended.<br>3) Review a sample case.<br> <br>\\- The development of these procedures is addressed in LEG PQ 1.029.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | CC<br>Art. 37 & 38<br>GM<br>Doc 9734<br>Part A, C3                                                                                                                                                                                                                                                                | CE-2 | Não          | SAR                        | n/a                       | GTPN                         | \\[1\\] - Resolution Nº 30/2008, art. 2º e 3º<br>\\[2\\] - IN 15/2008,  art. 6º<br>\\[3\\] MPR/SAR-301-R00                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | n/a                                                |\n| 5.011  | Has the State established means to ensure that copies of the airworthiness enabling regulations and directives, orders, circulars, publications, etc. are readily available to the public?                                                                                                                                                                                                                                                                        | Verify the means available to access the regulations and supplementary regulatory instruments(i.e. Official Gazette; internet, government printing office).<br><br>\\-The publication of legislation is addressed in LEG PQ 1.011.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | GM<br>Doc 9734<br>Part A, C3                                                                                                                                                                                                                                                                                      | CE-2 | Não          | SAR                        | n/a                       | GTPN                         | \\[1\\] - ANAC website                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | n/a                                                |\n| 5.013  | Has the State implemented procedures for the granting of exemptions?                                                                                                                                                                                                                                                                                                                                                                                              | Verify:<br>a) effective implementation of procedures.<br>b) system for recording and publishing exemptions granted.<br>c) examples of exemptions granted in the area of airworthiness.<br>d) criteria used for the risk assessment before granting the exemption.<br><br>Notes to the auditor:<br>\\-The legal/regulatory basis for the granting of exemptions is addressed in LEG PQ 1.027.<br>\\-The establishment of a policy and procedures for the granting of exemptions is addressed in LEG PQ 1.028.<br>\\-The term “exemptions” also includes exceptions, deviations and prolonged extensions.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | GM<br>Doc 9734<br>Part A, C3<br>Doc 9760<br>Part II, 3.1.6                                                                                                                                                                                                                                                        | CE-2 | Não          | SAR                        | n/a                       | GTPN                         | \\[1\\] RBAC 11 Subpart C<br>\\[2\\] MPR 301/SAR<br>\\[3\\] IN107/2016                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | n/a                                                |\n| 5.021  | Has the State established an organizational structure for the airworthiness inspection division (AID)?                                                                                                                                                                                                                                                                                                                                                            | Confirm current approved organizational structure for AID, including lines of responsibility.<br> <br>\\- This PQ is not linked to ORG PQ 2.010.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | STD<br>A6<br>Part I, App. 5, 3.1<br>Part III, App. 1, 3.1<br>A19<br>App. 1, 3.1<br>GM<br>Doc 9734<br>Part A, C3 <br>Doc 9760<br>Part II, 4.7.1                                                                                                                                                                    | CE-3 | Não          | SAR                        | n/a                       | GGAC                         | Resolution 110, ANAc                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | n/a                                                |\n| 5.023  | Are all the functions and responsibilities of the AID clearly defined?                                                                                                                                                                                                                                                                                                                                                                                            | Review document detailing functions and responsibilities of the AID.<br> <br>\\- This PQ is not linked to ORG PQ 2.011.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | STD<br>A6<br>Part I, App. 5, 3.1<br>Part III, App. 1, 3.1<br>A19<br>App. 1, 3.1<br>GM<br>Doc 9760<br>Part II, 4.7                                                                                                                                                                                                 | CE-3 | Não          | SAR                        | n/a                       | GGAC                         | Resolution 110, ANAc                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | n/a                                                |\n| 5.027  | Have job descriptions been developed for technical staff and key management personnel of the AID?                                                                                                                                                                                                                                                                                                                                                                 | Verify job descriptions for AID staff, including:<br>aircraft register staff.<br>airworthiness inspectors.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | GM<br>Doc 9734<br>Part A, C3 Doc 9760<br>Part II, 4.7                                                                                                                                                                                                                                                             | CE-3 | Não          | SAR                        | n/a                       | GGAC                         | ANAC IN 101                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | n/a                                                |\n| 5.029  | If the State is involved in the provision of aircraft operations or maintenance of aircraft, is there a clear separation of authority between the State operating agency and the State regulatory authority?                                                                                                                                                                                                                                                      | Verify separation provisions.<br>Documented evidence of the method used to ensure separation of authority.<br> <br>\\- This PQ is linked to ORG PQ 2.021.<br>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | GM<br>Doc 9734<br>Part A, C2<br>Doc 9760<br>Part II, 1.1.9                                                                                                                                                                                                                                                        | CE-3 | n/a          | n/a                        | n/a                       | n/a                          | n/a                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | n/a                                                |\n| 5.031  | Has the State established appropriate minimum qualifications and experience requirements for airworthiness inspectors?                                                                                                                                                                                                                                                                                                                                            | Verify that criteria include:<br>1) relevant knowledge, background and appropriate experience related to aircraft continuing airworthiness management;<br><br>2) aeronautical licences, certificates or academic degrees commensurate with their job responsibilities, and<br><br>3) operational and technical work experience compatible with the activities they are required to certify or inspect.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | STD<br>A19<br>App. 1, 4.1<br>GM<br>Doc 9734<br>Part A, C3<br>Doc 9760<br>Part II, 4.5.1, 4.5.3, 4.5.4<br>& 4.5.5.1                                                                                                                                                                                                | CE-4 | Não          | SAR                        | n/a                       | GGAC                         | PPC, page 49                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | n/a                                                |\n| 5.032  | Does the State ensure that the established minimum qualification and experience requirements are met by all airworthiness inspectors?                                                                                                                                                                                                                                                                                                                             | Sample recruitment files.<br>Cross-check with established requirements.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | STD<br>A19<br>App. 1, 4.1<br>GM<br>Doc 9734<br>Part A, C3<br>Doc 9760<br>Part II, 4.5.1, 4.5.3 &<br>4.5.4                                                                                                                                                                                                         | CE-4 | Não          | SAR                        | n/a                       | GGAC                         | n/a                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | n/a                                                |\n| 5.033  | Does the AID have sufficient human resources to carry out its functions and mandate?                                                                                                                                                                                                                                                                                                                                                                              | Verify:<br>1) methodology established for determining staffing needs.<br>2) ability to attract new airworthiness inspectors as well as existing vacancies and level of turnover in the past years.<br>3) ability to carry out all safety oversight related tasks, including review and revision of regulations, training of technical staff, development of guidance material, issuance of certificates, approvals, and permits, conduct of surveillance and resolution of identified safety deficiencies.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | STD<br>A6<br>Part I, App. 5, 3.2<br>Part III, App. 1, 3.2<br>A19<br>App. 1, 3.1<br>RP<br>A19<br>App. 1, 3.2 & 3.4<br>GM<br>Doc 9734<br>Part A, C3<br>Doc 9760<br>Part II, 4.5.1                                                                                                                                   | CE-3 | Não          | SAR                        | n/a                       | GGAC                         | Manual MPR/SAR-422-R00 “Planning and Monitoring SAR Activities.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | n/a                                                |\n| 5.035  | Have airworthiness inspectors been issued credentials to facilitate access to aircraft and aviation facilities for the purpose of inspections?                                                                                                                                                                                                                                                                                                                    | Review credentials to ensure:<br>1) Reference to empowering legislation.<br>2) Method established to control currency of credential.<br>3) Inspector’s photo.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | STD<br>A6<br>Part I, App. 5, 1 & 3.4<br>Part III, App. 1, 1 & 3.4<br>GM<br>Doc 9734<br>Part A, C3<br>Doc 9760<br>Part II, 4.5.7                                                                                                                                                                                   | CE-3 | Não          | SAR                        | n/a                       | GGAC                         | : IN 101, June 14, 2016.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | n/a                                                |\n| 5.037  | If the AID delegates its duties to other CAA divisions, State bodies, Contracting States, regional organizations, private agencies or individuals, have requirements for competency been established?                                                                                                                                                                                                                                                             | Review competency requirements for delegated entities.<br>Review minimum qualifications and experience requirements for individuals receiving delegation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | GM<br>Doc 9734<br>Part A, C3<br>Doc 9760<br>Part II, 4.1 & 4.7.3 j)                                                                                                                                                                                                                                               | CE-4 | Não          | SAR                        | n/a                       | GGAC<br>GGCP<br>GTGC         | \\[1\\] RBAC 183<br>\\[2\\] IS 183-002<br>Processo de Credenciamento de Pessoa Física na SAR e orientações de atuação para os Profissionais Credenciados<br>\\[3\\] PI 900-02<br>                                                                                                                                                                                                                                                                                                                                                                                                                                                           | n/a                                                |\n| 5.039  | If the AID delegates its duties to other CAA divisions, State bodies, Contracting States, regional organizations, private agencies or individuals, are the delegated tasks clearly defined?                                                                                                                                                                                                                                                                       | Review documentation clearly defining the delegated tasks.<br>Verify the legal mechanism for delegation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | GM<br>Doc 9734<br>Part A, C3 Doc 9760<br>Part II, 4.1                                                                                                                                                                                                                                                             | CE-3 | Não          | SAR                        | n/a                       | GGAC<br>GGCP<br>GTGC         | \\[1\\] RBAC 183<br>\\[2\\] IS 183-002<br>Processo de Credenciamento de Pessoa Física na SAR e orientações de atuação para os Profissionais Credenciados<br>\\[3\\] PI 900-02                                                                                                                                                                                                                                                                                                                                                                                                                                                               | n/a                                                |\n| 5.041  | Does the AID conduct surveillance of tasks delegated to other CAA divisions, State bodies, Contracting States, regional organizations, private agencies or individuals?                                                                                                                                                                                                                                                                                           | 1) Review mechanism for oversight.<br>2) Review evidence to confirm effective implementation.<br>3) Maintenance of competency.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | STD<br>A19, App. 1, 7<br>GM<br>Doc 9734<br>Part A, C3<br>Doc 9760<br>Part II, 4.1 & 4.4                                                                                                                                                                                                                           | CE-7 | Não          | SAR                        | n/a                       | GGAC<br>GGCP<br>GTGC         | \\[1\\] RBAC 183<br>\\[2\\] IS 183-002<br>Processo de Credenciamento de Pessoa Física na SAR e orientações de atuação para os Profissionais Credenciados<br>\\[3\\] PI 900-02<br>\\[4\\] F-900-50                                                                                                                                                                                                                                                                                                                                                                                                                                             | n/a                                                |\n| 5.043  | If deficiencies or concerns are identified in the tasks delegated to other CAA divisions, State bodies, Contracting States, regional organizations, private agencies or individuals, does the AID have a process in place for their resolution?                                                                                                                                                                                                                   | Review examples of corrective actions taken to resolve concerns related to delegated tasks.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | STD<br>A6<br>Part I, App. 5, 5.2 & 8<br>Part III, App. 1, 5.2 & 8<br>A19<br>App. 1, 8<br>GM<br>Doc 9734<br>Part A, C3                                                                                                                                                                                             | CE-8 | Não          | SAR                        | n/a                       | GGAC<br>GGCP<br>GTGC         | \\[1\\] RBAC 183<br>\\[2\\] IS 183-002<br>Processo de Credenciamento de Pessoa Física na SAR e orientações de atuação para os Profissionais Credenciados<br>\\[3\\] PI 900-02<br>\\[4\\] F-900-51                                                                                                                                                                                                                                                                                                                                                                                                                                             | n/a                                                |\n| 5.045  | If no AED has been established, and the State approves/accepts airworthiness engineering data (modifications, repairs), how and to whom has the airworthiness engineering responsibility been assigned?                                                                                                                                                                                                                                                           | Review organization for capability to address engineering responsibilities, if required.<br> <br>This PQ is not linked to ORG PQ 2.011.<br>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | GM<br>Doc 9760<br>Part II, 4.7.1.2, 4.7.2 k),<br>4.7.3 e) & f)                                                                                                                                                                                                                                                    | CE-3 | Não          | SAR                        | n/a                       | GGCP                         | n/a                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | Como a ANAC possui um AED, essa PQ é não aplicável |\n| 5.047  | Has the AID developed a formal training programme detailing the type of training to be provided to airworthiness inspectors?                                                                                                                                                                                                                                                                                                                                      | 1) Review contents of training programme.<br><br>2) Confirm inclusion of initial, OJT, recurrent and specialized training, as applicable, with time periods to be provided.<br><br>3) Verify specialized training for:<br>a) Air operator certification<br>b) Reliability monitoring<br>c) Non-destructive testing<br>d) Avionics<br>e) Human factors<br>f) Specific operational approvals (i.e. EDTO, RVSM, CAT II/III, RNP)<br>g) Aircraft type knowledge<br>h) Ramp inspection methods.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | STD<br>A6<br>Part I, App. 5, 4<br>Part III, App. 1, 4<br>A19<br>App. 1, 4.1<br>GM<br>Doc 9683<br>Part 1, C6<br>Doc 9734<br>Part A, C3<br>Doc 9760<br>Part II, 4.5.5 & 4.5.6<br>Doc 9824<br>5.7                                                                                                                    | CE-4 | Não          | SAR                        | n/a                       | GGAC<br>GTGC                 | : PPC, page 49                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | n/a                                                |\n| 5.049  | Does the AID develop a periodic training plan detailing and prioritizing the type of training to be provided during the established period?                                                                                                                                                                                                                                                                                                                       | Review most recent training plan.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | STD<br>A6<br>Part I, App. 5, 4<br>Part III, App. 1, 4<br>A19<br>App. 1, 4.1<br>GM<br>Doc 9734<br>Part A, C3<br>Doc 9760<br>Part II, 4.5.5 & 4.5.6                                                                                                                                                                 | CE-4 | Não          | SAR                        | n/a                       | GGAC<br>GTGC                 | General Calendar of Annual Training Plan of ANAC                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | n/a                                                |\n| 5.051  | Is the training programme appropriately implemented for airworthiness inspectors?                                                                                                                                                                                                                                                                                                                                                                                 | Verify that the type and frequency of training provided (initial, recurrent and specialized) are sufficient for the technical staff to acquire/maintain the required level of knowledge, skills, competence and qualifications in accordance with their assigned duties and responsibilities.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | STD<br>A6<br>Part I, App. 5, 4<br>Part III, App. 1, 4<br>A19<br>App. 1, 4.1<br>GM<br>Doc 9734<br>Part A, C3<br>Doc 9760<br>Part II, 4.5.5 & 4.5.6                                                                                                                                                                 | CE-4 | Não          | SAR                        | n/a                       | GGAC<br>GTGC                 | “Registro de Capacitação” of SACI                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | n/a                                                |\n| 5.053  | Are airworthiness inspectors required to satisfactorily complete OJT before being assigned tasks and responsibilities?                                                                                                                                                                                                                                                                                                                                            | Verify:<br>1) requirement for the provision of OJT.<br>2) that OJT is provided by an experienced, senior inspector.<br>3) that completion of OJT is documented.<br>4) competency assessment and authorization process                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | STD<br>A19<br>App. 1, 4<br>GM<br>Doc 9734<br>Part A, C3<br>Doc 9760<br>Part II, 4.5.6                                                                                                                                                                                                                             | CE-4 | Não          | SAR                        | n/a                       | GGAC<br>GTGC                 | “Registro de Capacitação” of SACI versus PPC versus MPR 401                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | n/a                                                |\n| 5.055  | Does the AID have a system for the maintenance of training records for its technical staff?                                                                                                                                                                                                                                                                                                                                                                       | 1) Review instruction or requirement for the establishment and maintenance of training records.<br>2) Verify training records are systematically retained.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | STD<br>A19<br>App. 1, 4.2<br>GM<br>Doc 9734<br>Part A, C3<br>Doc 9760<br>Part II, 4.5.6                                                                                                                                                                                                                           | CE-4 | Não          | SAR                        | n/a                       | GGAC<br>GTGC                 | “Registro de Capacitação” of SACI                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | n/a                                                |\n| 5.101  | Are the relevant ICAO documents and other technical and regulatory publications readily available to the technical and administrative staff of the AID?                                                                                                                                                                                                                                                                                                           | Verify if relevant publications are readily available, such as:<br>State laws and regulations<br>Orders and instructions<br>Current copies of Annexes 6, Parts I, II and<br>III, 7, 8, 16 and 19<br>Copies of ICAO guidance material (i.e. Doc 9734, Doc 9735, Doc 9760, Doc 9859, CIR 295, etc.).<br> <br>Note to the auditor:<br>Check for field/regional offices as well as Headquarters.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | GM<br>Doc 9734<br>Part A, C3 Doc 9760<br>Part II, 4.9                                                                                                                                                                                                                                                             | CE-5 | Não          | SAR                        | n/a                       | GGAC                         | Technical Library access                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | n/a                                                |\n| 5.103  | Is there a technical library available for airworthiness inspectors or another method to ensure receipt, control and distribution of the necessary technical documentation?                                                                                                                                                                                                                                                                                       | Evaluate:<br>1) Document control system.<br>2) Method to determine currency of documents.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | GM<br>Doc 9734<br>Part A, C3<br>Doc 9760<br>Part II, 4.9                                                                                                                                                                                                                                                          | CE-5 | Não          | SAR                        | n/a                       | GGAC                         | Technical Library access                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | n/a                                                |\n| 5.105  | Do airworthiness inspectors have access to up-to-date design organization documentation and continuing airworthiness information to support the certificates/approvals issued for the aircraft on the State’s register?                                                                                                                                                                                                                                           | Verify accessibility and currency of documents, such as:<br>1) Aircraft flight manual<br>2) Maintenance manual<br>3) Structural repair manual<br>4) Service bulletins<br>5) Master minimum equipment list (MMEL)<br>6) Maintenance review board (MRB) report<br>7) ADs<br><br>Note to the auditor:<br>Documents may be found in the technical library in hard/electronic copy or available via the Intranet/Internet. If access to documents is dependent on industry, airworthiness inspectors should at least have an index to confirm currency of documents.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | STD<br>A8<br>Part II, 4.2.3<br>GM<br>Doc 9760<br>Part II, 4.9                                                                                                                                                                                                                                                     | CE-5 | Não          | SAR                        | n/a                       | GGAC                         | Technical Library access                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | n/a                                                |\n| 5.107  | Are airworthiness inspectors provided with comprehensive procedures and checklists to assist them in carrying out their functions in a standardized and efficient manner?                                                                                                                                                                                                                                                                                         | Verify:<br>1) availability of applicable procedures and checklists.<br>2) mechanism to issue procedures.<br>3) method to ensure currency.<br><br>Note. — May be compiled in an inspector’s handbook or in a procedures manual.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | STD<br>A6<br>Part I, App. 5, 5<br>Part III, App. 1, 5<br>A19<br>App. 1, 5.1<br>GM<br>Doc 9734<br>Part A, C3<br>Doc 9760<br>Part II, 4.7                                                                                                                                                                           | CE-5 | Não          | SAR                        | n/a                       | GGAC                         | MPR 100, MPR 900-01, 900-02, 900-03, 900-04 and 900-06. Forms F-100-32 up to F-100-97 and F-900-17 up to F-900-82.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | n/a                                                |\n| 5.109  | Does the AID have sufficient office equipment?                                                                                                                                                                                                                                                                                                                                                                                                                    | Check available communication means and office equipment:<br>1) Telephones/cellular phones<br>2) Fax<br>3) Printer<br>4) Computers/laptops/notebooks<br>5) Internet/Intranet<br>6) Photocopiers                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | STD<br>A19<br>App. 1, 5.1<br>GM<br>Doc 9734<br>Part A, C3                                                                                                                                                                                                                                                         | CE-5 | Não          | SAR                        | n/a                       | GGAC                         | Equipment available at the offices.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | n/a                                                |\n| 5.111  | Does the AID provide transportation for airworthiness inspectors to perform their duties?                                                                                                                                                                                                                                                                                                                                                                         | Review means of transportation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | STD<br>A6<br>Part I, App. 5, 3.4<br>Part III, App. 1, 3.4<br>A19<br>App. 1, 5.1<br>GM<br>Doc 9734<br>Part A, C3<br>Doc 9760<br>Part II, 4.1.2                                                                                                                                                                     | CE-5 | Não          | SAR                        | n/a                       | GGAC                         | Request using PCDP                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | n/a                                                |\n| 5.121  | Has the State promulgated regulations for the issuance of a certificate of registration?                                                                                                                                                                                                                                                                                                                                                                          | Verify regulations.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | CC<br>Art. 19<br>STD<br>A7<br>8<br>GM<br>Doc 9760<br>Part III, 2.1                                                                                                                                                                                                                                                | CE-2 | Não          | SAR                        | n/a                       | GGAC<br>GTRAB<br>GTPN        | Resolution 293, November 19, 2013                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | Incluído GTRAB e GTPN.                             |\n| 5.122  | Has the State defined in its regulations on the use for the registration marks, that no combinations shall be used which might be confused with:                                                                                                                                                                                                                                                                                                                  | Verify regulations.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | STD<br>A7<br>3.6                                                                                                                                                                                                                                                                                                  | CE-2 | Não          | SAR                        | n/a                       | GGAC                         | RBAC 45.23-I                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | n/a                                                |\n| 5.123  | Do the regulations dictate the location, measurements and type of the nationality or common and registration marks to be used on heavier than air aircraft registered in the State?                                                                                                                                                                                                                                                                               | Verify regulations address the following:<br>1) Location<br>2) Measurement<br>3) Type                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | CC<br>Art. 20<br>STD<br>A7<br>4, 5 & 6                                                                                                                                                                                                                                                                            | CE-2 | Não          | SAR                        | n/a                       | GGAC                         | RBAC 45.25, 45.27 e 45.29-I                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | n/a                                                |\n| 5.125  | Have procedures been developed for the issuance of certificate of registration and for the maintenance of the aircraft register?                                                                                                                                                                                                                                                                                                                                  | 1) Verify procedures.<br>2) Verify that aircraft must be de-registered from previous State first.<br>3) Verify that procedures indicate that no combinations shall be used which might be confused with the five-letter combinations used in the International Code of Signals, Part II, the three-letter combinations beginning with Q used in the Q Code, and with the distress signal SOS, or other similar urgent signals, for example XXX, PAN and TTT.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | CC<br>Art. 19<br>STD<br>A7<br>7 & 8<br>GM<br>Doc 9760<br>Part III, C2                                                                                                                                                                                                                                             | CE-5 | Não          | SAR                        | n/a                       | GGAC<br>GTRAB<br>GTPA        | a) Working Instruction n° ITD-181-01 –<br>b) Working Instruction n° ITD - 181-04                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | Incluído GTRAB e GTPA.                             |\n| 5.127  | Does the State maintain a current register showing for each aircraft registered the information recorded on the certificate of registration?                                                                                                                                                                                                                                                                                                                      | 1) Review register to confirm effective implementation of procedures.<br>2) Verify that the aircraft register is kept in a secure, fire-proof location or, if the register is kept electronically, that there are safeguards and backup means in place regarding protection of the electronic file.<br>3) Verify content by comparing with the certificate of registration shown in Figure 1 of Annex 7.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | STD<br>A7<br>7 & 8<br>GM<br>Doc 9760<br>Part III, 2.4                                                                                                                                                                                                                                                             | CE-6 | Não          | SAR                        | n/a                       | GGAC<br>GTRAB                | n/a                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | Incluído GTRAB.                                    |\n| 5.129  | Is the certificate of registration, in wording and arrangement, a replica of the model shown in Annex 7?                                                                                                                                                                                                                                                                                                                                                          | 1) Review certificate of registration and verify certificate content, including both the wording and the arrangement.<br>2) If not issued in English, an English translation should be included.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | STD<br>A7<br>8 & Fig. 1<br>GM<br>Doc 9760<br>Part III, 2.3.1                                                                                                                                                                                                                                                      | CE-6 | Não          | SAR                        | n/a                       | GGAC<br>GTRAB                | n/a                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | Incluído GTRAB.                                    |\n| 5.130  | Does the State ensure that an aircraft carries an identification plate inscribed with at least its nationality or common mark and registration mark, made of fireproof metal or other fireproof material of suitable physical properties and secured to the aircraft in a prominent position near the main entrance?                                                                                                                                              | Review method, procedures and/or checklists to ensure effective implementation of the requirement.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | STD<br>A7<br>9.1 & 9.2                                                                                                                                                                                                                                                                                            | CE-6 | Não          | SAR                        | n/a                       | GGAC                         | RBAC 45.30-I<br>MPR 100, item 4.2(p)<br>F-100-34 (item 3, III – Vistoria Física                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | n/a                                                |\n| 5.141  | If the State has special requirements for imported aircraft or aeronautical products to the State, are the special requirements up-to-date and available to Contracting States?                                                                                                                                                                                                                                                                                   | 1) Verify import requirements.<br>2) Review method implemented to make requirements known and verify easy access.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | GM<br>Doc 9760<br>Part III, 6.2 & 6.5.2<br>Part V, 7.4.2                                                                                                                                                                                                                                                          | CE-2 | Não          | SAR                        | n/a                       | GGCP                         | MPR 101 - Certificação de Projeto de Produto Aeronáutico + IS 21-10                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | n/a                                                |\n| 5.143  | If the State validates type certificates (TCs), have the associated regulations been promulgated?                                                                                                                                                                                                                                                                                                                                                                 | 1) Verify regulations.<br>2) Validation implies a technical review and approval issued by a State, which is not the State of Design.<br><br>Note. — If the State only accepts TCs issued by certain States of Design, this question is Not Applicable.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | STD<br>A8<br>Part II, 1.4<br>GM<br>Doc 9760<br>Part III, 4.3                                                                                                                                                                                                                                                      | CE-2 | Não          | SAR                        | n/a                       | GGCP                         | \\[1\\] RBAC 21.29<br>\\[2\\] IS 21-010                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | n/a                                                |\n| 5.145  | Have procedures for the validation of type certificates been established?                                                                                                                                                                                                                                                                                                                                                                                         | Verify that procedures include:<br>1) Review of the differences that exist between State’s national airworthiness requirements and those of the State of Design, or on those requirements where the State of Registry retains exclusive approval authority under its certification system.<br>2) At the completion of the type validation activity, confirm approval or acceptance of the type design by issuing own type certificate, or a letter of approval or acceptance.<br>3) The certification basis by which the State of Registry grants its type design approval or acceptance should be clearly documented in the type certificate data sheet or in the approval letter.                                                                                                                                                                                                                                                                                                                                                                                                                                                             | STD<br>A8<br>Part II, 1.4.2<br>GM<br>Doc 9760<br>Part III, 4.3.6 & 4.3.7                                                                                                                                                                                                                                          | CE-5 | Não          | SAR                        | n/a                       | GGCP                         | \\[1\\] - MPR/SAR-101 - section 5.4<br>\\[2\\] - ITD-101-07 - section 8.10<br>\\[3\\] - RBAC 21 - section 21.29(a)<br>\\[4\\]\\] - ITD-101-04                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | n/a                                                |\n| 5.147  | Have the procedures for type certificate validation been implemented?                                                                                                                                                                                                                                                                                                                                                                                             | Confirm effective implementation of procedures.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | STD<br>A8<br>Part II, 1.4.2<br>GM<br>Doc 9760<br>Part III, 4.3.6 & 4.3.7                                                                                                                                                                                                                                          | CE-6 | Não          | SAR                        | n/a                       | GGCP                         | ITD-101-07 - section 8.10                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | n/a                                                |\n| 5.149  | Has the AID developed procedures for the issuance of a first certificate of airworthiness for an aircraft type?                                                                                                                                                                                                                                                                                                                                                   | \\- Acceptance of aircraft design by<br>1\\. Issuance of TC (see AIR protocols Part II: Design certification and production).<br>2\\. Validation of TC issued by the State of Design.<br>3\\. Acceptance of TC issued by State of Design.<br>\\- Followed by procedures for the initial issuance of a certificate of airworthiness (see AIR PQ 5.183).<br>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | STD<br>A8<br>Part II, 3.2<br>GM<br>Doc 9760<br>Part III, C4                                                                                                                                                                                                                                                       | CE-5 | Não          | SAR                        | n/a                       | GGAC                         | MPR 100, Capítulos 4, 5 e 7, F-100-34 e F-900-39<br>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | n/a                                                |\n| 5.151  | Has the AID implemented the procedures for the issuance of a first certificate of airworthiness for an aircraft type?                                                                                                                                                                                                                                                                                                                                             | Review aircraft files to confirm effective implementation of procedures.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | STD<br>A8<br>Part II, 3.2<br>GM<br>Doc 9760<br>Part III, C4                                                                                                                                                                                                                                                       | CE-6 | Não          | SAR                        | n/a                       | GGAC                         | n/a                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | n/a                                                |\n| 5.152  | Does the State ensure that, when it first enters on its register an aircraft of a particular type for which it is not the State of Design and issues or validates a certificate of airworthiness, it advises the State of Design that it has entered such an aircraft on its register?                                                                                                                                                                            | Review examples of correspondence with the State of Design for aircraft types first entered on the State’s registry.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | STD<br>A8<br>Part II, 4.2.3 a)<br>GM<br>Doc 9760<br>Part II, 1.4.4<br>Part III, 1.2 g), 2.5.2, 9.2.2 a) & 9.3.1                                                                                                                                                                                                   | CE-6 | Não          | SAR                        | n/a                       | GGAC                         | n/a                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | n/a                                                |\n| 5.153  | Has the State promulgated regulations for operations‑derived equipment which are not part of the type certification of aircraft?                                                                                                                                                                                                                                                                                                                                  | Verify regulations for operations derived equipment, as applicable:<br>1) FDR – Ref A6, Part I, 6.3<br>2) CVR - Ref A6, Part I, 6.3<br>3) VFR flights – Ref A6, Part I, 6.4<br>4) Over water operations – Ref A6, Part I, 6.5<br>5) Flight over designated land – Ref A6, Part 1, 6.6<br>6) High altitude flights - Ref A6, Part I, 6.7 & 6.12<br>7) Icing conditions - Ref A6, Part I, 6.8<br>8) GPWS - Ref A6, Part I, 6.15<br>9) ELT - Ref A6, Part I, 6.17<br>10) ACAS - Ref A6, Part I, 6.18.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | STD<br>A6<br>Part I, C6<br>Part II, 2.4 & 3.6<br>Part III, Section II, C4 & Section III, C4                                                                                                                                                                                                                       | CE-2 | Não          | SAR                        | n/a                       | GGAC<br>GTPN                 | n/a                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | n/a                                                |\n| 5.154  | Has the State developed procedures for the verification of operations derived equipment which are not part of the type certification of aircraft?                                                                                                                                                                                                                                                                                                                 | Verify procedures and/or checklists to assess compliance of operations derived equipment, as applicable, including their installation, with the provisions of Annex 6.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | STD<br>A6<br>Part I, C6<br>Part II, 2.4 & 3.6<br>Part III, Section II, C4 & Section III, C4                                                                                                                                                                                                                       | CE-5 | Não          | SAR                        | n/a                       | GGAC                         | MPR 100, MPR 100, itens 4.2(c) e (f), e F-100-34 (item 11, III – Vistoria Física) F-100-39 (seção VI – INSTRUMENTO E EQUIPAMENTOS DA AERONAVE)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | n/a                                                |\n| 5.155  | Does the AID adhere to the developed procedures for the verification of operations derived equipment which are not part of the type certification of aircraft?                                                                                                                                                                                                                                                                                                    | Review examples of compliance checklists or other method to confirm effective implementation of procedures.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | STD<br>A6<br>Part I, C6<br>Part II, 2.4 & 3.6<br>Part III, Section II, C4 & Section III, C4                                                                                                                                                                                                                       | CE-6 | Não          | SAR                        | n/a                       | GGAC                         | n/a                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | n/a                                                |\n| 5.161  | Has the State promulgated a regulation for all aircraft to comply with the noise certification standards in Annex 16, Volume I?                                                                                                                                                                                                                                                                                                                                   | Verify regulations.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | STD<br>A16<br>Vol. I, Part II, 1.1                                                                                                                                                                                                                                                                                | CE-2 | Não          | SAR                        | n/a                       | GGAC<br>GGCP<br>GTPN         | n/a                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | n/a                                                |\n| 5.163  | Has the State, as a State of Registry, developed procedures for the granting or validation of noise certification?                                                                                                                                                                                                                                                                                                                                                | 1) Review procedures based on satisfactory evidence that the aircraft complies with requirements at least equivalent to those specified in Annex 16.<br>2) Review procedures to verify that they include at least the items listed in Part II, 1.5 of Annex 16, Volume I in the documents attesting noise certification.<br>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | STD<br>A16<br>Vol. I, Part II, 1.2, 1.4, 1.5, 1.6 & 1.7<br>GM<br>A16<br>Vol. I, Att. G<br>Doc 9760<br>Part III, C3                                                                                                                                                                                                | CE-5 | Não          | SAR                        | n/a                       | GGAC<br>GGCP                 | MPR 280, Capitulo 5                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | n/a                                                |\n| 5.164  | Does the State as the State of Registry approve the document attesting noise certification or issue a suitable statement in another document?                                                                                                                                                                                                                                                                                                                     | 1) Review examples of approved documents or suitable statements attesting noise certification to confirm effective implementation of procedures.<br>2) If not issued in English, an English translation should be included.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | STD<br>A16<br>Vol. I, Part II, 1.2, 1.4, 1.5, 1.6 & 1.7<br>GM<br>A16<br>Vol I, Att. G<br>Doc 9760<br>Part III, C3                                                                                                                                                                                                 | CE-6 | Não          | SAR                        | n/a                       | GGAC                         | n/a                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | n/a                                                |\n| 5.171  | Has the State promulgated a regulation for modifications and repairs to be approved and the regulations to be met for obtaining such an approval?                                                                                                                                                                                                                                                                                                                 | Verify the regulations for the following:<br>1) Applicant has comprehensive knowledge, experience and capabilities in the applicable technologies, such that in-depth analyses can be performed where required, as well as sufficient information on the type design of the aircraft involved.<br>2) Definition of major/minor modification/repair and different requirements for each.<br><br>Note. — In practice, States with limited or no engineering competence accept modifications or repairs. In this case, verify that the data have been approved by the State responsible for the type design.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | STD<br>A6<br>Part I, 8.6<br>Part II, 2.6.3<br>Part III, Section II, 6.6 & Section III, 6.4<br>A8<br>Part II, 1.3.4<br>GM<br>Doc 9760<br>Part III, C8                                                                                                                                                              | CE-2 | Não          | SAR                        | n/a                       | GGAC<br>GGCP<br>GTPN         | n/a                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | n/a                                                |\n| 5.173  | Has the State developed procedures for the approval of modifications and repairs?                                                                                                                                                                                                                                                                                                                                                                                 | Review procedures and verify:<br>1) Guidelines to determine if a modification requires an amendment to the type certificate or supplemental type certificate (STC).<br>2) Contact with the State of Design as part of the assessment of a repair or modification if necessary.<br>3) Consideration given to the compatibility between proposed design changes and other existing design changes.<br>4) Evaluation of impact to noise certification.<br>5) Evaluation of impact to mass and balance.<br><br>Note. — For States with limited or no engineering competence, see note under AIR PQ 5.171.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | STD<br>A6<br>Part I, 8.6<br>Part II, 2.6.3<br>Part III, Section II, 6.6 & Section III, 6.4<br>A16<br>Vol. I, Part II, 1.3<br>GM<br>Doc 9760<br>Part III, 8.6 & 8.7                                                                                                                                                | CE-5 | Não          | SAR                        | n/a                       | GGAC<br>GGCP<br>GTPN<br>GTPA | IS 21-004 – “Aprovação de Grandes Modificações e Grandes Alterações em aeronaves com marcas brasileiras, ou que venham a ter marcas brasileiras”.<br>IS 21-010 – “Procedimentos para a aprovação de produtos aeronáuticos civis importados/Procedures for approval of imported civil aeronautical products”.<br>IS 21-021 – “Apresentação de Dados Requeridos para Certificação Suplementar de Tipo”<br>MPR-102-SAR – “Aprovação Suplementar de Tipo”.<br>MPR-101/SAR – “Certificação de Projeto de Produto Aeronáutico”<br>MPR 900-04, Aprovação e Registro de Modificações e Reparos, Capítulo 9 (item 4-1185(c) for major repair). | n/a                                                |\n| 5.175  | Does the AID approve modifications and repairs in an effective and correct manner?                                                                                                                                                                                                                                                                                                                                                                                | 1) Review examples of approved modifications and repairs to confirm that the approval was performed in a correct manner.<br>2) Confirm that detailed records of approved data are retained.<br><br>Note.— For States with limited or no engineering competence, see note under AIR PQ 5.171.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | GM<br>Doc 9760<br>Part III, 8.6 & 8.7                                                                                                                                                                                                                                                                             | CE-6 | Não          | SAR                        | n/a                       | GGAC<br>GGCP                 | n/a                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | n/a                                                |\n| 5.181  | Do State regulations define whether the certificate of airworthiness will be renewed at set intervals or issued on a continuing basis?                                                                                                                                                                                                                                                                                                                            | Verify that the State has chosen one or the other; if issued on a continuing basis, a system for maintaining the validity of the certificate of airworthiness must be established.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | STD<br>A8<br>Part II, 3.2.3                                                                                                                                                                                                                                                                                       | CE-2 | Não          | SAR                        | n/a                       | GGAC                         | IS 21.181-001                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | n/a                                                |\n| 5.183  | Has the State developed procedures and checklists for the initial issuance/renewal of a certificate of airworthiness?                                                                                                                                                                                                                                                                                                                                             | Review procedures and verify that they include at least the following:<br>1) Application completed and submitted to the AID.<br>2) Design standards and airworthiness requirements under which the aircraft was type-certificated.<br>3) Review and retention of documents, such as:<br>   a) Type certificate and type certificate data sheet or equivalent<br>   b) Flight manual or equivalent document<br>   c) Mass and balance report<br>   d) Electrical load analysis<br>   e) MMEL<br><br>Note. — This may also be accomplished by a certification from an approved organization that the aircraft is airworthy.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | GM<br>Doc 9760<br>Part III, C4                                                                                                                                                                                                                                                                                    | CE-5 | Não          | SAR                        | n/a                       | GGAC                         | MPR 100, Capítulos 4, 5, 6 e 7,<br><br>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | n/a                                                |\n| 5.185  | Has the State developed procedures for the validation of a certificate of airworthiness?                                                                                                                                                                                                                                                                                                                                                                          | Review procedures to verify if:<br>1) The State ensures that the certificate was issued in compliance with all aspects of the Chicago Convention and the provisions of the applicable Annexes.<br>2) The State provides a suitable statement of authorization to be carried with the original certificate.<br>3) The validity of the authorization shall not extend beyond the period of validity of the original certificate.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | GM<br>Doc 9760<br>Part III, 4.7                                                                                                                                                                                                                                                                                   | CE-5 | Não          | SAR                        | n/a                       | GGAC                         | n/a                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | n/a                                                |\n| 5.187  | Does the certificate of airworthiness issued by the State contain all the information required by Annex 8?                                                                                                                                                                                                                                                                                                                                                        | Review certificate of airworthiness and verify inclusion of the following information:<br>1) State of Registry or issuing authority<br>2) Nationality and registration marks<br>3) Manufacturer and manufacturer’s designation of aircraft<br>4) Aircraft serial number<br>5) Date of issuance<br>6) Signature of approving official<br>7) Expiration date or reference to statement that aircraft is being maintained under a system of continuous inspection<br>8) Issued in English or English translation included.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | STD<br>A8<br>Part II, 3.3.1, Fig. 1                                                                                                                                                                                                                                                                               | CE-6 | Não          | SAR                        | n/a                       | GGAC                         | n/a                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | n/a                                                |\n| 5.189  | Does the CAA keep records for every aircraft registered in the State?                                                                                                                                                                                                                                                                                                                                                                                             | Review records to confirm that the following are available or retained in aircraft files:<br>1) records detailing applications and supporting documents for the certificates of registration and airworthiness;<br>2) copies of certificates issued;<br>3) the maintenance programme approved for the aircraft;<br>4) records of major modifications; and<br>5) other information relevant to the continuing airworthiness of the aircraft.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | GM<br>Doc 9760<br>Part II, 4.9.5                                                                                                                                                                                                                                                                                  | CE-6 | Não          | SAR                        | n/a                       | GGAC<br>GTRAB                | n/a                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | n/a                                                |\n| 5.201  | Do State regulations require periodic mass and balance reports for all aircraft?                                                                                                                                                                                                                                                                                                                                                                                  | Verify regulations for inclusion of requirement and frequency.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | GM<br>Doc 9760<br>Part III, 7.6                                                                                                                                                                                                                                                                                   | CE-2 | Não          | SAR                        | n/a                       | GGAC                         | RBAC/RBHA 135.185, 121.135(b)(21), 121.153(b), 91.423                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | n/a                                                |\n| 5.203  | Does the AID verify that the mass and balance of the aircraft is checked periodically?                                                                                                                                                                                                                                                                                                                                                                            | 1) Review mechanism established.<br>2) Review evidence to confirm effective implementation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | GM<br>Doc 9760<br>Part III, 7.6.2                                                                                                                                                                                                                                                                                 | CE-7 | Não          | SAR                        | n/a                       | GGAC                         | MPR 100, 6.3.1(f) – VTE, RCA F-900 -34, item 48 e IAM<br>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | n/a                                                |\n| 5.204  | Has the State promulgated regulations for air operators to maintain up-to-date and sufficient documentation concerning FDR parameter allocation, conversion equations, periodic calibration and other serviceability/maintenance information and ensure their availability to accident investigation authorities?                                                                                                                                                 | Verify regulations.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | STD<br>A6<br>Part I, 6.3; App. 8, 2.3.3                                                                                                                                                                                                                                                                           | CE-2 | Sim          | SAR                        | SPO                       | GGAC                         | RBHA 91.609(e)(1) e (g), RBAC 121.343(J), 121.344(J), 121.344a(d), 135.152(f)(1), 135.152(f)(2) e 135.152(d)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | n/a                                                |\n| 5.205  | Does the State ensure at regular intervals that its air operators maintain up-to-date and sufficient documentation concerning FDR parameter allocation, conversion equations, periodic calibration and other serviceability/maintenance information?                                                                                                                                                                                                              | 1) Review surveillance programme.<br>2) Review inspectors procedures.<br>3) Sample inspection records.<br>4) Confirm that the documentation is sufficient to ensure that accident investigation authorities have the necessary information to read out the data in engineering units.<br>5) Verify during industry visit.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | STD<br>A6<br>Part I, 6.3 & 11.6; App. 8, 2.3.3                                                                                                                                                                                                                                                                    | CE-7 | Sim          | SAR                        | SPO                       | GGAC                         | An aircraft inspection needs to be followed up in order to check how item 65 of Form 100-34 is complied with.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | n/a                                                |\n| 5.211  | Has the State promulgated regulations for compliance with mandatory continuing airworthiness information from the State of Design?                                                                                                                                                                                                                                                                                                                                | Verify regulations for compliance requirements to ADs in the State:<br>1) Adopted directly.<br>2) CAA’s letter/circular/document with reference to AD from State of Design.<br>3) Promulgation of a State AD.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | STD<br>A8<br>Part II, 4.2.3 d)                                                                                                                                                                                                                                                                                    | CE-2 | Não          | SAR                        | n/a                       | GGAC<br>GGCP - PAC<br>GTPN   | \\[1\\] - RBAC 39.5 e RBAC 39.5-I<br>\\[2\\] - RBHA 91.403(a)<br>\\[3\\] - RBAC 39.13-I                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | n/a                                                |\n| 5.215  | Has the State established procedures for developing its own mandatory continuing airworthiness information on a product for which it is not the State of Design?                                                                                                                                                                                                                                                                                                  | 1) Guidelines for determining when additional information is necessary.<br>2) Coordination with the State of Design.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | STD<br>A8<br>Part II, 4.2.3<br>GM<br>Doc 9760<br>Part III, 9.5                                                                                                                                                                                                                                                    | CE-5 | Não          | SAR                        | n/a                       | GGAC<br>GGCP - PAC           | : item 5.6 and 5.7 of IS 39-001<br>ver MPR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | n/a                                                |\n| 5.216  | Has the State established and implemented a system for appropriate actions upon receipt of mandatory continuing airworthiness information and/or issuance of additional mandatory continuing airworthiness information?                                                                                                                                                                                                                                           | 1) Review system to ensure compliance with mandatory continuing airworthiness information received from the State of Design and additional information issued, as applicable.<br>2) Confirm necessary coordination with the State of Design.<br>3) Confirm that State verifies the applicability to the aircraft on its register.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | STD<br>A8<br>Part II, 4.2.3<br>GM<br>Doc 9760<br>Part III, 9.4 & 9.5                                                                                                                                                                                                                                              | CE-8 | Não          | SAR                        | n/a                       | GGAC<br>GGCP - PAC           | \\[1\\] - RBAC 39.5-I;<br>\\[2\\] – RBAC 39.13-I<br>\\[3\\] - SAR web page (https://sistemas.anac.gov.br/certificacao/DA/DA.asp);<br>\\[4\\] - F-100-34, Section II, item 24 to 28;<br>\\[5\\] - Annual Maintenance Inspection (IAM), RBHA 91.403(i)(4); and<br>\\[6\\] - PP-LRA Special Aircraft Inspection.                                                                                                                                                                                                                                                                                                                                     | n/a                                                |\n| 5.217  | Has the State established and implemented a system to ensure that information on faults, malfunctions and defects for aircraft registered, being operated or receiving maintenance under an approval issued by the State is transmitted to the organization responsible for the type design of the aircraft, or the organization responsible for the design of the modification when the continuing airworthiness safety issue is associated with a modification? | 1) Review established system.<br>2) Review evidence to confirm effective implementation.<br>3) Limited to aeroplanes over 5700 kg or helicopters over 3175 kg maximum certificated take-off mass.<br>4) Confirm that the system also covers the transmittal of information, where a continuing airworthiness safety issue is associated with a modification, to the organization responsible for the design of the modification.<br>5) Verify during industry visit.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | STD<br>A8<br>Part II, 4.2.3 f)<br>GM<br>Doc 9760<br>Part III, 9.6                                                                                                                                                                                                                                                 | CE-8 | Não          | SAR                        | n/a                       | GGAC<br>GGCP - PAC           | \\[1\\] - RBAC 121.703(d)<br>\\[2\\] - RBAC 135.415(d)<br>\\[3\\] - RBAC 145.221(a)<br>\\[4\\] - RBAC 21.3<br>\\[5\\] - IS 00-001<br>\\[6\\] - Sample Service Difficult Report                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | n/a                                                |\n| 5.231  | Do State regulations provide for the issuance of a special flight permit in the case that an aircraft is no longer airworthy but must be flown for repair?                                                                                                                                                                                                                                                                                                        | Verify regulations.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | STD<br>A8<br>Part II, 3.6.3<br>GM<br>Doc 9760<br>Part III, C5                                                                                                                                                                                                                                                     | CE-2 | Não          | SAR                        | n/a                       | GGAC                         | : RBAC 21.197                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | n/a                                                |\n| 5.233  | Has the State established procedures for the issuance of a special flight permit?                                                                                                                                                                                                                                                                                                                                                                                 | Review procedures to determine if the following are included:<br>1\\. Criteria for safe flight<br>2\\. Limitations.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | STD<br>A8<br>Part II, 3.6.3<br>GM<br>Doc 9760<br>Part III, C5                                                                                                                                                                                                                                                     | CE-5 | Não          | SAR                        | n/a                       | GGAC                         | MPR 100 Chapter 10 and Resolution Nº 178, 2112/2010                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | n/a                                                |\n| 5.235  | Do the special flight permits issued by the CAA contain all the pertinent information?                                                                                                                                                                                                                                                                                                                                                                            | Review example of certificate or letter to be used for inclusion of:<br>1) Expiration date.<br>2) All essential limitations, such as non-commercial flight only, avoid areas where flights might create hazardous exposure to persons or property, etc.<br>3) Not valid for use in foreign airspace unless validated by the foreign CAA whose airspace will be over flown.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | GM<br>Doc 9760<br>Part III, 5.3                                                                                                                                                                                                                                                                                   | CE-6 | Não          | SAR                        | n/a                       | GGAC                         | Form 100-47 and AVANAC                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | n/a                                                |\n| 5.241  | If the State issues airworthiness approvals for the export of aeronautical products, have the associated requirements been promulgated?                                                                                                                                                                                                                                                                                                                           | Verify regulations addressing aeronautical products for which export approvals are issued:<br>1) Class I<br>2) Class II<br>3) Class III.<br><br>Note. — This PQ and two subsequent ones are not applicable to States which choose not to issue these types of approvals.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | GM<br>Doc 9760<br>Part III, C6<br>Part V, C7                                                                                                                                                                                                                                                                      | CE-2 | Não          | SAR                        | n/a                       | GGCP-GTAI                    | \\[1\\] - RBAC 21- Subparte L<br>\\[2\\] - IS 43.9 002B                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | n/a                                                |\n| 5.243  | If the State issues airworthiness approvals for the export of aeronautical products, have the related procedures been developed?                                                                                                                                                                                                                                                                                                                                  | Verify procedures include identification of additional special requirements or conditions from the CAA of the importing State.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | GM<br>Doc 9760<br>Part III, C6<br>Part V, C7                                                                                                                                                                                                                                                                      | CE-5 | Não          | SAR                        | n/a                       | GGCP-GTAI                    | MPR 131 sections 5.3 and 5.4<br>CI 21-008 “Procedimento Para Aprovação De Aeronavegabilidade Para Exportação”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | n/a                                                |\n| 5.245  | If the State issues airworthiness approvals for the export of aeronautical products, does the export airworthiness approval issued include all the appropriate information?                                                                                                                                                                                                                                                                                       | Review approvals to ensure inclusion of:<br>1) Conformity certification.<br>2) Indication of whether the product is new or used.<br>3) Specific regulations of the exporting State that the product does not comply with.<br>4) Statement of compliance with any additional special requirements or special conditions specified by the importing State.<br>5) Statement that the approval is not an authorization to fly.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | GM<br>Doc 9760<br>Part III, C6<br>Part V, C7                                                                                                                                                                                                                                                                      | CE-6 | Não          | SAR                        | n/a                       | GGCP-GTAI                    | SEGVOO 001 Form                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | n/a                                                |\n| 5.251  | Has the State developed industry guidelines for the reporting of unapproved parts to type certificate holders and regulatory agencies?                                                                                                                                                                                                                                                                                                                            | 1) Review guidelines.<br>2) Verify awareness of guidelines during industry visit.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | GM<br>Doc 9760<br>Part III, 9.10.6                                                                                                                                                                                                                                                                                | CE-5 | Não          | SAR                        | n/a                       | GGAC<br>GGCP - PAC           | Item 5.10.2 of IS nº 43-001 and Steps 8 and 18 of Procedure 5.4 of MPR 245-SAR.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | n/a                                                |\n| 5.253  | Has the State developed industry guidelines for the proper usage of parts removed from an aircraft no longer in service?                                                                                                                                                                                                                                                                                                                                          | 1) Review guidelines.<br>2) The guidelines should include the removal of parts from unserviceable aircraft and aircraft involved in accidents.<br>3) Verify awareness of guidelines during industry visit.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | GM<br>Doc 9760<br>Part III, 9.10.8 & 9.10.9                                                                                                                                                                                                                                                                       | CE-5 | Não          | SAR                        | n/a                       | GGAC                         | IS 43-001, 5.4(c), II, III                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | n/a                                                |\n| 5.255  | Has the State developed industry guidelines for the disposal of scrapped parts?                                                                                                                                                                                                                                                                                                                                                                                   | 1) Review guidelines.<br>2) Verify awareness of guidelines during industry visit.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | GM<br>Doc 9760<br>Part III, 9.10.10                                                                                                                                                                                                                                                                               | CE-5 | Não          | SAR                        | n/a                       | GGAC                         | : IS 43.001, 5.2                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | n/a                                                |\n| 5.261  | Do State regulations require that an air operator can only operate an aircraft, if it has been maintained and released to service by an AMO, or under an equivalent system?                                                                                                                                                                                                                                                                                       | 1) Verify regulations.<br>2) If under an equivalent system:<br>   a) Persons signing the maintenance release required to be licensed in accordance with Annex 1.<br>…b) Quality control.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | STD<br>A6<br>Part I, 8.1.2 & 8.1.3<br>Part II, 2.6.1.2, 2.6.1.3 & 3.8.1.1<br>Part III, Section II, 6.1.2 & 6.1.3 & Section III, 6.1.2 & 6.1.3<br>GM<br>Doc 9760<br>Part III, 7.1.1, 7.1.4, 7.7.1 & 10.1                                                                                                           | CE-2 | Sim          | SAR                        | SPO                       | GGAC                         | RBAC 121.362, 135.412, RBAC 145.157 and 145.211, RBAC 43.3(f) and 43.7(e)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | n/a                                                |\n| 5.263  | Is the AID involved in the process of evaluating an air operator for the issuance of an AOC, including the specific operating provisions issued in conjunction with an AOC?                                                                                                                                                                                                                                                                                       | 1) Review with aircraft operations and verify established coordination arrangements and related documentation.<br>2) Verify AID endorsement prior to AOC issuance to confirm implementation of procedures.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | STD<br>A6<br>Part I, 4.2.1<br>Part III, Section II, 2.2.1<br>GM<br>A6<br>Part I, Att. E, 2.4 <br>Part III, Att. E, 2.4<br>Doc 9760<br>Part II, 4.7.1.2 c) & 4.7.3 h)<br>Part IV, C2                                                                                                                               | CE-6 | Sim          | SAR                        | SPO                       | GGAC                         | IS 119.001, IS 119.004, FOP 113.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | n/a                                                |\n| 5.265  | Does the State verify that the air operator employs qualified personnel to ensure that all aircraft maintenance is carried out in accordance with the maintenance control manual?                                                                                                                                                                                                                                                                                 | 1) Review certification process/checklists.<br>2) Review evidence to confirm effective implementation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | STD<br>A6<br>Part I, 8.1.4<br>Part III, Section II, 6.1.4<br>A19<br>App. 1, 6<br>GM<br>Doc 9760<br>Part III, 7.1.1 b)<br>Part IV, C2                                                                                                                                                                              | CE-6 | Sim          | SAR                        | SPO                       | GGAC                         | RBAC 119.65(a)(4); 119.65(a)(5); 119.65(d)(v); 119.67(d); 119.67(e) and F-900-17                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | n/a                                                |\n| 5.267  | Does the AID review maintenance contracts?                                                                                                                                                                                                                                                                                                                                                                                                                        | 1) Review process.<br>2) Review evidence to confirm effective implementation.<br>3) Verify during industry visit.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | STD<br>A6<br>Part I, 11.2 a)<br>Part III, Section II, 9.2 a)<br>A19<br>App. 1, 6<br>GM<br>Doc 9760<br>Part III, 7.7<br>Part IV, 2.3.2.5 & 2.4.7.7                                                                                                                                                                 | CE-6 | Não          | SAR                        | n/a                       | GGAC                         | RBAC 121.365, MPR900-03; Chapter 8, F-900-54                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | n/a                                                |\n| 5.281  | Has the State promulgated a regulation for air operators to submit an air operator maintenance control manual for review and acceptance?                                                                                                                                                                                                                                                                                                                          | Verify regulations.<br><br>Note. — For European Union Member States, this is addressed with the requirement for the approval of a Continuing Airworthiness Management Exposition (CAME).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | STD<br>A6<br>Part I, 8.2<br>Part III, Section II, 6.2                                                                                                                                                                                                                                                             | CE-2 | Sim          | SAR                        | SPO                       | GGAC                         | RBAC 121.133 e 121.135, RBAC 135.21                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | n/a                                                |\n| 5.283  | Has the State promulgated regulations for the content of a maintenance control manual?                                                                                                                                                                                                                                                                                                                                                                            | Verify regulations for the content of the maintenance control manual:<br>1) Names and duties of persons employed.<br>2) Reference to maintenance programme.<br>3) Methods for completion and retention of records.<br>4) Procedures for implementing mandatory continuing airworthiness action.<br>5) Observance of Human Factors principles.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | STD<br>A6<br>Part I, 8.2 & 11.2<br>Part III, Section II, 6.2 & 9.2<br>GM<br>Doc 9683<br>Part 1, C6<br>Doc 9760<br>Part III, 7.2                                                                                                                                                                                   | CE-2 | Sim          | SAR                        | SPO                       | GGAC                         | G1: 121.369(a) e 135.427(a);<br>G2: 121.369(b) e 135.427(b);<br>G3: 121.369(c) e 135.427(c);<br>G4: 121.369 e 121.380(a)(2)(v) e 135.427 e 135.439(a)(2)(v);<br>G5: 121.369(b)(14) e 135.427(b)(14)                                                                                                                                                                                                                                                                                                                                                                                                                                   | n/a                                                |\n| 5.285  | Has the State developed procedures for the review and acceptance of an operator’s maintenance control manual?                                                                                                                                                                                                                                                                                                                                                     | Review procedures for:<br>1) Inclusion of required contents.<br>2) Revision control.<br>3) Document control.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | STD<br>A6<br>Part I, 11.2; App. 5, 5.1<br>Part III, Section II, 9.2; App. 1, 5.1<br>A19<br>App. 1, 5.1<br>GM<br>Doc 9760<br>Part III, 7.2                                                                                                                                                                         | CE-5 | Não          | SAR                        | n/a                       | GGAC                         | MPR 900-03, Chapter 3                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | n/a                                                |\n| 5.287  | Does the AID review and approve/accept the maintenance control manual as part of the AOC issuance process?                                                                                                                                                                                                                                                                                                                                                        | 1) Review AOC issuance process.<br>2) Check, if up-to-date copy is kept by the AID.<br>3) Sample an AID approved/accepted maintenance control manual to confirm effective implementation of established requirements and procedures.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | STD<br>A6<br>Part I, 11.2<br>Part III, Section II, 9.2<br>A19<br>App. 1, 6<br>GM<br>A6<br>Part I, Att. E<br>Part III, Att. E<br>Doc 9760<br>Part IV, 2.4.7.2 & 2.5.3                                                                                                                                              | CE-6 | Não          | SAR                        | n/a                       | GGAC                         | n/a                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | n/a                                                |\n| 5.301  | Has the State promulgated a regulation for maintenance programmes to be approved by the State of Registry?                                                                                                                                                                                                                                                                                                                                                        | Verify regulations.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | STD<br>A6<br>Part I, 8.3.1<br>Part III, Section II, 6.3.1                                                                                                                                                                                                                                                         | CE-2 | Não          | SAR                        | n/a                       | GGAC                         | RBAC 121.369(b) and RBAC 135.425.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | n/a                                                |\n| 5.303  | Has the State promulgated a regulation for the content of a maintenance programme?                                                                                                                                                                                                                                                                                                                                                                                | Verify regulations include the following content requirements:<br>1) Maintenance tasks and intervals.<br>2) Continuing structural integrity programme, if applicable.<br>3) Certification maintenance requirements identified.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | STD<br>A6<br>Part I, 11.3<br>Part II, 3.11.2<br>Part III, Section II, 9.3<br>GM<br>Doc 9760<br>Part III, 7.3                                                                                                                                                                                                      | CE-2 | Não          | SAR                        | n/a                       | GGAC                         | G1: 121.369(b)(10) and 135.427(b)(10);<br>G2: 121.369(b)(11) and 135.427(b)(11);<br>G3: 121.369(b)(13), 135.427(b)(13)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | n/a                                                |\n| 5.305  | Has the State developed procedures for the approval of maintenance programmes?                                                                                                                                                                                                                                                                                                                                                                                    | Review procedures for approval:<br>1) Based on maintenance programme information made available by the State of Design or the organization responsible for the type design, and any additional applicable experience.<br>2) Document control.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | STD<br>A6<br>Part I, 11.3; App. 5, 5.1<br>Part III, Section II, 9.3; App. 1, 5.1<br>A19<br>App. 1, 5.1<br>GM<br>Doc 9760<br>Part III, 7.3                                                                                                                                                                         | CE-5 | Não          | SAR                        | n/a                       | GGAC                         | IS 120-001, F-900-42                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | n/a                                                |\n| 5.307  | Does the AID review and approve maintenance programmes in accordance with established requirements and procedures?                                                                                                                                                                                                                                                                                                                                                | 1) Verify, if up-to-date copies kept by the AID.<br>2) Sample an AID approved maintenance programme to confirm effective implementation of established requirements and procedures.<br>3) Review an example of an escalation request.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | STD<br>A6<br>Part I, 11.3<br>Part III, Section II, 9.3<br>A19<br>App. 1, 6<br>GM<br>A6<br>Part I, Att. E<br>Part III, Att. E<br>Doc 9760<br>Part IV, 2.4.7.3                                                                                                                                                      | CE-6 | Não          | SAR                        | n/a                       | GGAC                         | n/a                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | n/a                                                |\n| 5.321  | Has the State promulgated a regulation for operators to prepare a MEL on the basis of the MMEL for review and approval?                                                                                                                                                                                                                                                                                                                                           | Verify regulations.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | STD<br>A6<br>Part I, 6.1.3<br>Part II, 3.6.1.1<br>Part III, Section II, 4.1.3<br>GM<br>A6<br>Part I, Att. F<br>Part II, Att. 3.B<br>Part III, Att. D                                                                                                                                                              | CE-2 | Sim          | SAR                        | SPO                       | GGAC                         | RBHA 91.213, RBAC 121.628, RBAC 135.179                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | n/a                                                |\n| 5.323  | Has the CAA developed procedures for approving a MEL?                                                                                                                                                                                                                                                                                                                                                                                                             | Review procedures to include review and approval of airworthiness- related aspects for the MEL.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | STD<br>A6<br>Part I, 6.1.3; App. 5, 5.1<br>Part II, 3.6.1.1<br>Part III, Section II, 4.1.3; App. 1, 5.1<br>A19<br>App. 1, 5.1<br>GM<br>A6<br>Part I, Att. F<br>Part II, Att. 3.B<br>Part III, Att. D<br>Doc 9760<br>Part IV, 2.4.7.10                                                                             | CE-5 | Sim          | SAR                        | SPO                       | GGAC                         | IAC 3507; MPR-0031/SPO/SAR; MPR900-4, Revision 05, Chapter 04 and F-900-49<br>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | n/a                                                |\n| 5.324  | Does the AID review and approve/accept the airworthiness-related elements of a MEL to be approved in conjunction with an AOC?                                                                                                                                                                                                                                                                                                                                     | 1) Review process to include review and approval/acceptance of airworthiness-related aspects for the MEL.<br>2) Review examples to confirm effective implementation.<br>3) Coordinate with OPS auditor.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | STD<br>A6<br>Part I, 6.1.3,<br>Part III, Section II, 4.1.3<br>A19<br>App. 1, 6<br>GM<br>A6<br>Part I, Att. F<br>Part III, Att. D<br>Doc 9760<br>Part IV, 2.4.7.10                                                                                                                                                 | CE-6 | Sim          | SAR                        | SPO                       | GGAC                         | Tem ITTA 119-012/GCVC                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | n/a                                                |\n| 5.325  | Has the State promulgated regulations for the approval of EDTO?                                                                                                                                                                                                                                                                                                                                                                                                   | Verify regulations for the following:<br>1) Airworthiness certification of the aircraft type specifically permits operations beyond the threshold time<br>2) Maturity and reliability of the propulsion system<br>3) Air operator must demonstrate the ability to maintain the level of reliability required for EDTO approval<br>4) Necessary special maintenance requirements included as part of the maintenance programme<br>5) Maintenance control manual or EDTO manual.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | STD<br>A6<br>Part I, 4.7<br>GM<br>A6<br>Part I, Att. D<br>Doc 9760<br>Part IV, C5                                                                                                                                                                                                                                 | CE-2 | Sim          | SAR                        | SPO                       | GGAC<br>GTPN                 | G1: Appendix K to RBAC 25, 25.1.4(a)(2)<br>G2: Appendix K to RBAC 25, 25.2.1(b)<br>G3: RBAC 121.374(h) and RBAC 135.364(b)(2)<br>G4: RBAC 121.374(a)(ii), 135.364(b)(3)<br>G5: RBAC 121.374(a), 135.364(b)(6)                                                                                                                                                                                                                                                                                                                                                                                                                         | n/a                                                |\n| 5.327  | Has the State established procedures for the airworthiness-related aspects of approval of EDTO operations?                                                                                                                                                                                                                                                                                                                                                        | Review approval procedures to ensure that the following is addressed in an EDTO manual or maintenance control manual:<br>1) Reference to maintenance programme, oil consumption programme and engine condition monitoring.<br>2) Rectification of aircraft defects.<br>3) Reliability programme.<br>4) Propulsion system monitoring.<br>5) Maintenance training.<br>6) EDTO parts control.<br>7) All EDTO requirements, including supportive programme procedures, duties and responsibilities, identified and subject to revision control.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | STD<br>A6<br>Part I, App. 5, 5.1<br>A19<br>App. 1, 5.1<br>GM<br>Doc 9760<br>Part IV, C5                                                                                                                                                                                                                           | CE-5 | Sim          | SAR                        | SPO                       | GGAC                         | IAC 3501, F-900-45<br>G1: Item 10(c) of IAC 3501, item 1(a)(2); 1(a)(4) and 1(a)(4) of Appendix 4 to IAC 3501<br>G2: 1(a)(6) of Appendix 4 to IAC 3501<br>G3: 1(a)(7) of Appendix 4 to IAC 3501<br>G4: 1(a)(8) of Appendix 4 to IAC 3501<br>G5: 1(a)(9) of Appendix 4 to IAC 3501<br>G6: 1(a)(10) of Appendix 4 to IAC 3501<br>G7: 1(a)(3) of Appendix 4 to IAC 3501<br>                                                                                                                                                                                                                                                              | n/a                                                |\n| 5.328  | Does the AID review and approve/accept EDTO as part of the operations specifications issued in conjunction with an AOC?                                                                                                                                                                                                                                                                                                                                           | 1) Review process to include review and approval/acceptance of airworthiness-related aspects for EDTO operation.<br>2) Review examples of EDTO manuals or maintenance control manual to confirm effective implementation of the items listed in PQ 5.325.<br>3) Coordinate with OPS auditor.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | STD<br>A6<br>Part I, 4.7.1<br>GM<br>Doc 9760<br>Part IV, 2.4.4 & C5                                                                                                                                                                                                                                               | CE-6 | Sim          | SAR                        | SPO                       | GGAC                         | IAC 119-1003<br>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | n/a                                                |\n| 5.329  | Has the State promulgated airworthiness regulations for RVSM approval?                                                                                                                                                                                                                                                                                                                                                                                            | Verify regulations.<br><br>Acceptable models include:<br><br>1) JAA Temporary Guidance Leaflet No. 6 – Guidance Material on the Approval of Aircraft and Operators for Flight in Airspace above Flight Level 290 where a 300 m (1000 ft.) Vertical Separation Minimum Applies or any subsequent version thereof.<br>2) FAA Doc 91 – Interim Guidance on the Approval of Operators/Aircraft for RVSM Operations.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | STD<br>A6<br>Part I, 7.2.4, 7.2.5 & 7.2.7<br>Part II, 2.5.2.4, 2.5.2.5 & 2.5.2.7<br>GM<br>Doc 9574                                                                                                                                                                                                                | CE-2 | Sim          | SAR                        | SPO                       | GGAC<br>GGAC                 | RBHA 91 Apêndice G<br>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | n/a                                                |\n| 5.331  | Has the State developed airworthiness-related procedures for the authorization of operators to conduct operations in navigational areas requiring RVSM approval?                                                                                                                                                                                                                                                                                                  | Review procedures developed by the State to ensure that they provide sufficient guidance on the approval of operators/aircraft for RVSM operations.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | STD<br>A6<br>Part I, 7.2.4, 7.2.5 & 7.2.7; App. 5, 5.1<br>Part II, 2.5.2.4, 2.5.2.5 & 2.5.2.7<br>A19<br>App. 1, 5.1<br>GM<br>Doc 9574<br>C3                                                                                                                                                                       | CE-5 | Sim          | SAR                        | SPO                       | GGAC                         | IAC 3508 CAP 10<br>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | n/a                                                |\n| 5.333  | Does the AID carry out an evaluation of the airworthiness-related aspects for RVSM approval?                                                                                                                                                                                                                                                                                                                                                                      | 1) Review process to include airworthiness-related evaluation.<br>2) Review evidence to confirm effective implementation.<br>3) Coordinate with OPS auditor.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | STD<br>A6<br>Part I, 7.2.4, 7.2.5 & 7.2.7<br>Part II, 2.5.2.4, 2.5.2.5 & 2.5.2.7<br>A19<br>App. 1, 6<br>GM<br>Doc 9574<br>C3                                                                                                                                                                                      | CE-6 | Sim          | SAR                        | SPO                       | GGAC                         | RBHA 91 Apêndice G, IAC 3508, MPR 900-04<br>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | n/a                                                |\n| 5.334  | Has the State developed airworthiness-related procedures for the evaluation for the conduct of CAT II and III instrument approaches?                                                                                                                                                                                                                                                                                                                              | 1) Review procedures.<br>2) Review process to include evaluation of the aircraft, equipment reliability and maintenance procedures.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | STD<br>A6<br>Part I, 4.2.8.2 & 4.2.8.3<br>GM<br>A6<br>Part I, Att. E, 2.4                                                                                                                                                                                                                                         | CE-5 | Sim          | SAR                        | SPO                       | GGAC                         | ITTA 119-012/GCVC. Para o público externo GEA<br>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | Apenas CAT III.                                    |\n| 5.335  | Does the AID carry out an airworthiness evaluation for the conduct of CAT II and III instrument approaches?                                                                                                                                                                                                                                                                                                                                                       | 1) Review evidence to confirm effective implementation.<br>2) Coordinate with OPS auditor.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | STD<br>A6<br>Part I, 4.2.8.2 & 4.2.8.3<br>GM<br>A6<br>Part I, Att. E, 2.4                                                                                                                                                                                                                                         | CE-6 | Sim          | SAR                        | SPO                       | GGAC                         | ITTA 119-012/GCVC. Para o público externo GEA<br>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | Apenas CAT III.                                    |\n| 5.341  | Has the State promulgated airworthiness regulations for the approval of leases among commercial air transport operators?                                                                                                                                                                                                                                                                                                                                          | Review regulations as they relate to airworthiness for the type of leases (dry, wet or damp).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | GM<br>A6<br>Part I, Att. E, 2.5<br>Part III, Att. E, 2.5<br>Doc 8335<br>Part V<br>CIR 295                                                                                                                                                                                                                         | CE-2 | Sim          | SAR                        | SPO                       | GGAC                         | n/a                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | n/a                                                |\n| 5.343  | Has the CAA developed procedures, as they relate to airworthiness, for the approval of leases among commercial air transport operators?                                                                                                                                                                                                                                                                                                                           | 1) Review approval procedures as they relate to airworthiness for the type of leases (dry, wet or damp) to include the determination of the responsibility for the signing of the maintenance release and the airworthiness of the aircraft.<br>2) Coordinate with OPS auditor.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | STD<br>A6<br>Part I, App. 5, 5.1<br>Part III, App. 1, 5.1<br>A19<br>App. 1, 5.1<br>GM<br>A6<br>Part I, Att. E, 2.5<br>Part III, Att. E, 2.5<br>Doc 8335<br>Part IV, C2, 2.4<br>Part V<br>Doc 9760<br>Part IV, C6<br>CIR 295                                                                                       | CE-5 | Não          | SAR                        | n/a                       | GGAC                         | Seção 1 do capítulo 13 do MPR-900 Volume 03                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | n/a                                                |\n| 5.345  | Prior to approving an aircraft lease, does the AID ensure that the signing of the maintenance release has been considered and that the lease clearly defines who is responsible for the airworthiness of the aircraft?                                                                                                                                                                                                                                            | Review evidence to confirm that the following responsibilities and authority is clearly identified and the evaluation of the airworthiness-related elements of the lease are documented:<br>1) the signing of the maintenance release;<br>2) ensuring AD compliance; and<br>3) completion of maintenance programme tasks.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | STD,<br>A19<br>App. 1, 6<br>GM<br>A6<br>Part I, Att. E, 2.5<br>Part III, Att. E, 2.5<br>Doc 8335<br>Part V<br>Doc 9760<br>Part IV, C6                                                                                                                                                                             | CE-6 | Não          | SAR                        | n/a                       | GGAC                         | Seção 1 do capítulo 13 do MPR-900 Volume 03, F-900-66                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | n/a                                                |\n| 5.347  | If the State has entered into any agreement under the provisions of Article 83 bis of the Chicago Convention, has the State developed guidance and procedures for the transfer and acceptance of functions and duties according to an Article 83 bis agreement with another State, as far it concern airworthiness?                                                                                                                                               | 1) Confirm procedures for evaluation of capability of State accepting oversight duties.<br>2) Guidance for the recognition of certificates of airworthiness and radio station licences.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | CC<br>Art. 83 bis<br>GM<br>A6<br>Part I, Att. E, 2.5.2<br>Part III, Att. E, 2.5.2<br>Doc 8335<br>Part V<br>Doc 9760<br>Part IV, C6<br>CIR 295                                                                                                                                                                     | CE-5 | Não          | SAR                        | n/a                       | GGAC                         | Cn/a                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | Confirmar entendimento sobre não palicabilidade.   |\n| 5.349  | If the State has entered into any agreement under the provisions of Article 83 bis of the Chicago Convention, does the CAA evaluate the capability of the State accepting the oversight responsibilities with respect to the airworthiness functions?                                                                                                                                                                                                             | 1) Review evidence of effective implementation, if applicable.<br>2) Clear allocation of duties and responsibilities.<br>3) Notification to ICAO.<br>4) Coordinate with OPS auditor.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | CC<br>Art. 83 bis<br>GM<br>A6<br>Part I, Att. E, 2.5.2<br>Part III, Att. E, 2.5.2<br>Doc 8335<br>Part V<br>Doc 9760<br>Part IV, C6<br>CIR 295                                                                                                                                                                     | CE-6 | Não          | SAR                        | n/a                       | GGAC                         | Cn/a                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | Confirmar entendimento sobre não palicabilidade.   |\n| 5.361  | Has the State promulgated a regulation for operators of aeroplanes over 5700 kg or helicopters over 3175 kg maximum certificated take-off mass to monitor and assess maintenance and operational experience with respect to continuing airworthiness?                                                                                                                                                                                                             | Verify regulations.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | STD<br>A6<br>Part I, 8.5.1<br>Part III, Section II, 6.5.1<br>GM<br>Doc 9760<br>Part IV, 4.2.3                                                                                                                                                                                                                     | CE-2 | Sim          | SAR                        | SPO                       | GGAC<br>GGAC                 | RBAC 121.703(d), RBAC 135.415(d)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | n/a                                                |\n| 5.363  | Has the State promulgated a regulation for operators of aeroplanes over 5700 kg or helicopters over 3175 kg maximum certificated take-off mass to obtain and assess continuing airworthiness information and recommendations from the organization responsible for the type design?                                                                                                                                                                               | Verify regulations for obtaining service bulletins, alerts, etc. from the organization responsible for the type design.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | STD<br>A6<br>Part I, 8.5.2<br>Part III, Section II, 6.5.2<br>GM<br>Doc 9760<br>Part IV, 4.1.2, 4.2.1.3 & 4.2.3<br>Part V, 6.6.5.2                                                                                                                                                                                 | CE-2 | Sim          | SAR                        | SPO                       | GGAC<br>GGAC                 | 135.23(a)(27)<br>121.135(b) itens (17) e (18)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | n/a                                                |\n| 5.371  | Has the State promulgated regulations for obtaining a maintenance organization approval?                                                                                                                                                                                                                                                                                                                                                                          | Verify that regulations include requirements on:<br>1) Maintenance organization procedures manual.<br>2) A quality system to monitor compliance with and adequacy of the maintenance procedures or an inspection system to ensure that all maintenance is properly performed.<br>3) Facilities and working environment.<br>4) Technical data, equipment, tools and material.<br>5) Personnel.<br>6) Maintenance records.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | STD<br>A6<br>Part I, 8.7<br>GM<br>Doc 9760<br>Part III, C10                                                                                                                                                                                                                                                       | CE-2 | Não          | SAR                        | n/a                       | GGAC                         | RBAC 145<br>G1: 145.207<br>G2: 145.214-I(b)(2)<br>G3: 145.3(a)-I and 145.51(a)<br>G4: 145.211<br>G5: 145.217                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | n/a                                                |\n| 5.373  | Has the AID developed procedures for the approval of maintenance organizations?                                                                                                                                                                                                                                                                                                                                                                                   | 1) Review procedures.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | GM<br>Doc 9760<br>Part III, C10                                                                                                                                                                                                                                                                                   | CE-5 | Não          | SAR                        | n/a                       | GGAC                         | IS 145-001; IS 145-002 and IS 145.214-001                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | n/a                                                |\n| 5.377  | Has the AID issued AMO certificates in accordance with the promulgated regulations and established procedures?                                                                                                                                                                                                                                                                                                                                                    | 1) Review file(s) for the issuance of an AMO certificate to confirm adherence to regulations/procedures.<br>2) Verify that the AMO certificate contains at least the following:<br>     a) organization’s name and location;<br>     b) date of issuance and period of validity; and<br>     c) terms of approval.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | STD<br>A6<br>Part I, 8.7.1.2 & 8.7.3<br>GM<br>Doc 9760<br>Part III, C10                                                                                                                                                                                                                                           | CE-6 | Não          | SAR                        | n/a                       | GGAC                         | RBAC 145.214-I(b), SMS is to be implemented in March 8, 2019.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | n/a                                                |\n| 5.391  | Has the State promulgated a regulation for a maintenance procedures manual to be submitted to the regulatory authority as part of the approval process for a maintenance organization?                                                                                                                                                                                                                                                                            | Verify regulations.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | STD<br>A6<br>Part I, 8.7.2                                                                                                                                                                                                                                                                                        | CE-2 | Não          | SAR                        | n/a                       | GGAC<br>GTPN                 | RBAC 145.51(a)(1) e RBAC 145.20719.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | n/a                                                |\n| 5.393  | Has the State promulgated regulations for the content of a maintenance procedures manual in accordance with provisions of the Annexes and ICAO Documents?                                                                                                                                                                                                                                                                                                         | Verify regulations address:<br>1) General description of work authorized,<br>2) Description of procedures and quality or inspection system,<br>3) General description of facilities,<br>4) Names and duties of persons required to ensure compliance with the requirements for an AMO,<br>5) Description of the procedures used to establish the competence of maintenance personnel,<br>6) Description of the method used for the completion and retention of maintenance records,<br>7) Description of the procedures for preparing maintenance release and the circumstances under which the release is to be signed,<br>8) Personnel authorized to sign the maintenance release and the scope of their authorization,<br>9) Description, when applicable, of the additional procedures for complying with an operator’s maintenance procedures and requirements,<br>10) Description of the procedures for complying with the service information reporting requirements, and<br>11) Description of the procedure for receiving, assessing, amending and distributing the airworthiness data from the TC holder or type design organization. | STD<br>A6<br>Part I, 8.7.2<br>GM<br>Doc 9760<br>Part III, C10, Att. A                                                                                                                                                                                                                                             | CE-2 | Não          | SAR                        | n/a                       | GGAC<br>GTPN                 | RBAC 145.209                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | n/a                                                |\n| 5.395  | Has the AID developed procedures for the review of the maintenance procedures manual as part of the process for approving a maintenance organization?                                                                                                                                                                                                                                                                                                             | Review procedures for inclusion of:<br>1) Required contents<br>2) Revision control<br>3) Document control                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | STD<br>A6<br>Part I, 8.7.2<br>GM<br>Doc 9760<br>Part III, 10.3                                                                                                                                                                                                                                                    | CE-5 | Não          | SAR                        | n/a                       | GGAC                         | IS 145-001, item 5.4<br>IS 145-009                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | n/a                                                |\n| 5.397  | Does the AID review and approve/accept the maintenance procedures manual as part of the approval process for a maintenance organization?                                                                                                                                                                                                                                                                                                                          | 1) Sample an approved maintenance procedures manual to confirm effective implementation of established requirements and procedures.<br>2) Verify, if up-to-date copy is kept by the AID.<br>3) Verify during industry visit that AMO and AID are working to the same version of the maintenance procedures manual.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | GM<br>Doc 9760<br>Part III, 10.3                                                                                                                                                                                                                                                                                  | CE-6 | Não          | SAR                        | n/a                       | GGAC                         | n/a                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | n/a                                                |\n| 5.411  | Has the State promulgated a regulation for AMOs to have facilities and working environment appropriate for the task to be performed?                                                                                                                                                                                                                                                                                                                              | Verify regulations.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | STD<br>A6<br>Part I, 8.7.5<br>GM<br>Doc 9760<br>Part III, 10.6.1                                                                                                                                                                                                                                                  | CE-2 | Não          | SAR                        | n/a                       | GGAC                         | RBAC 145.103                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | n/a                                                |\n| 5.412  | Has the State promulgated regulations for a maintenance release, the circumstances under which a maintenance release shall be made and the persons who are entitled to sign the release?                                                                                                                                                                                                                                                                          | Verify regulations.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | STD<br>A6<br>Part I, 8.8<br>Part II, 2.6.4 & 3.8.5<br>Part III, Section II, 6.7 &<br>Section III, 6.5<br>GM<br>Doc 9760<br>Part III, 10.9                                                                                                                                                                         | CE-2 | Não          | SAR                        | n/a                       | GGAC                         | RBAC 43.5 e RBAC 43.7                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | n/a                                                |\n| 5.413  | Has the AID developed procedures and a checklist for the conduct of AMO facilities inspections?                                                                                                                                                                                                                                                                                                                                                                   | 1) Review procedures and checklist.<br>2) Verify that procedures/ checklists contain items addressed in AIR PQs 5.415, 5.417 and 5.419.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | GM<br>Doc 9760<br>Part III, 10.6.1                                                                                                                                                                                                                                                                                | CE-5 | Não          | SAR                        | n/a                       | GGAC                         | MPR-900-06, Chapter 9<br>F-900-36, F900-38, F900-39 and F900-41                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | n/a                                                |\n| 5.415  | Has the AID established and implemented a mechanism to ensure that the AMO has proper storage facilities and appropriate working environment for the task to be performed?                                                                                                                                                                                                                                                                                        | 1) Review certification inspection documents to confirm that the following points were checked:<br> a) Adequate lighting.<br> b) Control of the environment.<br> c) Instrument maintenance performed in a dust-free environment.<br> d) Proper storage facilities for parts, tools and material.<br> e) Secure storage conditions.<br> f) Storage which prevents deterioration and damage to stored items.<br> g) Adequately ventilated and environmentally controlled storage facilities.<br>2) Verify during industry visit.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | STD<br>A6<br>Part I, 8.7.5<br>GM<br>Doc 9760<br>Part III, 10.6.1                                                                                                                                                                                                                                                  | CE-6 | Não          | SAR                        | n/a                       | GGAC                         | F-900-38                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | n/a                                                |\n| 5.417  | Has the AID established and implemented a mechanism to ensure that the AMO has the necessary technical data, equipment, tools and material?                                                                                                                                                                                                                                                                                                                       | 1) Review certification inspection documents for confirmation.<br>2) Verify during industry visit.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | STD<br>A6<br>Part I, 8.7.5.2<br>GM<br>Doc 9760<br>Part III, 10.6.2                                                                                                                                                                                                                                                | CE-6 | Não          | SAR                        | n/a                       | GGAC                         | F-900-39                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | n/a                                                |\n| 5.419  | Has the AID established and implemented a mechanism to verify that precision measurement test equipment and/or precision tools used at AMOs are properly calibrated?                                                                                                                                                                                                                                                                                              | 1) Review certification inspection documents for confirmation.<br>2) Verify during industry visit.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | GM<br>Doc 9760<br>Part III, 10.6.2                                                                                                                                                                                                                                                                                | CE-6 | Não          | SAR                        | n/a                       | GGAC                         | F-900-39                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | n/a                                                |\n| 5.423  | Has the AID established and implemented a mechanism to ensure that AMOs employ trained and qualified personnel to ensure compliance with the requirements and good maintenance practices?                                                                                                                                                                                                                                                                         | 1) Review documents to confirm adherence.<br>2) Verify during industry visit.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | STD<br>A6<br>Part I, 8.7.6<br>GM<br>Doc 9760<br>Part III, 10.7.1                                                                                                                                                                                                                                                  | CE-6 | Não          | SAR                        | n/a                       | GGAC                         | F-900-36                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | n/a                                                |\n| 5.425  | Has the AID established and implemented a mechanism to ensure that AMOs establish appropriate minimum qualifications for managers, certifying staff, auditors, mechanics and specialist technicians (i.e. NDT and welding)?                                                                                                                                                                                                                                       | 1) Review documentation to ensure appropriate minimum qualifications are established.<br>2) Verify implementation during industry visit.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | STD<br>A6<br>Part I, 8.7.6<br>GM<br>Doc 9760<br>Part III, 10.7.1                                                                                                                                                                                                                                                  | CE-6 | Não          | SAR                        | n/a                       | GGAC                         | F-900-36                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | n/a                                                |\n| 5.429  | Has the AID established and implemented a mechanism to ensure that AMO employees receive initial and recurrent training appropriate to their assigned tasks and responsibilities?                                                                                                                                                                                                                                                                                 | 1) Review training requirements established in AMO documentation including knowledge and skills related to human performance, where appropriate.<br>2) Review evidence to confirm effective implementation.<br>3) Verify during industry visit.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | STD<br>A6<br>Part I, 8.7.6<br>GM<br>Doc 9760<br>Part III, 10.7.2                                                                                                                                                                                                                                                  | CE-6 | Não          | SAR                        | n/a                       | GGAC                         | IS 145-010 (Training Program), F-900-36                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | n/a                                                |\n| 5.441  | Has the AID developed a formal surveillance policy/procedure to be used by airworthiness inspectors for conducting surveillance activities of AOC holders, foreign air operators and domestic and foreign AMOs?                                                                                                                                                                                                                                                   | Review policy/procedure and check for inclusion of:<br>1) Identification of surveillance activities (inspections, audits) to be carried out for AOC holders, foreign air operators, domestic and foreign AMOs.<br>2) Guidelines for scheduling surveillance activities.<br>3) Standardized checklists for maintenance facility inspections.<br>4) Inspection/audit process.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | STD<br>A6<br>Part I, 4.2.1.8 & 4.2.2.2;<br>App. 5, 5.1 & 7<br>Part III, Section II, 2.2.1.8<br>& 2.2.2.2; App. 1, 5.1 & 7<br>A19<br>App. 1, 5.1 & 7<br>GM<br>Doc 8335<br>Part I, 2.2.3 & 5.2<br>Part IV & Part VI<br>Doc 9760<br>Part II, 2.2.1, 4.4 & 4.7.4<br>Part III, 1.2 r) & s)<br>Part IV, 1.2 i), j) & k) | CE-5 | Não          | SAR                        | n/a                       | GGAC                         | Programa de Vigilância Continuada (PVC) e F-900-17, -18, -19, -20, -21, -22, -23, -24, -27, -28, -29, -31, -32, -36, -38, -39 e -41. + PTA                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | n/a                                                |\n| 5.443  | Is a formal surveillance programme implemented to verify that all AOC holders comply on a continuing basis with airworthiness-related national regulations, international standards, AOCs and corresponding operations specifications?                                                                                                                                                                                                                            | 1) Review surveillance programme for previous and current year (planned and completed).<br>2) Inclusion of random checks on all aspects of maintenance.<br>3) Confirm appropriate frequency of surveillance activities (may be based on proven safety indicators or results of previous activities, such as inspections/audits).<br>4) Sample inspection/audit records for AOC holders.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | STD<br>A6<br>Part I, 4.2.1.8; App. 5, 7<br>Part III, Section II,<br>2.2.1.8; App. 1, 7<br>A19<br>App. 1, 7<br>GM<br>Doc 8335<br>Part I, 2.2.3 & 5.2<br>Part IV<br>Doc 9734<br>Part A, C3<br>Doc 9760<br>Part II, 2.2.1, 4.4 & 4.7.4<br>Part III, 1.2 r) & s)<br>Part IV, 1.2 i), j) & k)                          | CE-7 | Não          | SAR                        | n/a                       | GGAC                         | : Programa de Trabalho Anual (PTA)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | n/a                                                |\n| 5.444  | Is a formal surveillance programme implemented to verify that all AMOs comply on a continuing basis with national regulations, international standards and AMO certificates?                                                                                                                                                                                                                                                                                      | 1) Review surveillance programme for previous and current year (planned and completed).<br>2) Inclusion of random checks on all aspects of maintenance.<br>3) Confirm appropriate frequency of surveillance activities (may be based on proven safety indicators or results of previous activities, such as inspections/audits).<br>4) Sample inspection/audit records for domestic and AMOs in foreign States.<br>5) For AMOs in a foreign State, if tasks have been delegated to foreign authorities, check for evidence that the State has received and<br>evaluated inspection/audit records provided by foreign authorities.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | STD<br>A6<br>Part I, 8.7.1.3<br>A19<br>App. 1, 7<br>GM<br>Doc 9734<br>Part A, C3<br>Doc 9760<br>Part II, 2.2.1, 4.4 & 4.7.4<br>Part III, 1.2 r) & s)<br>Part IV, 1.2 i), j) & k)                                                                                                                                  | CE-7 | Não          | SAR                        | n/a                       | GGAC                         | : Programa de Trabalho Anual (PTA)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | n/a                                                |\n| 5.445  | Has the AID implemented a documented process and/or a method to track identified deficiencies, to evaluate corrective actions presented by air operators and/or AMOs and to take appropriate actions, up to and including enforcement measures, to resolve identified deficiencies and safety issues in a timely manner?                                                                                                                                          | 1) Sample surveillance reports and correspondence with AOC holders, foreign air operators and domestic and foreign AMOs.<br>2) Review process/method to track identified deficiencies.<br>3) Confirm deficiencies rectified in a timely manner.<br>4) Review examples of actions taken, such as:<br> a) fines,<br> b) restrictions, and<br> c) suspension/revocation, limitation, restriction of certificate and/or operation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | STD<br>A6<br>Part I, App. 5, 5.2 & 8<br>Part III, App. 1, 5.2 & 8<br>A19<br>App. 1, 8<br>GM<br>Doc 8335<br>Part I, 5.2<br>Part IV & Part VI<br>Doc 9734<br>Part A, C3<br>Doc 9760<br>Part II, 4.2 k), 4.4 & 4.7.4<br>Part III, 1.2 t) & u)<br>Part IV, 1.2 l)                                                     | CE-8 | Não          | SAR                        | n/a                       | GGAC                         | MPRI 900-08 (OMA),                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | n/a                                                |\n| 5.447  | Does the surveillance programme include ramp inspections of aircraft operated by AOC holders and foreign air operators?                                                                                                                                                                                                                                                                                                                                           | 1) Review ramp inspection programme for previous and current year (planned versus completed).<br>2) Confirm appropriate frequency.<br>3) Review evidence on policy on items to be checked during ramp inspections, such as:<br> a) Flight deck - general (e.g. condition, emergency exit, equipment);<br> b) Flight deck - documentation (e.g. manuals, checklists, route guide, MEL, documents to be carried on board, flight deck safety equipment);<br> c) Cabin/Safety;<br> d) Aircraft external condition, e.g. previous structural repairs, obvious damage, leakage (e.g. apparent corrosion);<br> e) Cargo (condition of cargo compartment and containers, dangerous goods, safety of cargo on board); and<br> f) General (additional remarks, refuelling, language for  communication).                                                                                                                                                                                                                                                                                                                                                 | STD<br>A6<br>Part I, 4.2.1.8 & 4.2.2.2;<br>App. 5, 7<br>Part III, Section II, 2.2.1.8<br>& 2.2.2.2; App. 1, 7<br>A19<br>App. 1, 7<br>GM<br>Doc 8335<br>Part IV & Part VI<br>Doc 9760<br>Part II, 4.7.4<br>Part IV, 1.2 k)                                                                                         | CE-7 | Não          | SAR                        | n/a                       | GGAC                         | PTA, F-900-24                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | n/a                                                |\n| 5.448  | Does the CAA keep records of all ramp inspections of aircraft carried out, accessible to and updated by the inspectors concerned?                                                                                                                                                                                                                                                                                                                                 | 1) Check records for ramp inspections or database.<br>2) Verify the scope of ramp inspections performed.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | Doc 8335<br>Part IV, Att.                                                                                                                                                                                                                                                                                         | CE-6 | Não          | SAR                        | n/a                       | GGAC                         | GIASO                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | n/a                                                |\n| 5.449  | If deficiencies are identified during the conduct of ramp inspections and indicate serious safety deficiencies/concerns, does the regulatory authority take appropriate action when necessary to preserve safety?                                                                                                                                                                                                                                                 | Verify:<br>1) procedures to guide inspectors on actions to be taken against air operators, including level of findings (minor, significant, major).<br>2) examples of actions taken.<br>3) feedback provided to air operators and the air operator’s response/proposal regarding the rectification of deficiencies/concerns.<br>4) examples of correspondence with the State of Registry of the aircraft.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | STD<br>A6<br>Part I, 4.2.1.8 & 4.2.2.2;<br>App. 5, 5.2 & 8<br>Part III, Section II, 2.2.1.8<br>& 2.2.2.2; App. 1, 5.2 & 8<br>A19<br>App. 1, 8<br>GM<br>Doc 8335<br>Part VI, 1.3.2<br>Doc 9760<br>Part II, 4.7.4.3                                                                                                 | CE-8 | Não          | SAR                        | n/a                       | GGAC                         | PISOR, NCIA, MPR 100<br>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | n/a                                                |\n| 5.451  | Does the AID conduct ongoing surveillance of reliability programmes?                                                                                                                                                                                                                                                                                                                                                                                              | Verify<br>1) monitoring of reliability programmes.<br>2) EDTO monitoring.<br>3) Attendance by AID at air operator’s periodic meetings.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | GM<br>Doc 9760<br>Part II, 4.7.4.4 d)<br>Part III, 7.4<br>Part IV, C2 & C5                                                                                                                                                                                                                                        | CE-7 | Não          | SAR                        | n/a                       | GGAC                         | IS 120-079, Manual do SASC, Programa de Confiabilidade, Relatório de Confiabilidade                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | n/a                                                |\n| 5.453  | Does the AID initiate a special evaluation or impose special operational restrictions if information obtained from reliability monitoring indicates a degraded level of safety?                                                                                                                                                                                                                                                                                   | Review examples of actions taken.<br><br>Note. — If surveillance of reliability programmes is not conducted, this PQ is automatically Not Satisfactory.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | GM<br>Doc 9760<br>Part II, 4.7.4.4 d)<br>Part IV, 5.4                                                                                                                                                                                                                                                             | CE-8 | Não          | SAR                        | n/a                       | GGAC                         | SASC                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | n/a                                                |\n| 5.461  | Has the State established an organizational structure for AED?                                                                                                                                                                                                                                                                                                                                                                                                    | Confirm current approved organizational structure for CAA and AED, including lines of responsibility.<br><br>\\- This PQ is not linked to ORG PQ 2.010.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | STD<br>A19<br>App. 1, 3.1<br>GM<br>Doc 9734<br>Part A, C3<br>Doc 9760<br>Part II, 4.1.2 & 4.6.1                                                                                                                                                                                                                   | CE-3 | Não          | SAR                        | n/a                       | GGCP                         | \\[1\\] - Law Nº 11182/2005<br>\\[2\\] - Resolução Nº 381/2016 – Tit II<br>\\[3\\] - Resolução Nº 381/2016 – Sec V<br>\\[4\\] - Portaria Nº 1655/2017/SAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | n/a                                                |\n| 5.463  | Are the functions and responsibilities of the AED clearly defined?                                                                                                                                                                                                                                                                                                                                                                                                | 1) Review the document detailing functions and responsibilities of the AED.<br>2) This PQ is not linked to ORG PQ 2.011.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | STD<br>A19<br>App. 1, 3.1<br>GM<br>Doc 9760<br>Part II, 4.6                                                                                                                                                                                                                                                       | CE-3 | Não          | SAR                        | n/a                       | GGCP                         | Regimento ANAC (currently approved by Resolution 381 dated 14th June 2016)<br>Portaria SAR 1.655 dated 12th May 2017<br>Portaria GGCP 1.262 dated 10 April 2017                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | n/a                                                |\n| 5.467  | Have job descriptions been developed for technical staff and key management personnel of the AED?                                                                                                                                                                                                                                                                                                                                                                 | Review job descriptions for AED staff, including:<br>1) aircraft certification engineers,<br>2) continuing airworthiness engineers, and<br>3) manufacturing inspectors.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | GM<br>Doc 9734<br>Part A, C3<br>Doc 9760<br>Part II, 4.6                                                                                                                                                                                                                                                          | CE-3 | Não          | SAR                        | n/a                       | GGCP                         | 1- Lei 11\\_182-CriacaoANAC exerpt.pdf<br>2- Lei 10871-CarreirasAgReguladoras.pdf<br>3- RES 381-2016 Reg Interno.pdf<br>4- Ord 1655/2017 SAR mgmt responsibilities.pdf                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | n/a                                                |\n| 5.469  | If the State is involved in design or manufacturing activities, is there a clear separation of authority between the State manufacturing/design organization and the State regulatory authority?                                                                                                                                                                                                                                                                  | 1) Review organizational structure and verify separation of authority.<br>2) Verify documented evidence to ensure separation of authority.<br>3) This PQ is linked to ORG PQ 2.021.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | GM<br>Doc 9734<br>Part A, C2                                                                                                                                                                                                                                                                                      | CE-3 | Não          | SAR                        | n/a                       | GGCP                         | n/a                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | n/a                                                |\n| 5.471  | Has the State established the appropriate minimum qualifications and experience requirements for airworthiness engineers?                                                                                                                                                                                                                                                                                                                                         | Qualification/experience requirements should include:<br>1) Relevant knowledge, background and experience related to the design, manufacture and airworthiness certification of aircraft and<br>its related aeronautical products; and<br>2) Aeronautical licences, certificates or academic degrees commensurate with their job responsibilities.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | STD<br>A19<br>App. 1, 4.1<br>GM<br>Doc 9734<br>Part A, C3<br>Doc 9760<br>Part II, 4.5.1, 4.5.2 &<br>4.5.5.1                                                                                                                                                                                                       | CE-4 | Não          | SAR                        | n/a                       | GGCP                         | AIR-Specific Training Program                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | n/a                                                |\n| 5.472  | Does the State ensure that the established minimum qualification and experience requirements are met by all airworthiness engineers?                                                                                                                                                                                                                                                                                                                              | 1) Sample recruitment files.<br>2) Cross-check with established requirements.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | STD<br>A19<br>App. 1, 4.1<br>GM<br>Doc 9734<br>Part A, C3<br>Doc 9760<br>Part II, 4.5.1 & 4.5.2                                                                                                                                                                                                                   | CE-4 | Não          | SAR                        | n/a                       | GGCP                         | MPR-401                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | n/a                                                |\n| 5.473  | Does the AED have sufficient human resources to carry out its functions and mandate?                                                                                                                                                                                                                                                                                                                                                                              | Verify :<br>1) mechanism established for determining<br>staffing needs.<br>2) ability to attract new airworthiness<br>engineers as well as existing vacancies and<br>level of turnover in past years.<br>3) ability to carry out all safety oversight<br>related tasks, including review and revision of<br>regulations, training of technical staff,<br>development of guidance material, issuance<br>of certificates, approvals, and permits,<br>conduct surveillance and resolution of<br>identified safety deficiencies.<br><br>\\- This PQ is not linked to ORG PQ 2.053.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | STD<br>A19<br>App. 1, 3.1<br>RP<br>A19<br>App. 1, 3.2 & 3.4<br>GM<br>Doc 9734<br>Part A, C3<br>Doc 9760<br>Part II, 4.5.1                                                                                                                                                                                         | CE-3 | Não          | SAR                        | n/a                       | GGCP                         | MPR-050                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | n/a                                                |\n| 5.477  | If the AED delegates its engineering tasks to other CAA divisions, State bodies, Contracting States, regional organizations, private agencies or individuals, have requirements for competency been established?                                                                                                                                                                                                                                                  | 1) Review competency requirements for delegated entities.<br>2) Review minimum qualifications and experience required for individuals receiving delegation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | GM<br>Doc 9734<br>Part A, C3<br>Doc 9760<br>Part II, 4.1                                                                                                                                                                                                                                                          | CE-4 | Não          | SAR                        | n/a                       | GGCP                         | \\[1\\] - Law 11.182/2005 Art. 8 §1º<br>\\[2\\] - RBAC 183.29<br>\\[3\\] - IS 183-002 – section 5.3.3                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | n/a                                                |\n| 5.479  | If the State delegates engineering tasks to other CAA divisions, State bodies, Contracting States, regional organizations, private agencies or individuals, have the delegated tasks been clearly defined?                                                                                                                                                                                                                                                        | 1) Review documentation clearly defining tasks delegated.<br>2) Verify the legal mechanism for the delegation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | GM<br>Doc 9734<br>Part A, C3<br>Doc 9760<br>Part II, 4.1                                                                                                                                                                                                                                                          | CE-3 | Não          | SAR                        | n/a                       | GGCP                         | \\[1\\] - RBAC 183.29<br>\\[2\\] - IS 183-002 – sec 5.9.10<br>\\[3\\] - F-200-08<br>\\[4\\] - Law 11.182/2005 Art. 8 §1º 4                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | n/a                                                |\n| 5.481  | Does the AED conduct surveillance of engineering tasks delegated to other CAA divisions, State bodies, Contracting States, regional organizations, private agencies or individuals?                                                                                                                                                                                                                                                                               | 1) Review mechanism for oversight and confirm adherence.<br>2) Maintenance of competency.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | STD<br>A19<br>App. 1, 7<br>GM<br>Doc 9734<br>Part A, C3<br>Doc 9760<br>Part II, 4.1 & 4.4                                                                                                                                                                                                                         | CE-7 | Não          | SAR                        | n/a                       | GGCP                         | ITD-441-01                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | n/a                                                |\n| 5.483  | If deficiencies or concerns are identified in the engineering tasks delegated to other CAA divisions, State bodies, Contracting States, regional organizations, private agencies or individuals, does the AED have a process in place to resolve said deficiencies or concerns?                                                                                                                                                                                   | Review examples of corrective actions taken to resolve concerns related to delegated tasks.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | STD<br>A19<br>App. 1, 8<br>GM<br>Doc 9734<br>Part A, C3                                                                                                                                                                                                                                                           | CE-8 | Não          | SAR                        | n/a                       | GGCP                         | MPR-SAR-441                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | n/a                                                |\n| 5.485  | Has the AED developed a formal training programme detailing the type of training to be provided to airworthiness engineers?                                                                                                                                                                                                                                                                                                                                       | 1) Review contents of training programme.<br>2) Confirm inclusion of initial, OJT, recurrent<br>and specialized training, as applicable, with<br>time periods to be provided.<br>3) Verify specialized training, as applicable,<br>for:<br> a)) Avionics<br> b) Propulsion systems<br> c) Structures<br> d) General aviation aircraft<br> e) Helicopters<br> f) Flight testing<br> g) Human factors<br> h) Quality systems<br> i) Modifications and repairs<br> j) MRB and MSG3<br> k) System safety assessment.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | STD<br>A19<br>App. 1, 4.1<br>GM<br>Doc 9683<br>Doc 9734<br>Part A, C3<br>Doc 9760<br>Part II, 4.5.5                                                                                                                                                                                                               | CE-4 | Não          | SAR                        | n/a                       | GGCP                         | Training programme                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | n/a                                                |\n| 5.487  | Does the AED develop a periodic training plan for each engineer detailing and prioritizing the type of training to be provided during the established period?                                                                                                                                                                                                                                                                                                     | Review most recent training plan.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | STD<br>A19<br>App. 1, 4.1<br>GM<br>Doc 9734<br>Part A, C3<br>Doc 9760<br>Part II, 4.5.5                                                                                                                                                                                                                           | CE-4 | Não          | SAR                        | n/a                       | GGCP                         | PDA<br>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | n/a                                                |\n| 5.489  | Is the training programme for airworthiness engineers appropriately implemented?                                                                                                                                                                                                                                                                                                                                                                                  | Verify that the type and frequency of training provided (initial, recurrent and specialized) are sufficient for the technical staff to achieve/maintain the required level of knowledge, skills, competence and qualifications in accordance with their assigned duties and responsibilities.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | STD<br>A19<br>App. 1, 4.1<br>GM<br>Doc 9734<br>Part A, C3<br>Doc 9760<br>Part II, 4.5.5                                                                                                                                                                                                                           | CE-4 | Não          | SAR                        | n/a                       | GGCP                         | \\[1\\] – PEC-AIR<br>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | n/a                                                |\n| 5.491  | Are airworthiness engineers required to satisfactorily complete OJT prior to being assigned tasks and responsibilities?                                                                                                                                                                                                                                                                                                                                           | 1) Review requirement for the provision of OJT.<br>2) Verify that OJT is provided by na experienced, senior engineer.<br>3) Verify that completion of OJT has been documented.<br>4) Verify competency assessment and authorization process.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | STD<br>A19<br>App. 1, 4<br>GM<br>Doc 9734<br>Part A, C3                                                                                                                                                                                                                                                           | CE-4 | Não          | SAR                        | n/a                       | GGCP                         | \\[1\\] – PEC-AIR<br>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | n/a                                                |\n| 5.493  | Does the AED have a system for the maintenance of training records for its technical staff?                                                                                                                                                                                                                                                                                                                                                                       | 1) Review instruction or requirement for the establishment and maintenance of training records.<br>2) Verify training records are systematically retained.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | STD<br>A19<br>App. 1, 4.2<br>GM<br>Doc 9734<br>Part A, C3                                                                                                                                                                                                                                                         | CE-4 | Não          | SAR                        | n/a                       | GGCP                         | 1- MPR-401<br>2 - SACI                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | n/a                                                |\n| 5.501  | Are the relevant ICAO documents and other technical publications readily available to the technical and administrative staff of the AED?                                                                                                                                                                                                                                                                                                                          | Verify if relevant publications are readily available, such as:<br>1) State laws and regulations;<br>2) Orders and instructions;<br>3) Current copy of Annexes 6, Parts I, II, and<br>III; 7, 8; 16, Volumes I and II; and 19;<br>4) Copies of ICAO guidance material (Doc<br>9734, Doc 9735, Doc 9760, Doc 9859, CIR<br>295, etc.).<br><br>Note to the auditor:<br>\\- Check for field/regional offices as well as<br>Headquarters.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | GM<br>Doc 9734<br>Part A, C3<br>Doc 9760<br>Part II, 4.9                                                                                                                                                                                                                                                          | CE-5 | não          | SAR                        | n/a                       | GGCP<br>                     | 1- Informações Técnicas<br>2- Certificados e Especificações de Tipo<br>3- Manuais e boletins de produtos aeronáuticos<br>4- Publicações da OACI<br>5- MPR-SAF-072                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | n/a                                                |\n| 5.503  | Is there an airworthiness technical library available for airworthiness engineers or another method to ensure receipt, control and distribution of the necessary technical documentation?                                                                                                                                                                                                                                                                         | Evaluate:<br>1) Document control system.<br>2) Method to determine currency of documents.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | GM<br>Doc 9734<br>Part A, C3<br>Doc 9760<br>Part II, 4.9                                                                                                                                                                                                                                                          | CE-5 | não          | SAR                        | n/a                       | GGCP<br>                     | 1MPR-SAF-072                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | n/a                                                |\n| 5.505  | Do airworthiness engineers have access to design organization documentation and continuing airworthiness information for the aircraft designed in other State and on the State’s register?                                                                                                                                                                                                                                                                        | Verify accessibility of documents, such as:<br>1) Aircraft flight manual<br>2) Maintenance manual<br>3) Structural repair manual<br>4) Service bulletins<br>5) MMEL<br>6) MRB report<br>7) ADs.<br><br>Note to the auditor:<br>Documents may be found in the technical library in hard/electronic copy or via the Intranet/Internet. If access to documents is dependent on industry, engineers should at least have an index to confirm currency of<br>documents.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | STD<br>A8<br>Part II, 4.2.3<br>GM<br>Doc 9760<br>Part II, 4.9                                                                                                                                                                                                                                                     | CE-5 | não          | SAR                        | n/a                       | GGCP<br>                     | 1- Informações Técnicas — ANAC<br>2- Manuais e boletins de produtos aeronáuticos — ANAC                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | n/a                                                |\n| 5.507  | Are airworthiness engineers provided with comprehensive and sufficiently detailed guidance material and procedures to effectively carry out their functions?                                                                                                                                                                                                                                                                                                      | 1)Verify availability of applicable guidance material and procedures.<br>2) Verify mechanism to issue procedures.<br>3) Verify method to ensure currency.<br><br>Note — May be compiled in an inspector’s handbook or in a procedures manual.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | STD<br>A19<br>App. 1, 5.1<br>GM<br>Doc 9734<br>Part A, C3<br>Doc 9760<br>Part II, 4.6                                                                                                                                                                                                                             | CE-5 | não          | SAR                        | n/a                       | GGCP<br>                     | 1- MPR-SAR-421<br>2- MPR-SAR-101                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | n/a                                                |\n| 5.509  | Does the AED have sufficient office equipment?                                                                                                                                                                                                                                                                                                                                                                                                                    | Check available communication means and office equipment:<br>1) Telephones/cellular phones<br>2) Fax<br>3) Printer<br>4) Computers/laptops/notebooks<br>5) Photocopier<br>6) Internet/Intranet<br>7) Microfiche/microfilm reader, if needed.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | STD<br>A19<br>App. 1, 5.1<br>GM<br>Doc 9734<br>Part A, C3                                                                                                                                                                                                                                                         | CE-5 | não          | SAR                        | n/a                       | GGCP<br>                     | n/a                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |                                                    |\n| 5.511  | Does the AED provide transportation for airworthiness engineers to perform their duties?                                                                                                                                                                                                                                                                                                                                                                          | Review means of transportation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | STD<br>A19<br>App. 1, 5.1<br>GM<br>Doc 9734<br>Part A, C3<br>Doc 9760<br>Part II, 4.1.2                                                                                                                                                                                                                           | CE-5 | não          | SAR                        | n/a                       | GGCP<br>                     | n/a                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |                                                    |\n| 5.521  | If the State, as the State of Design, issues type certificate approvals, are there regulatory provisions in place to allow the CAA to impose additional requirements to provide at least an equivalent level of safety in the event that the applicable airworthiness requirements are inadequate or inappropriate?                                                                                                                                               | Verify regulations.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | STD<br>A8<br>Part II, 1.2.3 & 1.2.4<br>GM<br>Doc 9760<br>Part V, 2.3.2.4.3                                                                                                                                                                                                                                        | CE-2 | não          | SAR                        | n/a                       | GGCP<br>                     | \\[1\\] - RBAC 21.16<br>\\[2\\] - RBAC 21.21                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | n/a                                                |\n| 5.523  | Has the State promulgated a regulation for type certificate applicants to provide and keep all the drawing, specifications, reports and documentary evidence necessary to define the design of the aircraft and show compliance with the design aspects of the appropriate airworthiness requirements?                                                                                                                                                            | Verify regulations.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | STD<br>A8<br>Part II, 1.3.1<br>GM<br>Doc 9760<br>Part V, 2.3.6.2                                                                                                                                                                                                                                                  | CE-2 | não          | SAR                        | n/a                       | GGCP<br>                     | \\[1\\] - RBAC 21.21<br>\\[2\\] - RBAC 21.49                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | n/a                                                |\n| 5.525  | Has the State promulgated a regulation for aircraft to be subjected to such inspections and ground and flight tests as are deemed necessary by the State to show compliance prior to receiving a type certificate?                                                                                                                                                                                                                                                | Verify regulations.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | STD<br>A8<br>Part II, 1.3.2<br>GM<br>Doc 9760<br>Part V, 2.3.4 & 2.3.5.1                                                                                                                                                                                                                                          | CE-2 | não          | SAR                        | n/a                       | GGCP<br>                     | RBAC 21.33 and RBAC 21.34                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | n/a                                                |\n| 5.527  | Has the State promulgated a regulation for type certificate applicants to develop the maintenance tasks and frequencies (maintenance programme) required for maintaining the aeroplane in an airworthy condition?                                                                                                                                                                                                                                                 | Verify regulations.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | STD<br>A8<br>Part IIIA, C10<br>Part IIIB, 7.7<br>Part IVB, 7.7<br>Part V, 7.7<br>GM<br>Doc 9760<br>Part V, 2.5 & 2.6                                                                                                                                                                                              | CE-2 | não          | SAR                        | n/a                       | GGCP<br>GTPN<br>             | \\[1\\] - RBAC 21.50<br>\\[2\\] - RBAC 23.1529 & Appendix G<br>\\[3\\] - RBAC 25.1529 & Appendix H<br>\\[4\\] - RBAC 27.1529 & Appendix A<br>\\[5\\] - RBAC 29.1529 & Appendix A                                                                                                                                                                                                                                                                                                                                                                                                                                                                | n/a                                                |\n| 5.529  | Has the State promulgated a regulation for type certificate applicants to develop and provide a flight manual, placards or other documents stating the approved limitations within which the aircraft is considered airworthy and any additional instructions for the safe operation of the aircraft?                                                                                                                                                             | Verify regulations.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | STD<br>A8<br>Part II, 3.4<br>                                                                                                                                                                                                                                                                                     | CE-2 | não          | SAR                        | n/a                       | GGCP<br>GTPN<br>             | \\[1\\] - RBAC 21.5<br>\\[2\\] - RBAC 23 - Subpart G<br>\\[3\\] - RBAC 25 - Subpart G<br>\\[4\\] - RBAC 27 - Subpart G<br>\\[5\\] - RBAC 29 - Subpart G                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | n/a                                                |\n| 5.531  | Has the State established procedures for the approval of a type design and the issuance of a type certificate?                                                                                                                                                                                                                                                                                                                                                    | Review and verify inclusion of:<br>1) Establishment of applicable designstandards<br>2) Applicant provides proof that the design meets the applicable standards<br>3) Operating limitations identified<br>4) Special conditions identified<br>5) Type inspection of prototype completed<br>6) Flight test completed with satisfactory results<br>7) Aircraft Flight Manual (AFM) approved<br>8) Type certificate data sheet developed<br>9) Production drawings approved<br>10) Type design record approved<br>11) Type certificate issued<br>12\\. Maintenance and repair manual approved                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | GM<br>Doc 9760<br>Part V, 2.2 & 2.3                                                                                                                                                                                                                                                                               | CE-5 | não          | SAR                        | n/a                       | GGCP                         | \\[1\\] - RBAC 21.17<br>\\[2\\] - MPR/SAR-101 – Section 5.2<br>\\[3\\] - ITD-101-02<br>\\[4\\] - MPR/SAR-101 – Section 5.3<br>\\[5\\] - ITD-101-04<br>\\[6\\] - form F-200-24<br>\\[7\\] - form F-200-06<br>\\[8\\] - RBAC 21.31                                                                                                                                                                                                                                                                                                                                                                                                                      | n/a                                                |\n| 5.533  | Does the AED have procedures to ensure AID involvement for the approval of instructions for continued airworthiness for an aeronautical product?                                                                                                                                                                                                                                                                                                                  |  Review procedures.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | GM<br>Doc 9760<br>Part II, 4.7.5<br>Part V, 2.1.4.1                                                                                                                                                                                                                                                               | CE-5 | não          | SAR                        | n/a                       | GGCP<br>GGAC                 | MPR-270                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | n/a                                                |\n| 5.535  | Has the State promulgated a regulation for human factors principles to be observed in the design and application of maintenance programmes?                                                                                                                                                                                                                                                                                                                       | Verify regulations.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | STD<br>A6<br>Part I, 8.3.1<br>Part II, 3.8.3.1<br>Part III, Section II, 6.3.1<br>GM<br>Doc 9683<br>Part 1, C6<br>Doc 9760<br>Part III, 7.3.1.1<br>Doc 9824<br>6.4 & 6.5; App. B to C6                                                                                                                             | CE-2 | não          | SAR                        | n/a                       | GGCP<br>GGAC<br>GTPN<br>     | 1- RBAC 23<br>2- RBAC 25                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | n/a                                                |\n| 5.537  | Has the AED implemented the requirements and procedures established for the issuance of a type certificate?                                                                                                                                                                                                                                                                                                                                                       | Review a file for the issuance of a type certificate for evidence of procedures followed.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | GM<br>Doc 9760<br>Part V, 2.2 & 2.3                                                                                                                                                                                                                                                                               | CE-6 | não          | SAR                        | n/a                       | GGCP<br>                     | MPR-101                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | n/a                                                |\n| 5.539  | Has the State established and implemented a mechanism to ensure that, in respect of aeroplanes over 5700 kg maximum certificated take-off mass, a continuing structural integrity programme, including specific information regarding corrosion prevention and control, is submitted by the type certificate holder for CAA approval?                                                                                                                             | Review procedures and verify implementation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | STD<br>A8<br>Part II, 4.2.1.1 c)<br>GM<br>Doc 9760<br>Part II, 4.6.4 e)<br>Part V, 2.7                                                                                                                                                                                                                            | CE-6 | não          | SAR                        | n/a                       | GGCP<br>                     | MPR-270                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | n/a                                                |\n| 5.541  | If an MRB will be established, are the AID and AED involved in the MRB process?                                                                                                                                                                                                                                                                                                                                                                                   | Review process.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | GM<br>Doc 9760<br>Part II, 4.6.4 f) & 4.7.5 b)<br>Part V, 2.8                                                                                                                                                                                                                                                     | CE-6 | não          | SAR                        | n/a                       | GGCP/ PAC<br>GGAC<br>        | MPR-270                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | n/a                                                |\n| 5.543  | Do the contents of the type certificate adhere to ICAO guidance material?                                                                                                                                                                                                                                                                                                                                                                                         | Verify the following details:<br>1) certificate number;<br>2) holder’s name;<br>3) product identification ( e.g. aircraft, engine or propeller type designation);<br>4) applicable airworthiness regulations;<br>5) statement incorporating or referencing the type certificate data sheet; and<br>6) date of issuance and signature of the issuing authority.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | GM<br>Doc 9760<br>Part V, 2.3.5.3.1                                                                                                                                                                                                                                                                               | CE-6 | não          | SAR                        | n/a                       | GGCP<br>                     | F-200-01                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | n/a                                                |\n| 5.545  | Does the AED develop a type certificate data sheet showing the applicable airworthiness standards, limitations and any other condition of approval to supplement each type certificate?                                                                                                                                                                                                                                                                           | Sample type certificate data sheets to confirm.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | GM<br>Doc 9760<br>Part V, C2, 2.3.5.4 & Att.<br>B                                                                                                                                                                                                                                                                 | CE-6 | não          | SAR                        | n/a                       | GGCP<br>                     | ITD-101-04                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | n/a                                                |\n| 5.547  | Does the AED keep copies of documents issued?                                                                                                                                                                                                                                                                                                                                                                                                                     | Confirm the following are retained, as applicable:<br>1) Type certificate,<br>2) Type certificate data sheet,<br>3) STC,<br>4) Design data approvals, and<br>5) Modifications and repairs approval.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | GM<br>Doc 9760<br>Part II, 4.9.4                                                                                                                                                                                                                                                                                  | CE-6 | não          | SAR                        | n/a                       | GGCP<br>                     | MPR-101                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | n/a                                                |\n| 5.549  | Has the State established the guidelines for the transfer of a type certificate?                                                                                                                                                                                                                                                                                                                                                                                  | Verify that:<br>1) Necessary background data for type design can be transferred to new holder.<br>2) New holder is competent to use the data as necessary for the continuing airworthiness of the aircraft type.<br>3) If new holder is in a different State, agreement between States needed to decide on applicable procedures.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | GM<br>Doc 9760<br>Part V, 6.2.3                                                                                                                                                                                                                                                                                   | CE-5 | não          | SAR                        | n/a                       | GGCP<br>                     | RBAC 21<br>MPR-101 (ainda em revisão)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | n/a                                                |\n| 5.551  | Has the State established procedures for the amendment of a type certificate?                                                                                                                                                                                                                                                                                                                                                                                     | Verify that:<br>1) Only the type certificate holder can apply.<br>2) Same procedures for the initial issuance of a type certificate.<br>3) Consideration given to the compatibility between proposed design changes and other existing design changes.<br>4) Instructions for continuing airworthiness.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | GM<br>A8<br>Part II, 1.3.4, Note 2<br>Doc 9760<br>Part III, 8.5, 8.7.9 & 8.8<br>Part V, 3.1                                                                                                                                                                                                                       | CE-5 | não          | SAR                        | n/a                       | GGCP<br>                     | RBAC 21<br>ITD-101-05                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | n/a                                                |\n| 5.561  | Has the State established procedures for the issuance of an STC?                                                                                                                                                                                                                                                                                                                                                                                                  | Verify that:<br>1) Same procedures for the initial issuance of a type certificate.<br>2) State of Design and/or organization responsible for the type design as part of the assessment is contacted.<br>3) Instructions for continuing airworthiness.<br>4) Consideration given to the compatibility between proposed design changes and other existing design changes, such as modifications, repairs and ADs.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | GM<br>A8<br>Part II, 1.3.4, Note 2<br>Doc 9760<br>Part III, 8.5, 8.7.9 & 8.8<br>Part V, 3.1                                                                                                                                                                                                                       | CE-5 | não          | SAR                        | n/a                       | GGCP<br>                     | MPR-102 “APROVAÇÃO SUPLEMENTAR DE TIPO”<br>IS 21-004B “Aprovação de Grandes Modificações em aeronaves com marcas brasileiras, ou que venham a ter marcas brasileiras”                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | n/a                                                |\n| 5.563  | Has the State established and implemented a mechanism to ensure that the applicant complies with the requirements for the issuance of an STC prior to receiving the approval?                                                                                                                                                                                                                                                                                     | Review an STC approval package to confirm effective implementation of established requirements and procedures.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | GM<br>Doc 9760<br>Part III, 8.7                                                                                                                                                                                                                                                                                   | CE-6 | não          | SAR                        | n/a                       | GGCP<br>                     | IS 21-004B<br> IS 21-021A<br>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | n/a                                                |\n| 5.565  | Has the State promulgated a regulation for STC approval holders to keep information related to their design approvals?                                                                                                                                                                                                                                                                                                                                            | Verify regulations.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | GM<br>Doc 9760<br>Part III, 8.8.2                                                                                                                                                                                                                                                                                 | CE-2 | não          | SAR                        | n/a                       | GGCP<br>                     | \\[1\\] - RBAC 21.115<br>\\[2\\] - RBAC 21.49                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | n/a                                                |\n| 5.567  | Has the State promulgated a regulation for STC approval holders to receive and analyse continuing airworthiness information from operators and AMOs?                                                                                                                                                                                                                                                                                                              | Verify regulations.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | STD<br>A8<br>Part II, 4.2.1.1 b)<br>GM<br>Doc 9760<br>Part III, 8.8                                                                                                                                                                                                                                               | CE-2 | não          | SAR                        | n/a                       | GGCP<br>                     | RBAC 21.3(a)&(f)<br>RBAC 21.99                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | n/a                                                |\n| 5.581  | Has the State promulgated regulations for the approval of design organizations?                                                                                                                                                                                                                                                                                                                                                                                   | Verify regulations.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | GM<br>A8<br>Part II, 1.3.1 Note                                                                                                                                                                                                                                                                                   | CE-2 | não          | SAR                        | n/a                       | GGCP<br>GTPN<br>             | RBAC 21                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | n/a                                                |\n| 5.583  | Has the AED developed procedures for the issuance of a design organization approval?                                                                                                                                                                                                                                                                                                                                                                              | Review procedures.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | GM<br>A8<br>Part II, 1.3.1 Note                                                                                                                                                                                                                                                                                   | CE-5 | não          | SAR                        | n/a                       | GGCP<br>                     | IS 21.231-001A COPj                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | n/a                                                |\n| 5.585  | Have the design organizations in the State been approved in accordance with the established regulations and procedures?                                                                                                                                                                                                                                                                                                                                           | Review evidence to confirm effective implementation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | GM<br>A8<br>Part II, 1.3.1 Note                                                                                                                                                                                                                                                                                   | CE-6 | não          | SAR                        | n/a                       | GGCP<br>                     | IS 21.231-001A COPj                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | n/a                                                |\n| 5.587  | Does the State conduct any continuing surveillance of approved design organizations and the approvals they are authorized to issue?                                                                                                                                                                                                                                                                                                                               | 1) Review surveillance programme.<br>2) Review evidence to confirm effective implementation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | STD<br>A19<br>App. 1, 7<br>GM<br>Doc 9734<br>Part A, C3                                                                                                                                                                                                                                                           | CE-7 | não          | SAR                        | n/a                       | GGCP<br>                     | IS 21.231-001A COPj                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | n/a                                                |\n| 5.589  | What actions are taken if deficiencies identified during surveillance of design organizations are not rectified in a reasonable time?                                                                                                                                                                                                                                                                                                                             | Review examples of actions taken.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | STD<br>A19<br>App. 1, 8<br>GM<br>Doc 9734<br>Part A, C3                                                                                                                                                                                                                                                           | CE-8 | não          | SAR                        | n/a                       | GGCP<br>                     | Como não há organizações de projeto já certificadas, não estabelecemos processo ainda.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | n/a                                                |\n| 5.601  | Has the State developed a method to track the notification from a Contracting State entering their aircraft on its registry?                                                                                                                                                                                                                                                                                                                                      | Review procedures and verify implementation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | STD<br>A8<br>Part II, 4.2.1                                                                                                                                                                                                                                                                                       | CE-6 | não          | SAR                        | n/a                       | GGCP-PAC<br>                 | MPR-201 item 5.6                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | n/a                                                |\n| 5.603  | Has the AED established and implemented a mechanism to ensure that design organizations have a system for receiving continuing airworthiness information from operators and providing necessary guidance?                                                                                                                                                                                                                                                         | Review evidence to confirm effective implementation of the requirements.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | GM<br>Doc 9760<br>Part V, 6.6                                                                                                                                                                                                                                                                                     | CE-6 | não          | SAR                        | n/a                       | GGCP-PAC<br>                 | RBAC 21.3(f)<br><br>IS 00-001 “Dificuldades em serviço” (see 5.4)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | n/a                                                |\n| 5.605  | Has the AED established and implemented a mechanism to ensure that design organizations have procedures for taking appropriate action after conducting a proper assessment of continuing airworthiness information received from operators and AMOs?                                                                                                                                                                                                              | 1) Review procedures.<br>2) Review evidence to confirm effective implementation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | GM<br>Doc 9760<br>Part V, 6.6                                                                                                                                                                                                                                                                                     | CE-8 | não          | SAR                        | n/a                       | GGCP-PAC<br>                 | RBAC 21.3<br>IS 00-001                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | n/a                                                |\n| 5.607  | Has the State established and implemented a system to ensure that, in respect of aeroplanes over 5700 kg and helicopters over 3175 kg maximum certificated take-off mass, information on faults, malfunctions, defects and other occurrences for aeronautical products designed in the State is received?                                                                                                                                                         | 1) Evaluate system.<br>2) Review evidence to confirm effective implementation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | STD<br>A8<br>Part II, 4.2.1.1 b) i)                                                                                                                                                                                                                                                                               | CE-8 | não          | SAR                        | n/a                       | GGCP-PAC<br>                 | RBAC 21.3<br>IS 00-002                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | n/a                                                |\n| 5.609  | Has the State developed and implemented procedures for the review of faults, malfunctions and defects information received for aeronautical products designed in the State, and has it developed the appropriate airworthiness actions required?                                                                                                                                                                                                                  | 1) Review procedures.<br>2) Limited to aeroplanes over 5700 kg or helicopters over 3175 kg maximum certificated take-off mass.<br>3) Review evidence to confirm effective implementation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | STD<br>A8<br>Part II, 4.2.1.1 b)<br>GM<br>Doc 9760<br>Part V, 6.6                                                                                                                                                                                                                                                 | CE-8 | não          | SAR                        | n/a                       | GGCP-PAC<br>                 | MPR 201                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | n/a                                                |\n| 5.611  | For aeronautical products designed in the State, does the State transmit mandatory continuing airworthiness information to States of Registry and other Contracting States on demand?                                                                                                                                                                                                                                                                             | 1) Review procedures.<br>2) Review evidence to confirm effective implementation                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | STD<br>A8<br>Part II, 4.2.1<br>GM<br>Doc 9760<br>Part V, 6.9                                                                                                                                                                                                                                                      | CE-8 | não          | SAR                        | n/a                       | GGCP-PAC<br>                 | MPR-201 items 5.2, 5.3 and 5.4 describe the procedures to transmit the Brazilian ADs.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | n/a                                                |\n| 5.621  | Has the State promulgated regulations for production approval?                                                                                                                                                                                                                                                                                                                                                                                                    | Verify regulations.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | GM<br>Doc 9760<br>Part V, 4.1.1.1                                                                                                                                                                                                                                                                                 | CE-2 | não          | SAR                        | n/a                       | GGCP-GTAI<br>GTPN<br>        | \\[1\\] - RBAC 21 Subpart G<br>\\[2\\] - RBAC 21 Subpart K<br>\\[3\\] - RBAC 21 Subpart O<br>\\[4\\] - RBAC 21.123                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | n/a                                                |\n| 5.623  | Has the State promulgated a regulation for production certificate/approval applicants to submit a manual which describes the production inspection system and quality control?                                                                                                                                                                                                                                                                                    | Verify regulations.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | GM<br>Doc 9760<br>Part V, 4.1.2.3                                                                                                                                                                                                                                                                                 | CE-2 | não          | SAR                        | n/a                       | GGCP-GTAI<br>GTPN<br>        | \\[1\\] - RBAC 21 – Subpart G<br>\\[2\\] - RBAC 21 – Subpart K<br>\\[3\\] - RBAC 21 – Subpart O                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | n/a                                                |\n| 5.627  | Has the State promulgated a regulation for all materials used in those parts of an aircraft which are essential for its safe operation to conform to approved specifications?                                                                                                                                                                                                                                                                                     | Verify regulations.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | STD<br>A8<br>Part IIIA, 4.1.2<br>Part IIIB, 4.1.3<br>Part IVA, 4.1.2<br>Part IVB, 4.1.3<br>Part V, 4.1.3                                                                                                                                                                                                          | CE-2 | não          | SAR                        | n/a                       | GGCP-GTAI<br>GTPN<br>        | \\[1\\] - RBAC 21 – Subpart G<br>\\[2\\] - RBAC 21 – Subpart K<br>\\[3\\] - RBAC 21 – Subpart O                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | n/a                                                |\n| 5.629  | Has the State promulgated a regulation for production approval holders to establish a system which ensures that only parts meeting the approved design data applicable to a particular aircraft are installed on that aircraft and are in a condition for safe operation?                                                                                                                                                                                         | Verify regulations.<br><br>Note.— In some States, the system includes a required form for each part in order for the part to be installed on an aircraft (e.g. EASA Form 1, FAA 8130-3).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | STD<br>A8<br>Part II, 2.2<br>GM<br>Doc 9760<br>Part III, 9.10.1.2<br>Part V, 4.1.3.2 b)                                                                                                                                                                                                                           | CE-2 | não          | SAR                        | n/a                       | GGCP-GTAI<br>GTPN<br>        | \\[1\\] - RBAC 21.137<br>\\[2\\] - RBAC 21.307<br>\\[3\\] - RBAC 21.607                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | n/a                                                |\n| 5.631  | Has the State established procedures for the approval of production organizations?                                                                                                                                                                                                                                                                                                                                                                                | Review procedures.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | GM<br>Doc 9760<br>Part V, 4.1.2                                                                                                                                                                                                                                                                                   | CE-5 | não          | SAR                        | n/a                       | GGCP-GTAI<br>                | \\[1\\] - MPR/SAR-121                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | n/a                                                |\n| 5.633  | Has the CAA established and implemented a mechanism to ensure that an applicant for a production certificate/approval has established and can maintain a quality system for any product or part for which he/she has requested approval?                                                                                                                                                                                                                          | \\- Review procedures for inclusion of:<br>1) An organizational chart with chain of authority/ responsibility<br>2) Design data control<br>3) Documents and data control<br>4) Conformance of supplier furnished products/parts/ materials<br>5) Manufacturing control<br>6) Conformity inspection/testing<br>7) Calibration<br>8) Status identification<br>9) Separation of non-conforming products/parts/ materials<br>10) Corrective/ preventive action<br>11) Parts storage<br>12) Retention of compliance records<br>13) Software quality assurance<br>14) Reporting to the design holder.<br><br>\\- Review evidence to confirm effective<br>implementation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | GM<br>Doc 9760<br>Part V, 4.1.2.1                                                                                                                                                                                                                                                                                 | CE-6 | não          | SAR                        | n/a                       | GGCP-GTAI<br>                | RBAC 21.137, 21.307 and 21.607<br>MPR 121 5.2<br>MPR 221 5.3<br>IS 21-006A 5.2<br>\\[1\\] Form F-300-28H System Elements<br>\\[2\\] F-300-28                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | n/a                                                |\n| 5.635  | Has the CAA established and implemented a mechanism to ensure that an applicant for a production certificate/approval establishes procedures for an independent quality assurance function including any corrective action system of ensuring compliance with the approved quality system?                                                                                                                                                                        | Verify:<br>1) procedures and effective implementation.<br>2) evidence on internal quality audits.<br>3) examples of corrective actions taken.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | GM<br>Doc 9760<br>Part V, 4.1.2.2                                                                                                                                                                                                                                                                                 | CE-6 | não          | SAR                        | n/a                       | GGCP-GTAI<br>                | \\[1\\] F-300-28<br>\\[2\\] F-300-28                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | n/a                                                |\n| 5.637  | Does the CAA issue a production limitation record which lists every product that the applicant is authorized to manufacture under the terms of the production certificate/approval?                                                                                                                                                                                                                                                                               | 1) Review limitation records to confirm effective implementation.<br>2) Check any revisions or additions which have been made.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | GM<br>Doc 9760<br>Part V, 4.1.2.5                                                                                                                                                                                                                                                                                 | CE-6 | não          | SAR                        | n/a                       | GGCP-GTAI<br>                | MPR-121<br>F-300-25                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | n/a                                                |\n| 5.639  | Has the CAA established and implemented a mechanism to ensure that the holder of a production certificate/approval determines that each part and completed product conforms to the type design and is in a condition for safe operation?                                                                                                                                                                                                                          | Review conformity inspection records to confirm effective implementation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | GM<br>Doc 9760<br>Part V, 4.1.3.2 b)                                                                                                                                                                                                                                                                              | CE-6 | não          | SAR                        | n/a                       | GGCP-GTAI<br>                | RBAC 21.145(a)(1)<br> RBAC 21.146(c)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | n/a                                                |\n| 5.640  | Has the CAA established and implemented a mechanism to ensure that all materials used in parts of the aeroplane essential for its safe operation conform to approved specifications?                                                                                                                                                                                                                                                                              | Review inspection reports to confirm effective implementation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | STD<br>A8<br>Part IIIA, 4.1.2<br>Part IIIB, 4.1.3<br>Part IVA, 4.1.2<br>Part IVB, 4.1.3<br>Part V, 4.1.3                                                                                                                                                                                                          | CE-6 | não          | SAR                        | n/a                       | GGCP-GTAI<br>                | RBAC 21.137(c)(1)<br> F-300-28                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | n/a                                                |\n| 5.641  | Has the CAA established and implemented a mechanism to ensure that production certificate/approval holders mark all products in accordance with the applicable regulations?                                                                                                                                                                                                                                                                                       | Review evidence to confirm effective implementation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | GM<br>Doc 9760<br>Part V, 4.1.3.2 c)                                                                                                                                                                                                                                                                              | CE-6 | não          | SAR                        | n/a                       | GGCP-GTAI<br>                | RBAC 21.146(d)<br>RBAC 21.316(d) and 21.616 (d)<br> F-300-28                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | n/a                                                |\n| 5.643  | Has the CAA established and implemented a mechanism to ensure that production certificate/approval holders maintain complete and current records showing that all inspections and tests to show compliance have been completed and documented?                                                                                                                                                                                                                    | Review inspection reports to confirm effective implementation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | GM<br>Doc 9760<br>Part V, 4.1.3.2 e)                                                                                                                                                                                                                                                                              | CE-6 | não          | SAR                        | n/a                       | GGCP-GTAI<br>                | RBAC 21.137(e)<br>RBAC 21.137(k)<br> F-300-28.- 3.C.4                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | n/a                                                |\n| 5.651  | Has the State promulgated regulations that allow production activity in the absence of a production certificate or production organization approval?                                                                                                                                                                                                                                                                                                              | Verify that regulations address the following:<br>1) Make each product and part available for inspection by the CAA.<br>2) Maintain all necessary technical data and drawings for conformity determination.<br>3) Establish and maintain an accepted/approved production inspection<br>system.<br>4) Submission of a manual to the CAA describing the system<br>5) Mark each product and part.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | GM<br>Doc 9760<br>Part V, 4.2.2                                                                                                                                                                                                                                                                                   | CE-2 | não          | SAR                        | n/a                       | GGCP-GTAI<br>                | RBAC 21<br>1 -> 21.123(b)<br>2 -> 21.123(a)<br>3 and 4 -> The regulation requires that the applicant obtain a Production Certificate within 6 months.<br>5 -> 21.123(e) and (f)                                                                                                                                                                                                                                                                                                                                                                                                                                                       | n/a                                                |\n| 5.653  | Has the State established procedures for production approval in the absence of a production certificate or production organization approval?                                                                                                                                                                                                                                                                                                                      | Review procedures.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | GM<br>Doc 9760<br>Part V, 4.2.2                                                                                                                                                                                                                                                                                   | CE-5 | não          | SAR                        | n/a                       | GGCP-GTAI<br>                | MPR 121 section 5.4                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | n/a                                                |\n| 5.655  | Has the CAA issued production approvals in the absence of a production certificate or production organization approval in accordance with the established regulations and procedures?                                                                                                                                                                                                                                                                             | Review evidence to confirm effective implementation of procedures.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | GM<br>Doc 9760<br>Part V, 4.2.2                                                                                                                                                                                                                                                                                   | CE-6 | não          | SAR                        | n/a                       | GGCP-GTAI<br>                | Subpart F RBAC 21                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | n/a                                                |\n| 5.657  | Has the State established and implemented a mechanism to ensure that the holder of a type certificate who produces a product without a production certificate establishes a CAA accepted/approved production inspection system?                                                                                                                                                                                                                                   | Review procedures and examples to confirm effective implementation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | GM<br>Doc 9760<br>Part V, 4.2.1 & 4.2.2 c)                                                                                                                                                                                                                                                                        | CE-6 | não          | SAR                        | n/a                       | GGCP-GTAI<br>                | In the past, ANAC used to require a production inspection system. However, that is not required anymore as we understand that the only alternative is holding a production certificate. As a transition, the current Subpart F reliefs a short-period of time (six months) for the applicant while manufacturing the first products (aircraft, engine or propellers), based only in the type certificate.                                                                                                                                                                                                                             | n/a                                                |\n| 5.659  | Upon the establishment of an accepted/approved production inspection system, does the State ensure that the manufacturer of a product or part fabricated under a type certificate only submits a manual to the CAA which describes the system and the materials review board quality control procedures?                                                                                                                                                          | Review procedures and examples to confirm effective implementation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | GM<br>Doc 9760<br>Part V, 4.2.2 d)                                                                                                                                                                                                                                                                                | CE-6 | não          | SAR                        | n/a                       | GGCP-GTAI<br>                | In the past, ANAC used to require a production inspection system. However, that is not required anymore as we understand that the only alternative is holding a production certificate. As a transition, the current Subpart F reliefs a short-period of time (six months) for the applicant while manufacturing the first products (aircraft, engine or propellers), based only in the type certificate.                                                                                                                                                                                                                             | n/a                                                |\n| 5.661  | Has the State established and implemented a mechanism to ensure that the manufacturer of a product or part fabricated under a type certificate only marks each product and part in accordance with the applicable regulations?                                                                                                                                                                                                                                    | Review<br>a) procedures<br>and,<br>b) examples to confirm effective implementation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | GM<br>Doc 9760<br>Part V, 4.2.2 e)                                                                                                                                                                                                                                                                                | CE-6 | não          | SAR                        | n/a                       | GGCP-GTAI<br>                | RBAC 21.123 (e)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | n/a                                                |\n| 5.663  | Has the State established and implemented a mechanism to ensure that each manufacturer of an aircraft under a type certificate only establishes a CAA-approved production flight test procedure and flight tests are carried out in accordance with that procedure?                                                                                                                                                                                               | 1) Review procedures to ensure inclusion of the following:<br>a) Operational check of the trim, controllability or other characteristics to establish that production aircraft has same range and control as prototype<br> b) Operational check of each part of the system operated by the crew while in flight<br> c) Instruments properly marked, placards installed and flight manuals available<br> d) Ground operational test<br> e) Check on any items peculiar to the aircraft which can be done on ground or in flight.<br>2) Review evidence to confirm effective implementation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | GM<br>Doc 9760<br>Part V, 4.2.4                                                                                                                                                                                                                                                                                   | CE-6 | não          | SAR                        | n/a                       | GGCP-GTAI<br>                | RBAC 21.127<br>Production Flight Test Procedure approval                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | n/a                                                |\n| 5.667  | Has the State established and implemented a mechanism to ensure that each aircraft engine manufactured under a type certificate only is subjected to an acceptable test run?                                                                                                                                                                                                                                                                                      | 1) Review procedures to confirm the following tests are required:<br>a) Break-in runs which include a determination of fuel and oil consumption and a determination of power characteristics at<br>rated maximum continuous power or thrust and, if applicable, at rated take-off power or thrust<br> b) Five hours of operation at rated maximum continuous power or thrust<br>2) Review evidence to confirm effective<br>implementation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | GM<br>Doc 9760<br>Part V, 4.2.5                                                                                                                                                                                                                                                                                   | CE-6 | não          | SAR                        | n/a                       | GGCP-GTAI<br>                | RBAC 21.128                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | n/a                                                |\n| 5.669  | Has the State established and implemented a mechanism to ensure that each variable pitch propeller manufactured under a type certificate only is given an acceptable functional test to determine that it operates properly throughout the normal range of operation?                                                                                                                                                                                             | 1) Review procedures.<br>2) Review evidence to confirm effective implementation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | GM<br>Doc 9760<br>Part V, 4.2.6                                                                                                                                                                                                                                                                                   | CE-6 | não          | SAR                        | n/a                       | GGCP-GTAI<br>                | 21.129                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | n/a                                                |\n| 5.671  | Has the State established and implemented a mechanism to ensure that each holder of a type certificate or holder of an authorization to a type certificate who produces a product in the absence of a production certificate/approval provides a statement of conformity, as required by the CAA?                                                                                                                                                                 | Review examples to verify that the statement is provided:<br>1) At the time of initial transfer of ownership of such product, provided an airworthiness approval has not been issued.<br>2) At the time of application for the original issuance of an aircraft certificate of airworthiness or an aircraft engine or propeller airworthiness approval tag.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | GM<br>Doc 9760<br>Part V, 4.2.7                                                                                                                                                                                                                                                                                   | CE-6 | não          | SAR                        | n/a                       | GGCP-GTAI<br>                | 21130<br>Form-100-06                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | n/a                                                |\n| 5.673  | Has the State established and implemented a mechanism to ensure that the statement of conformity includes all relevant information and is signed by an authorized person who holds a responsible position in the manufacturing organization?                                                                                                                                                                                                                      | Review examples to verify inclusion of:<br>1) For each product, a statement that the product conforms to its type certificate and is in a condition for safe operation.<br>2) For each aircraft, a statement that the aircraft has been flight checked.<br>3) For each aircraft engine or variable pitch propeller, a statement that the engine or propeller has been subjected by the manufacturer to a final operational check.<br>4) Signature of the responsible person.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | GM<br>Doc 9760<br>Part V, 4.2.7                                                                                                                                                                                                                                                                                   | CE-6 | não          | SAR                        | n/a                       | GGCP-GTAI<br>                | MPR-121<br>MPR-221<br>F-300-28                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | n/a                                                |\n| 5.681  | Has the AED developed a formal surveillance policy/procedure to be used by airworthiness engineers/inspectors for conducting surveillance activities for all production organizations?                                                                                                                                                                                                                                                                            | Review policy/procedure and check for inclusion of:<br>1) Guidelines for scheduling inspections/audits.<br>2) Standardized checklists for production facility inspections.<br>3) Inspection/audit process.<br>4) Inspections of approved and non-approved organizations.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | STD<br>A19<br>App. 1, 5.1 & 7<br>GM<br>Doc 9734<br>Part A, C3                                                                                                                                                                                                                                                     | CE-5 | não          | SAR                        | n/a                       | GGCP-GTAI<br>                | MPR 221<br>F-300-28<br>F-300-30<br>ITD-121-01                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | n/a                                                |\n| 5.683  | Does the AED establish a formal surveillance programme for the continuing supervision of all production organizations?                                                                                                                                                                                                                                                                                                                                            | 1) Review surveillance programme for current and previous year.<br>2) Verify inclusion of random checks on all aspects of approved/non-approved production organizations.<br>3) Confirm appropriate frequency of inspection/audit.<br>4) For foreign production organization surveillance:<br> a) Review reports from local authority.<br> b) Confirm that approval is based on locally issued certificate.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | STD<br>A19<br>App. 1, 7<br>GM<br>Doc 9734<br>Part A, C3                                                                                                                                                                                                                                                           | CE-7 | não          | SAR                        | n/a                       | GGCP-GTAI<br>                | PLANO DE TRABALHO ANUAL                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | n/a                                                |\n| 5.685  | Has the State established means to take actions if deficiencies identified during the surveillance activities of a production organization are not rectified in a reasonable time?                                                                                                                                                                                                                                                                                | 1) Review the means established.<br>2) Review examples of actions taken.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | STD<br>A19<br>App. 1, 8<br>GM<br>Doc 9734<br>Part A, C3                                                                                                                                                                                                                                                           | CE-8 | não          | SAR                        | n/a                       | GGCP-GTAI<br>                | MPR-121                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | n/a                                                |"
      }
    },
    {
      "_id": "elem-XxlwNwVV",
      "attributes": {
        "label": "21. Obter validação de grande modificação ao projeto de tipo de produto aeronáutico estrangeiro",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-XxsW4Qt9",
      "attributes": {
        "label": "4. Gerência Técnica de Processo Normativo (GTPN)",
        "element type": "Organization",
        "description": "---\n### 4. Gerência Técnica de Processo Normativo (GTPN)\n> Gerente: [[Marco Aurelio Bonilauri Santin]]\n\nCompetências:\n\n* Coordenação, condução e suporte ao desenvolvimento de normativos\n* Coordenação, condução e suporte a atividades de articulação com outras entidades, nacionais ou estrangeiras, com vistas ao estabelecimento de acordos, ao intercâmbio de informações, à internalização de informações e ao desenvolvimento de normativos\n* Coordenação e suporte ao desenvolvimento de interpretações de requisitos\n* Gerenciamento do banco de dados com as interpretações e os meios alternativos de demonstração de cumprimento de requisito\n* Suporte à definição da base de certificação e atividades correlatas\n* Coordenação e suporte à elaboração de respostas a demandas especiais",
        "rdf:type": "org:OrganizationUnit",
        "skos:preflabel": "GTPN"
      }
    },
    {
      "_id": "elem-Y6SGHnW4",
      "attributes": {
        "label": "Caixa de ferramentas",
        "description": "* [Estrutura de dados do Kumu (.PDF em inglês)](https://docs.kumu.io/content/kumu-data-structure-guide.pdf)\n\n## Ferramentas\n\n[[list/tools]]\n\n## Ajudas do Kumu\n\n* [Help direto do mapa](https://kumu.io/kumu/help)\n* [DOCs para detalhamento dos recursos](https://docs.kumu.io/)\n* [Comunidade](https://kumu.io/community)\n* [Galeria](https://kumu.io/gallery)\n* [Chat no Slack](http://chat.kumu.io/)\n\n## Exemplos úteis em formato aberto\n* [Mapa com imagem de cadeia de valor no fundo](https://kumu.io/bemosior/wardley-map-example). Decoração das conexões muda a depender das tags empregadas.",
        "element type": "#Tools"
      }
    },
    {
      "_id": "elem-Y6unIuTv",
      "attributes": {
        "label": "8. Reestruturação da Gestão do Conhecimento na SAR",
        "element type": "Project",
        "rdf:type": "foaf:Project"
      }
    },
    {
      "_id": "elem-YC71w0d7",
      "attributes": {
        "label": "10. Estruturação de uma metodologia para a elaboração do PDP no âmbito da SAR",
        "rdf:type": "foaf:Project",
        "element type": "Project"
      }
    },
    {
      "_id": "elem-YpWe5tEQ",
      "attributes": {
        "label": "Julia Lopes da Cunha",
        "tags": [
          "Comunicação"
        ],
        "description": "Julia conhece das trocas de informações na SAR.\n\n- Comunicação interna\n- Comunicação externa\n- Ciência política",
        "rdf:type": "foaf:Person",
        "element type": "Person"
      }
    },
    {
      "_id": "elem-YritCr4H",
      "attributes": {
        "label": "FDH/CHOPP - Programas de certificação/Programas de certificação",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-ZQiPCpLP",
      "attributes": {
        "label": "13. Otimização do Processo de Emissão de DA",
        "rdf:type": "foaf:Project",
        "element type": "Project"
      }
    },
    {
      "_id": "elem-ZhV3q4CO",
      "attributes": {
        "label": "URLs",
        "element type": "#Tools",
        "description": "Fonte: https://docs.kumu.io/guides/urls.html\n\n# URLs\n\nOs URLs Kumu seguem um padrão previsível: todo URL começa https://kumu.io e termina com uma das opções descritas na tabela abaixo. Ao visitar os links da Kumu ou enviá-los para seus amigos, colegas e colaboradores, esta tabela ajudará você a saber exatamente ao que está vinculando.\n\nAntes de mergulhar: se você não tem certeza do que queremos dizer _slug_ (apelido) na tabela abaixo, confira nosso [guia completo sobre _slugs_](https://docs.kumu.io/guides/slugs.html)."
      }
    },
    {
      "_id": "elem-ZnZiSGA2",
      "attributes": {
        "label": "3. Matricular aeronave ou reativar matrícula cancelada",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-a7gvoxnd",
      "attributes": {
        "label": "Navegação",
        "description": "## Dicas de navegação no grafo\n\n    Scroll \npara aumentar e diminuir o zoom\n\n    Clique e arraste \n\nmover-se\n\n    Pressione \\ \n\npara ajustar o zoom ao mapa\n\n    Pressione tab \n\npara ocultar / mostrar esta barra lateral\n\n    Clique nos elementos \n\npara ver informações detalhadas\n\n    Click em um elemento e pressione 1 \n\npara focar em suas conexões\n\n     Pare o cursor sobre os elementos \n\npara mostrar suas conexões\n\n    Pressione S\n\npara ativar a barra de pesquisa",
        "element type": "#Tools"
      }
    },
    {
      "_id": "elem-a8nbgACt",
      "attributes": {
        "label": "4. Obter aprovação de Grande Modificação desenvolvida pelo detentor do Certificado de Tipo de Produto Aeronáutico",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-aLutnlXO",
      "attributes": {
        "label": "FDH/CHOPP/Manuais de voo",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-aYPUViHg",
      "attributes": {
        "label": "7. Obter autorização excepcional para execução de serviços específicos em artigos aéreos",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-aeSDFFAb",
      "attributes": {
        "label": "2.1. Gerência de Engenharia de Manutenção (GAEM)",
        "description": "---\n### 2.1. Gerência de Engenharia de Manutenção (GAEM)\n\n> Gerente: [[Eduardo Américo Campos Filho]]\n\nCompetências:\n\n* Gestão dos recursos humanos necessários para a execução das atividades da Gerência-Geral de Aeronavegabilidade Continuada, pelas Gerências Técnicas de Aeronavegabilidade\n* Padronização da execução das atividades administrativas da Gerência-Geral, pelas Gerências Técnicas de Aeronavegabilidade, incluindo auditorias periódicas.",
        "element type": "Organization",
        "rdf:type": "org:OrganizationUnit",
        "skos:preflabel": "GAEM"
      }
    },
    {
      "_id": "elem-bafwKNr0",
      "attributes": {
        "label": "5. Consistência em Processos de Certificação de Tipo Nacionais",
        "rdf:type": "foaf:Project",
        "element type": "Project"
      }
    },
    {
      "_id": "elem-bbHaXkZZ",
      "attributes": {
        "label": "Oficinas mecânicas/FDH e CHOPP - Oficinas mecânicas",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-bvEeYakG",
      "attributes": {
        "label": "2.1.1. Gerência Técnica de Aeronavegabilidade de São Paulo (GTAR/SP)",
        "description": "---\n### 2.1.1. Gerência Técnica de Aeronavegabilidade de São Paulo (GTAR/SP)\n\n> Gerente: [[Fabiano dos Santos Nascimento Silva]]\n\nCompetências da GTAR/SP, RJ e SF\n\n* Execução de inspeção, de vistoria, de auditoria ou de atividade necessária para certificação e vigilância continuada, nas áreas de competência da Gerência-Geral de Aeronavegabilidade Continuada\n* Avaliação e aprovação ou aceitação de documentos e processos relacionados às atividades de manutenção das empresas aéreas, organizações de manutenção aeronáutica, aviação geral e aeronaves civis\n* Realização de exame prático visando à habilitação de mecânico de manutenção aeronáutica e execução de atividades relacionadas com o credenciamento de examinadores de mecânico de manutenção\n* Orientação, supervisão e monitoramento de pessoas credenciadas, em sua área de atuação.",
        "rdf:type": "org:OrganizationUnit",
        "skos:preflabel": "GTAR/SP",
        "element type": "Organization"
      }
    },
    {
      "_id": "elem-c3hiHkuy",
      "attributes": {
        "label": "GIASO SAR/Gerenciamento Inspeções de Aeronavegabilidade e Segurança Operacional 2011-2016",
        "description": "Gerenciamento de Inspeções de Aeronavegabilidade e Segurança Operacional relativos ao periodo 2011-2016 na SAR.",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-cjPNFKb9",
      "attributes": {
        "label": "11. Obter Certificado de Aeronavegabilidade Especial para Aeronave Leve Esportiva",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-csEJCAzO",
      "attributes": {
        "label": "Marcos Simplício Sousa da Silva",
        "element type": "Person",
        "tags": [
          "Serviços aéreos",
          "Credenciamento de pessoas",
          "Processo normativo",
          "Fiscalização de serviços aéreos",
          "Sistema de Gerenciamento de Segurança Operacional"
        ],
        "description": "Servidor efetivo da [[GTGC]]\n\nFormado na área de Gestão Pública\n\nExperiência profissional na ANAC: Fiscalização de serviços aéreos, normatização, gestão de equipes, SGSO",
        "status": "Bad",
        "rdf:type": "foaf:Person"
      }
    },
    {
      "_id": "elem-cvHHqpb8",
      "attributes": {
        "label": "6. Melhoria no Procedimento de Solução de Conflito Técnico",
        "rdf:type": "foaf:Project",
        "element type": "Project"
      }
    },
    {
      "_id": "elem-d3782YjR",
      "attributes": {
        "label": "3. Matricular aeronave ou reativar matrícula cancelada",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-dQDCJJjb",
      "attributes": {
        "label": "1. Gerência-Geral de Certificação de Produto Aeronáutico (GGCP)",
        "description": "---\n### 1. Gerência-Geral de Certificação de Produto Aeronáutico (GGCP)\n> Gerente: [[Mário Igawa]]\n\nCompetências:\n\n* Emitir, suspender e extinguir certificado de tipo, certificado suplementar de tipo, certificado de organização de produção e certificado de produto aeronáutico aprovado, incluindo as respectivas especificações técnicas e suas revisões, como aplicável\n* Emitir, suspender e extinguir certificado de autorização de voo experimental\n* Emitir, suspender e extinguir autorização especial de voo, com os propósitos de entrega ou exportação de aeronave a seu comprador, voo de produção, voo de demonstração para comprador, e voo com peso superior ao peso máximo de decolagem aprovado\n* Emitir, suspender ou extinguir aprovação de aeronavegabilidade para exportação\n* Emitir, suspender e extinguir outros atestados, aprovações e autorizações relativas às atividades em seu âmbito de atuação\n* Conceder meio alternativo de demonstração de cumprimento a requisito em sua área de atuação.",
        "element type": "Organization",
        "rdf:type": "org:OrganizationUnit"
      }
    },
    {
      "_id": "elem-dh3mmDFo",
      "attributes": {
        "label": "URLs",
        "description": "Fonte: https://docs.kumu.io/guides/urls.html\n\n# URLs\n\nOs URLs Kumu seguem um padrão previsível: todo URL começa https://kumu.io e termina com uma das opções descritas na tabela abaixo. Ao visitar os links da Kumu ou enviá-los para seus amigos, colegas e colaboradores, esta tabela ajudará você a saber exatamente ao que está vinculando.\n\nAntes de mergulhar: se você não tem certeza do que queremos dizer _slug_ (apelido) na tabela abaixo, confira nosso [guia completo sobre _slugs_](https://docs.kumu.io/guides/slugs.html).",
        "element type": "#Tools"
      }
    },
    {
      "_id": "elem-dyFWToGr",
      "attributes": {
        "label": "Luciana Ferreira da Silva",
        "element type": "Person",
        "rdf:type": "foaf:Person"
      }
    },
    {
      "_id": "elem-e5RBhB0F",
      "attributes": {
        "label": "Maria Clara Costa Teixeira",
        "rdf:type": "foaf:Person",
        "element type": "Person"
      }
    },
    {
      "_id": "elem-e6ATGOnG",
      "attributes": {
        "label": "19. Obter um Certificado de Organização da Produção (COP) com Registro de Limitação da Produção (RLP)",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-eKpmJoVx",
      "attributes": {
        "label": "SCPRAB/Processos administrativos relacionados a aeronaves",
        "description": "Sistema Consulta Processual do RAB\nRelaciona todos todos os processos administrativos que têm relação com a aeronave.",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-emjr8UjF",
      "attributes": {
        "label": "César Rodrigues Hess",
        "rdf:type": "foaf:Person",
        "element type": "Person"
      }
    },
    {
      "_id": "elem-evZPlgKh",
      "attributes": {
        "label": "Produtos/FDH e CHOPP - Produtos",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-ey7iasyA",
      "attributes": {
        "label": "Marcos Vinicios de Lima",
        "element type": "Person",
        "tags": [
          "Gestão do conhecimento",
          "Capacitação",
          "Gerenciamento de CAS"
        ],
        "status": "Bad"
      }
    },
    {
      "_id": "elem-fFKK44Fz",
      "attributes": {
        "label": "José Helder da Silva Lima",
        "rdf:type": "foaf:Person",
        "element type": "Person"
      }
    },
    {
      "_id": "elem-fN82bTAj",
      "attributes": {
        "label": "FDH/CHOPP/Aeronaves experimentais",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-fQblgMfp",
      "attributes": {
        "label": "24. Realizar Emenda a Certificado de Organização de Manutenção de Produto Aeronáutico ou às suas Especificações Operativas",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-fW10qseS",
      "attributes": {
        "label": "14. Obter Certificado Suplementar de Tipo de Produto Aeronáutico",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-fa52lVzx",
      "attributes": {
        "label": "9. Obter certificação de organização de manutenção de produto aeronáutico doméstica",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-g49f2rZT",
      "attributes": {
        "label": "1.1. Gerência de Programas de Certificação (GCPR)",
        "description": "---\n### 1.1. Gerência de Programas de Certificação (GCPR)\n> Gerente: [[César Rodrigues Hess]]\n\nCompetências:\n\n* Coordenação dos processos de certificação de projeto de produto aeronáutico\n* Coordenação dos processos de certificação de modificação de projeto de produto aeronáutico\n* Processamento de dificuldades em serviço e eventual proposição de diretriz de aeronavegabilidade\n* Orientação, supervisão e monitoramento de pessoas credenciadas, em sua área de atuação",
        "rdf:type": "org:OrganizationUnit",
        "element type": "Organization"
      }
    },
    {
      "_id": "elem-gTDzZUsx",
      "attributes": {
        "label": "José Helder da Silva Lima",
        "element type": "Person",
        "rdf:type": "foaf:Person"
      }
    },
    {
      "_id": "elem-gpQjwSd2",
      "attributes": {
        "label": "25. Requerer novo certificado de matrícula (transferência de operação ou operação)",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-gufE82ji",
      "attributes": {
        "label": "13. Obter Certificado de Tipo",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-h5u2XdIw",
      "attributes": {
        "label": "26. Solicitar cancelamento de matrícula de aeronaves",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-hAi8r1Zd",
      "attributes": {
        "label": "5. Obter Atestado de Produto Aeronáutico Aprovado",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-hL8UIzdT",
      "attributes": {
        "label": "SAR",
        "description": "---\n## SAR\nDivisão das competências da Superintendência de Aeronavegabilidade",
        "element type": "Organization",
        "rdf:type": "org:OrganizationUnit",
        "skos:preflabel": "SAR"
      }
    },
    {
      "_id": "elem-hXHnqTPi",
      "attributes": {
        "label": "Atalhos",
        "description": "## Geral\n\n`W` Wizard\n`S` Search\n`T` Settings\n`]` Zoom In\n`[` Zoom Out\n`\\` Zoom Fit\n`DBLCLICK` Quick Zoom\n`UP/DOWN/LEFT/RIGHT` Pan\n`SPACE` Pause\n`TAB` Toggle Sidebar\n`Z` Reset View\n\n## Edição\n\n`E` New Element\n`C` New Connection\n`L` New Loop\n`K` Sketch Mode\n`R` Rename Selection\n`DELETE` Delete Selection\n`ALT+CLICK` New Element\n`ALT+DRAG` New Connection\n\n## Seleção\n\n`A` Select All\n`SHIFT+E` Select Elements\n`SHIFT+C` Select Connections\n`SHIFT+L` Select Loops\n`SHIFT+CLICK` Toggle Selection\n\n## Atalhos avançados\n\n### Elementos\n\n`P` Pin\n`ALT+P` Unpin\n\n### Conexões\n\n`U` Undirected\n`D` Directed\n`M` Mutual\n`ALT+D` Reverse\n\n### Estilos\n\n`Q` Toggle Quality\n`ALT+S` View Source\n`.` Edit source\n\n### Layout\n\n`B` Bump\n`O` Remove Overlap\n`ALT+O` Remove Overlap (Labels Only)\n\n### Foco\n\n`0-9` Set Focus\n`+` Expand Focus\n`-` Contract Focus\n`'` Clear Focus\n`CLICK+HOLD (MAP)` Clear Focus\n`CLICK+HOLD (TARGET)` Extend Focus\n`SHIFT+CLICK+HOLD (TARGET)` Shift Focus",
        "element type": "#Tools"
      }
    },
    {
      "_id": "elem-hd7KwvJa",
      "attributes": {
        "label": "2.1.1. Gerência Técnica de Aeronavegabilidade de São Paulo (GTAR/SP)",
        "element type": "Organization",
        "description": "---\n### 2.1.1. Gerência Técnica de Aeronavegabilidade de São Paulo (GTAR/SP)\n\n> Gerente: [[Fabiano dos Santos Nascimento Silva]]\n\nCompetências da GTAR/SP, RJ e SF\n\n* Execução de inspeção, de vistoria, de auditoria ou de atividade necessária para certificação e vigilância continuada, nas áreas de competência da Gerência-Geral de Aeronavegabilidade Continuada\n* Avaliação e aprovação ou aceitação de documentos e processos relacionados às atividades de manutenção das empresas aéreas, organizações de manutenção aeronáutica, aviação geral e aeronaves civis\n* Realização de exame prático visando à habilitação de mecânico de manutenção aeronáutica e execução de atividades relacionadas com o credenciamento de examinadores de mecânico de manutenção\n* Orientação, supervisão e monitoramento de pessoas credenciadas, em sua área de atuação.",
        "rdf:type": "org:OrganizationUnit",
        "skos:preflabel": "GTAR/SP"
      }
    },
    {
      "_id": "elem-hvAMgTcx",
      "attributes": {
        "label": "10. Estruturação de uma metodologia para a elaboração do PDP no âmbito da SAR",
        "element type": "Project",
        "rdf:type": "foaf:Project"
      }
    },
    {
      "_id": "elem-i09rfuc0",
      "attributes": {
        "label": "Produtos/FDH e CHOPP - Produtos",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-i9yLniMW",
      "attributes": {
        "label": "01. Auditorias de Supervisão Remotas na SAR",
        "element type": "Project",
        "rdf:type": "foaf:Project",
        "description": "SEI nº 00058.018244/2020-35 (Projeto setorial)\nSEI nº [00058.034120/2020-05](https://sei.anac.gov.br/sei/modulos/pesquisa/md_pesq_processo_exibir.php?iI3OtHvPArITY997V09rhsSkbDKbaYSycOHqqF2xsM0IaDkkEyJpus7kCPb435VNEAb16AAxmJKUdrsNWVIqQ6MPmvkM2XpDeTTGOM4Ylp-M6h8ZEkyW96XmIqStCSBm) (Setorial)",
        "skos:preflabel": "Auditorias de Supervisão Remotas na SAR",
        "vigente": "Não"
      }
    },
    {
      "_id": "elem-iEAT3dfC",
      "attributes": {
        "label": "FDH/CHOPP/Organizações de produção",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-iYhI7mvO",
      "attributes": {
        "label": "12. Gestão da criação, armazenamento e acesso a informações sobre objetivos dos normativos de aeronavegabilidade",
        "description": "1ª Reunião em 13/08/2020\n\n* Link para [equipe no Teams](https://teams.microsoft.com/l/team/19%3a182be3bff5ab4995ad968d696b912118%40thread.tacv2/conversations?groupId=f524cac2-cc3d-4deb-aa87-6a4c478f5be5&tenantId=b5748f6e-b4a4-4b2b-ab2a-ef9522368366)\n* Pasta de [arquivos no Teams](https://teams.microsoft.com/_#/files/Geral?threadId=19%3A182be3bff5ab4995ad968d696b912118%40thread.tacv2&ctx=channel&context=General&rootfolder=%252Fsites%252F12.Gestodacriaoarmazenamentoeacessoainformaessobreobjetivosd%252FDocumentos%2520Compartilhados%252FGeneral)\n* Link para [quadro do MIRO](https://miro.com/app/board/o9J_kiiAdTo=/)\n\nProcesso SEI 00058.029038/2020-51",
        "rdf:type": "foaf:Project",
        "element type": "Project"
      }
    },
    {
      "_id": "elem-j3iH1u91",
      "attributes": {
        "label": "FDH/CHOPP/Organizações de projetos",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-jC0fCSlM",
      "attributes": {
        "label": "EAEV",
        "description": "automatizar a solicitação e emissão de autorizações de especiais de voo que constam no MPR-100  capítulo 10 feita por empresas aéreas e de manutenção com o objetivo de transladar ou efetuar voos de teste em aeronaves com certificado de aeronavegabilidade inválida.",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-jdBVsEHD",
      "attributes": {
        "label": "Conhecimentos",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-jfr0MYNC",
      "attributes": {
        "label": "6. Melhoria no Procedimento de Solução de Conflito Técnico",
        "element type": "Project",
        "rdf:type": "foaf:Project"
      }
    },
    {
      "_id": "elem-jnVApgiA",
      "attributes": {
        "label": "Vinícius Costa e Silva",
        "rdf:type": "foaf:Person",
        "element type": "Person"
      }
    },
    {
      "_id": "elem-k9SAU96c",
      "attributes": {
        "label": "RBAC145/Organizações de Manutenção",
        "description": "Relaciona-se com as empresas de manutenção, onde as empresas poderão manter atualizados seus dados cadastrais, encaminhar relatórios previstos em regulamento ou outros dados de interesse da ANAC e das empresas, como: relação de serviços mensais e relatórios trimestral de pessoal, informações solicitadas pela ANAC.",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-kKG2T7iZ",
      "attributes": {
        "label": "Edson Souza de Jesus Filho",
        "element type": "Person",
        "rdf:type": "foaf:Person"
      }
    },
    {
      "_id": "elem-kUzFD2PE",
      "attributes": {
        "label": "27. Transferir propriedade de aeronave ou  motor de Pessoa Física para Pessoa Física",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-kWpEJuo6",
      "attributes": {
        "label": "11. Mapeamento de Riscos dos Processos Organizacionais da SAR",
        "element type": "Project",
        "rdf:type": "foaf:Project"
      }
    },
    {
      "_id": "elem-kdAeMhGE",
      "attributes": {
        "label": "6. Gerência Técnica de Planejamento e Acompanhamento (GTPA)",
        "description": "---\n### 6. Gerência Técnica de Planejamento e Acompanhamento (GTPA)\n> Gerente: [[Lawrence Josuá Fernandes Costa]]\n\nPara assuntos de julgamento de primeira instância, contatar o Setor Julgamento em Primeira Instância – JPI\nE-mail: [julgamentoAI.SAR@anac.gov.br](mailto:julgamentoAI.SAR@anac.gov.br )\n\nCompetências:\n\n* Desenvolvimento e coordenação de atividades de planejamento\n* Acompanhamento e supervisão, junto às demais unidades da Superintendência, do cumprimento do planejamento e dos planos de trabalho estabelecidos\n* Atuação como Área Local de Gestão de Processos - ALGP da SAR, no que diz respeito ao mapeamento de processos e suporte à aprovação de manual de procedimentos\n* Assessoramento, análise e guarda dos processos administrativos instaurados por autos de infração visando emissão de decisões de primeira instância, relativos à área de competência da Superintendência.",
        "element type": "Organization",
        "vigente": "Não",
        "data de fim": "2020-10-15",
        "data de início": "06/14/2016",
        "rdf:type": "org:OrganizationUnit",
        "skos:preflabel": "GTPA"
      }
    },
    {
      "_id": "elem-keAtppy9",
      "attributes": {
        "label": "FDH/CHOPP/Organizações de produção",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-keYGEajb",
      "attributes": {
        "label": "Fabiano dos Santos Nascimento Silva",
        "element type": "Person",
        "rdf:type": "foaf:Person"
      }
    },
    {
      "_id": "elem-kqSsR04J",
      "attributes": {
        "label": "FDH/CHOPP/Processo normativo",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-ksJb8tp6",
      "attributes": {
        "label": "Hélio Tarquínio Júnior",
        "element type": "Person",
        "rdf:type": "foaf:Person"
      }
    },
    {
      "_id": "elem-l7fWLJeq",
      "attributes": {
        "label": "CRP_AERONAVE",
        "description": "Base integrada de aeronaves (replicada)",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-lFwQJzZn",
      "attributes": {
        "label": "2.1.2. Gerência Técnica de Aeronavegabilidade do Rio de Janeiro (GTAR/RJ)",
        "description": "---\n### 2.1.2. Gerência Técnica de Aeronavegabilidade do Rio de Janeiro (GTAR/RJ)\n> Gerente: [[José Helder da Silva Lima]]\n\nCompetências da GTAR/SP, RJ e SF\n\n* Execução de inspeção, de vistoria, de auditoria ou de atividade necessária para certificação e vigilância continuada, nas áreas de competência da Gerência-Geral de Aeronavegabilidade Continuada\n* Avaliação e aprovação ou aceitação de documentos e processos relacionados às atividades de manutenção das empresas aéreas, organizações de manutenção aeronáutica, aviação geral e aeronaves civis\n* Realização de exame prático visando à habilitação de mecânico de manutenção aeronáutica e execução de atividades relacionadas com o credenciamento de examinadores de mecânico de manutenção\n* Orientação, supervisão e monitoramento de pessoas credenciadas, em sua área de atuação.",
        "rdf:type": "org:OrganizationUnit",
        "skos:altlabel": "GTAR/RJ",
        "skos:preflabel": "Gerência Técnica de Aeronavegabilidade do Rio de Janeiro",
        "element type": "Organization"
      }
    },
    {
      "_id": "elem-lZiEbhkl",
      "attributes": {
        "label": "LIVRO RAB/LIVRO RAB",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-laEOHDO0",
      "attributes": {
        "label": "César Rodrigues Hess",
        "element type": "Person",
        "rdf:type": "foaf:Person"
      }
    },
    {
      "_id": "elem-lkV2bB9g",
      "attributes": {
        "label": "Hélio Tarquínio Júnior",
        "rdf:type": "foaf:Person",
        "element type": "Person"
      }
    },
    {
      "_id": "elem-loWR3RDA",
      "attributes": {
        "label": "Mateus Frois Santa Catarina",
        "element type": "Person",
        "rdf:type": "foaf:Person"
      }
    },
    {
      "_id": "elem-m23FtD0F",
      "attributes": {
        "label": "9. Proposta de revisão do processo de credenciamento de pessoas na SAR",
        "element type": "Project",
        "rdf:type": "foaf:Project"
      }
    },
    {
      "_id": "elem-m9EpSJna",
      "attributes": {
        "label": "Oficinas mecânicas/FDH e CHOPP - Oficinas mecânicas",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-mDk2xrAI",
      "attributes": {
        "label": "27. Transferir propriedade de aeronave ou  motor de Pessoa Física para Pessoa Física",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-mKStIRyJ",
      "attributes": {
        "label": "16. Obter mudança de categoria de registro de aeronave",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-mR8qttAO",
      "attributes": {
        "label": "12. Gestão da criação, armazenamento e acesso a informações sobre objetivos dos normativos de aeronavegabilidade",
        "element type": "Project",
        "description": "1ª Reunião em 13/08/2020\n\n* Link para [equipe no Teams](https://teams.microsoft.com/l/team/19%3a182be3bff5ab4995ad968d696b912118%40thread.tacv2/conversations?groupId=f524cac2-cc3d-4deb-aa87-6a4c478f5be5&tenantId=b5748f6e-b4a4-4b2b-ab2a-ef9522368366)\n* Pasta de [arquivos no Teams](https://teams.microsoft.com/_#/files/Geral?threadId=19%3A182be3bff5ab4995ad968d696b912118%40thread.tacv2&ctx=channel&context=General&rootfolder=%252Fsites%252F12.Gestodacriaoarmazenamentoeacessoainformaessobreobjetivosd%252FDocumentos%2520Compartilhados%252FGeneral)\n* Link para [quadro do MIRO](https://miro.com/app/board/o9J_kiiAdTo=/)\n\nProcesso SEI 00058.029038/2020-51",
        "rdf:type": "foaf:Project"
      }
    },
    {
      "_id": "elem-mRwfcbJi",
      "attributes": {
        "label": "29. Validar projeto aeronáutico certificado no exterior",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-mWJ1Pkpb",
      "attributes": {
        "label": "Julio Giampa Scheibel",
        "element type": "Person",
        "rdf:type": "foaf:Person"
      }
    },
    {
      "_id": "elem-mZ3klnYJ",
      "attributes": {
        "label": "EDIAM/Declaração de Inspeção Anual de Manutenção Eletrônica",
        "description": "Declaração de Inspeção Anual de Manutenção Eletrônica de Aeronaves é prevista no RBAC 91, recentemente a IAM foi substítuida pelo CVA e portal EDIAM está em processo de migração para o portal ECVA - Certificado de Verificação de Aeronavegabilidade Eletrônico.",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-mbRVYUFg",
      "attributes": {
        "label": "ERIAM",
        "description": "Declaração de Inspeção Anual de Manutenção Eletrônica  das Aeronaves Experimentais",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-mgNODmRi",
      "attributes": {
        "label": "Intranet SAR",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-n1SBsgQe",
      "attributes": {
        "label": "5. Consistência em Processos de Certificação de Tipo Nacionais",
        "element type": "Project",
        "rdf:type": "foaf:Project"
      }
    },
    {
      "_id": "elem-nBtdBtH9",
      "attributes": {
        "label": "1.3. Gerência Técnica de Auditoria e Inspeção (GTAI)",
        "element type": "Organization",
        "description": "---\n### 1.3. Gerência Técnica de Auditoria e Inspeção (GTAI)\n> Gerente: [[Pedro Henrique Leite Paludo]]\n\nCompetências:\n\n* Certificação e vigilância continuada de organizações de produção\n* Dentro do processo de certificação de produto aeronáutico, inspeção necessária à verificação da conformidade de produto, de processo, de espécime de ensaio e de instalação associada\n* Certificação de aeronavegabilidade associada com as atividades inerentes à certificação de produto aeronáutico e aviação experimental\n* Inspeção para emissão de certificado de exportação de produto aeronáutico, incluindo aeronave usada\n* Orientação, supervisão e monitoramento de pessoas credenciadas, em sua área de atuação.",
        "rdf:type": "org:OrganizationUnit"
      }
    },
    {
      "_id": "elem-nCZFRVWM",
      "attributes": {
        "label": "18. Obter um Certificado de Marca Experimental",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-nCuVepBy",
      "attributes": {
        "label": "RBAC145/Organizações de Manutenção",
        "description": "Relaciona-se com as empresas de manutenção, onde as empresas poderão manter atualizados seus dados cadastrais, encaminhar relatórios previstos em regulamento ou outros dados de interesse da ANAC e das empresas, como: relação de serviços mensais e relatórios trimestral de pessoal, informações solicitadas pela ANAC.",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-nPorGk79",
      "attributes": {
        "label": "8. Obter Certidão de Propriedade e Ônus Reais",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-nYGiscwS",
      "attributes": {
        "label": "7. Obter autorização excepcional para execução de serviços específicos em artigos aéreos",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-np1RA9Ep",
      "attributes": {
        "label": "Caixa de ferramentas",
        "element type": "#Tools",
        "description": "* [Estrutura de dados do Kumu (.PDF em inglês)](https://docs.kumu.io/content/kumu-data-structure-guide.pdf)\n\n## Ferramentas\n\n[[list/tools]]\n\n## Ajudas do Kumu\n\n* [Help direto do mapa](https://kumu.io/kumu/help)\n* [DOCs para detalhamento dos recursos](https://docs.kumu.io/)\n* [Comunidade](https://kumu.io/community)\n* [Galeria](https://kumu.io/gallery)\n* [Chat no Slack](http://chat.kumu.io/)\n\n## Exemplos úteis em formato aberto\n* [Mapa com imagem de cadeia de valor no fundo](https://kumu.io/bemosior/wardley-map-example). Decoração das conexões muda a depender das tags empregadas."
      }
    },
    {
      "_id": "elem-nyozFAzh",
      "attributes": {
        "label": "Atalhos",
        "element type": "#Tools",
        "description": "## Geral\n\n`W` Wizard\n`S` Search\n`T` Settings\n`]` Zoom In\n`[` Zoom Out\n`\\` Zoom Fit\n`DBLCLICK` Quick Zoom\n`UP/DOWN/LEFT/RIGHT` Pan\n`SPACE` Pause\n`TAB` Toggle Sidebar\n`Z` Reset View\n\n## Edição\n\n`E` New Element\n`C` New Connection\n`L` New Loop\n`K` Sketch Mode\n`R` Rename Selection\n`DELETE` Delete Selection\n`ALT+CLICK` New Element\n`ALT+DRAG` New Connection\n\n## Seleção\n\n`A` Select All\n`SHIFT+E` Select Elements\n`SHIFT+C` Select Connections\n`SHIFT+L` Select Loops\n`SHIFT+CLICK` Toggle Selection\n\n## Atalhos avançados\n\n### Elementos\n\n`P` Pin\n`ALT+P` Unpin\n\n### Conexões\n\n`U` Undirected\n`D` Directed\n`M` Mutual\n`ALT+D` Reverse\n\n### Estilos\n\n`Q` Toggle Quality\n`ALT+S` View Source\n`.` Edit source\n\n### Layout\n\n`B` Bump\n`O` Remove Overlap\n`ALT+O` Remove Overlap (Labels Only)\n\n### Foco\n\n`0-9` Set Focus\n`+` Expand Focus\n`-` Contract Focus\n`'` Clear Focus\n`CLICK+HOLD (MAP)` Clear Focus\n`CLICK+HOLD (TARGET)` Extend Focus\n`SHIFT+CLICK+HOLD (TARGET)` Shift Focus"
      }
    },
    {
      "_id": "elem-o9s9vMAT",
      "attributes": {
        "label": "Planilha SIGA/Planilha SIGA",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-oHHwZdJE",
      "attributes": {
        "label": "2.1.2. Gerência Técnica de Aeronavegabilidade do Rio de Janeiro (GTAR/RJ)",
        "element type": "Organization",
        "description": "---\n### 2.1.2. Gerência Técnica de Aeronavegabilidade do Rio de Janeiro (GTAR/RJ)\n> Gerente: [[José Helder da Silva Lima]]\n\nCompetências da GTAR/SP, RJ e SF\n\n* Execução de inspeção, de vistoria, de auditoria ou de atividade necessária para certificação e vigilância continuada, nas áreas de competência da Gerência-Geral de Aeronavegabilidade Continuada\n* Avaliação e aprovação ou aceitação de documentos e processos relacionados às atividades de manutenção das empresas aéreas, organizações de manutenção aeronáutica, aviação geral e aeronaves civis\n* Realização de exame prático visando à habilitação de mecânico de manutenção aeronáutica e execução de atividades relacionadas com o credenciamento de examinadores de mecânico de manutenção\n* Orientação, supervisão e monitoramento de pessoas credenciadas, em sua área de atuação.",
        "rdf:type": "org:OrganizationUnit",
        "skos:preflabel": "Gerência Técnica de Aeronavegabilidade do Rio de Janeiro",
        "skos:altlabel": "GTAR/RJ"
      }
    },
    {
      "_id": "elem-oRLOTIJa",
      "attributes": {
        "label": "1.2. Gerência de Engenharia de Produto (GCEN)",
        "description": "---\n### 1.2. Gerência de Engenharia de Produto (GCEN)\n> Gerente: [[Nelson Eisaku Nagamine]]\n\nCompetências:\n\n* Certificação de projeto de produto aeronáutico, provendo parecer especializado nas áreas de aeronáutica, desempenho em voo e qualidade de voo resistência estrutural em aeronaves sistemas de aeronaves (hidráulicos, pneumáticos, eletroeletrônicos, software embarcado, integração inter-sistemas, etc)\n* propulsão de aeronaves\n* fator humano relacionado a projeto de aeronave\n* proteção do ocupante da aeronave\n* proteção ambiental (ruído e emissões)\n* outros aspectos técnicos considerados essenciais à segurança de voo\n* Orientação, supervisão e monitoramento de pessoas credenciadas, em sua área de atuação.",
        "rdf:type": "org:OrganizationUnit",
        "element type": "Organization"
      }
    },
    {
      "_id": "elem-ojVaLCXk",
      "attributes": {
        "label": "GIASO SAR/Gerenciamento Inspeções de Aeronavegabilidade e Segurança Operacional 2011-2016",
        "description": "Gerenciamento de Inspeções de Aeronavegabilidade e Segurança Operacional relativos ao periodo 2011-2016 na SAR.",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-pIRrgXCZ",
      "attributes": {
        "label": "RDS - Report de dificuldade em serviço",
        "description": "Registro de Dificuldade em Serviço de Operações de Aeronaves",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-pxgcYHz7",
      "attributes": {
        "label": "14. RAB Digital",
        "rdf:type": "foaf:Project",
        "element type": "Project"
      }
    },
    {
      "_id": "elem-q4XKDmhG",
      "attributes": {
        "label": "17. Obter Parecer Técnico sobre requisitos de Aeronavegabilidade",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-qccUlS7W",
      "attributes": {
        "label": "1.1. Gerência de Programas de Certificação (GCPR)",
        "element type": "Organization",
        "description": "---\n### 1.1. Gerência de Programas de Certificação (GCPR)\n> Gerente: [[César Rodrigues Hess]]\n\nCompetências:\n\n* Coordenação dos processos de certificação de projeto de produto aeronáutico\n* Coordenação dos processos de certificação de modificação de projeto de produto aeronáutico\n* Processamento de dificuldades em serviço e eventual proposição de diretriz de aeronavegabilidade\n* Orientação, supervisão e monitoramento de pessoas credenciadas, em sua área de atuação",
        "rdf:type": "org:OrganizationUnit"
      }
    },
    {
      "_id": "elem-qisM3mN9",
      "attributes": {
        "label": "Seletores e Operadores para filtros",
        "element type": "#Tools",
        "description": "## Seletores\n\nFonte: \n- https://docs.kumu.io/guides/selector-reference.html\n- https://docs.kumu.io/guides/selectors.html\n\n**Seletor**"
      }
    },
    {
      "_id": "elem-qufplmV4",
      "attributes": {
        "label": "ERIAM",
        "description": "Declaração de Inspeção Anual de Manutenção Eletrônica  das Aeronaves Experimentais",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-rWbwMW4S",
      "attributes": {
        "label": "25. Requerer novo certificado de matrícula (transferência de operação ou operação)",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-rYk8NW0E",
      "attributes": {
        "label": "6. Gerência Técnica de Planejamento (GTPL)",
        "element type": "Organization",
        "fonte da informação": "DOU",
        "fonte da informação-url": "https://www.in.gov.br/en/web/dou/-/resolucao-n-581-de-21-de-agosto-de-2020-273916813",
        "description": "---\n### 6. Gerência Técnica de Planejamento\n> Gerente: [[Mariana de Sousa Rosa Vieira]]\n\nCompetências da GTPL\n\nI - Propor e acompanhar o planejamento financeiro da SAR.\nII - Propor ao Superintendente de Aeronavegabilidade a metodologia de acompanhamento de metas institucionais e demais indicadores que suportem o alcance dos objetivos da SAR.\nIII - Estabelecer a metodologia e aplicabilidade da gestão de riscos dos processos.\nIV - Monitorar a execução do processo de manifestação de usuários.\nV - Estabelecer a política de capacitação e desenvolvimento dos colaboradores da SAR, em consonância com o disposto pela Superintendência de Gestão de Pessoas.\nVI - Promover a melhoria contínua dos processos de trabalho da SAR.\nVII - Estabelecer e aprimorar metodologia para desenvolvimento de sistemas atrelados a melhorias de processos.\nVIII - Estabelecer e aprimorar continuamente a metodologia de gerenciamento dos projetos setoriais.\nIX - Estabelecer e aprimorar continuamente a metodologia para o planejamento e gestão do orçamento da SAR.\n\nFonte: [Portaria de Organização Interna (POI) nº 3.881, de 29 de dezembro de 2020](https://www.anac.gov.br/assuntos/legislacao/legislacao-1/boletim-de-pessoal/2020/53/bps-no-53-de-31-de-dezembro-de-2020.pdf)",
        "data de início": "10/16/2020",
        "vigente": "Sim",
        "rdf:type": "org:OrganizationUnit",
        "skos:preflabel": "GTPL"
      }
    },
    {
      "_id": "elem-ra8DPlXE",
      "attributes": {
        "label": "2. Credenciar-se como Profissional de Aeronavegabilidade, Fabricação ou Projeto",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-rpa2AjHT",
      "attributes": {
        "label": "Marcos Simplício Sousa da Silva",
        "tags": [
          "Serviços aéreos",
          "Credenciamento de pessoas",
          "Processo normativo",
          "Fiscalização de serviços aéreos",
          "Sistema de Gerenciamento de Segurança Operacional"
        ],
        "description": "Servidor efetivo da [[GTGC]]\n\nFormado na área de Gestão Pública\n\nExperiência profissional na ANAC: Fiscalização de serviços aéreos, normatização, gestão de equipes, SGSO",
        "status": "Bad",
        "rdf:type": "foaf:Person",
        "element type": "Person"
      }
    },
    {
      "_id": "elem-rqjCuxq4",
      "attributes": {
        "label": "SAR",
        "description": "---\n## SAR\nDivisão das competências da Superintendência de Aeronavegabilidade",
        "rdf:type": "org:OrganizationUnit",
        "skos:preflabel": "SAR",
        "element type": "Organization"
      }
    },
    {
      "_id": "elem-sCwzoC2k",
      "attributes": {
        "label": "ANAC",
        "description": "# National Civil Aviation Agency (ANAC), Brazil.\n\n[Acesse na íntegra a Portaria de Organização Interna](https://www.anac.gov.br/assuntos/legislacao/legislacao-1/boletim-de-pessoal/2017/19/bps-no-19-de-12-de-maio-de-2017.pdf)\n\nFonte: https://www.anac.gov.br/acesso-a-informacao/institucional/gerencias e demais documentos abertos publicados nos canais oficiais do órgão.\n\n## Selecionar grupo de elementos\n\n* [Pessoas](=[\"element type\"=\"Person\"]) - azul claro\n* [Estrutura Organizacional](=[\"element type\"=\"Organization\"]) - azul escuro\n* [Serviços](=[\"element type\"=\"Service\"]) - verde claro\n* [Projetos](=[\"element type\"=\"Project\"]) - verde escuro\n* [Bases de dados](=[\"element type\"=\"Database\"]) - rosa\n* [Caixa de ferramentas](=[\"element type\"=\"#Tools\"]) - vermelho\n\n## Lista de elementos em exibição no grafo (padrão = todos)\n\n### Pessoas (_Person_)\n[[list/person]]\n\n### Estrutura Organizacional (_Organization_)\n[[list/organization]]\n\n### Serviços (_Service_)\n[[list/service]]\n\n### Projetos (_Project_)\n[[list/project]]\n\n### Bases de dados (_Database_)\n[[list/database]]\n\n## XML do Governo Federal\n* https://estruturaorganizacional.dados.gov.br/id/unidade-organizacional/86144\nThis XML file does not appear to have any style information associated with it. The document tree is shown below.\n\n~~~xml\n<resultadoConsultarUnidadeResumida>\n<servico>\n<codigoErro>0</codigoErro>\n<data>2020-08-12</data>\n<ipRequisitante>xxx.xxx.xxx.xxx</ipRequisitante>\n<mensagem>Processamento sem erros</mensagem>\n<versaoServico>3.7.1</versaoServico>\n</servico>\n<unidade>\n<codigoEsfera>https://estruturaorganizacional.dados.gov.br/id/esfera/federal</codigoEsfera>\n<codigoNaturezaJuridica>https://estruturaorganizacional.dados.gov.br/id/natureza-juridica/autarquia</codigoNaturezaJuridica>\n<codigoOrgaoEntidade>https://estruturaorganizacional.dados.gov.br/id/unidade-organizacional/86144</codigoOrgaoEntidade>\n<codigoPoder>https://estruturaorganizacional.dados.gov.br/id/poder/executivo</codigoPoder>\n<codigoSubNaturezaJuridica>https://estruturaorganizacional.dados.gov.br/id/subnatureza-juridica/autarquia-especial---agencia-reguladora</codigoSubNaturezaJuridica>\n<codigoTipoUnidade>https://estruturaorganizacional.dados.gov.br/id/tipo-unidade/entidade</codigoTipoUnidade>\n<codigoUnidade>https://estruturaorganizacional.dados.gov.br/id/unidade-organizacional/86144</codigoUnidade>\n<codigoUnidadePai>https://estruturaorganizacional.dados.gov.br/id/unidade-organizacional/2846</codigoUnidadePai>\n<dataInicialVersaoConsulta>2020-08-06</dataInicialVersaoConsulta>\n<nivelNormatizacao>LEI_DECRETO</nivelNormatizacao>\n<nome>Agência Nacional de Aviação Civil</nome>\n<sigla>ANAC</sigla>\n<versaoConsulta>110.4.0</versaoConsulta>\n</unidade>\n</resultadoConsultarUnidadeResumida>\n~~~",
        "element type": "Organization",
        "uorg-xml": "https://estruturaorganizacional.dados.gov.br/id/unidade-organizacional/86144",
        "rdf:type": "org:Organization",
        "skos:preflabel": "Agência Nacional de Aviação Civil",
        "skos:altlabel": "ANAC"
      }
    },
    {
      "_id": "elem-sL0ruk0S",
      "attributes": {
        "label": "Rosemberg Andre da Silva",
        "rdf:type": "foaf:Person",
        "element type": "Person"
      }
    },
    {
      "_id": "elem-sSTwIqdZ",
      "attributes": {
        "label": "15. Obter Emenda a um Certificado Suplementar de Tipo (CST) de Produto Aeronáutico",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-sWlXTUfp",
      "attributes": {
        "label": "4. Obter aprovação de Grande Modificação desenvolvida pelo detentor do Certificado de Tipo de Produto Aeronáutico",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-uDrbG8RU",
      "attributes": {
        "label": "Julia Lopes da Cunha",
        "element type": "Person",
        "description": "Julia conhece das trocas de informações na SAR.\n\n- Comunicação interna\n- Comunicação externa\n- Ciência política",
        "tags": [
          "Comunicação"
        ],
        "rdf:type": "foaf:Person"
      }
    },
    {
      "_id": "elem-uYgK4BzN",
      "attributes": {
        "label": "Antonio José Parente",
        "element type": "Person",
        "rdf:type": "foaf:Person"
      }
    },
    {
      "_id": "elem-uqZERg0z",
      "attributes": {
        "label": "3. Gerência Técnica do Registro Aeronáutico Brasileiro (GTRAB)",
        "description": "---\n### 3. Gerência Técnica do Registro Aeronáutico Brasileiro (GTRAB)\n> Gerente: [[Luciana Ferreira da Silva]]\n\nCompetências:\n\n* Administrar o Registro Aeronáutico Brasileiro\n* Emitir, suspender ou extinguir certificado de matrícula\n* Emitir, suspender ou extinguir certificado de aeronavegabilidade\n* Conceder meio alternativo de demonstração de cumprimento a requisito em sua área de atuação.",
        "rdf:type": "org:OrganizationUnit",
        "skos:preflabel": "GTRAB",
        "element type": "Organization"
      }
    },
    {
      "_id": "elem-uvmDTU4U",
      "attributes": {
        "label": "15. Revisão das Resoluções nº 293/2013 e 309/2014",
        "rdf:type": "foaf:Project",
        "element type": "Project"
      }
    },
    {
      "_id": "elem-uyQIPOTL",
      "attributes": {
        "label": "FDH/CHOPP/Aeronaves experimentais",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-v4Uoyw2M",
      "attributes": {
        "label": "22. Obter validação de nível de segurança de produto aeronáutico",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-vQcCIzgx",
      "attributes": {
        "label": "AERONAVE/RRAB",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-w9fW4R9P",
      "attributes": {
        "label": "HST/Certificação suplementar de tipo",
        "description": "Dados de projeto de aprovação de grandes modificações e grandes alterações em produto aeronáutico.Controle de processos de certificação suplementar de tipo",
        "status": "Bad",
        "element type": "Database"
      }
    },
    {
      "_id": "elem-wHHcWjQp",
      "attributes": {
        "label": "14. Obter Certificado Suplementar de Tipo de Produto Aeronáutico",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-wl1Iwyg2",
      "attributes": {
        "label": "02. Supervisão de PCA utilizando avaliação de risco",
        "element type": "Project",
        "rdf:type": "foaf:Project",
        "description": "SEI nº 00058.028167/2020-21 (Projeto Setorial)\nSEI nº 00058.034119/2020-72 (GTPL)",
        "skos:preflabel": "Supervisão de PCA utilizando avaliação de risco"
      }
    },
    {
      "_id": "elem-xXU62P7E",
      "attributes": {
        "label": "4. Propostas de melhorias ao processo de conformidade",
        "rdf:type": "foaf:Project",
        "element type": "Project"
      }
    },
    {
      "_id": "elem-xeR2isJR",
      "attributes": {
        "label": "SKOS",
        "element type": "#Tools",
        "description": "## SKOS Vocabulary Organized by Theme"
      }
    },
    {
      "_id": "elem-xppS3zAl",
      "attributes": {
        "label": "9. Proposta de revisão do processo de credenciamento de pessoas na SAR",
        "rdf:type": "foaf:Project",
        "element type": "Project"
      }
    },
    {
      "_id": "elem-xytzsrnJ",
      "attributes": {
        "label": "10. Obter certificado de aeronavegabilidade",
        "element type": "Service"
      }
    },
    {
      "_id": "elem-y5J5tL7r",
      "attributes": {
        "label": "2.1.3. Gerência Técnica de Aeronavegabilidade de Brasília (GTAR/DF)",
        "description": "---\n### 2.1.3. Gerência Técnica de Aeronavegabilidade de Brasília (GTAR/DF)\n> Gerente: Paulo Sérgio Degrazia Dellamora\n\nCompetências da GTAR/SP, RJ e SF\n\n* Execução de inspeção, de vistoria, de auditoria ou de atividade necessária para certificação e vigilância continuada, nas áreas de competência da Gerência-Geral de Aeronavegabilidade Continuada\n* Avaliação e aprovação ou aceitação de documentos e processos relacionados às atividades de manutenção das empresas aéreas, organizações de manutenção aeronáutica, aviação geral e aeronaves civis\n* Realização de exame prático visando à habilitação de mecânico de manutenção aeronáutica e execução de atividades relacionadas com o credenciamento de examinadores de mecânico de manutenção\n* Orientação, supervisão e monitoramento de pessoas credenciadas, em sua área de atuação.",
        "rdf:type": "org:OrganizationUnit",
        "skos:preflabel": "GTAR/DF",
        "element type": "Organization"
      }
    },
    {
      "_id": "elem-zTPJncM0",
      "attributes": {
        "label": "Eduardo Américo Campos Filho",
        "rdf:type": "foaf:Person",
        "element type": "Person"
      }
    },
    {
      "_id": "elem-vofRtzCV",
      "attributes": {
        "label": "CE/SC nº 25-032",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável à Instalação do Enhanced Flight Vision System (EFVS). / Special Condition for the Installation of the Enhanced Flight Vision System (EFVS).",
        "data de início": 42489,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-032@@download/arquivo_norma/CE SC 25-032.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-vntO1mF5",
      "attributes": {
        "label": "CE/SC nº 25-033",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável a Assentos Orientados Lateralmente com a Incorporação de Sistemas de Airbag. / Special Condition for Side Facing Seats with Airbag Systems.",
        "data de início": 42552,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-033@@download/arquivo_norma/CE SC 25-033.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-BUaZ85mQ",
      "attributes": {
        "label": "CE/SC nº 25-034",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável ao Synthetic Vision System (SVS) e ao Enhanced Flight Vision System (EFVS) no Head Up Display (HUD). / Special Condition for the Synthetic Vision System (SVS) and Enhanced Flight Vision System (EFVS) on Head Up Display (HUD).",
        "data de início": 42552,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-034@@download/arquivo_norma/CE SC 25-034.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-MLSu13jB",
      "attributes": {
        "label": "CE/SC nº 25-035",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável ao Uso do Sistema ATTCS para Arremetida. / Special Condition for Using ATTCS System in Go-Around.",
        "data de início": 42608,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-035@@download/arquivo_norma/CE SC 25-035.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-nck3L53d",
      "attributes": {
        "label": "CE/SC nº 25-036",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial aplicável à recuperação de manobra por um sistema automático de voo com uma instalação de um sistema protetor de alta velocidade incorporado nas leis de controle de voo. / Special Condition for Maneuver Recovery by an Automatic Flight System with a High Speed Protection System Incorporated in Flight Control Laws.",
        "data de início": 42622,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-036@@download/arquivo_norma/CE SC 25-036.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-XeGBWQ6H",
      "attributes": {
        "label": "CE/SC nº 25-037",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial aplicável às cargas de torque limite durante parada súbita de motor e APU. / Special Condition for Sudden APU and Engine Stoppage.",
        "data de início": 42622,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-037@@download/arquivo_norma/CE SC 25-037.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-JvtqpsdV",
      "attributes": {
        "label": "CE/SC nº 25-038",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial aplicável ao sistema de geração e distribuição de energia elétrica. / Special Condition for Electrical Power Generation and Distribution System.",
        "data de início": 42622,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-25-038@@download/arquivo_norma/CE SC 25-038.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-NgBjqslr",
      "attributes": {
        "label": "CE/SC n° 25-039",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável ao Uso de Grandes Painéis não Tradicionais e não Metálicos Integrados à Estrutura dos Assentos de Passageiros. / Special Condition for Use of Non-Traditional, Large, Non-Metallic Panels Assembled to Seat Passenger Structures.",
        "data de início": 42636,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-ndeg-25-039@@download/arquivo_norma/CE SC 25-039 - Retificado.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-YsDaXx8G",
      "attributes": {
        "label": "CE/SC n° 25-040",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável à Proteção dos Sistemas Eletrônicos contra Acessos Externos não Autorizados. / Special Condition for Electronic Systems Protection from Unauthorized External Access.",
        "data de início": 42633,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-ndeg-25-040@@download/arquivo_norma/CE SC 25-040.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-0OdzbT3w",
      "attributes": {
        "label": "CE/SC n° 25-041",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável à Proteção dos Sistemas Eletrônicos contra Acessos Internos não Autorizados. / Special Condition for Electronic Systems Protection from Unauthorized Internal Access.",
        "data de início": 42633,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-25-041@@download/arquivo_norma/CE SC 25-041.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-0APO44sz",
      "attributes": {
        "label": "CE/SC nº 25-042",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável à Detecção de Fumaça nos Compartimentos Eletroeletrônicos e às Proteções contra Penetração de Fumaça Oriunda desses Compartimentos. / Special Condition for Electrical/Electronic Equipment Bay Fire Detection and Smoke Penetration.",
        "data de início": 42664,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-042@@download/arquivo_norma/CE SC 25-042.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-qeNC1p81",
      "attributes": {
        "label": "CE/SC nº 25-043",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável ao Sistema de Controle Eletrônico de Voo com Relação ao Efeito das Proteções de Arfagem, de Rolamento e de Alta Velocidade Sobre a Controlabilidade e Manobrabilidade da Aeronave.\nSpecial Condition for Flight Envelope Protection: Pitch, Roll and High Speed Limiting Functions.",
        "data de início": 42769,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-043@@download/arquivo_norma/CE SC 25-043.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-rf2VHs64",
      "attributes": {
        "label": "CE/SC nº 25-044",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável às Manobras de Rolamento. \n/ Special Condition for Rolling Maneuvering.",
        "data de início": 42776,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-044@@download/arquivo_norma/CE SC 25-044.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-G8PWHyHY",
      "attributes": {
        "label": "CE/SC nº 25-045",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável à Interação de Sistemas e Estruturas. / Special Condition for Interaction of Systems and Structures.",
        "data de início": 42776,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-045@@download/arquivo_norma/CE SC 25-045.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-9yAh7wMz",
      "attributes": {
        "label": "CE/SC nº 25-046",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável à Proteção de Envelope de Voo para Limitação do Fator de Carga Normal Excessivo. / Special Condition for Flight Envelope Protection: Normal Load Factor (g) Limiting Function.",
        "data de início": 42776,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-046@@download/arquivo_norma/CE SC 25-046.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-gz1cCKeo",
      "attributes": {
        "label": "CE/SC nº 23-011",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável à Instalação de Sistema de Retenção do Assento do Piloto com Sistema Inflável (Airbag) Incorporado em sua Porção Superior (Arnês de Ombro). / Special Condition for Inflatable Restraint Safety Belt with an Integrated Airbag Device.",
        "data de início": 42731,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-23-011@@download/arquivo_norma/CE SC 23-011.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-4LBhyb8a",
      "attributes": {
        "label": "CE/SC nº 25-047",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável ao Controle para Seleção do Reversor de Empuxo. / Special Condition for Reverse Thrust Setting Below the Flight Regime.",
        "data de início": 42811,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-047@@download/arquivo_norma/Anexo I - CE SC 25-047.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-KMiEfBdA",
      "attributes": {
        "label": "CE/SC nº 25-048",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável a Requisitos de Fatores Humanos. / Special Condition for Human Factors Requirements.",
        "data de início": 42832,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-048@@download/arquivo_norma/CE-SC-25-048.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-YCxLKEB7",
      "attributes": {
        "label": "CE/SC nº 25-049",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável a Requisitos Gerais de Limitação da Proteção de Envelope de Voo. / Special Condition for General Limiting Requirements of the Flight Envelope Protection.",
        "data de início": 42849,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-049@@download/arquivo_norma/CE SC 25-049.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-IvFnasOV",
      "attributes": {
        "label": "CE/SC nº 25-050",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável à Condição de Aterrissagem com Carregamento de Arfagem. / Special Condition for Landing Pitchover Condition.",
        "data de início": 42849,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-050@@download/arquivo_norma/CE SC 25-050.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-TQswRT9l",
      "attributes": {
        "label": "CE/SC nº 25-051",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável ao EFCS: Estabilidade Látero-Direcional e Longitudinal e Alerta de Baixa Energia. / Special Condition for EFCS: Lateral-Directional and Longitudinal Stability and Low Energy Awareness.",
        "data de início": 42849,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-051@@download/arquivo_norma/CE SC 25-051.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-KxSZsybb",
      "attributes": {
        "label": "CE/SC nº 25-052",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável à Proteção da Estrutura do Tanque de Combustível Contra Raios. / Special Condition for Lightning Protection of Fuel Tank Structure.",
        "data de início": 42860,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-052@@download/arquivo_norma/CE SC 25-052.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-DJBUQrAL",
      "attributes": {
        "label": "CE/SC nº 25-053",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável às Forças Limite Aplicadas pelo Piloto ao Manche Lateral. /\nSpecial Condition for the Limit Pilot Force for Side Stick Controls.",
        "data de início": 42799,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-053@@download/arquivo_norma/CE SC 25-053.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-sb1s8NU6",
      "attributes": {
        "label": "CE/SC nº 25-012",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável ao Uso do Sistema ATTCS para Arremetida / Special Condition for Using ATTCS System in Go-Around",
        "data de início": 41542,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-012@@download/arquivo_norma/CE SC 25-012.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-dzFSZiTb",
      "attributes": {
        "label": "CE/SC nº 25-009",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável à Película Hidrofóbica a Ser Utilizada no Lugar de Limpadores de Para-Brisas / Special Condition for the Hydrophobic Coatings to Be Used in Lieu of Windshield Wipers",
        "data de início": 41542,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-009@@download/arquivo_norma/CE SC 25-009.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-OUmiQWyo",
      "attributes": {
        "label": "CE/SC nº 25-010",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável à Notificação da Posição das Superfícies de Controle / Special Condition for Control Surface Position Awareness",
        "data de início": 41542,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-010@@download/arquivo_norma/CE SC 25-010.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-k7O8BIA3",
      "attributes": {
        "label": "CE/SC nº 25-011",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável aos Múltiplos Modos de Operação do Sistema de Controle de Voo  / Special Condition for the Flight Control System Multiple Modes of Operation",
        "data de início": 41542,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-011@@download/arquivo_norma/CE SC 25-011.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-Ckt3VXav",
      "attributes": {
        "label": "CE/SC nº 25-054",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável ao Sistema de Geração e Distribuição de Energia Elétrica./ Special Condition for Electrical Power Generation and Distribution System.",
        "data de início": 42874,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-054@@download/arquivo_norma/CE SC 25-054.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-ut9IWFFq",
      "attributes": {
        "label": "CE/SC nº 25-055",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável ao Sistema de Ejeção de Bote Salva-Vidas./ Special Condition for Life Raft Deployment System.",
        "data de início": 42874,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-055@@download/arquivo_norma/CE SC 25-055.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-uXorKi89",
      "attributes": {
        "label": "CE/SC nº 25-056",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável aos Manches Laterais Ativos. /Special Condition for Active Sidestick Inceptors.",
        "data de início": 42888,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-056@@download/arquivo_norma/CE SC 25-056.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-SYsEU9T2",
      "attributes": {
        "label": "CE/SC nº 25-057",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável à Proteção de Envelope de Voo em Alto Ângulo de Ataque. /Special Condition for Flight Envelope Protection of High Angle of Attack.",
        "data de início": 42888,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-057@@download/arquivo_norma/CE SC 25-057.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-UQwvMEi5",
      "attributes": {
        "label": "CE/SC nº 25-058",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável a Baterias não Recarregáveis de Íons de Lítio. /Special Condition for Non-Rechargeable Lithium-Ion Batteries",
        "data de início": 42958,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-058@@download/arquivo_norma/CE SC 25-058.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-onge0Ohq",
      "attributes": {
        "label": "CE/SC nº 25-059",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável à Proteção de Envelope de Voo para Limitação do Fator de Carga Normal Excessivo. /Special Condition for Flight Envelope Protection: Normal Load Factor (g) Limiting Function.",
        "data de início": 42958,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-059@@download/arquivo_norma/CE SC 25-059.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-0RP4wFjV",
      "attributes": {
        "label": "CE/SC nº 25-060",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável a Requisitos de Manobras de Rolamento para Projeto de Sistemas de Comandos Eletrônicos. /Special Condition for Design Roll Maneuver Requirement for Electronic Flight Controls.",
        "data de início": 42958,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-060@@download/arquivo_norma/CE SC 25-060.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-0FCqtjCN",
      "attributes": {
        "label": "CE/SC nº 25-061",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável à Proteção de Envelope de Voo em Alto Ângulo de Ataque. /Special Condition for Flight Envelope Protection of High Angle of Attack.",
        "data de início": 42958,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-061@@download/arquivo_norma/CE SC 25-061.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-r9He7DhI",
      "attributes": {
        "label": "CE/SC nº 25-062",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável a Baterias e Sistemas de Baterias Recarregáveis de Íons de Lítio. /Special Condition for Rechargeable Lithium-Ion Batteries and Battery Systems.",
        "data de início": 42746,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-062@@download/arquivo_norma/CE SC 25-062.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-SXvIBmJF",
      "attributes": {
        "label": "CE/SC nº 25-063",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável à Detecção de Fumaça nos Compartimentos Eletroeletrônicos e às Proteções contra Penetração de Fumaça Oriunda desses Compartimentos. /Special Condition for Electrical/Electronic Equipment Bay Fire Detection and Smoke Penetration.",
        "data de início": 42958,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-063@@download/arquivo_norma/CE SC 25-063.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-n9YqlCVF",
      "attributes": {
        "label": "CE/SC nº 25-064",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável à Proteção de Envelope de Voo para Limite de Arfagem, Rolamento e Alta Velocidade./ Special Condition for Pitch, Roll and High Speed Limiting Flight Envelope Protection.",
        "data de início": 42972,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-064@@download/arquivo_norma/CE SC 25-064.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-2pHCaVrh",
      "attributes": {
        "label": "CE/SC nº 25-065",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável à Recuperação de Manobra por um Sistema Automático de Voo com uma Instalação de um Sistema Protetor de Alta Velocidade Incorporado nas Leis de Controle de Voo./ Special Condition for Maneuver Recovery by an Automatic Flight System with a High Speed Protection System Incorporated in Flight Control Laws.",
        "data de início": 42972,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-065@@download/arquivo_norma/CE SC 25-065.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-2oKp6Ojz",
      "attributes": {
        "label": "CE/SC nº 25-066",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável aos Múltiplos Modos de Operação do Sistema de Controle de Voo, à Operação em Qualquer Atitude e à Notificação da Tripulação Acerca da Posição das Superfícies de Controle./ Special Condition for Electronic Flight Control System: Control Surface Position Awareness, Multiple Modes of Operation, Flight Control in All Attitudes.",
        "data de início": 43000,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-066@@download/arquivo_norma/CE SC 25-066.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-ltblWhIH",
      "attributes": {
        "label": "CE/SC nº 25-067",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável à Definição de Uma Condição de Aterrissagem com Carregamento de Arfagem que Considere os Efeitos do Sistema de Frenagem Automático./ Special Condition for the Definition of a Landing Pitchover Condition which Takes into Account the Effect of the Autobrake System.",
        "data de início": 43028,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-067@@download/arquivo_norma/CE SC-025-067.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-xzdSVrs2",
      "attributes": {
        "label": "CE/SC nº 23-012",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável ao Sistema de Controle Eletrônico do Motor. / Special Condition for Eletronic Engine Control System.",
        "data de início": 43805,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-23-012@@download/arquivo_norma/CE SC 23-012.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-fznPCJpW",
      "attributes": {
        "label": "CE/SC nº 23-013",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável ao Sistema de Tração Automática (Auto Throttle). / Special Condition for Auto Throttle System.",
        "data de início": 43788,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-23-013@@download/arquivo_norma/CE SC 23-013.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-yAHSV6Ky",
      "attributes": {
        "label": "CE/SC nº 23-002",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável às Características de Voo e Limitações Operacionais. / Special Condition for Flight Characteristics and Operating Limitations.",
        "data de início": 40148,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-23-002@@download/arquivo_norma/CE SC 23-002.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-8VLmbIMN",
      "attributes": {
        "label": "CE/SC nº 23-003",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável ao Sistema Automático de Reserva de Potência. / Special Condition for Automatic Thrust Reserve System.",
        "data de início": 40148,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-23-003@@download/arquivo_norma/CE SC 23-003.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-gMpq4CrR",
      "attributes": {
        "label": "CE/SC nº 23-005",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável aos Equipamentos e Suprimento de Oxigênio. / Special Condition for Oxygen Equipment and Supply.",
        "data de início": 40148,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-23-005@@download/arquivo_norma/CE SC 23-005.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-woDbUE7S",
      "attributes": {
        "label": "CE/SC nº 23-006",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável à Integridade do Vaso de Pressão e ao Sistema de Pressurização. / Special Condition for Pressure Vessel Integrity and Pressurization System.",
        "data de início": 40148,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-23-006@@download/arquivo_norma/CE SC 23-006.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-2uOQol3b",
      "attributes": {
        "label": "CE/SC nº 23-007",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável ao Sistema Automático de Proteção Contra gelo. / Special Condition for Ice Protection Automatic System.",
        "data de início": 40148,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-23-007@@download/arquivo_norma/CE SC 23-007.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-y1NUZPo6",
      "attributes": {
        "label": "CE/SC nº 23-009",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável ao Assento Orientado Transversalmente, Para um Único Ocupante / Special Condition for Single-Place Side-Facing Seat",
        "data de início": 40794,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-23-009@@download/arquivo_norma/CE SC 23-009.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-M1OsrEVD",
      "attributes": {
        "label": "CE/SC nº 23-010",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição especial aplicável ao sistema de bolsa de ar (airbag) instalado em cintos de segurança de ombro em assentos de múltipla ocupação orientados transversalmente.",
        "data de início": 41022,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-23-010@@download/arquivo_norma/CE23-010.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-J0f667Rs",
      "attributes": {
        "label": "CE/SC nº 25-001",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável aos Assentos com Grandes Painéis não Metálicos e não Tradicionais / Special Condition for Seats with Non-Traditional, Large, Non-Metallic Panels.",
        "data de início": 40298,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-001@@download/arquivo_norma/CE 25-001.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-g51IyAN2",
      "attributes": {
        "label": "CE/SC nº 25-003",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável à Parada Súbita de Motor e APU / Special Condition for Sudden APU and Engine Stoppage.",
        "data de início": 41376,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-003@@download/arquivo_norma/CE SC 25-003.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-O4BAAEPk",
      "attributes": {
        "label": "CE/SC nº 25-004",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável aos Assentos com Grandes Painéis não Metálicos e não Tradicionais / Special Condition for Seats with Non-Traditional, Large, Non-Metallic Panels.",
        "data de início": 40787,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-004@@download/arquivo_norma/CE SC 25-004.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-KhDHjlDs",
      "attributes": {
        "label": "CE/SC nº 25-005",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável às Manobras de Rolamento  / Special Condition for Rolling Maneuvering.",
        "data de início": 40933,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-005@@download/arquivo_norma/CE 25-005.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-p1Uv7V7Y",
      "attributes": {
        "label": "CE/SC nº 25-006",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável ao Uso de Grandes Painéis não Tradicionais e não Metálicos Integrados à Estrutura dos Assentos de Passageiros / Special Condition for Use of Non-Traditional, Large, Non-Metallic Panels Assembled to Seat Passenger Structures",
        "data de início": 41180,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-006@@download/arquivo_norma/CE SC 25-006.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-3aUgD9Ap",
      "attributes": {
        "label": "CE/SC nº 25-007",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável à Recuperação de Manobra por um Sistema Automático de Voo com uma Instalação de um Sistema Protetor de Alta Velocidade Incorporado nas Leis de Controle de Voo / Special Condition for Maneuver Recovery by an Automatic Flight System with a High Speed Protection System Incorporated in Flight Control Laws",
        "data de início": 41536,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-007@@download/arquivo_norma/CE25-007.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-3zcX1kDQ",
      "attributes": {
        "label": "CE/SC nº 25-008",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável à Película Hidrofóbica a Ser Utilizada no Lugar de Limpadores de Para-Brisas/ Special Condition for the Hydrophobic Coatings to Be Used in Lieu of Windshield Wipers",
        "data de início": 41536,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-008@@download/arquivo_norma/CE25-008.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-9FF26lnY",
      "attributes": {
        "label": "CE/SC nº 25-013",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável ao Sistema de Controle Eletrônico de Voo com Relação à Estabilidade Lateral Direcional e Longitudinal, bem como a Alerta de Baixa Energia / Special Condition for Electronic Flight Control System Regarding its Lateral-Directional and Longitudinal Stability and Low Energy Awareness",
        "data de início": 41557,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-013@@download/arquivo_norma/CE25-013.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-TLzhev7I",
      "attributes": {
        "label": "CE/SC nº 25-014",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável às Forças Limite Aplicadas pelo Piloto ao Manche Lateral / Special Condition for the Limit Pilot Force for Side Stick Controls.",
        "data de início": 41557,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-014@@download/arquivo_norma/CE25-014.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-HVZcbTzM",
      "attributes": {
        "label": "CE/SC nº 25-015",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável aos Manches Laterais / Special Condition for Side Stick Controllers.",
        "data de início": 41579,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-015@@download/arquivo_norma/Anexo.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-bZFRiRIB",
      "attributes": {
        "label": "CE/SC nº 25-016",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável à Interação entre Sistemas e Estrutura / Special Condition for Interaction of Systems and Structures",
        "data de início": 41607,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-016@@download/arquivo_norma/CE25-016.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-20qixaIw",
      "attributes": {
        "label": "CE/SC nº 25-017",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável ao Sistema de Geração e Distribuição de Energia Elétrica /Special Condition for Electrical Power Generation and Distribution System.",
        "data de início": 41607,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-017@@download/arquivo_norma/CE25-017.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-PAT8E6kv",
      "attributes": {
        "label": "CE/SC nº 25-018",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável à Definição de Uma Condição de Aterrissagem com Carregamento de Arfagem que Considere os Efeitos do Sistema de Frenagem Automático /Special Condition for the Definition of a Landing Pitchover Condition which Takes into Account the Effect of the Autobrake System.",
        "data de início": 41626,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-018@@download/arquivo_norma/CE25-018.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-YYOzgNVq",
      "attributes": {
        "label": "CE/SC nº 25-019",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável ao Modo de Aproximação Íngreme (SAM – Steep Approach Mode)\nSpecial Condition for the Steep Approach Mode – SAM.",
        "data de início": 41618,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-019@@download/arquivo_norma/CE25-019.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-F6JaGrQZ",
      "attributes": {
        "label": "CE/SC nº 23-004",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável ao Sistema de Ventilação. / Special Condition for Ventilation System.",
        "data de início": 40179,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-23-004@@download/arquivo_norma/CE SC 23-004.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-Iu1QPwPx",
      "attributes": {
        "label": "CE/SC nº 23-008",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável ao Assento Orientado Transversalmente, Para um Único Ocupante / Special Condition for Single-Place Side-Facing Seat.",
        "data de início": 40526,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-23-008@@download/arquivo_norma/CESC nº 23 - 008.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-qQ9fmZlZ",
      "attributes": {
        "label": "CE/SC nº 25-002",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável à Parada Súbita de Motor e APU / Special Condition for Sudden APU and Engine Stoppage.",
        "data de início": 40361,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-002@@download/arquivo_norma/CESC 25-002.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-S3niWrRo",
      "attributes": {
        "label": "CE/SC nº 25-020",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável à Detecção de Fumaça nos Compartimentos Eletroeletrônicos e às Proteções contra Penetração de Fumaça Oriunda desses Compartimentos - Special Condition for Electrical/Electronic Equipment Bay Fire Detection and Smoke Penetration.",
        "data de início": 41656,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-020@@download/arquivo_norma/CE25-020.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-vYG0LnxA",
      "attributes": {
        "label": "CE/SC nº 25-021",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável à Proteção de Envelope de Voo para Alto Ângulo de Ataque.",
        "data de início": 41768,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-021@@download/arquivo_norma/CE25-021.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-UEogg7CZ",
      "attributes": {
        "label": "CE/SC nº 25-022",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável a Créditos de Proteção de Envelope de Voo Robusta em Condições de Formação de Gelo",
        "data de início": 41768,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-022@@download/arquivo_norma/CE25-022.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-joI9YT6E",
      "attributes": {
        "label": "CE/SC nº 25-023",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável à Proteção de Envelope de Voo para Limite de Arfagem, Rolamento e Alta Velocidade",
        "data de início": 41768,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-023@@download/arquivo_norma/CE25-023.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-xZVbhcZX",
      "attributes": {
        "label": "CE/SC nº 25-024",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável à Proteção de Envelope de Voo para Limitação do Fator de Carga Normal Excessivo",
        "data de início": 41768,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-024@@download/arquivo_norma/CE25-024.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-JwUNIEdg",
      "attributes": {
        "label": "CE/SC nº 25-025",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável a Condições Gerais da Proteção de Envelope de Voo",
        "data de início": 41768,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-025@@download/arquivo_norma/CE25-025.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-kSRUleDU",
      "attributes": {
        "label": "CE/SC nº 25-026",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável a Assentos Orientados Transversalmente.",
        "data de início": 41775,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-026@@download/arquivo_norma/CE25-026.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-Do3OWULQ",
      "attributes": {
        "label": "CE/SC nº 25-027",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável à Proteção dos Sistemas Eletrônicos contra Acessos Internos não Autorizados / Special Condition for Electronic Systems Protection from Unauthorized Internal Access.",
        "data de início": 41789,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-027@@download/arquivo_norma/CE25-027.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-ZnApNCGp",
      "attributes": {
        "label": "CE/SC nº 25-028",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável à Proteção dos Sistemas Eletrônicos contra Acessos Externos não Autorizados / Special Condition for Electronic Systems Protection from Unauthorized External Access.",
        "data de início": 41789,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-028@@download/arquivo_norma/CE25-028.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-ZtyxY1lC",
      "attributes": {
        "label": "CE/SC nº 25-029",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável à Proteção contra Fogo no Compartimento de Acondicionamento de Objetos Localizado no Interior do Lavatório / Special Condition for Fire Protection in the Stowage Compartment Located in the Lavatory.",
        "data de início": 41824,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-029@@download/arquivo_norma/CE_SC_25-029.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-OEWdWKbe",
      "attributes": {
        "label": "CE/SC nº 25-030",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável a Assentos Orientados para a Frente com Incorporação de Sistemas de Airbag. / Special Condition for Forward Facing Seats with Incorporation of Airbag Systems.",
        "data de início": 42341,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-030@@download/arquivo_norma/CE_SC_25-030.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-aexH7GyX",
      "attributes": {
        "label": "CE/SC nº 25-031",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável ao Braço Estrutural entre Assentos. / Special Condition for the Structural Armrest Between Seats.",
        "data de início": 42341,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-031@@download/arquivo_norma/CE_SC_25-031.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-CUV8SoU1",
      "attributes": {
        "label": "CE/SC nº 23-014",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável à Proteção de Segurança dos Sistemas e Redes da Aeronave. / Special Condition for Security Protection of Aircraft Systems And Networks.",
        "data de início": 44050,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-23-014@@download/arquivo_norma/CE SC 23-014.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-zIFzTOkL",
      "attributes": {
        "label": "CE/SC nº 25-068",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável ao Enhanced Vision System (EVS) no Head-Up Display (HUD). / Special Condition for Enhanced Vision System (EVS) on Head-Up Display (HUD).",
        "data de início": 44063,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-068@@download/arquivo_norma/CE SC 25-068.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-IuGyFPlH",
      "attributes": {
        "label": "CE/SC nº 25-061-1",
        "tags": [
          "Condição especial"
        ],
        "description": "Condição Especial Aplicável à Proteção de Envelope de Voo em Alto Ângulo de Ataque. / Special Condition for Flight Envelope Protection of High Angle of Attack",
        "data de início": 44161,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/cesc-condicao-especial/ce-sc-no-25-061-1@@download/arquivo_norma/CE SC 25-061-01.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-jgeLB15v",
      "attributes": {
        "label": "RBAC-E 111 EMD 00",
        "tags": [
          "RBAC"
        ],
        "description": "Sistemas de oxigênio dos lavatórios.",
        "data de início": 40984,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-e-111@@download/arquivo_norma/RBAC-E111EMD00.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-zks2dYnC",
      "attributes": {
        "label": "RBAC 027 EMD 46",
        "tags": [
          "RBAC"
        ],
        "description": "Requisitos de aeronavegabilidade: aeronaves de asas rotativas categoria normal.",
        "data de início": 41438,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-027@@download/arquivo_norma/RBAC27EMD46.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-RLoM4phO",
      "attributes": {
        "label": "RBAC 029 EMD 53",
        "tags": [
          "RBAC"
        ],
        "description": "Requisitos de aeronavegabilidade: aeronaves de asas rotativas categoria transporte.",
        "data de início": 41438,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-029@@download/arquivo_norma/RBAC29EMD53.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-wPkTIsyu",
      "attributes": {
        "label": "RBAC 031 EMD 07",
        "tags": [
          "RBAC"
        ],
        "description": "Requisitos de aeronavegabilidade: balões livres tripulados.",
        "data de início": 42293,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-031@@download/arquivo_norma/RBAC31EMD07.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-6egD9GUZ",
      "attributes": {
        "label": "RBAC 033 EMD 28",
        "tags": [
          "RBAC"
        ],
        "description": "Requisitos de aeronavegabilidade: motores aeronáuticos.",
        "data de início": 39925,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-033@@download/arquivo_norma/RBAC 33.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-uORFpse8",
      "attributes": {
        "label": "RBAC 039 EMD 00",
        "tags": [
          "RBAC"
        ],
        "description": "Diretrizes de aeronavegabilidade",
        "data de início": 40604,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-039@@download/arquivo_norma/RBAC 39.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-4qsWMd08",
      "attributes": {
        "label": "RBAC 139 EMD 05",
        "tags": [
          "RBAC"
        ],
        "description": "Certificação operacional de aeroportos.",
        "data de início": 42355,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-139@@download/arquivo_norma/RBAC139EMD05.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-139@@download/anexo_norma/Perguntas e Respostas RBAC139_EMD05.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-BS1OQxAG",
      "attributes": {
        "label": "RBAC 025 EMD 136",
        "tags": [
          "RBAC"
        ],
        "description": "Requisitos de aeronavegabilidade: aviões categoria transporte",
        "data de início": 41677,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-025@@download/arquivo_norma/BAC25EMD136.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-10vkeTcG",
      "attributes": {
        "label": "RBAC 121 EMD 12",
        "tags": [
          "RBAC"
        ],
        "description": "Operações de transporte aéreo público com aviões com configuração máxima certificada de assentos para passageiros de mais 19 assentos ou capacidade máxima de carga paga acima de 3.400 kg.",
        "data de início": 44238,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-121@@download/arquivo_norma/RBAC121EMD12.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-121@@download/anexo_norma/PA2020-1031 - CEF RBAC 121.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-eeSq9lrx",
      "attributes": {
        "label": "RBAC 110 EMD 00",
        "tags": [
          "RBAC"
        ],
        "description": "Programa Nacional de Instrução em Segurança da Aviação Civil Contra Atos de Interferência Ilícita - PNIAVSEC.",
        "data de início": 42202,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-110@@download/arquivo_norma/RBAC110EMD00.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-110@@download/anexo_norma/CEF RBAC nº 110.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-yNB87eYS",
      "attributes": {
        "label": "RBAC 120 EMD 03",
        "tags": [
          "RBAC"
        ],
        "description": "Programa de prevenção do risco associado ao uso indevido de substâncias psicoativas na aviação civil.",
        "data de início": 44238,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-120@@download/arquivo_norma/RBAC120EMD03.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-120@@download/anexo_norma/CEF RBAC 120.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-zd6UwNSo",
      "attributes": {
        "label": "RBAC 023 EMD 64",
        "tags": [
          "RBAC"
        ],
        "description": "Requisitos de aeronavegabilidade: aviões categoria normal.",
        "data de início": 43684,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-023@@download/arquivo_norma/RBAC23EMD64.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-81nxliMx",
      "attributes": {
        "label": "RBAC 65 EMD 00",
        "tags": [
          "RBAC"
        ],
        "description": "Licenças, habilitações e regras gerais para despachante operacional de voo e mecânico de manutenção aeronáutica",
        "data de início": 43245,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-65@@download/arquivo_norma/RBAC65EMD00.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-65@@download/anexo_norma/PA2018-3159 - CEF RBAC nº 65.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-e2cX6oro",
      "attributes": {
        "label": "RBAC 155 EMD 00",
        "tags": [
          "RBAC"
        ],
        "description": "Helipontos.",
        "data de início": 43245,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-155@@download/arquivo_norma/RBAC155EMD00.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-155@@download/anexo_norma/CEF RBAC 155 e Perguntas e Respostas.zip",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-dndCB5iU",
      "attributes": {
        "label": "RBAC 103 EMD 00",
        "tags": [
          "RBAC"
        ],
        "description": "Operação Aerodesportiva em Aeronaves sem Certificado de Aeronavegabilidade.",
        "data de início": 43259,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-103@@download/arquivo_norma/RBAC103_EMD00 - Retificado.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-103@@download/anexo_norma/CEF RBAC 103.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-i4fTIJl7",
      "attributes": {
        "label": "RBAC 183 EMD 01",
        "tags": [
          "RBAC"
        ],
        "description": "Credenciamento de pessoas.",
        "data de início": 43259,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-183@@download/arquivo_norma/RBAC183_EMD01.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-u75RL8SC",
      "attributes": {
        "label": "RBAC 035 EMD 10",
        "tags": [
          "RBAC"
        ],
        "description": "Requisitos de Aeronavegabilidade: Hélices.",
        "data de início": 43684,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-035@@download/arquivo_norma/RBAC35EMD10.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-TOghSgFg",
      "attributes": {
        "label": "RBAC 129 EMD 01",
        "tags": [
          "RBAC"
        ],
        "description": "Operação de empresas estrangeiras que têm por objetivo o transporte aéreo público no Brasil (Operations of foreign air carriers within Brazil engaged in common carriage).",
        "data de início": 43343,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-129@@download/arquivo_norma/RBAC129EMD01.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-129@@download/anexo_norma/CEF RBAC nº 129.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-pnrn0hRj",
      "attributes": {
        "label": "RBAC 45  EMD 04",
        "tags": [
          "RBAC"
        ],
        "description": "Marcas de Identificação, de Nacionalidade e de Matrícula.",
        "data de início": 44006,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-045@@download/arquivo_norma/RBAC45EMD04.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-045@@download/anexo_norma/CEF RBAC 45.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-yLzWylQX",
      "attributes": {
        "label": "RBAC 107 EMD 04",
        "tags": [
          "RBAC"
        ],
        "description": "Segurança da aviação civil contra atos de interferência ilícita – Operador de aeródromo.",
        "data de início": 44354,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-107@@download/arquivo_norma/RBAC107EMD04 - versão em vigor de 01.07 a 01.08.2021.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-107@@download/anexo_norma/Anexos RBAC 107.zip",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-5YzIEFIB",
      "attributes": {
        "label": "RBAC 108 EMD 04",
        "tags": [
          "RBAC"
        ],
        "description": "Segurança da aviação civil contra atos de interferência ilícita - Operador aéreo.",
        "data de início": 44354,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-108@@download/arquivo_norma/RBAC108EMD04 - versão em vigor de 01.07 a 01.08.2021.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-108@@download/anexo_norma/Anexos.zip",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-Dyd9Fctb",
      "attributes": {
        "label": "RBAC 11 EMD 03",
        "tags": [
          "RBAC"
        ],
        "description": "Regras Gerais para petição de emissão, alteração, revogação e isenção de cumprimento de regra.",
        "data de início": 43914,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-011@@download/arquivo_norma/RBAC11EMD03.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-cagePqhw",
      "attributes": {
        "label": "RBAC 034 EMD 06",
        "tags": [
          "RBAC"
        ],
        "description": "Requisitos para drenagem de combustível e emissões de escapamento de aviões com motores a turbina.",
        "data de início": 43452,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-034@@download/arquivo_norma/RBAC34EMD06.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-1UrGXpLy",
      "attributes": {
        "label": "RBAC 038 EMD 00",
        "tags": [
          "RBAC"
        ],
        "description": "Requisitos para emissões de CO2 de aviões.",
        "data de início": 43452,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-038@@download/arquivo_norma/RBAC38EMD00.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-PMxaReRu",
      "attributes": {
        "label": "RBAC 142 EMD 03",
        "tags": [
          "RBAC"
        ],
        "description": "Certificação e Requisitos Operacionais: Centros de treinamento de aviação civil.",
        "data de início": 44238,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-142@@download/arquivo_norma/RBAC142EMD03.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-142@@download/anexo_norma/CEF RBAC 142 EMD 02.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-l1qdIugO",
      "attributes": {
        "label": "RBAC 145 EMD 07",
        "tags": [
          "RBAC"
        ],
        "description": "Organizações de manutenção de produto aeronáutico.",
        "data de início": 44250,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-145@@download/arquivo_norma/RBAC145EMD07.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-145@@download/anexo_norma/CEF RBAC nº 145.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-EdrmBuAH",
      "attributes": {
        "label": "RBAC 117 EMD 00",
        "tags": [
          "RBAC"
        ],
        "description": "Requisitos para gerenciamento de risco de fadiga humana.",
        "data de início": 43543,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-117@@download/arquivo_norma/RBAC117EMD00.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-117@@download/anexo_norma/ CEF RBAC nº 117.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-e9kzrK6q",
      "attributes": {
        "label": "RBAC 90 EMD 00",
        "tags": [
          "RBAC"
        ],
        "description": "Requisitos para operações especiais de aviação pública.",
        "data de início": 43567,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-90@@download/arquivo_norma/RBAC90EMD00.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-90@@download/anexo_norma/ CEF RBAC nº 90.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-XV9GYRdM",
      "attributes": {
        "label": "RBAC 105 EMD 02",
        "tags": [
          "RBAC"
        ],
        "description": "Salto de paraquedas.",
        "data de início": 43567,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-105@@download/arquivo_norma/RBAC105EMD02.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-pvSEFBKt",
      "attributes": {
        "label": "RBAC 133 EMD 02",
        "tags": [
          "RBAC"
        ],
        "description": "Operação de aeronaves de asas rotativas com cargas externas.",
        "data de início": 43567,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-133@@download/arquivo_norma/RBAC133EMD02.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-133@@download/anexo_norma/CEF RBAC-133.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-Jizblha4",
      "attributes": {
        "label": "RBAC 175 EMD 03",
        "tags": [
          "RBAC"
        ],
        "description": "Transporte de artigos perigosos em aeronaves civis.",
        "data de início": 44238,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-175@@download/arquivo_norma/RBAC175EMD03.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-175@@download/anexo_norma/CEF RBAC 175.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-X0meS7dX",
      "attributes": {
        "label": "RBAC 141 EMD 01",
        "tags": [
          "RBAC"
        ],
        "description": "Certificação e requisitos operacionais: Centros de Instrução de Aviação Civil.",
        "data de início": 43896,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-141@@download/arquivo_norma/RBAC141EMD01.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-141@@download/anexo_norma/CEF RBAC 141.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-ubt1u7vD",
      "attributes": {
        "label": "RBAC 61 EMD 13",
        "tags": [
          "RBAC"
        ],
        "description": "Licenças, habilitações e certificados para pilotos.",
        "data de início": 43909,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-61@@download/arquivo_norma/RBAC61EMD13.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-61@@download/anexo_norma/ CEF RBAC 61.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-00qiTgYp",
      "attributes": {
        "label": "RBAC 153 EMD 06",
        "tags": [
          "RBAC"
        ],
        "description": "Aeródromos - Operação, manutenção e resposta à emergência.",
        "data de início": 44264,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-153@@download/arquivo_norma/RBAC153EMD06.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-153@@download/anexo_norma/Anexos RBAC 153.zip",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-IC8DGf2u",
      "attributes": {
        "label": "RBAC 137 EMD 04",
        "tags": [
          "RBAC"
        ],
        "description": "Certificação e requisitos operacionais: operações aeroagrícolas.",
        "data de início": 43963,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-137@@download/arquivo_norma/RBAC137EMD04.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-137@@download/anexo_norma/CEF RBAC 137.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-MFRI3kAr",
      "attributes": {
        "label": "RBAC 135 EMD 10",
        "tags": [
          "RBAC"
        ],
        "description": "Operações de transporte aéreo público com aviões com configuração máxima certificada de assentos para passageiros de até 19 assentos e capacidade máxima de carga paga de até 3.400 kg (7.500 lb), ou helicópteros.",
        "data de início": 44238,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-135@@download/arquivo_norma/RBAC135EMD10.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-135@@download/anexo_norma/ CEF RBAC nº 135.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-JSPSzx1J",
      "attributes": {
        "label": "RBAC 01 EMD 08",
        "tags": [
          "RBAC"
        ],
        "description": "Definições, regras de redação e unidades de medida para uso nos normativos da ANAC.",
        "data de início": 44238,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-01@@download/arquivo_norma/RBAC01EMD08.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-0C0dn1tH",
      "attributes": {
        "label": "RBAC 119 EMD 08",
        "tags": [
          "RBAC"
        ],
        "description": "Certificação: Operadores de Transporte Aéreo Público.",
        "data de início": 44238,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-119@@download/arquivo_norma/RBAC119EMD08.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-119@@download/anexo_norma/CEF RBAC 119.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-S13rzZZ3",
      "attributes": {
        "label": "RBAC 67 EMD 04",
        "tags": [
          "RBAC"
        ],
        "description": "Requisitos para concessão de certificados médicos aeronáuticos, para o cadastro e credenciamento de médicos, credenciamento de clínicas e para o convênio com entidades públicas.",
        "data de início": 43910,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-067@@download/arquivo_norma/RBAC67EMD04.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-067@@download/anexo_norma/CEF RBAC 67.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-efVFgFAH",
      "attributes": {
        "label": "RBAC 60 EMD 00",
        "tags": [
          "RBAC"
        ],
        "description": "Requisitos para qualificação e uso de dispositivos de treinamento para simulação de voo.",
        "data de início": 43910,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-60@@download/arquivo_norma/RBAC60EMD00.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-CyZr04Zp",
      "attributes": {
        "label": "RBAC 136 EMD 00",
        "tags": [
          "RBAC"
        ],
        "description": "Certificação e requisitos operacionais: voos panorâmicos.",
        "data de início": 44006,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-136@@download/arquivo_norma/RBAC136EMD00.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-KMaLLR1w",
      "attributes": {
        "label": "RBAC 161 EMD 03",
        "tags": [
          "RBAC"
        ],
        "description": "Planos de Zoneamento de Ruído de Aeródromos&nbsp; - PZR",
        "data de início": 44250,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-161@@download/arquivo_norma/RBAC161EMD03 - Retificado.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-161@@download/anexo_norma/CEF RBAC nº 161.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-qpMznaj2",
      "attributes": {
        "label": "RBAC 43 EMD 05",
        "tags": [
          "RBAC"
        ],
        "description": "Manutenção, manutenção preventiva, reconstrução e alteração.",
        "data de início": 44264,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-43-emd-05@@download/arquivo_norma/RBAC43EMD05.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-AL0mLTaD",
      "attributes": {
        "label": "RBAC 135 EMD 11",
        "tags": [
          "RBAC"
        ],
        "description": "Operações de transporte aéreo público com aviões com configuração máxima certificada de assentos para passageiros de até 19 assentos e capacidade máxima de carga paga de até 3.400 kg (7.500 lb), ou helicópteros.",
        "data de início": 44264,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-135-emd-11@@download/arquivo_norma/RBAC135EMD11.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-seIwx7MS",
      "attributes": {
        "label": "RBAC 43 EMD 04",
        "tags": [
          "RBAC"
        ],
        "description": "Manutenção, manutenção preventiva, reconstrução e alteração.",
        "data de início": 43679,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-43@@download/arquivo_norma/RBAC43EMD04.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-43@@download/anexo_norma/CEF RBAC nº 43.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-YeX7fcU2",
      "attributes": {
        "label": "RBAC 36",
        "tags": [
          "RBAC"
        ],
        "description": "Requisitos de ruído para aeronave.",
        "data de início": 44294,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-36@@download/arquivo_norma/RBAC36EMD31.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-qKLInObk",
      "attributes": {
        "label": "RBAC-E 94 EMD 01",
        "tags": [
          "RBAC"
        ],
        "description": "Requisitos gerais para aeronaves não tripuladas de uso civil",
        "data de início": 44348,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-e-94-emd-01@@download/arquivo_norma/RBACE94EMD01.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-e-94-emd-01@@download/anexo_norma/CEF RBAC-E 94.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-QDmWrojE",
      "attributes": {
        "label": "RBAC 21 EMD 08",
        "tags": [
          "RBAC"
        ],
        "description": "Certificação de Produto e Artigo Aeronáuticos.",
        "data de início": 44361,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-21-emd-08@@download/arquivo_norma/RBAC21EMD08.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-21-emd-08@@download/anexo_norma/CEF RBAC 21.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-cOFLctKK",
      "attributes": {
        "label": "RBAC 26 EMD 03",
        "tags": [
          "RBAC"
        ],
        "description": "Aeronavegabilidade continuada e melhorias na segurança para aviões categoria transporte.",
        "data de início": 44361,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-26-emd-03@@download/arquivo_norma/RBAC26EMD03.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-Je3DQCsQ",
      "attributes": {
        "label": "RBAC 91 EMD 03",
        "tags": [
          "RBAC"
        ],
        "description": "Requisitos gerais de operação para aeronaves civis.",
        "data de início": 44361,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-91-emd-03@@download/arquivo_norma/RBAC91EMD03.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-Dnz8NVT5",
      "attributes": {
        "label": "RBAC 121 EMD 14",
        "tags": [
          "RBAC"
        ],
        "description": "Operações de transporte aéreo público com aviões com configuração máxima certificada de assentos para passageiros de mais 19 assentos ou capacidade máxima de carga paga acima de 3.400 kg.",
        "data de início": 44361,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-121-emd-14@@download/arquivo_norma/RBAC121EMD14.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-HcRhd0F1",
      "attributes": {
        "label": "RBAC 154 EMD 07",
        "tags": [
          "RBAC"
        ],
        "description": "Projeto de Aeródromos.",
        "data de início": 44363,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-154-emd-07@@download/arquivo_norma/RBAC154EMD07.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/rbha-e-rbac/rbac/rbac-154-emd-07@@download/anexo_norma/Perguntas e Respostas  RBAC nº 154  Emenda nº 07.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-AMWrZDKK",
      "attributes": {
        "label": "IS 145-002B",
        "tags": [
          "IS"
        ],
        "description": "Certification of Foreign Maintenance Organization",
        "data de início": 42475,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-145-002@@download/arquivo_norma/IS145-002B - Inglês.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-ECVyQAUj",
      "attributes": {
        "label": "IS 67-003C",
        "tags": [
          "IS"
        ],
        "description": "Procedimentos para preenchimento online dos dados do Certificado Médico Aeronáutico no Sistema de Aviação Civil.",
        "data de início": 42482,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-67-003@@download/arquivo_norma/IS67-003C.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-haVr2oe7",
      "attributes": {
        "label": "IS 118-001A",
        "tags": [
          "IS"
        ],
        "description": "Lista de equipamentos e acessórios de aeronave considerados não essenciais",
        "data de início": 42531,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-118-001@@download/arquivo_norma/IS118-001A - SAR.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-102mllqV",
      "attributes": {
        "label": "IS 91-004B",
        "tags": [
          "IS"
        ],
        "description": "Instruções e procedimentos para autorização de operações de aproximação de precisão ILS categorias II e III por operadores aéreos regidos pelo RBHA 91.",
        "data de início": 42566,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-91-004@@download/arquivo_norma/IS 91-004 Revisão B.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-ZS5XunUV",
      "attributes": {
        "label": "IS 153.103-001A",
        "tags": [
          "IS"
        ],
        "description": "Orientações para aplicação do método ACN-PCN.",
        "data de início": 42594,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-153-103-001@@download/arquivo_norma/IS153.103-001A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-4jw5BESr",
      "attributes": {
        "label": "IS 153.205-001B",
        "tags": [
          "IS"
        ],
        "description": "Monitoramento da irregularidade longitudinal, atrito e macrotextura do pavimento da pista pouso e decolagem.",
        "data de início": 44092,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-153-205-001@@download/arquivo_norma/IS153.205-001B.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-EV3ybdm9",
      "attributes": {
        "label": "IS 39.19-001A",
        "tags": [
          "IS"
        ],
        "description": "Método Alternativo de Cumprimento de uma Diretriz de Aeronavegabilidade.",
        "data de início": 42601,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-39-19-001@@download/arquivo_norma/IS39.19-001A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-57pNN4rT",
      "attributes": {
        "label": "IS 43.9-002B",
        "tags": [
          "IS"
        ],
        "description": "Uso e preenchimento do Certificado de Liberação Autorizada (Etiqueta de Aprovação de Aeronavegabilidade).",
        "data de início": 42608,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-43-9-002@@download/arquivo_norma/IS43.9-002B.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-SdNUS4Ia",
      "attributes": {
        "label": "IS 21-013B",
        "tags": [
          "IS"
        ],
        "description": "Instruções para obtenção de aprovação de instalação de equipamentos GNSS (Global Navigation Satellite Systems) stand alone para operações VFR e IFR.",
        "data de início": 42720,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-21-013@@download/arquivo_norma/IS21-013B.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-oLaSNbqD",
      "attributes": {
        "label": "IS 43.1-001A",
        "tags": [
          "IS"
        ],
        "description": "Certificação expedita de OM estrangeira não certificada pela ANAC nos termos do parágrafo RBAC 43.1(e)-I.",
        "data de início": 42720,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-43.1-001@@download/arquivo_norma/IS43.1-001A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-Mply8ukr",
      "attributes": {
        "label": "IS 21-010B",
        "tags": [
          "IS"
        ],
        "description": "Procedimentos para a aprovação de produtos aeronáu-ticos civis importados. / Procedures for approval of imported civil aeronautical products.",
        "data de início": 41390,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-21-010@@download/arquivo_norma/IS21-010B.zip",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-vP0MzFqQ",
      "attributes": {
        "label": "IS 175-007D",
        "tags": [
          "IS"
        ],
        "description": "Programa de treinamento de artigos perigosos - PTAP.",
        "data de início": 44272,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-175-007@@download/arquivo_norma/IS175-007D.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-X21SuDRr",
      "attributes": {
        "label": "IS 120-002C",
        "tags": [
          "IS"
        ],
        "description": "Orientações gerais para a implantação dos programas de prevenção de uso indevido de substâncias psicoativas na aviação civil.",
        "data de início": 43091,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-120-002@@download/arquivo_norma/IS120-002C.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-8ybO4VUD",
      "attributes": {
        "label": "IS 23-001A",
        "tags": [
          "IS"
        ],
        "description": "Execução de Ensaios em Voo para Avaliação de Desempenho de Equipamentos de Comunicação em VHF (VHF-COMM) instalados em Aeronaves certificadas segundo o RBAC 23.",
        "data de início": 42853,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-23-001@@download/arquivo_norma/IS 23-001A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-kRl88HEY",
      "attributes": {
        "label": "IS E94.503-001A",
        "tags": [
          "IS"
        ],
        "description": "Emissão de Certificado de Autorização de Voo Experimental para Aeronaves Remotamente Pilotadas",
        "data de início": 42858,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-e94-503-001@@download/arquivo_norma/ISE94.503-001A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-z03NhykS",
      "attributes": {
        "label": "IS E94-002A",
        "tags": [
          "IS"
        ],
        "description": "Autorização de Projeto de Sistema de Aeronave Remotamente Pilotada - RPAS - Requisitos Técnicos",
        "data de início": 42858,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-94-002@@download/arquivo_norma/ISE94-002A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-nDycKeoX",
      "attributes": {
        "label": "IS E94-001B",
        "tags": [
          "IS"
        ],
        "description": "Autorização de Projeto de Sistema de Aeronave Remotamente Pilotada - Procedimentos Gerais.",
        "data de início": 43763,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-e94-001@@download/arquivo_norma/ISE94-001B.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-xSjD9L0f",
      "attributes": {
        "label": "IS E94-003A",
        "tags": [
          "IS"
        ],
        "description": "Procedimentos para elaboração e utilização de avaliação de risco operacional para operadores de aeronaves não tripuladas.",
        "data de início": 42858,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-e94-003@@download/arquivo_norma/ISE94-003A - Retificada.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-AY4sSZdA",
      "attributes": {
        "label": "IS 91-001E",
        "tags": [
          "IS"
        ],
        "description": "Aprovação operacional de navegação baseada em desempenho (PBN).",
        "data de início": 42881,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-91-001@@download/arquivo_norma/IS91-001E.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-kguOwJ3C",
      "attributes": {
        "label": "IS 145.109-001C",
        "tags": [
          "IS"
        ],
        "description": "Publicações técnicas: obtenção e controle pelas organizações de manutenção de produto aeronáutico.",
        "data de início": 42902,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-145-109-001@@download/arquivo_norma/IS145.109-001C.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-HQ33yrSu",
      "attributes": {
        "label": "IS 142-001A",
        "tags": [
          "IS"
        ],
        "description": "Instruções e procedimentos para certificação de um Centro de Treinamento de Aviação Civil ou alterações de suas respectivas Especificações de Treinamento.",
        "data de início": 41831,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-142-001@@download/arquivo_norma/IS 142-001A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-qcokHoBy",
      "attributes": {
        "label": "IS 119-000A",
        "tags": [
          "IS"
        ],
        "description": "Processo de certificação de empresa de transporte aéreo regida pelo RBAC nº 135.",
        "data de início": 43007,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-119-000@@download/arquivo_norma/IS119-000A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-SZRbdktc",
      "attributes": {
        "label": "IS 135-004A",
        "tags": [
          "IS"
        ],
        "description": "Procedimentos para credenciamento de comissário de voo como examinador em operador sob o RBAC nº 135.",
        "data de início": 43007,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-135-004@@download/arquivo_norma/IS135-004A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-4NnNMtKh",
      "attributes": {
        "label": "IS 20-003A",
        "tags": [
          "IS"
        ],
        "description": "Extintores de incêndio portáteis.",
        "data de início": 41789,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-20-003@@download/arquivo_norma/IS20-003A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-m9HE7hcm",
      "attributes": {
        "label": "IS 21.17-2A",
        "tags": [
          "IS"
        ],
        "description": "Certificação de aeronavegabilidade de planadores e motoplanadores.",
        "data de início": 41187,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-21-17-2@@download/arquivo_norma/IS 21.17-2A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-DhJjzl5b",
      "attributes": {
        "label": "IS 21.191-001A",
        "tags": [
          "IS"
        ],
        "description": "Aeronaves de construção amadora.",
        "data de início": 41064,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-21-191-001@@download/arquivo_norma/IS21.191-001A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-W8eJpn1h",
      "attributes": {
        "label": "IS 23-002A",
        "tags": [
          "IS"
        ],
        "description": "Aviões categoria normal, utilidade, acrobática e transporte regional, modificados para transporte de carga. (Arquivo substituído em 24 de outubro de 2012 - Retificação DOU 24/20/2012).",
        "data de início": 40396,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-23-002@@download/arquivo_norma/IS 23-002A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-swffcXBC",
      "attributes": {
        "label": "IS 43-001A",
        "tags": [
          "IS"
        ],
        "description": "Elegibilidade, qualidade e identificação de peças de reposição.",
        "data de início": 39945,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-43-001@@download/arquivo_norma/IS_43-001A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-WVZLrGOq",
      "attributes": {
        "label": "IS 43.9-003B",
        "tags": [
          "IS"
        ],
        "description": "Caderneta de célula, de motor e de hélice.",
        "data de início": 43889,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-43-9-003@@download/arquivo_norma/IS43.9-003B.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-mPvHrb4T",
      "attributes": {
        "label": "IS 43.13-005A",
        "tags": [
          "IS"
        ],
        "description": "Ferramentas especiais.",
        "data de início": 41513,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-43-13-005@@download/arquivo_norma/IS43.13-005A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-qpvqbP8b",
      "attributes": {
        "label": "IS 43.13-003C",
        "tags": [
          "IS"
        ],
        "description": "Ensaios não destrutivos na manutenção de produto aeronáutico.",
        "data de início": 41544,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-43-13-003@@download/arquivo_norma/IS43.13-003C.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-N3FAK2aP",
      "attributes": {
        "label": "IS 67-001A",
        "tags": [
          "IS"
        ],
        "description": "Procedimentos para reconhecimento de Curso Básico de Perícia Médica na Aviação Civil.",
        "data de início": 40956,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-67-001@@download/arquivo_norma/IS67-001A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-SKgkHVqW",
      "attributes": {
        "label": "IS 67-002B",
        "tags": [
          "IS"
        ],
        "description": "Instruções para obtenção e revalidação de um Certificado Médico Aeronáutico (CMA).",
        "data de início": 42146,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-67-002@@download/arquivo_norma/IS67-002B.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-RcG58KGQ",
      "attributes": {
        "label": "IS 67-004B",
        "tags": [
          "IS"
        ],
        "description": "Guia médico - meios aceitáveis de cumprimento do RBAC nº 67.",
        "data de início": 43955,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-67-004@@download/arquivo_norma/IS67-004B.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-Uv5zp8KA",
      "attributes": {
        "label": "IS 91-003A",
        "tags": [
          "IS"
        ],
        "description": "Aprovação operacional para aproximações ILS CAT I com autorização requerida e decolagens com baixa visibilidade mediante o emprego do Head Up Guidance System (HGS).",
        "data de início": 42295,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-91-003@@download/arquivo_norma/IS91-003A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-Iyjdov7b",
      "attributes": {
        "label": "IS 21.191-002A",
        "tags": [
          "IS"
        ],
        "description": "Aeronaves históricas.",
        "data de início": 40900,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-21-191-002@@download/arquivo_norma/IS 21.191-002A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-17sFqZKc",
      "attributes": {
        "label": "IS 91.21-001A",
        "tags": [
          "IS"
        ],
        "description": "Utilização de dispositivos eletrônicos portáteis.",
        "data de início": 41942,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-91-21-001@@download/arquivo_norma/IS9121-001A.PDF",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-wbeXymRK",
      "attributes": {
        "label": "IS 91.409-001B",
        "tags": [
          "IS"
        ],
        "description": "Manutenção de aeronaves, tempo recomendado entre as revisões gerais.",
        "data de início": 44088,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-91-409-001@@download/arquivo_norma/IS91.409-001B.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-U98FRwOi",
      "attributes": {
        "label": "IS 110-001A",
        "tags": [
          "IS"
        ],
        "description": "Processo de autorização de centros de instrução e Manual de Procedimentos do Centro de Instrução (MPCI).",
        "data de início": 42306,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-110-001@@download/arquivo_norma/IS110-001A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-hEHaMHTS",
      "attributes": {
        "label": "IS 119-002D",
        "tags": [
          "IS"
        ],
        "description": "Guia para a elaboração de SGSO de empresa aérea certificada de acordo com o RBAC 119.",
        "data de início": 41222,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-119-002@@download/arquivo_norma/IS 119-002D.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-1TG1s39f",
      "attributes": {
        "label": "IS 119-003A",
        "tags": [
          "IS"
        ],
        "description": "Procedimentos para elaboração e utilização de Manual de Procedimentos Operacionais Padronizados (SOP).",
        "data de início": 41411,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-119-003@@download/arquivo_norma/IS119-003A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-iY0CJVIn",
      "attributes": {
        "label": "IS 120-001B",
        "tags": [
          "IS"
        ],
        "description": "Programa de manutenção de empresas de transporte aéreo.",
        "data de início": 41642,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-120-001@@download/arquivo_norma/IS120-001B.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-LIQVRFO7",
      "attributes": {
        "label": "IS 121-001B",
        "tags": [
          "IS"
        ],
        "description": "Procedimentos para elaboração, revisão e utilização do guia de rota.",
        "data de início": 44218,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-121-001@@download/arquivo_norma/IS121-001B.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-6D8xGcUJ",
      "attributes": {
        "label": "IS 121.1225-001A",
        "tags": [
          "IS"
        ],
        "description": "Programa de reporte voluntário de empresa aérea certificada de acordo com o RBAC nº 121.",
        "data de início": 41838,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-121-1225-001@@download/arquivo_norma/IS121.1225-001A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-wJq7jrET",
      "attributes": {
        "label": "IS 137-003A",
        "tags": [
          "IS"
        ],
        "description": "Processo de certificação de empresa aeroagrícola",
        "data de início": 42181,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-137-003@@download/arquivo_norma/IS137-003A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-ruFIsnVp",
      "attributes": {
        "label": "IS 137.201-001C",
        "tags": [
          "IS"
        ],
        "description": "Uso de etanol em aeronaves agrícolas.",
        "data de início": 44415,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-137-201-001@@download/arquivo_norma/IS137.201-001C.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-a9mZ6tD9",
      "attributes": {
        "label": "IS 135.21-001A",
        "tags": [
          "IS"
        ],
        "description": "Instruções para elaboração do Manual Geral de Manutenção (MGM) - táxis aéreos operando exclusivamente aeronaves com configuração máxima para passageiros igual ou inferior a 9 (nove) assentos.",
        "data de início": 41138,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-135-21-001@@download/arquivo_norma/IS 135.21-001A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-HoSYlzzC",
      "attributes": {
        "label": "IS 141-001C",
        "tags": [
          "IS"
        ],
        "description": "Procedimentos para comunicação da relação de alunos de cursos homologados em escolas de aviação civil.",
        "data de início": 42181,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-141-001@@download/arquivo_norma/IS141-001C.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-oy2AWi7b",
      "attributes": {
        "label": "IS 145-003B",
        "tags": [
          "IS"
        ],
        "description": "Situações em que deve ocorrer a análise e aceitação dos Manuais de Procedimentos de Inspeção (MPI) de empresas certificadas RBHA 145.",
        "data de início": 41117,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-145-003@@download/arquivo_norma/IS 145-003B.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-lC1qHD8o",
      "attributes": {
        "label": "IS 145-010B",
        "tags": [
          "IS"
        ],
        "description": "Programa de Treinamento em Organizações de Manutenção.",
        "data de início": 43854,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-145-010@@download/arquivo_norma/IS145-010B.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-OQyqDlkn",
      "attributes": {
        "label": "IS 145.163-001A",
        "tags": [
          "IS"
        ],
        "description": "Qualificação e Autorização em Ensaios não destrutivos na manutenção de produto aeronáutico",
        "data de início": 41544,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-145-163-001@@download/arquivo_norma/IS145.163-001A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-CwZJcZBF",
      "attributes": {
        "label": "IS 153-109B",
        "tags": [
          "IS"
        ],
        "description": "Sistema de Orientação e Controle da Movimentação no Solo - SOCMS.",
        "data de início": 43896,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-153-109@@download/arquivo_norma/IS153-109B.pdf, https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-153-109@@download/anexo_norma/SOCMS.docx",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-po8zWisF",
      "attributes": {
        "label": "IS 161.55-001A",
        "tags": [
          "IS"
        ],
        "description": "Projeto de Monitoramento de Ruído",
        "data de início": 41425,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-161-55-001@@download/arquivo_norma/IS161.55-001A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-DEluDIY5",
      "attributes": {
        "label": "IS 164-001A",
        "tags": [
          "IS"
        ],
        "description": "Análise do risco de colisão entre aeronaves e fauna.",
        "data de início": 42216,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-164-001@@download/arquivo_norma/IS164-001A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-HXsOwJ7e",
      "attributes": {
        "label": "IS 121-002A",
        "tags": [
          "IS"
        ],
        "description": "Examinadores credenciados no âmbito dos operadores aéreos regidos pelo RBAC nº 121.",
        "data de início": 43084,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-121-002@@download/arquivo_norma/IS121-002A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-5NhSb73K",
      "attributes": {
        "label": "IS 00-007A",
        "tags": [
          "IS"
        ],
        "description": "Avaliação Operacional de Aeronaves.",
        "data de início": 43084,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-00-007@@download/arquivo_norma/IS00-007A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-ouHnzSaD",
      "attributes": {
        "label": "IS 141-003A",
        "tags": [
          "IS"
        ],
        "description": "Currículo mínimo para a formação teórica e prática do Despachante Operacional de Voo (DOV).",
        "data de início": 43091,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-141-003@@download/arquivo_norma/IS141-003A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-RGyiRgcN",
      "attributes": {
        "label": "IS 121-003A",
        "tags": [
          "IS"
        ],
        "description": "Procedimentos para a elaboração dos procedimentos operacionais padronizados (SOP) de operadores certificados sob o RBAC n º 121.",
        "data de início": 43119,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-121-003@@download/arquivo_norma/IS121-003A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-6LEKHyDq",
      "attributes": {
        "label": "IS 121-004A",
        "tags": [
          "IS"
        ],
        "description": "Procedimentos para a elaboração do Manual de Operações da Aeronave (Aircraft Operating Manual - AOM) por operadores certificados sob o RBAC nº 121.",
        "data de início": 43119,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-121-004@@download/arquivo_norma/IS121-004A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-CpmN8Jxe",
      "attributes": {
        "label": "IS 121-005D",
        "tags": [
          "IS"
        ],
        "description": "Procedimentos para elaboração, revisão e utilização do Manual Geral de Operações (MGO) de operadores aéreos regidos pelo RBAC nº 121.",
        "data de início": 44218,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-121-005@@download/arquivo_norma/IS121-005D.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-F0g3A02a",
      "attributes": {
        "label": "IS 142-002C",
        "tags": [
          "IS"
        ],
        "description": "Procedimentos para validação de centro de treinamento de aviação civil estrangeiro.",
        "data de início": 43126,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-142-002@@download/arquivo_norma/IS142-002C.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-5yPhNqAi",
      "attributes": {
        "label": "IS 119-005A",
        "tags": [
          "IS"
        ],
        "description": "Programa de degelo e antigelo no solo.",
        "data de início": 43140,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-119-005@@download/arquivo_norma/IS119-005A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-Ko8uxgqH",
      "attributes": {
        "label": "IS 00-006C",
        "tags": [
          "IS"
        ],
        "description": "Procedimentos para interposição de recurso sobre indeferimento de solicitação de licença, certificado ou habilitação emitidos sob o RBAC nº 61, RBHA 63 ou RBHA 65.",
        "data de início": 43951,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-00-006@@download/arquivo_norma/IS00-006C.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-2pJHTN6D",
      "attributes": {
        "label": "IS 67-005B",
        "tags": [
          "IS"
        ],
        "description": "Procedimentos administrativos para credenciamento e revalidação de credenciamento de médicos, clínicas e convênio com entidades.",
        "data de início": 43168,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-67-005@@download/arquivo_norma/IS67-005B.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-KPOK1ah0",
      "attributes": {
        "label": "IS 129-001B",
        "tags": [
          "IS"
        ],
        "description": "Procedimentos relativos a operação de empresas estrangeiras de transporte aéreo público no Brasil.",
        "data de início": 43168,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-129-001@@download/arquivo_norma/IS129-001B.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-YTlKOnwA",
      "attributes": {
        "label": "IS 00-001B",
        "tags": [
          "IS"
        ],
        "description": "Sistema de Dificuldades em Serviço.",
        "data de início": 43172,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-00-001@@download/arquivo_norma/IS00-001B.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-GC7MP97K",
      "attributes": {
        "label": "IS 121-006C",
        "tags": [
          "IS"
        ],
        "description": "Procedimentos gerais para elaboração, aprovação, revisão e utilização de programas de treinamento operacional (PTO) de operadores aéreos regidos pelo RBAC nº 121.",
        "data de início": 44246,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-121-006@@download/arquivo_norma/IS121-006C.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-iw7jPknl",
      "attributes": {
        "label": "IS 121-008A",
        "tags": [
          "IS"
        ],
        "description": "Procedimentos para elaboração de programa de treinamento operacional de despachantes operacionais de voo segundo o RBAC nº 121.",
        "data de início": 43154,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-121-008@@download/arquivo_norma/IS121-008A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-0J7y7J5z",
      "attributes": {
        "label": "IS 39-001C",
        "tags": [
          "IS"
        ],
        "description": "Diretrizes de Aeronavegabilidade.",
        "data de início": 43679,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-39-001@@download/arquivo_norma/IS39-001C.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-PTkvISdn",
      "attributes": {
        "label": "IS 121-009A",
        "tags": [
          "IS"
        ],
        "description": "Conteúdo aceitável dos conjuntos de sobrevivência para operações sob o RBAC nº 121 sobre grandes extensões de água e sobre terreno desabitado.",
        "data de início": 43229,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-121-009@@download/arquivo_norma/IS121-009A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-U04fB0aA",
      "attributes": {
        "label": "IS 91-006A",
        "tags": [
          "IS"
        ],
        "description": "Procedimentos para a aprovação de operações no Espaço Aéreo NAT – HLA (North Atlantic High Level Airspace).",
        "data de início": 43231,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-91-006@@download/arquivo_norma/IS 91-006A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-feGKB4qe",
      "attributes": {
        "label": "IS 119-006A",
        "tags": [
          "IS"
        ],
        "description": "Operação de aeronaves sob contratos de intercâmbio.",
        "data de início": 43231,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-119-006@@download/arquivo_norma/IS 119-006A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-yPOeZWrl",
      "attributes": {
        "label": "IS 145.214-001B",
        "tags": [
          "IS"
        ],
        "description": "Sistema de Gerenciamento da Segurança Operacional em Organizações de Manutenção de Produto Aeronáutico.",
        "data de início": 43259,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-145-214-001@@download/arquivo_norma/IS145.214-001B.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-yREr94sa",
      "attributes": {
        "label": "IS 91-008A",
        "tags": [
          "IS"
        ],
        "description": "Procedimentos para realização de evento aeronáutico.",
        "data de início": 43270,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-91-008@@download/arquivo_norma/IS91-008A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-eZZNM9tS",
      "attributes": {
        "label": "IS 183-004A",
        "tags": [
          "IS"
        ],
        "description": "Credenciamento de associações aerodesportivas pela ANAC.",
        "data de início": 43270,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-183-004@@download/arquivo_norma/ IS183-004A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-ByFp8GlN",
      "attributes": {
        "label": "IS 154.5-001A",
        "tags": [
          "IS"
        ],
        "description": "Orientações para a elaboração de análise de risco com vistas à demonstração de nível aceitável de segurança operacional.",
        "data de início": 43285,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-154-5-001@@download/arquivo_norma/IS154.5-001A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-QhAlWkYb",
      "attributes": {
        "label": "IS 121-010A",
        "tags": [
          "IS"
        ],
        "description": "Sistema de documentos de segurança operacional.",
        "data de início": 43287,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-121-010@@download/arquivo_norma/IS121-010A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-KNXQ3Hnp",
      "attributes": {
        "label": "IS 00-004H",
        "tags": [
          "IS"
        ],
        "description": "Diretrizes Interpretativas aplicáveis às normas de âmbito da Superintendência de Padrões Operacionais.",
        "data de início": 44295,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-00-004@@download/arquivo_norma/IS00-004H.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-8qtVFE2h",
      "attributes": {
        "label": "IS 175-003D",
        "tags": [
          "IS"
        ],
        "description": "Instruções para preenchimento completo e adequado do Conhecimento de Transporte eletrônico - CT-e - e do Manifesto de Documentos Fiscais eletrônico - MDF-e.",
        "data de início": 44272,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-175-003@@download/arquivo_norma/IS175-003D.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-iwgKnIuU",
      "attributes": {
        "label": "IS 175-008C",
        "tags": [
          "IS"
        ],
        "description": "Orientações para solicitação e obtenção de aprovação (approval) e isenção (exemption) para transporte de artigos perigosos por via aérea.",
        "data de início": 44272,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-175-008@@download/arquivo_norma/IS175-008C.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-HmBam2ys",
      "attributes": {
        "label": "IS 175-009B",
        "tags": [
          "IS"
        ],
        "description": "Instruções para preenchimento e envio do Relatório de Transporte de Artigos Perigosos à ANAC.",
        "data de início": 44272,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-175-009@@download/arquivo_norma/IS175-009B.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-Gf4iTntL",
      "attributes": {
        "label": "IS 61-007A",
        "tags": [
          "IS"
        ],
        "description": "Procedimentos para trâmite de informações acerca da execução de um programa de treinamento operacional.",
        "data de início": 43308,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-61-007@@download/arquivo_norma/IS61-007A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-kF5SFNQT",
      "attributes": {
        "label": "IS 103-001B",
        "tags": [
          "IS"
        ],
        "description": "Operação de veículos ultraleves e balões livres tripulados sob o RBAC nº 103.",
        "data de início": 43315,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-103-001@@download/arquivo_norma/IS103-001B.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-0zklAqkP",
      "attributes": {
        "label": "IS 65-001C",
        "tags": [
          "IS"
        ],
        "description": "Procedimentos para concessão de licença e de habilitação e para recadastramento de mecânicos de manutenção aeronáutica.",
        "data de início": 43713,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-65-001@@download/arquivo_norma/IS65-001C.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-wUV7Tort",
      "attributes": {
        "label": "IS 183-002E",
        "tags": [
          "IS"
        ],
        "description": "Processo de Credenciamento de Pessoa Física na SAR e orientações de atuação para os Profissionais Credenciados.",
        "data de início": 44029,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-183-002@@download/arquivo_norma/IS183-002E.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-GhpQwbHh",
      "attributes": {
        "label": "IS 137-002C",
        "tags": [
          "IS"
        ],
        "description": "Orientações relativas à instalação de DGPS em aeronaves agrícolas.",
        "data de início": 43336,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-137-002@@download/arquivo_norma/IS137-002C.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-UVQHuBba",
      "attributes": {
        "label": "IS 183-001D",
        "tags": [
          "IS"
        ],
        "description": "Processo de credenciamento de pessoa jurídica para aplicação do exame de proficiência linguística da ANAC.",
        "data de início": 43417,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-183-001@@download/arquivo_norma/IS183-001D.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-bunmRV5w",
      "attributes": {
        "label": "IS 137-001C",
        "tags": [
          "IS"
        ],
        "description": "Orientações relativas a equipamentos dispersores.",
        "data de início": 43427,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-137-001@@download/arquivo_norma/IS137-001C.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-LAeDgkZ5",
      "attributes": {
        "label": "IS 61-005B",
        "tags": [
          "IS"
        ],
        "description": "Treinamento requerido para concessão e revalidação de habilitação de tipo.",
        "data de início": 43405,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-61-005@@download/arquivo_norma/IS61-005B.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-vp6ZjEs6",
      "attributes": {
        "label": "IS 00-009B",
        "tags": [
          "IS"
        ],
        "description": "Procedimentos para realização de inspeção de rampa em operadores aéreos no território brasileiro.",
        "data de início": 43479,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-00-009@@download/arquivo_norma/ IS00-009B.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-0MS6SqaB",
      "attributes": {
        "label": "IS 175-006D",
        "tags": [
          "IS"
        ],
        "description": "Manual de Artigos Perigosos – MAP.",
        "data de início": 44284,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-175-006@@download/arquivo_norma/IS175-006D.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-ZwBDO2K1",
      "attributes": {
        "label": "IS 175-011B",
        "tags": [
          "IS"
        ],
        "description": "Declaração do expedidor para artigos perigosos.",
        "data de início": 44284,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-175-011@@download/arquivo_norma/IS175-011B.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-1utl1VqM",
      "attributes": {
        "label": "IS 175-001H",
        "tags": [
          "IS"
        ],
        "description": "Transporte de artigos perigosos em aeronaves civis.",
        "data de início": 44272,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-175-001@@download/arquivo_norma/IS175-001H.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-d23o1Q0w",
      "attributes": {
        "label": "IS 175-010C",
        "tags": [
          "IS"
        ],
        "description": "Guia de resposta a emergências para incidentes aeronáuticos envolvendo artigos perigosos.",
        "data de início": 44272,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-175-010@@download/arquivo_norma/IS175-010C.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-ftz7VEqV",
      "attributes": {
        "label": "IS 175-002F",
        "tags": [
          "IS"
        ],
        "description": "Curso de artigos perigosos para pessoal envolvido com transporte aéreo.",
        "data de início": 43504,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-175-002@@download/arquivo_norma/IS175-002F.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-wa0y5evL",
      "attributes": {
        "label": "IS 43-012B",
        "tags": [
          "IS"
        ],
        "description": "Manutenção preventiva por pilotos.",
        "data de início": 43195,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-43-012@@download/arquivo_norma/IS43-012B.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-62u5nFys",
      "attributes": {
        "label": "IS 107-001D",
        "tags": [
          "IS"
        ],
        "description": "Segurança da aviação contra atos de interferência ilícita - operador de aeródromo.",
        "data de início": 43573,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-107-001@@download/arquivo_norma/IS107-001D.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-ThpDfka4",
      "attributes": {
        "label": "IS 108-001D",
        "tags": [
          "IS"
        ],
        "description": "Segurança da aviação contra atos de interferência ilícita – operador aéreo.",
        "data de início": 44239,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-108-001@@download/arquivo_norma/IS108-001D.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-QLfh8ydV",
      "attributes": {
        "label": "IS 21-008B",
        "tags": [
          "IS"
        ],
        "description": "Aprovação de aeronavegabilidade para exportação.",
        "data de início": 43567,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-21-008@@download/arquivo_norma/IS21-008B.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-JwrQ9E8N",
      "attributes": {
        "label": "IS 91-007B",
        "tags": [
          "IS"
        ],
        "description": "Processo de autorização de empresas de serviço aéreo público.",
        "data de início": 43581,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-91-007@@download/arquivo_norma/IS91-007B.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-pd7dp9fG",
      "attributes": {
        "label": "IS 145-001E",
        "tags": [
          "IS"
        ],
        "description": "Certificação de organizações de manutenção domésticas.",
        "data de início": 43997,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-145-001@@download/arquivo_norma/IS145-001E.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-MDZ5E5V4",
      "attributes": {
        "label": "IS 153.37-001A",
        "tags": [
          "IS"
        ],
        "description": "Programa de Treinamento Recorrente para Bombeiros de Aeródromo – PTR-BA.",
        "data de início": 43600,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-153-37-001@@download/arquivo_norma/IS153.37-001A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-IPstPT2P",
      "attributes": {
        "label": "IS 153.403-001A",
        "tags": [
          "IS"
        ],
        "description": "CAT – Categoria Contraincêndio de Aeródromo.",
        "data de início": 43600,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-153-403-001@@download/arquivo_norma/IS153.403-001A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-XeVSJVEZ",
      "attributes": {
        "label": "IS 153.405-001A",
        "tags": [
          "IS"
        ],
        "description": "Agentes extintores.",
        "data de início": 43600,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-153-405-001@@download/arquivo_norma/IS153.405-001A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-oNwQtfSt",
      "attributes": {
        "label": "IS 153.421-001A",
        "tags": [
          "IS"
        ],
        "description": "Equipamentos de Proteção.",
        "data de início": 43600,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-153-421-001@@download/arquivo_norma/IS153.421-001A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-gUeo25e2",
      "attributes": {
        "label": "IS 153.407-001A",
        "tags": [
          "IS"
        ],
        "description": "CCI e demais veículos do SESCINC.",
        "data de início": 43600,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-153-407-001@@download/arquivo_norma/IS153.407-001A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-GNW6lpHk",
      "attributes": {
        "label": "IS 153.409-001A",
        "tags": [
          "IS"
        ],
        "description": "Tempo-resposta.",
        "data de início": 43600,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-153-409-001@@download/arquivo_norma/IS153.409-001A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-4Su8uOnp",
      "attributes": {
        "label": "IS 153.413-001A",
        "tags": [
          "IS"
        ],
        "description": "Operações Compatíveis com a CAT.",
        "data de início": 43600,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-153-413-001@@download/arquivo_norma/IS153.413-001A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-1Cpw0ZT8",
      "attributes": {
        "label": "IS 153.417-001A",
        "tags": [
          "IS"
        ],
        "description": "Formação dos profissionais.",
        "data de início": 43600,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-153-417-001@@download/arquivo_norma/IS153.417-001A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-jMPdSzfL",
      "attributes": {
        "label": "IS 153.423-001A",
        "tags": [
          "IS"
        ],
        "description": "Equipamentos de apoio às operações de resgate.",
        "data de início": 43600,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-153-423-001@@download/arquivo_norma/IS153.423-001A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-mYZeCwVa",
      "attributes": {
        "label": "IS 153.431-001A",
        "tags": [
          "IS"
        ],
        "description": "Informações operacionais.",
        "data de início": 43600,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-153-431-001@@download/arquivo_norma/IS153.431-001A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-KjOn1VnA",
      "attributes": {
        "label": "IS 153.425-001A",
        "tags": [
          "IS"
        ],
        "description": "Seção Contraincêndio.",
        "data de início": 43600,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-153-425-001@@download/arquivo_norma/IS153.425-001A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-qd5P3cKK",
      "attributes": {
        "label": "IS 153.427-001A",
        "tags": [
          "IS"
        ],
        "description": "Sistemas de comunicação e alarme.",
        "data de início": 43600,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-153-427-001@@download/arquivo_norma/IS153.427-001A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-S5wyoGlI",
      "attributes": {
        "label": "IS 153.429-001A",
        "tags": [
          "IS"
        ],
        "description": "Vias de acesso de emergência.",
        "data de início": 43600,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-153-429-001@@download/arquivo_norma/IS153.429-001A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-jrekWZMa",
      "attributes": {
        "label": "IS 153.433-001A",
        "tags": [
          "IS"
        ],
        "description": "Serviço Especializado de Salvamento Aquático - SESAQ.",
        "data de início": 43600,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-153-433-001@@download/arquivo_norma/IS153.433-001A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-InHbVO1e",
      "attributes": {
        "label": "IS 141-004A",
        "tags": [
          "IS"
        ],
        "description": "Processo de certificação de centro de instrução de aviação civil pelo RBAC nº 141.",
        "data de início": 43609,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-141-004@@download/arquivo_norma/IS141-004.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-1D79Ot51",
      "attributes": {
        "label": "IS 91-005C",
        "tags": [
          "IS"
        ],
        "description": "Aprovação operacional para operação em espaço aéreo com separação vertical mínima reduzida (RVSM).",
        "data de início": 43616,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-91-005@@download/arquivo_norma/IS91-005C.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-hC9UgYxI",
      "attributes": {
        "label": "IS 135-002D",
        "tags": [
          "IS"
        ],
        "description": "Procedimentos para elaboração do manual geral de operações (MGO) dos operadores aéreos regidos pelo RBAC nº 135.",
        "data de início": 43630,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-135-002@@download/arquivo_norma/IS135-002D.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-pduvgG4f",
      "attributes": {
        "label": "IS 142-003B",
        "tags": [
          "IS"
        ],
        "description": "Aprovação de instrutores e credenciamento de examinadores vinculados à centros de treinamento de aviação civil.",
        "data de início": 43966,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-142-003@@download/arquivo_norma/IS142-003B.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-ME2omAUA",
      "attributes": {
        "label": "IS 135-001D",
        "tags": [
          "IS"
        ],
        "description": "Procedimentos para credenciamento de piloto examinador no âmbito do RBAC nº 135.",
        "data de início": 43644,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-135-001@@download/arquivo_norma/ IS135-001D.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-xy5eVdhs",
      "attributes": {
        "label": "IS 91-002D",
        "tags": [
          "IS"
        ],
        "description": "Uso de informação aeronáutica em formato digital -\nElectronic Flight Bag (EFB).",
        "data de início": 43644,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-91-002@@download/arquivo_norma/IS91-002D.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-bHTpkUys",
      "attributes": {
        "label": "IS 61.15-001D",
        "tags": [
          "IS"
        ],
        "description": "Autorização para Piloto de Ensaios em Voo.",
        "data de início": 43647,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-61-15-001@@download/arquivo_norma/IS61.15-001D - Retificada.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-IwRPIKZo",
      "attributes": {
        "label": "IS 141-006A",
        "tags": [
          "IS"
        ],
        "description": "Guia para implementação e manutenção do sistema de garantia da qualidade em CIAC.",
        "data de início": 43654,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-141-006@@download/arquivo_norma/ IS141-006A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-q12PNhzW",
      "attributes": {
        "label": "IS 141-005A",
        "tags": [
          "IS"
        ],
        "description": "Guia para implementação e manutenção do SGSO em Centros de Instrução de Aviação Civil certificados conforme o RBAC nº 141.",
        "data de início": 43654,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-141-005@@download/arquivo_norma/IS141-005A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-nlSZ5gJb",
      "attributes": {
        "label": "IS 117-003B",
        "tags": [
          "IS"
        ],
        "description": "Gerenciamento de risco da fadiga – GRF.",
        "data de início": 43763,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-117-003@@download/arquivo_norma/IS117-003B.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-ztn4Zkoa",
      "attributes": {
        "label": "IS 61-004Q",
        "tags": [
          "IS"
        ],
        "description": "Lista de habilitações averbadas pela ANAC nas licenças de pilotos.",
        "data de início": 44263,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-61-004@@download/arquivo_norma/IS61-004Q.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-kECZ6cUl",
      "attributes": {
        "label": "IS 43.9-004A",
        "tags": [
          "IS"
        ],
        "description": "Sistema de Documentos e Registros de Manutenção Eletrônicos - SDRMe.",
        "data de início": 43777,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-43-9-004@@download/arquivo_norma/IS43.9-004A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-TxzDeZy6",
      "attributes": {
        "label": "IS 21.231-001A",
        "tags": [
          "IS"
        ],
        "description": "Certificação de Organização de Projeto.",
        "data de início": 43777,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-21-231-001@@download/arquivo_norma/IS21.231-001A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-CajNRuul",
      "attributes": {
        "label": "IS 117-002A",
        "tags": [
          "IS"
        ],
        "description": "Nível básico do gerenciamento da fadiga – NB.",
        "data de início": 43805,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-117-002@@download/arquivo_norma/IS117-002A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-uh9SLcVh",
      "attributes": {
        "label": "IS 117-004A",
        "tags": [
          "IS"
        ],
        "description": "Orientações para implementação de um SGRF para operadores que tenham um GRF aceito pela ANAC.",
        "data de início": 43829,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-117-004@@download/arquivo_norma/IS117-004A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-JOvNA4HF",
      "attributes": {
        "label": "IS 154-001A",
        "tags": [
          "IS"
        ],
        "description": "Auxílios visuais para pátios de aeronaves.",
        "data de início": 43896,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-154-001@@download/arquivo_norma/Anexo IV - IS154-001A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-mq12WrWs",
      "attributes": {
        "label": "IS 61-003B",
        "tags": [
          "IS"
        ],
        "description": "Processo de exame de proficiência linguística de pilotos e averbação de proficiência linguística com base em licença estrangeira em processo de convalidação.",
        "data de início": 43973,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-61-003-1@@download/arquivo_norma/IS-61-003B.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-tXRQgDev",
      "attributes": {
        "label": "IS 00-010A",
        "tags": [
          "IS"
        ],
        "description": "Treinamento de Gerenciamento de Recursos de Equipes (Corporate Resource Management - CRM).",
        "data de início": 43994,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-00-010@@download/arquivo_norma/IS00-010A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-5d5mBBfs",
      "attributes": {
        "label": "IS 121-007B",
        "tags": [
          "IS"
        ],
        "description": "Procedimentos para elaboração de programa de treinamento operacional de tripulantes de voo segundo o RBAC nº 121.",
        "data de início": 43994,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-121-007@@download/arquivo_norma/IS-121-007B.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-PclL3XdD",
      "attributes": {
        "label": "IS 121-011B",
        "tags": [
          "IS"
        ],
        "description": "Procedimentos para elaboração de programa de treinamento operacional de comissários de voo segundo o RBAC nº 121.",
        "data de início": 43994,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-121-011-1@@download/arquivo_norma/IS121-011B.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-b0wBGtwX",
      "attributes": {
        "label": "IS 135-003D",
        "tags": [
          "IS"
        ],
        "description": "Procedimentos para elaboração e efetivação de programas de treinamento operacional (PrTrnOp) para operações conduzidas segundo o RBAC nº 135.",
        "data de início": 43994,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-135-003@@download/arquivo_norma/IS135-003D.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-74PW9FNO",
      "attributes": {
        "label": "IS 21-021B",
        "tags": [
          "IS"
        ],
        "description": "Apresentação de Dados Requeridos para Certificação Suplementar de Tipo.",
        "data de início": 43997,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-21-021@@download/arquivo_norma/IS21-021B.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-TN8QJIXt",
      "attributes": {
        "label": "IS 141-007A",
        "tags": [
          "IS"
        ],
        "description": "Programas de Instruções e Procedimentos e Manual de Instruções e Procedimentos.",
        "data de início": 43997,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-141-007@@download/arquivo_norma/IS141-007A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-JREqSFQd",
      "attributes": {
        "label": "IS 145.151-001E",
        "tags": [
          "IS"
        ],
        "description": "Cadastramento de Responsável Técnico de Organização de Manutenção de Produto Aeronáutico.",
        "data de início": 43997,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-145-151-001@@download/arquivo_norma/IS145.151-001E.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-CZTkQlDB",
      "attributes": {
        "label": "IS 119-004G",
        "tags": [
          "IS"
        ],
        "description": "Processo de certificação de empresa de transporte aéreo regida pelo RBAC nº 135.",
        "data de início": 44001,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-119-004@@download/arquivo_norma/IS119-004G.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-9rMlT0m7",
      "attributes": {
        "label": "IS 00-002F",
        "tags": [
          "IS"
        ],
        "description": "Padrões para a realização de exames de proficiência de pilotos.",
        "data de início": 44004,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-00-002@@download/arquivo_norma/IS00_002F.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-qA50jMo8",
      "attributes": {
        "label": "IS 00-008C",
        "tags": [
          "IS"
        ],
        "description": "Orientações e procedimentos para solicitação de licenças e habilitações e para a interação com a ANAC.",
        "data de início": 44004,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-00-008@@download/arquivo_norma/IS00-008C.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-Al6P5wb7",
      "attributes": {
        "label": "IS 61-001D",
        "tags": [
          "IS"
        ],
        "description": "Caderneta Individual de Voo Digital – CIV Digital.",
        "data de início": 44004,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-61-001@@download/arquivo_norma/IS61-001D.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-oj9CXrR6",
      "attributes": {
        "label": "IS 61-006H",
        "tags": [
          "IS"
        ],
        "description": "Procedimentos para o lançamento de endossos nos registros de voo de pilotos.",
        "data de início": 44148,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-61-006-1@@download/arquivo_norma/IS61-006H.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-nKs1Y9Tc",
      "attributes": {
        "label": "IS 91.403-001B",
        "tags": [
          "IS"
        ],
        "description": "Verificação de Aeronavegabilidade.",
        "data de início": 44029,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-91-403-001@@download/arquivo_norma/IS91.403-001B.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-1xb0RKA7",
      "attributes": {
        "label": "IS 43.9-001B",
        "tags": [
          "IS"
        ],
        "description": "Instruções para Preenchimento do Formulário F-400-04 (SEGVOO 001).",
        "data de início": 44039,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-43-9-001@@download/arquivo_norma/IS43.9-001B.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-S5hrRQGR",
      "attributes": {
        "label": "IS 175-000B",
        "tags": [
          "IS"
        ],
        "description": "Processo de certificação para o transporte de artigos perigosos.",
        "data de início": 44270,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-175-000@@download/arquivo_norma/175-000B.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-GuP7fLkz",
      "attributes": {
        "label": "IS 21.181-001E",
        "tags": [
          "IS"
        ],
        "description": "Validade de Certificados de Aeronavegabilidade - CA.",
        "data de início": 44050,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-21-181-001@@download/arquivo_norma/IS21.181-001E.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-MjWZebpB",
      "attributes": {
        "label": "IS 21-006C",
        "tags": [
          "IS"
        ],
        "description": "Produção sob o RBAC 21 subpartes F, G, K e O.",
        "data de início": 44050,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-21-006-1@@download/arquivo_norma/IS21-006C.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-rSZQvAUB",
      "attributes": {
        "label": "IS 153.203-001A",
        "tags": [
          "IS"
        ],
        "description": "Avaliação da condição funcional do pavimento.",
        "data de início": 44092,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-153-203-001@@download/arquivo_norma/IS153.203-001A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-nL15eZS8",
      "attributes": {
        "label": "IS 175-004D",
        "tags": [
          "IS"
        ],
        "description": "Orientações quanto aos procedimentos para a expedição e transporte de substâncias biológicas e infectantes em aeronaves civis.",
        "data de início": 44272,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-175-004@@download/arquivo_norma/IS175-004D.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-ym7o1PPJ",
      "attributes": {
        "label": "IS 21-019A",
        "tags": [
          "IS"
        ],
        "description": "Substituição de Tecidos, Espumas e Tapetes em Interiores de Aeronaves",
        "data de início": 44105,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-21-019@@download/arquivo_norma/IS 21-019A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-jgd9ql7i",
      "attributes": {
        "label": "IS 145-009C",
        "tags": [
          "IS"
        ],
        "description": "Manual da Organização de Manutenção, Manual de Controle da Qualidade e Declaração de Conformidade.",
        "data de início": 44109,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-145-009@@download/arquivo_norma/IS 145-009C.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-SRqONLio",
      "attributes": {
        "label": "IS 43.13-004C",
        "tags": [
          "IS"
        ],
        "description": "Procedimentos para Reparo de Aeronaves Avariadas em Acidente/Incidente Aeronáutico ou Ocorrência de Solo com Avarias Estruturais de Grande Monta.",
        "data de início": 44120,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-43-13-004@@download/arquivo_norma/IS43.13-004C.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-xlmE4fAb",
      "attributes": {
        "label": "IS 21-005A",
        "tags": [
          "IS"
        ],
        "description": "Informações sobre aprovação de artigos aeronáuticos para aplicação em aeronaves, motores e hélices",
        "data de início": 44123,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-21-005@@download/arquivo_norma/IS21-005A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-jpMmtxyf",
      "attributes": {
        "label": "IS 00-011A",
        "tags": [
          "IS"
        ],
        "description": "Diretrizes Interpretativas aplicáveis às normas de âmbito da Superintendência de Pessoal da Aviação Civil.",
        "data de início": 44140,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-00-011@@download/arquivo_norma/IS00-011A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-NDM6xY2t",
      "attributes": {
        "label": "IS 91-009A",
        "tags": [
          "IS"
        ],
        "description": "Procedimentos para autorização de operadores aéreos para uso de dados de desempenho específicos para pistas com pavimento antiderrapante.",
        "data de início": 44162,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-91-009@@download/arquivo_norma/IS91-009A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-3R4ojyW7",
      "attributes": {
        "label": "IS 21-018A",
        "tags": [
          "IS"
        ],
        "description": "Quality System Requirements for Corporative Distributor of COP Holder.",
        "data de início": 44561,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-21-018@@download/arquivo_norma/IS21-018A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-fz7Uc4CV",
      "attributes": {
        "label": "IS 154-201-001A",
        "tags": [
          "IS"
        ],
        "description": "Projeto de ranhuras transversais (grooving) em pavimentos aeroportuários.",
        "data de início": 44246,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-154-201-001@@download/arquivo_norma/IS154.201-001A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-vbKhJ5Gr",
      "attributes": {
        "label": "IS 175-012A",
        "tags": [
          "IS"
        ],
        "description": "Aprovação de projeto de embalagem para transporte aéreo de artigos perigosos e aprovação de produção.",
        "data de início": 44280,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-175-012@@download/arquivo_norma/IS 175-012A - Retificado.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-PLq7aiiQ",
      "attributes": {
        "label": "IS 153.505-001A",
        "tags": [
          "IS"
        ],
        "description": "Identificação dos perigos, monitoramento e implementação de técnicas de manejo de fauna.",
        "data de início": 44284,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-153-505-001@@download/arquivo_norma/IS153.505-001A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-4meR54yo",
      "attributes": {
        "label": "IS 153.501-001A",
        "tags": [
          "IS"
        ],
        "description": "Procedimentos básicos de gerenciamento do risco da fauna.",
        "data de início": 44284,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-153-501-001@@download/arquivo_norma/IS153.501-001A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-Y9v3KSxx",
      "attributes": {
        "label": "IS 153.503-00A",
        "tags": [
          "IS"
        ],
        "description": "Análise do risco de colisão entre aeronaves e fauna.",
        "data de início": 44284,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-153-503-001@@download/arquivo_norma/IS153.503-001A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-ba5PWZ5j",
      "attributes": {
        "label": "IS 175-005D",
        "tags": [
          "IS"
        ],
        "description": "Orientações para os procedimentos de Notificação de Ocorrências com Artigos Perigosos (NOAP) e de Notificação de Condições Latentes com Artigos Perigosos (NOCLAP).",
        "data de início": 44284,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-175-005@@download/arquivo_norma/IS175-005D.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-cMZz2DfE",
      "attributes": {
        "label": "IS 119-007A",
        "tags": [
          "IS"
        ],
        "description": "Concentradores de oxigênio portáteis.",
        "data de início": 44309,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-119-007@@download/arquivo_norma/IS119-007A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-aBmXzuhe",
      "attributes": {
        "label": "IS 21-004E",
        "tags": [
          "IS"
        ],
        "description": "Aprovação de Grandes Modificações e Grandes Alterações em aeronaves com marcas brasileiras, ou que venham a ter marcas brasileiras.",
        "data de início": 44211,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-21-004@@download/arquivo_norma/IS21-004E.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-CEo5nwhy",
      "attributes": {
        "label": "IS 119-001J",
        "tags": [
          "IS"
        ],
        "description": "Processo de certificação de empresa de transporte aéreo regida pelo RBAC nº 121.",
        "data de início": 44306,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-119-001@@download/arquivo_norma/IS119-001J.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-tJAp18Nq",
      "attributes": {
        "label": "IS 91.319-001A",
        "tags": [
          "IS"
        ],
        "description": "Sobrevoo de área densamente povoada por aeronave experimental.",
        "data de início": 44358,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-91-319-001@@download/arquivo_norma/IS91.319-001A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-dEyFVW8p",
      "attributes": {
        "label": "IS 154-002A",
        "tags": [
          "IS"
        ],
        "description": "Características físicas de aeródromos.",
        "data de início": 44372,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-154-002@@download/arquivo_norma/IS154-002A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-kD4RgxYl",
      "attributes": {
        "label": "IS 00-008D",
        "tags": [
          "IS"
        ],
        "description": "Orientações e procedimentos para solicitação de licenças e habilitações e para a interação com a ANAC.",
        "data de início": 44372,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-00-008-1@@download/arquivo_norma/IS00-008D.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-8QzTdti5",
      "attributes": {
        "label": "IS 119-006B",
        "tags": [
          "IS"
        ],
        "description": "Operação de aeronaves sob contratos de intercâmbio.",
        "data de início": 44372,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-119-006-1@@download/arquivo_norma/IS119-006B.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-nC9BDRJ8",
      "attributes": {
        "label": "IS 00-009C",
        "tags": [
          "IS"
        ],
        "description": "Orientações aos operadores aéreos nacionais para inspeção de rampa no território brasileiro.",
        "data de início": 44379,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-00-009-1@@download/arquivo_norma/IS00-009C.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-0JxYak4K",
      "attributes": {
        "label": "IS 65-001D",
        "tags": [
          "IS"
        ],
        "description": "Procedimentos para concessão de licença e de habilitação e para recadastramento de mecânicos de manutenção aeronáutica.",
        "data de início": 44379,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/is/is-65-001-1@@download/arquivo_norma/IS65-001D.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-gt4MeTNF",
      "attributes": {
        "label": "IAC 201",
        "tags": [
          "IAC"
        ],
        "description": "Fiscalização e controle da contribuição devida ao fundo aeroviário.",
        "data de início": 35468,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/iac/iac-201@@download/arquivo_norma/IAC0201.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-tHwaa8qz",
      "attributes": {
        "label": "IAC 119-1003",
        "tags": [
          "IAC"
        ],
        "description": "Certificado de homologação de operador aéreo e especificações operativas.",
        "data de início": 37841,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/iac/iac-119-1003@@download/arquivo_norma/IAC119_1003.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-xG4hi1Vf",
      "attributes": {
        "label": "IAC 119-1005",
        "tags": [
          "IAC"
        ],
        "description": "Programa de acompanhamento e análise de dados de vôo (PAADV).",
        "data de início": 38341,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/iac/iac-119-1005@@download/arquivo_norma/IAC119_1005.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-6bFp1w9j",
      "attributes": {
        "label": "IAC 121-1001",
        "tags": [
          "IAC"
        ],
        "description": "Padrões mínimos para estações de linha de empresas aéreas homologadas segundo o RBHA 121.",
        "data de início": 37820,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/iac/iac-121-1001@@download/arquivo_norma/IAC121_1001.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-7xpCZhTE",
      "attributes": {
        "label": "IAC 121-1003",
        "tags": [
          "IAC"
        ],
        "description": "Demonstrações de evacuação de emergência e aterrisagem conforme a seção 121.291 do RBHA 121.",
        "data de início": 37841,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/iac/iac-121-1003@@download/arquivo_norma/IAC121_1003.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-eDZI7ny8",
      "attributes": {
        "label": "IAC 121-1004",
        "tags": [
          "IAC"
        ],
        "description": "Recomendações para a elaboração do sistema de manuais de operações - empresas de transporte aéreo regidas pelo RBHA 121 (Alterada pela Resolução Nº 94, de 11/05/2009).",
        "data de início": 37841,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/iac/iac-121-1004@@download/arquivo_norma/IAC121_1004.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-2rGPgdtL",
      "attributes": {
        "label": "IAC 121-1006",
        "tags": [
          "IAC"
        ],
        "description": "Aprovação e padronização do treinamento e qualificação de tripulação de aviões B767 e B757",
        "data de início": 38250,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/iac/iac-121-1006@@download/arquivo_norma/IAC121_1006.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-VvPkRg2C",
      "attributes": {
        "label": "IAC 121-1008",
        "tags": [
          "IAC"
        ],
        "description": "Aprovação e padronização do treinamento e qualificação de tripulação de aviões ATR-42 e ATR-72.",
        "data de início": 38524,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/iac/iac-121-1008@@download/arquivo_norma/IAC121_1008.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-YjgIwexr",
      "attributes": {
        "label": "IAC 121-1009",
        "tags": [
          "IAC"
        ],
        "description": "Tripulação de aeronaves categoria trasporte; treinamento e qualificação",
        "data de início": 38530,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/iac/iac-121-1009@@download/arquivo_norma/IAC121_1009.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-3qtXKbKw",
      "attributes": {
        "label": "IAC 121-1011",
        "tags": [
          "IAC"
        ],
        "description": "Procedimentos para Ajuste de Tração (Potência) para Decolagem. Aviões Categoria Transporte",
        "data de início": 38530,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/iac/iac-121-1011@@download/arquivo_norma/IAC121_1011.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-EtLVPGH4",
      "attributes": {
        "label": "IAC 121-1013",
        "tags": [
          "IAC"
        ],
        "description": "Procedimentos e requisitos técnico-operacionais complementares para operação no aeroporto de Congonhas.",
        "data de início": 39539,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/iac/iac-121-1013@@download/arquivo_norma/IAC121-1013.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-GI8QeYin",
      "attributes": {
        "label": "IAC 160-1001",
        "tags": [
          "IAC"
        ],
        "description": "Peso máximo de decolagem padronizado das aeronaves do transporte aéreo regular e não regular (grupo 1) Última atualização (EMD 04 - 12/2005).",
        "data de início": 37727,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/iac/iac-160-1001@@download/arquivo_norma/IAC160_1001A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-LUAdnWoe",
      "attributes": {
        "label": "IAC 180-1002A",
        "tags": [
          "IAC"
        ],
        "description": "Cessão de equipamentos aeronáuticos Última atualização (EMD 03 - 05/2006).",
        "data de início": 38530,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/iac/iac-180-1002a@@download/arquivo_norma/IAC180_1002A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-Y9kZNINx",
      "attributes": {
        "label": "IAC 180-1003",
        "tags": [
          "IAC"
        ],
        "description": "Identificação de propriedade de material aeronáutico da ANAC.",
        "data de início": 38216,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/iac/iac-180-1003@@download/arquivo_norma/IAC180_1003.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-I5or0Mx2",
      "attributes": {
        "label": "IAC 187-1001",
        "tags": [
          "IAC"
        ],
        "description": "Cobrança de serviços prestados pelo Departamento de Aviação Civil e organizações subordinadas.",
        "data de início": 38432,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/iac/iac-187-1001@@download/arquivo_norma/IAC187_1001.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-za9bIpA5",
      "attributes": {
        "label": "IAC 200-1001",
        "tags": [
          "IAC"
        ],
        "description": "Plano de assistência às vítimas de acidentes aeronáuticos e apoio aos seus familiares",
        "data de início": 38530,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/iac/iac-200-1001@@download/arquivo_norma/IAC200_1001.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-RydPpijS",
      "attributes": {
        "label": "IAC 0201",
        "tags": [
          "IAC"
        ],
        "description": "F iscalização e controle da contribuição devida ao fundo aeroviário.",
        "data de início": 35468,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/iac/iac-0201@@download/arquivo_norma/IAC0201.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-NFRqU2iB",
      "attributes": {
        "label": "IAC 1302",
        "tags": [
          "IAC"
        ],
        "description": "Normas para apuração e o pagamento da suplementação tarifária e para a arrecadação e o recolhimento do adicional tarifário.",
        "data de início": 36951,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/iac/iac-1302@@download/arquivo_norma/IAC1302.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-IDjCD2MA",
      "attributes": {
        "label": "IAC 2306",
        "tags": [
          "IAC"
        ],
        "description": "Constituição e atribuições específicas das Seções de Aviação Civil (Última atualização EMD 01 - 04/1991).",
        "data de início": 33070,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/iac/iac-2306@@download/arquivo_norma/IAC2306.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-ubxTLPPr",
      "attributes": {
        "label": "IAC 3130",
        "tags": [
          "IAC"
        ],
        "description": "Procedimentos e requisitos complementares para operação de grandes aviões categoria transporte no Aeroporto Santos Dumont.",
        "data de início": 35430,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/iac/iac-3130@@download/arquivo_norma/IAC3130.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-nHytg5ad",
      "attributes": {
        "label": "IAC 3134",
        "tags": [
          "IAC"
        ],
        "description": "Transporte aéreo público de enfermos.",
        "data de início": 36371,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/iac/iac-3134@@download/arquivo_norma/IAC3134.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-0jew5Pbd",
      "attributes": {
        "label": "IAC 3203",
        "tags": [
          "IAC"
        ],
        "description": "Registro de horas de vôo em Cadernetas Individuais de Vôo.",
        "data de início": 37395,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/iac/iac-3203@@download/arquivo_norma/IAC3203.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-8oiqsHDN",
      "attributes": {
        "label": "IAC 3252",
        "tags": [
          "IAC"
        ],
        "description": "Registro de horas de vôo de tripulantes.",
        "data de início": 35488,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/iac/iac-3252@@download/arquivo_norma/IAC3252.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-khfUmrhL",
      "attributes": {
        "label": "IAC 3253",
        "tags": [
          "IAC"
        ],
        "description": "Expedição de comprovantes de horas de vôo.",
        "data de início": 31274,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/iac/iac-3253@@download/arquivo_norma/IAC3253.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-IJ8LgVYM",
      "attributes": {
        "label": "IAC 3316",
        "tags": [
          "IAC"
        ],
        "description": "Procedimentos para celebração de convênio para repasse de recursos financeiros.",
        "data de início": 37334,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/iac/iac-3316@@download/arquivo_norma/IAC3316.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-rQpaDKNt",
      "attributes": {
        "label": "IAC 3501",
        "tags": [
          "IAC"
        ],
        "description": "Operações de alcance prolongado com aviões bimotores (ETOPS) (Última atualização EMD 01 - 02/1999).",
        "data de início": 34547,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/iac/iac-3501@@download/arquivo_norma/IAC3501.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-gsA4Vwae",
      "attributes": {
        "label": "IAC 3502",
        "tags": [
          "IAC"
        ],
        "description": "Distâncias de pouso em pistas molhadas com superfície ranhurada ou capeada com Camada Porosa de Atrito - CPA.",
        "data de início": 32356,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/iac/iac-3502@@download/arquivo_norma/IAC3502.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-cXGqxFUh",
      "attributes": {
        "label": "IAC 3505",
        "tags": [
          "IAC"
        ],
        "description": "Operações Aéreas sobre o Atlântico Norte (NAT-MNPS).",
        "data de início": 33799,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/iac/iac-3505@@download/arquivo_norma/IAC3505.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-0vvW5eDF",
      "attributes": {
        "label": "IAC 3507",
        "tags": [
          "IAC"
        ],
        "description": "Normas e procedimentos para a confecção e aprovação de Listas Mestras de Equipamentos Mínimos (MMEL) e Lista de Equipamentos Mínimos (MEL).",
        "data de início": 36153,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/iac/iac-3507@@download/arquivo_norma/IAC3507.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-Djd6uIk0",
      "attributes": {
        "label": "IAC 3508",
        "tags": [
          "IAC"
        ],
        "description": "Orientação preliminar para aprovação de operadores e de aeronaves para operações com separação vertical mínima reduzida.",
        "data de início": 34936,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/iac/iac-3508@@download/arquivo_norma/IAC3508.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-FkXfEFBr",
      "attributes": {
        "label": "IAC 3512",
        "tags": [
          "IAC"
        ],
        "description": "Orientação para utilização de equipamento GPS (Global Positioning System) em operações IFR em rota e em terminais de aproximação de não-precisão por instrumentos no espaço aéreo brasileiro.",
        "data de início": 37007,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/iac/iac-3512@@download/arquivo_norma/IAC3512.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-R9pObSFA",
      "attributes": {
        "label": "IAC 3513",
        "tags": [
          "IAC"
        ],
        "description": "Orientação para segurança de aeronaves anfíbias ou hidroaviões em operações na água.",
        "data de início": 37057,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/iac/iac-3513@@download/arquivo_norma/IAC3513.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-pgMCwb4k",
      "attributes": {
        "label": "IAC 3515",
        "tags": [
          "IAC"
        ],
        "description": "Autorização para operações de helicópteros com carga externa.",
        "data de início": 37160,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/iac/iac-3515@@download/arquivo_norma/IAC3515.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-XQwbhgiw",
      "attributes": {
        "label": "IAC 4201",
        "tags": [
          "IAC"
        ],
        "description": "Desenvolvimento do módulo IV dos cursos de piloto de linha aérea - helicóptero: \"O comandante e sua função administrativa\".",
        "data de início": 34017,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/iac/iac-4201@@download/arquivo_norma/IAC4201.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-tQHedSve",
      "attributes": {
        "label": "IAC 4201A",
        "tags": [
          "IAC"
        ],
        "description": "Sistemática de controle e fiscalização do programa federal de auxílio a aeroportos.",
        "data de início": 37134,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/iac/iac-4201a@@download/arquivo_norma/IAC4201A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-Ls9K86NA",
      "attributes": {
        "label": "IAC 5001",
        "tags": [
          "IAC"
        ],
        "description": "Planejamento integrado de investimentos na infra-estrutura aeronáutica.",
        "data de início": 36381,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/iac/iac-5001@@download/arquivo_norma/IAC5001.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-EMUhfAAX",
      "attributes": {
        "label": "IAC 5301",
        "tags": [
          "IAC"
        ],
        "description": "Instalações para as Seções de Aviação Civil (SAC) nos aeroportos.",
        "data de início": 36364,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/iac/iac-5301@@download/arquivo_norma/IAC5301.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-xpyVcuAY",
      "attributes": {
        "label": "IAC 001-1001A",
        "tags": [
          "IAC"
        ],
        "description": "Elaboração e controle de publicações do DAC.",
        "data de início": 38523,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/iac/iac-001-1001a@@download/arquivo_norma/IAC001_1001A.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-oWbjxxAG",
      "attributes": {
        "label": "IAC 061-1004",
        "tags": [
          "IAC"
        ],
        "description": "Qualificação e aprovação de dispositivos de treinamento de vôo baseados em computadores pessoais (PCATD)",
        "data de início": 38250,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/iac/iac-061-1004@@download/arquivo_norma/IAC061_1004.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-nrPvQBfX",
      "attributes": {
        "label": "IAC 063-1001",
        "tags": [
          "IAC"
        ],
        "description": "Verificação de competência para concessão de licenças e habilitações de comissários de vôo.",
        "data de início": 38793,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/iac/iac-063-1001@@download/arquivo_norma/IAC063_1001.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-jiXiUKyB",
      "attributes": {
        "label": "IAC 118-1001",
        "tags": [
          "IAC"
        ],
        "description": "Processo de análise e aprovação dos programas de treinamento de operações - RBHA 121 e RBHA 135.",
        "data de início": 37974,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/iac/iac-118-1001@@download/arquivo_norma/IAC118_1001.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-zrzZDnsM",
      "attributes": {
        "label": "IAC 118-1002",
        "tags": [
          "IAC"
        ],
        "description": "Procedimentos e trâmite de documentação para realização e conclusão de treinamento de empresas aéreas",
        "data de início": 38530,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/iac/iac-118-1002@@download/arquivo_norma/IAC118_1002.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-q5TZDRFM",
      "attributes": {
        "label": "IAC 119-1002",
        "tags": [
          "IAC"
        ],
        "description": "Vôo de avaliação operacional.",
        "data de início": 37841,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/iac/iac-119-1002@@download/arquivo_norma/IAC119_1002.pdf",
        "element type": "Rules"
      }
    },
    {
      "_id": "elem-DoaHNePZ",
      "attributes": {
        "label": "IAC 160-1003",
        "tags": [
          "IAC"
        ],
        "description": "Reciprocidade de tratamento em relação à isenção das tarifas da infra-estrutura aeronáutica.",
        "data de início": 38530,
        "fonte da informação": "Dados abertos ANAC",
        "fonte da informação-url": "https://www.anac.gov.br/assuntos/legislacao/legislacao-1/iac-e-is/iac/iac-160-1003@@download/arquivo_norma/IAC 160-1003 - Compilado até RA2017-0432.pdf",
        "element type": "Rules"
      }
    }
  ],
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
