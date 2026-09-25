# 🚦 Dashboard de Acidentes de Trânsito — Recife | 2019

Análise de Segurança Viária e Mobilidade Urbana com QlikView

Dashboard analítico desenvolvido para explorar dados de acidentes de trânsito ocorridos no Recife durante 2019, transformando registros brutos em indicadores e visualizações interativas para análise de padrões temporais, características das ocorrências, veículos envolvidos, condições das vias e sinalização.

---

## 📌 Imagens

<table>
  <tr>
    <td><img src="https://github.com/jcarlossc/dashboard-qlikview--accidents/blob/main/07_images/01_capa.PNG" alt="Imagem Dashboard" width="200"/> </td>
    <td><img src="https://github.com/jcarlossc/dashboard-qlikview--accidents/blob/main/07_images/02_geral.PNG" alt="Imagem Dashboard" width="200"/> </td>
    <td><img src="https://github.com/jcarlossc/dashboard-qlikview--accidents/blob/main/07_images/03_datas.PNG" alt="Imagem Dashboard" width="200"/> </td>
    <td><img src="https://github.com/jcarlossc/dashboard-qlikview--accidents/blob/main/07_images/04_horas.PNG" alt="Imagem Dashboard" width="200"/> </td>
    <td><img src="https://github.com/jcarlossc/dashboard-qlikview--accidents/blob/main/07_images/05_veiculos.PNG" alt="Imagem Dashboard" width="200"/> </td>
    <td><img src="https://github.com/jcarlossc/dashboard-qlikview--accidents/blob/main/07_images/06_vias.PNG" alt="Imagem Dashboard" width="200"/> </td>
    <td><img src="https://github.com/jcarlossc/dashboard-qlikview--accidents/blob/main/07_images/07_sinalizacao.PNG" alt="Imagem Dashboard" width="200"/> </td>
    <td><img src="https://github.com/jcarlossc/dashboard-qlikview--accidents/blob/main/07_images/08_tabela.PNG" alt="Imagem Dashboard" width="200"/> </td>
    <td><img src="https://github.com/jcarlossc/dashboard-qlikview--accidents/blob/main/07_images/projeto_acidentes_tabelas.png" alt="Imagem Dashboard" width="200"/> </td>
  </tr>
</table>

## 📊 Visão Geral

O projeto utiliza recursos de Business Intelligence e Data Visualization para apresentar uma visão estruturada dos acidentes de trânsito.

A solução permite analisar os dados sob diferentes perspectivas e aplicar filtros interativos para identificar padrões relacionados a:

* 📅 Período e evolução temporal
* 🕐 Horários de ocorrência
* 📍 Localização e bairros
* 🚗 Tipos de veículos envolvidos
* ⚠️ Gravidade dos acidentes
* 🛣️ Condições das vias
* 🚦 Sinalização e semáforos
* 🌧️ Condições climáticas

O objetivo é facilitar a exploração dos dados e transformar informações operacionais em insights para análise de mobilidade e segurança viária.

## 🎯 Objetivos

O projeto foi desenvolvido com os seguintes objetivos:

Consolidar informações sobre acidentes de trânsito.
Identificar períodos e horários com maior concentração de ocorrências.
Analisar a distribuição dos acidentes por região e bairro.
Avaliar os tipos de veículos envolvidos.
Comparar acidentes com vítimas e sem vítimas.
Investigar possíveis relações entre acidentes, condições das vias, clima e sinalização.
Criar indicadores que permitam uma leitura rápida dos principais acontecimentos.
Desenvolver uma solução de BI com navegação e filtros interativos.

## 🎯 Público-Alvo

O dashboard foi desenvolvido para atender principalmente:

* Gestores públicos e analistas de trânsito
* Tomadores de decisão em órgãos governamentais
* Analistas de dados e BI
* Pesquisadores e estudantes da área de mobilidade urbana
* Cidadãos interessados em compreender dados de segurança viária

