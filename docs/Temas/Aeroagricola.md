---
title: "Aviação Aeroagrícola"
description: "Tema relacionado à aviação aeroagrícola"
hide:
    - navigation
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

### Github RAW
<script src="https://gist.github.com/gabrielmacedoanac/420d84b6034bd62db97ede4c9cf01c4b.js"></script>
