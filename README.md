# Retail Sales Forecasting Pipeline

# Versão em Português 



Pipeline completo para previsão de vendas no varejo utilizando Python, PostgreSQL, Prophet, Power BI, Docker e Apache Airflow.

## Visão Geral

A previsão de demanda é um dos principais desafios do setor varejista. Uma estimativa precisa das vendas futuras permite reduzir custos com excesso de estoque, minimizar rupturas de produtos e apoiar a tomada de decisão baseada em dados.

Este projeto tem como objetivo desenvolver um pipeline de dados completo, desde a extração e transformação dos dados até o treinamento de um modelo de séries temporais e a visualização dos resultados em dashboards.

O desenvolvimento será realizado de forma incremental, adicionando novas tecnologias conforme o projeto evolui.

---

## Objetivos

- Construir um pipeline ETL para dados de vendas.
- Realizar limpeza e transformação dos dados.
- Armazenar os dados em PostgreSQL.
- Treinar um modelo de previsão utilizando Prophet.
- Disponibilizar os resultados em um dashboard do Power BI.
- Evoluir o projeto com Docker e Apache Airflow.

---

## Tecnologias

- Python
- Pandas
- NumPy
- PostgreSQL
- SQLAlchemy
- Prophet
- Power BI
- Docker
- Apache Airflow

---


## Dataset

Este projeto utiliza um dataset público de vendas contendo informações históricas sobre vendas, produtos, lojas, promoções e datas, permitindo a construção de modelos de previsão de demanda.

---

## Roadmap

### Fase 1 — MVP

Nesta etapa será desenvolvido um pipeline funcional utilizando Python e PostgreSQL.

Etapas:

1. Download do dataset
2. Limpeza dos dados
3. Transformação dos dados
4. Carga no PostgreSQL
5. Treinamento do modelo Prophet
6. Geração das previsões
7. Desenvolvimento do dashboard no Power BI

Fluxo do pipeline:

```text
Dataset
    │
    ▼
Python ETL
    │
    ▼
PostgreSQL
    │
    ▼
Prophet
    │
    ▼
Forecast
    │
    ▼
Power BI
```

---

### Fase 2 — Aprendizado de Prophet

Nesta etapa serão estudados os principais conceitos da biblioteca Prophet:

- Trend
- Seasonality
- Holidays
- Train/Test Split
- Forecasting
- Model Evaluation

---

### Fase 3 — Docker

Após a conclusão do MVP, o pipeline será containerizado utilizando Docker.

Os principais conceitos incluem:

- Docker Images
- Containers
- Dockerfile
- Docker Compose

---

### Fase 4 — Apache Airflow

Na última etapa, o pipeline será automatizado utilizando Apache Airflow.

Inicialmente, o projeto será executado manualmente:

```bash
python src/etl.py
python src/train_model.py
```

Posteriormente, essas tarefas serão transformadas em DAGs do Airflow.

---

## Dashboard

O dashboard apresentará indicadores como:

- Total Sales
- Sales Trend
- Forecast vs Actual Sales
- Sales by Store
- Sales by Product Category
- Seasonality Analysis
- Future Sales Forecast

---

## Modelo

O modelo inicial será desenvolvido utilizando Prophet para previsão de séries temporais.

Futuramente poderão ser comparados outros modelos, como:

- Random Forest
- XGBoost
- LightGBM

---

## Como Executar

Clone o repositório:

```bash
git clone https://github.com/usuario/retail-sales-forecasting-pipeline.git
```

Instale as dependências:

```bash
pip install -r requirements.txt
```

Execute o pipeline:

```bash
python src/etl.py
python src/train_model.py
```

---

## Aprendizados

Este projeto demonstra conhecimentos em:

- Data Engineering
- ETL
- Data Cleaning
- PostgreSQL
- SQL
- Time Series Forecasting
- Prophet
- Power BI
- Docker
- Apache Airflow

---

## Próximas Melhorias

- Containerização completa
- Orquestração com Airflow
- Testes automatizados
- Logging
- Monitoramento
- Deploy em nuvem
- Comparação entre diferentes modelos de Machine Learning

---

## Autora

Flávia Vitória de Queiroz




# English version



An end-to-end retail sales forecasting pipeline built with Python, PostgreSQL, Prophet, Power BI, Docker, and Apache Airflow.

## Overview

Demand forecasting is one of the main challenges in the retail industry. Accurate sales predictions help businesses optimize inventory, reduce stock shortages, minimize overstock, and improve operational planning.

The goal of this project is to build a complete data pipeline, from data extraction and transformation to time series forecasting and business intelligence dashboards.

The project is developed incrementally, introducing new technologies as the architecture evolves.

---

## Objectives

- Build an ETL pipeline for retail sales data.
- Clean and transform raw datasets.
- Store processed data in PostgreSQL.
- Train a forecasting model using Prophet.
- Visualize predictions in Power BI.
- Extend the project with Docker and Apache Airflow.

---

## Technologies

- Python
- Pandas
- NumPy
- PostgreSQL
- SQLAlchemy
- Prophet
- Power BI
- Docker
- Apache Airflow

---

## Dataset

This project uses a public retail sales dataset containing historical sales information, products, stores, promotions, and calendar data, enabling demand forecasting applications.

---

## Roadmap

### Phase 1 — MVP

The first version focuses on building a working pipeline using Python and PostgreSQL.

Steps:

1. Download the dataset
2. Clean the data
3. Transform the data
4. Load data into PostgreSQL
5. Train a Prophet forecasting model
6. Generate future predictions
7. Build a Power BI dashboard

Pipeline architecture:

```text
Dataset
    │
    ▼
Python ETL
    │
    ▼
PostgreSQL
    │
    ▼
Prophet
    │
    ▼
Forecast
    │
    ▼
Power BI
```

---

### Phase 2 — Learning Prophet

During this phase, the following concepts will be explored:

- Trend
- Seasonality
- Holidays
- Train/Test Split
- Forecasting
- Model Evaluation

---

### Phase 3 — Docker

Once the pipeline is stable, it will be containerized using Docker.

Topics include:

- Docker Images
- Containers
- Dockerfile
- Docker Compose

---

### Phase 4 — Apache Airflow

The final stage introduces workflow orchestration with Apache Airflow.

Initially, the pipeline will be executed manually:

```bash
python src/etl.py
python src/train_model.py
```

Later, these tasks will be automated through Airflow DAGs.

---

## Dashboard

The dashboard will provide business insights such as:

- Total Sales
- Sales Trends
- Forecast vs Actual Sales
- Sales by Store
- Sales by Product Category
- Seasonality Analysis
- Future Sales Forecast

---

## Forecasting Model

The first forecasting model is built using Facebook Prophet.

Future versions may compare additional algorithms such as:

- Random Forest
- XGBoost
- LightGBM

---

## Getting Started

Clone the repository:

```bash
git clone https://github.com/username/retail-sales-forecasting-pipeline.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the pipeline:

```bash
python src/etl.py
python src/train_model.py
```

---

## Skills Demonstrated

- Data Engineering
- ETL Pipelines
- Data Cleaning
- SQL
- PostgreSQL
- Time Series Forecasting
- Prophet
- Power BI
- Docker
- Apache Airflow

---

## Future Improvements

- Full Docker deployment
- Airflow orchestration
- Automated testing
- Logging and monitoring
- Cloud deployment
- Comparison of multiple forecasting models

---

## Author

Flávia Vitória de Queiroz
