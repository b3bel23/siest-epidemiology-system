# 🦠 SIEST — Smart Epidemiology System

Sistema Inteligente de Epidemiologia em Saúde Territorial desenvolvido para análise de riscos epidemiológicos utilizando dados climáticos, territoriais e de saúde pública.

O projeto integra técnicas de Engenharia de Dados, ETL, análise geoespacial e bancos de dados não relacionais para auxiliar na identificação de áreas vulneráveis a surtos epidemiológicos.

---

## 📌 Sobre o projeto

O projeto SIEST foi desenvolvido com o objetivo de mitigar os impactos das crises epidemiológicas sazonais na cidade de Campinas - SP, especialmente em áreas onde:

* infraestrutura urbana precária
* eventos climáticos extremos
* vulnerabilidade social

favorecem a proliferação de arboviroses e doenças de veiculação hídrica.

O sistema busca construir uma ferramenta de inteligência territorial baseada em dados públicos e geolocalização.

---

## 🎯 Objetivos

* Identificar potenciais zonas de risco epidemiológico
* Relacionar clima, saneamento e saúde pública
* Auxiliar no direcionamento de agentes de saúde
* Produzir análises territoriais georreferenciadas
* Desenvolver pipelines ETL para integração de dados públicos

---

## 🧠 Problemas abordados

O projeto investiga a relação entre:

* Dengue
* Hepatite A
* Leptospirose
* Enchentes
* Temperatura
* Precipitação
* Vulnerabilidade habitacional
* Falta de saneamento básico

---

## ⚙️ Funcionalidades

✅ Extração de dados públicos

✅ Processamento ETL em Python

✅ Tratamento de grandes volumes de dados

✅ Geolocalização de unidades de saúde

✅ Conversão de dados para formato `.parquet`

✅ Análise climática e epidemiológica

✅ Integração com MongoDB

✅ Análise territorial geoespacial

✅ Estruturação para modelagem com grafos

---

## 🛠️ Tecnologias utilizadas

* Python
* Pandas
* GeoPandas
* NumPy
* Matplotlib
* Seaborn
* NetworkX
* MongoDB
* PyMongo
* Jupyter Notebook

---

## 📂 Estrutura do projeto

```txt id="e2xrx5"
📁 siest-epidemiology-system
 ┣ 📄 01_ETL_Extracao_SINAN.ipynb
 ┣ 📄 02_ETL_Geolocalizacao_CNES.ipynb
 ┣ 📄 03_ETL_Clima_Mosqlimate.ipynb
 ┣ 📄 04_ETL_Saneamento_IBGE.ipynb
 ┣ 📄 README.md
 ┣ 📄 requirements.txt
 ┗ 📄 .gitignore
```

---

## 🌎 Fontes de dados utilizadas

### 📍 Epidemiologia

* DATASUS
* SINAN
* CNES
* Painel Epidemiológico de Campinas

### 🌦️ Clima

* Mosqlimate
* INMET
* CEPAGRI/UNICAMP

### 🏙️ Infraestrutura e saneamento

* Portal Geoambiental de Campinas
* SNIS
* SANASA
* Fundação FEAC

---

## 🔄 Pipeline ETL

O projeto implementa pipelines de:

### 📥 Extração

Coleta de dados públicos através de APIs e bases governamentais.

### 🔧 Transformação

Tratamento, limpeza e padronização dos dados.

### 📤 Carga

Persistência dos dados processados em:

* formato `.parquet`
* MongoDB

---

## 🗄️ Banco de Dados

O banco de dados utilizado foi:

```txt id="9n41wb"
MongoDB
```

Coleções principais:

* `casos_epidemiologicos`
* `dados_climaticos`
* `vulnerabilidade_habitacional`
* `risco_inundacao`

---

## 🌐 Análise geoespacial

O sistema utiliza coordenadas geográficas e polígonos espaciais para:

* mapear áreas de risco
* identificar vulnerabilidade socioambiental
* cruzar clima, saneamento e saúde pública

---

## 📊 Conceitos aplicados

* Engenharia de Dados
* ETL
* Ciência de Dados
* Geoprocessamento
* Bancos NoSQL
* Epidemiologia
* Grafos
* Análise Exploratória de Dados
* Inteligência Territorial

---

## ▶️ Como executar

### 1️⃣ Instale as dependências

```bash id="n74g3r"
pip install pandas geopandas matplotlib seaborn networkx pymongo
```

---

### 2️⃣ Execute os notebooks

Abra os arquivos `.ipynb` em:

* Jupyter Notebook
* Google Colab
* VS Code

---

## 🎓 Objetivo acadêmico

Projeto desenvolvido para a disciplina de Bancos de Dados Não Relacionais (PI) da PUC Campinas.

O trabalho possui foco em:

* integração de dados públicos
* análise territorial
* prevenção epidemiológica
* apoio à tomada de decisão em saúde pública

---

## 👥 Integrantes

* Isabel Baungartner
* Francisco da Silva Bueno Junior
* Ítalo Fraga Botelho
* Tiago Noda Von Zuben

---

## 🚀 Autor

Desenvolvido por alunos de Ciência de Dados e Inteligência Artificial — PUC Campinas