A interface prioriza clareza visual, navegação intuitiva e autonomia do usuário, mesmo para quem não possui conhecimento técnico em análise de dados.

## 🧩 Perguntas de Negócio

O dashboard foi estruturado para responder perguntas como:

* Qual período apresenta maior quantidade de acidentes?
* Qual é o horário com maior concentração de ocorrências?
* Qual dia da semana apresenta mais acidentes?
* Quais bairros concentram mais ocorrências?
* Quais tipos de veículos aparecem com maior frequência?
* Quantos acidentes tiveram vítimas?
* Quantos acidentes resultaram em vítimas fatais?
* Quais condições de via aparecem com maior frequência?
* Como as condições climáticas estão distribuídas entre as ocorrências?
* Como a situação da sinalização se relaciona com os acidentes registrados?

## 📌 Principais KPIs

O dashboard apresenta indicadores para uma visão rápida da situação analisada:

| Indicador |	Descrição |
| --------- | --------- |
| Total de acidentes | Quantidade total de ocorrências |
| Vítimas não fatais | Total de vítimas não fatais |
| Vítimas fatais | Total de vítimas fatais |
| Acidentes sem vítimas | Ocorrências sem registro de vítimas |
| Taxa de acidentes com vítimas | Proporção de acidentes com vítimas |
| Dia crítico | Dia da semana com maior número de ocorrências |
| Horário crítico | Faixa horária com maior concentração |
| Mês crítico | Mês com maior quantidade de acidentes |
| Veículos envolvidos | Quantidade de veículos registrados nas ocorrências |

## 📈 Estrutura do Dashboard

O projeto está organizado em diferentes áreas de análise:

🏠 Capa

Apresentação do projeto e contexto dos dados.

📊 Visão Geral

Painel com os principais KPIs e indicadores de segurança viária.

📅 Análise Temporal

Análise da distribuição dos acidentes ao longo dos meses e períodos.

🕐 Análise por Horário

Identificação dos horários e períodos com maior concentração de ocorrências.

🚗 Análise de Veículos

Distribuição dos acidentes de acordo com os tipos de veículos envolvidos.

🛣️ Análise das Vias

Avaliação das condições das vias e características relacionadas às ocorrências.

🚦 Análise de Sinalização

Análise das condições de sinalização e funcionamento dos semáforos.

📍 Análise de Endereços

Visualização detalhada dos locais e endereços associados aos acidentes.

## 🔎 Filtros Interativos

Possibilidade de segmentar as análises por diferentes dimensões, incluindo:

* Bairro
* Mês
* Trimestre
* Dia da semana
* Horário
* Tipo de veículo
* Condição da via
* Sinalização

## 🔄 Fluxo da Solução
```
Dados brutos
     │
     ▼
┌─────────────────┐
│ Limpeza         │
│ Padronização    │
│ Validação       │
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│ Modelagem       │
│ dos dados       │
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│ QlikView        │
│ Dashboard       │
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│ KPIs e análises │
│ interativas     │
└─────────────────┘
```

## 🛠️ Tecnologias

| Tecnologia | Utilização |
| ---------- | ---------- |
| QlikView | Desenvolvimento do dashboard e visualizações |
| Qlik Script | Carga e transformação dos dados |
| CSV / QVD | Armazenamento e estruturação dos dados |
| Data Visualization | Representação visual dos indicadores |
| Business Intelligence | Exploração e análise dos dados |

