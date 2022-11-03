---
title: "Aviação Aeroagrícola"
description: "Tema relacionado à aviação aeroagrícola"
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
                width:'240',
                title:'Ementa',
                name: 'ementa'
            },
            {
                type:'text',
                width:'100',
                title:'Norma',
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
                type:'calendar',
                width:'80',
                title:'Data',
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
                title:'Tipo',
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
                type:'hidden',
                width:'100',
                name:'em_vigor'
            },
            {
                type:'text',
                width:'200',
                title:'Anexos',
                name:'anexos'
            }
         ]
    });
document.getElementById('download').onclick = function () {
    mySpreadsheet.download();
}
</script>





<div id="spreadsheet_intra"></div>

<script>
    jexcel(document.getElementById('spreadsheet_intra'), {
        search:true,
        pagination:10,
        data:[
    {
        "Título": "MPH-250",
        "Rev.": 5,
        "Descrição": "Homologação de Tipo de Motores e Hélices Fabricados no Brasil",
        "Emissão": "26 ago. 2008",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=250&MPHRev=005&MPHTipo=MPH",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPH-250-005-P.pdf"
    },
    {
        "Título": "MPH-260",
        "Rev.": 4,
        "Descrição": "Validação de Certificação de Tipo de Motor e Hélice Importados",
        "Emissão": "08 mai. 2008",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=260&MPHRev=004&MPHTipo=MPH",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPH-260-004-P.pdf"
    },
    {
        "Título": "MPH-310",
        "Rev.": 1,
        "Descrição": "Inspeção de Conformidade de Produtos Aeronáuticos",
        "Emissão": "10 out. 2006",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=310&MPHRev=001&MPHTipo=MPH",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPH-310-001-P.pdf"
    },
    {
        "Título": "MPH-500",
        "Rev.": 4,
        "Descrição": "Aprovação de Produtos Aeronáuticos, exceto Aeronaves, Motores Aeronáuticos e Hélices",
        "Emissão": "15 ago. 2008",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=500&MPHRev=004&MPHTipo=MPH",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPH-500-004-P.pdf"
    },
    {
        "Título": "MPH-810",
        "Rev.": 2,
        "Descrição": "Aprovação de Manuais de Vôo",
        "Emissão": "22 dez. 2008",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=810&MPHRev=002&MPHTipo=MPH",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPH-810-002-P.pdf"
    },
    {
        "Título": "MPH-830",
        "Rev.": 1,
        "Descrição": "Análise e Gerenciamento de Riscos nos Vôos de Certificação",
        "Emissão": "15 ago. 2008",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=830&MPHRev=001&MPHTipo=MPH",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPH-830-001-P.pdf"
    },
    {
        "Título": "MPR-0031",
        "Rev.": "--",
        "Descrição": "Procedimento para Análise de MEL no âmbito da SPO e da SAR",
        "Emissão": "28 out. 2015",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=0031&MPHRev=-&MPHTipo=MPR",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPR-0031-P.pdf"
    },
    {
        "Título": "MPR-010",
        "Rev.": 2,
        "Descrição": "Procedimentos de Apuração de Denúncias, Coordenação entre SAR e SFI",
        "Emissão": "13 dez. 2017",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=010&MPHRev=002&MPHTipo=MPR",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPR-010-002-P.pdf"
    },
    {
        "Título": "MPR-030",
        "Rev.": 1,
        "Descrição": "Gestão da Qualidade Interna",
        "Emissão": "27 mai. 2010",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=030&MPHRev=001&MPHTipo=MPR",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPR-030-001-P.pdf"
    },
    {
        "Título": "MPR-041",
        "Rev.": 1,
        "Descrição": "Comunicação entre SAR/SPO para os Processos Relacionados à Cert. de Produto e Avaliação Operacional",
        "Emissão": "21 jul. 2017",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=041&MPHRev=001&MPHTipo=MPR",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPR-041-001-P.pdf"
    },
    {
        "Título": "MPR-050",
        "Rev.": 1,
        "Descrição": "Procedimentos para determinação de recursos humanos na Superintendência de Aeronavegabilidade",
        "Emissão": "27 mai. 2010",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=050&MPHRev=001&MPHTipo=MPR",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPR-050-001-P.pdf"
    },
    {
        "Título": "MPR-101",
        "Rev.": 4,
        "Descrição": "Certificação de Projeto de Produto Aeronáutico",
        "Emissão": "18 set. 2020",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=101&MPHRev=004&MPHTipo=MPR",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPR-101-004-P.pdf"
    },
    {
        "Título": "MPR-102",
        "Rev.": "--",
        "Descrição": "Aprovação Suplementar de Tipo",
        "Emissão": "30 jun. 2017",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=102&MPHRev=-&MPHTipo=MPR",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPR-102-P.pdf"
    },
    {
        "Título": "MPR-103",
        "Rev.": 1,
        "Descrição": "Atividades de Engenharia na Certificação de Produto Aeronáutico",
        "Emissão": "24 jan. 2020",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=103&MPHRev=001&MPHTipo=MPR",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPR-103-001-P.pdf"
    },
    {
        "Título": "MPR-120.002",
        "Rev.": "--",
        "Descrição": "Procedimento de Fiscalização do Cumprimento do RBAC 120",
        "Emissão": "16 mai. 2013",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=120.002&MPHRev=-&MPHTipo=MPR",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPR-120.002-P.pdf"
    },
    {
        "Título": "MPR-121",
        "Rev.": "--",
        "Descrição": "Certificação de Organização de Produção",
        "Emissão": "18 abr. 2017",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=121&MPHRev=-&MPHTipo=MPR",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPR-121-P.pdf"
    },
    {
        "Título": "MPR-122",
        "Rev.": 1,
        "Descrição": "Laboratório de Inflamabilidade",
        "Emissão": "16 abr. 2020",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=122&MPHRev=001&MPHTipo=MPR",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPR-122-001-P.pdf"
    },
    {
        "Título": "MPR-131",
        "Rev.": "--",
        "Descrição": "CERTIFICAÇÃO DE AERONAVEGABILIDADE - CERTIFICADOS ESPECIAIS",
        "Emissão": "10 ago. 2017",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=131&MPHRev=-&MPHTipo=MPR",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPR-131-P.pdf"
    },
    {
        "Título": "MPR-141",
        "Rev.": 3,
        "Descrição": "Análise de Manuais de Organizações de Manutenção Aeronáutica",
        "Emissão": "31 mar. 2020",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=141&MPHRev=003&MPHTipo=MPR",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPR-141-003-P.pdf"
    },
    {
        "Título": "MPR-181",
        "Rev.": 2,
        "Descrição": "Análise e Processamento de Demandas ao RAB",
        "Emissão": "21 ago. 2020",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=181&MPHRev=002&MPHTipo=MPR",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPR-181-002-P.pdf"
    },
    {
        "Título": "MPR-201",
        "Rev.": "--",
        "Descrição": "Gestão de Dificuldades em Serviço",
        "Emissão": "25 ago. 2017",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=201&MPHRev=-&MPHTipo=MPR",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPR-201-P.pdf"
    },
    {
        "Título": "MPR-221",
        "Rev.": "--",
        "Descrição": "Vigilância Continuada de Organização de Produção",
        "Emissão": "30 jun. 2017",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=221&MPHRev=-&MPHTipo=MPR",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPR-221-P.pdf"
    },
    {
        "Título": "MPR-243",
        "Rev.": "--",
        "Descrição": "Avaliação de Segurança e Potencial de Risco na GGAC",
        "Emissão": "14 jul. 2017",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=243&MPHRev=-&MPHTipo=MPR",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPR-243-P.pdf"
    },
    {
        "Título": "MPR-244",
        "Rev.": 3,
        "Descrição": "Vigilância Continuada de Empresas de Transporte Aéreo",
        "Emissão": "17 abr. 2020",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=244&MPHRev=003&MPHTipo=MPR",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPR-244-003-P.pdf"
    },
    {
        "Título": "MPR-245",
        "Rev.": 5,
        "Descrição": "Vigilância Continuada de Produto Aeronáutico Certificado",
        "Emissão": "04 mar. 2020",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=245&MPHRev=005&MPHTipo=MPR",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPR-245-005-P.pdf"
    },
    {
        "Título": "MPR-270",
        "Rev.": 1,
        "Descrição": "Aprovação de Limitações Operacionais e de Aeronavegabilidade",
        "Emissão": "02 jul. 2010",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=270&MPHRev=001&MPHTipo=MPR",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPR-270-001-P.pdf"
    },
    {
        "Título": "MPR-280",
        "Rev.": 1,
        "Descrição": "Certificação de Ruído de Projetos de Tipo de Aeronaves",
        "Emissão": "23 dez. 2010",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=280&MPHRev=001&MPHTipo=MPR",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPR-280-001-P.pdf"
    },
    {
        "Título": "MPR-301",
        "Rev.": 4,
        "Descrição": "Processo Normativo na SAR",
        "Emissão": "23 jul. 2021",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=301&MPHRev=004&MPHTipo=MPR",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPR-301-004-P.pdf"
    },
    {
        "Título": "MPR-302",
        "Rev.": "--",
        "Descrição": "Análise de Isenção de Requisito e Meio Alternativo na GGAC",
        "Emissão": "09 jun. 2017",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=302&MPHRev=-&MPHTipo=MPR",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPR-302-P.pdf"
    },
    {
        "Título": "MPR-401",
        "Rev.": "--",
        "Descrição": "Gestão do Conhecimento em Aeronavegabilidade - Trilhas de Aprendizagem",
        "Emissão": "27 mai. 2016",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=401&MPHRev=-&MPHTipo=MPR",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPR-401-P.pdf"
    },
    {
        "Título": "MPR-421",
        "Rev.": 4,
        "Descrição": "Gestão de Processos - Mapeamento e Manuais de Procedimento",
        "Emissão": "07 ago. 2020",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=421&MPHRev=004&MPHTipo=MPR",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPR-421-004-P.pdf"
    },
    {
        "Título": "MPR-422",
        "Rev.": "--",
        "Descrição": "Planejamento e Acompanhamento de Atividades da SAR",
        "Emissão": "11 abr. 2017",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=422&MPHRev=-&MPHTipo=MPR",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPR-422-P.pdf"
    },
    {
        "Título": "MPR-423",
        "Rev.": 2,
        "Descrição": "Gestão Orçamentária na SAR",
        "Emissão": "25 jun. 2020",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=423&MPHRev=002&MPHTipo=MPR",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPR-423-002-P.pdf"
    },
    {
        "Título": "MPR-424",
        "Rev.": "--",
        "Descrição": "Disponibilização de Informações da SAR",
        "Emissão": "19 abr. 2017",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=424&MPHRev=-&MPHTipo=MPR",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPR-424-P.pdf"
    },
    {
        "Título": "MPR-441",
        "Rev.": 2,
        "Descrição": "Credenciamento de Pessoas Físicas na SAR",
        "Emissão": "14 abr. 2021",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=441&MPHRev=002&MPHTipo=MPR",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPR-441-002-P.pdf"
    },
    {
        "Título": "MPR-451",
        "Rev.": "--",
        "Descrição": "Processo Administrativo Sancionador na SAR",
        "Emissão": "13 out. 2016",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=451&MPHRev=-&MPHTipo=MPR",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPR-451-P.pdf"
    },
    {
        "Título": "MPR-461",
        "Rev.": 2,
        "Descrição": "Serviço Externo da SAR",
        "Emissão": "25 jun. 2020",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=461&MPHRev=002&MPHTipo=MPR",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPR-461-002-P.pdf"
    },
    {
        "Título": "MPR-462",
        "Rev.": 2,
        "Descrição": "Gestão de Ocorrências Aeronáuticas na SAR",
        "Emissão": "16 out. 2020",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=462&MPHRev=002&MPHTipo=MPR",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPR-462-002-P.pdf"
    },
    {
        "Título": "MPR-501",
        "Rev.": 1,
        "Descrição": "Acordos e Relacionamento com a ICAO",
        "Emissão": "13 ago. 2021",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=501&MPHRev=001&MPHTipo=MPR",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPR-501-001-P.pdf"
    },
    {
        "Título": "MPR-502",
        "Rev.": 3,
        "Descrição": "Tratamento de Manifestações Externas na SAR",
        "Emissão": "21 set. 2020",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=502&MPHRev=003&MPHTipo=MPR",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPR-502-003-P.pdf"
    },
    {
        "Título": "MPR-503",
        "Rev.": "--",
        "Descrição": "Ações de Orientação Técnica em Aeronavegabilidade",
        "Emissão": "19 mai. 2017",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=503&MPHRev=-&MPHTipo=MPR",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPR-503-P.pdf"
    },
    {
        "Título": "MPR-504",
        "Rev.": "--",
        "Descrição": "Tratamento de Demandas Especiais na SAR",
        "Emissão": "24 abr. 2017",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=504&MPHRev=-&MPHTipo=MPR",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPR-504-P.pdf"
    },
    {
        "Título": "MPR-505",
        "Rev.": "--",
        "Descrição": "Tratamento de Demandas Técnicas na GCVC",
        "Emissão": "19 mai. 2017",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=505&MPHRev=-&MPHTipo=MPR",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPR-505-P.pdf"
    },
    {
        "Título": "MPR-900.01",
        "Rev.": 1,
        "Descrição": "Manual do Inspetor, Volume 1 - Informações e Orientações Gerais aos Inspetores.",
        "Emissão": "08 jul. 2010",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=900.01&MPHRev=001&MPHTipo=MPR",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPR-900.01-001-P.pdf"
    },
    {
        "Título": "MPR-900.04",
        "Rev.": 5,
        "Descrição": "Manual do Inspetor, Volume 4 - Equipamentos de Aeronave e Autorizações Operacionais",
        "Emissão": "26 abr. 2013",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=900.04&MPHRev=005&MPHTipo=MPR",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPR-900.04-005-P.pdf"
    },
    {
        "Título": "MPR-900.06",
        "Rev.": 4,
        "Descrição": "Manual do Inspetor, Volume 6 - Fiscalização",
        "Emissão": "03 fev. 2011",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=900.06&MPHRev=004&MPHTipo=MPR",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPR-900.06-004-P.pdf"
    },
    {
        "Título": "MPR-900.15",
        "Rev.": "--",
        "Descrição": "Manual do Inspetor volume 15 - Avaliação de Segurança",
        "Emissão": "27 dez. 2013",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=900.15&MPHRev=-&MPHTipo=MPR",
        "URL-Arquivo": "http://sar/FDH/MPR/Textos/MPR-900.15-P.pdf"
    },
    {
        "Título": "MPR-900.50",
        "Rev.": "--",
        "Descrição": "Conteúdo em ambiente de compartilhamento SharePoint dos Operadores Aéreos",
        "Emissão": "11 mai. 2012",
        "URL-Documento": "http://sar/Regulamentacao/MPHDetail.asp?MPHNum=900.50&MPHRev=-&MPHTipo=MPR",
        "URL-Arquivo": ""
    }
],
        columns: [
            {
                type:'text',
                width:'240',
                title:'Título',
                name: 'Título'
            },
            {
                type:'text',
                width:'100',
                title:'Revisão',
                name:'Rev.'
            },
             {
                type:'text',
                width:'100',
                title:'Descrição',
                name:'Descrição'
            },
            {
                type:'calendar',
                width:'100',
                title:'Emissão',
                name:'Emissão'
            },
            {
                type:'text',
                width:'100',
                tilte:'URL-Documento',
                name:'URL-Documento'
            },
            {
                type:'text',
                width:'100',
                title:'URL-Arquivo',
                name:'URL-Arquivo'
            }
         ]
    });
document.getElementById('download').onclick = function () {
    mySpreadsheet.download();
}
</script>


## mkdocs-table-reader-plugin
  
{{ read_csv('https://raw.githubusercontent.com/gabrielmacedoanac/flat-data-anac/main/regulamentos-anac-tags.csv') }}

## Importado do KUMU depois do tratamento

### Github RAW
<script src="https://gist.github.com/gabrielmacedoanac/420d84b6034bd62db97ede4c9cf01c4b.js"></script>
