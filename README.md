Este repositório contém a resolução do desafio de projeto da Santander Dev Week na DIO. O objetivo principal é demonstrar o domínio do fluxo **ETL (Extract, Transform, Load)** utilizando a linguagem Python e bibliotecas de manipulação de dados.

## 📋 Contexto do Projeto
O objetivo é engajar clientes bancários através de mensagens personalizadas sobre a importância de **investimentos internacionais**. O fluxo percorre a extração de uma lista de IDs, a transformação desses dados em mensagens ricas via IA e o carregamento para um formato de saída estruturado.

## ⚙️ Tecnologias e Bibliotecas
* **Python 3**
* **Pandas**: Utilizado para extração e tratamento dos dados do CSV.
* **OpenAI (v0.28)**: Utilizada para a lógica de geração de mensagens personalizadas via GPT-3.5.
* **JSON**: Formato utilizado para a carga final dos dados.

# 📊 Processo ETL - Santander Dev Week 2026

Este repositório armazena os artefatos de dados gerados durante o desafio de projeto de ETL com Python.

## 📂 Arquivos Disponíveis

### 1. [SDW2026.csv](./SDW2026.csv)
**Fase de Extract:** Arquivo de entrada contendo a lista de IDs e nomes dos clientes que foram processados pelo pipeline.

### 2. [resultado_final_projeto.json](./resultado_final_projeto.json)
**Fase de Load:** Resultado final do processo. Este arquivo contém os dados originais dos clientes enriquecidos com mensagens personalizadas sobre investimentos internacionais, simulando a carga em um banco de dados NoSQL ou API.

---
**Nota:** O processamento foi realizado via Google Colab, utilizando a biblioteca Pandas para manipulação e lógica de transformação para personalização de mensagens