## 📁 Estrutura do Projeto
```
dashboard-qlikview-accidents
│
├─── LICENSE
├─── README.md
│
├───01_app
│   ├───01_dashboard
│   │   │   acidentes_dashboard_v1.0.0.qvw
│   │   │
│   │   └───01_images
│   │           placa_01.png
│   │           placa_02.png
│   │
│   └───02_development
│           acidentes_dev_v1.0.0.qvw
│
├───02_data
│   └───01_raw
│           acidentes_recife_2019.csv
│
├───03_scripts
│   ├───01_config
│   │       config.qvs
│   │
│   ├───02_logs_table
│   │       logs_table.qvs
│   │
│   ├───03_extract_raw
│   │       extract_raw.qvs
│   │
│   ├───04_utils
│   │       utils.qvs
│   │
│   ├───05_transform_stage
│   │       stage.qvs
│   │
│   ├───06_trusted
│   │       trusted.qvs
│   │
│   ├───07_fact
│   │       fact.qvs
│   │
│   ├───08_calendar
│   │       calendar.qvs
│   │
│   └───09_time
│           time.qvs
│
├───04_qvd
│   ├───01_qvd_raw
│   │       qvd_raw.qvd
│   │
│   ├───02_qvd_stage
│   │       stage.qvd
│   │
│   ├───03_qvd_trusted
│   │       trusted.qvs
│   │
│   └───04_qvd_fact
│           fact_qvd.qvd
│
├───05_docs
│   └───01_Admin
│       └───01_Documentation
│               Dicionario_Dados_Acidentes_Recife_2019 .csv
│               Manual_Projeto_Acidentes_Recife_2019.pdf
│
├───06_logs
│       reload_log.csv
│
└───07_images
        01_capa.PNG
        02_geral.PNG
        03_datas.PNG
        04_horas.PNG
        05_veiculos.PNG
        06_vias.PNG
        07_sinalizacao.PNG
        08_tabela.PNG
        projeto_acidentes_tabelas.png
```

## 🗃️ Dados

Os dados utilizados no projeto são referentes a acidentes de trânsito ocorridos no Recife em 2019.

Antes da construção do dashboard, os dados foram submetidos a etapas de preparação, incluindo:

* Limpeza;
* Padronização;
* Tratamento de inconsistências;
* Validação;
* Estruturação para análise;
* Modelagem para utilização no QlikView.

Nota: O projeto possui finalidade analítica e educacional. Os indicadores apresentados refletem os dados disponíveis na base utilizada.

## ⭐ Modo de Utilização

1. Caso não tenha, baixe o QlikView: [https://help.qlik.com/pt-BR/qlikview/September2025/Subsystems/Client/Content/QV_QlikView/Installing%20QlikView.htm](https://help.qlik.com/pt-BR/qlikview/September2025/Subsystems/Client/Content/QV_QlikView/Installing%20QlikView.htm)
2. clone o repositório e acesse o diretório:
```
git clone https://github.com/jcarlossc/dashboard-qlikview-accidents.git
git dashboard-qlikview-accidents
```
3. Acesse o Qlikview:
```
Abrir/dashboard-qlikview-accidents/01_app/01_dashboard/acidentes_dashboard_v1.0.0.qvw
```
4. Caso queira editar:
```
Editar Script
```

## 📜 Licença
Este projeto está licenciado sob MIT License.

## 👤 Autor
* Carlos da Costa
* Recife, PE - Brasil<br>
* Telefone: +55 81 99712 9140<br>
* Telegram: @jcarlossc<br>
* Tableau: [https://public.tableau.com/app/profile/carlos.da.costa7416/vizzes](https://public.tableau.com/app/profile/carlos.da.costa7416/vizzes)
* Blogger linguagem R: [https://informaticus77-r.blogspot.com/](https://informaticus77-r.blogspot.com/)<br>
* Blogger linguagem Python: [https://informaticus77-python.blogspot.com/](https://informaticus77-python.blogspot.com/)<br>
* Email: jcarlossc1977@gmail.com<br>
* LinkedIn: https://www.linkedin.com/in/carlos-da-costa-669252149/<br>
* GitHub: https://github.com/jcarlossc<br>
* Kaggle: https://www.kaggle.com/jcarlossc/  
* Twitter/X: https://x.com/jcarlossc1977
