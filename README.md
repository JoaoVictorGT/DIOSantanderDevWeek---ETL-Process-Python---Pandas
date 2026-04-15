# 🏦 Santander Dev Week 2023 - Pipeline ETL com Python

Este repositório contém a resolução do desafio de projeto da Santander Dev Week na DIO. O objetivo principal é demonstrar o domínio do fluxo **ETL (Extract, Transform, Load)** utilizando a linguagem Python e bibliotecas de manipulação de dados.

## 📋 Contexto do Projeto
O objetivo é engajar clientes bancários através de mensagens personalizadas sobre a importância de **investimentos internacionais**. O fluxo percorre a extração de uma lista de IDs, a transformação desses dados em mensagens ricas via IA e o carregamento para um formato de saída estruturado.

## ⚙️ Tecnologias e Bibliotecas
* **Python 3**
* **Pandas**: Utilizado para extração e tratamento dos dados do CSV.
* **OpenAI (v0.28)**: Utilizada para a lógica de geração de mensagens personalizadas via GPT-3.5.
* **JSON**: Formato utilizado para a carga final dos dados.

## 🔄 O Processo ETL

### 1. Extract (Extração)
Os dados foram extraídos do arquivo `SDW2026.csv`. Durante esta etapa, foi realizado o tratamento de delimitadores e a normalização de strings para garantir que o pipeline de dados fosse robusto contra erros de formatação.

### 2. Transform (Transformação)
Implementação de lógica para criação de mensagens personalizadas. 
> **Nota técnica:** Devido à descontinuação da API original e limitações de cota de API externa, foi implementada uma função de simulação de IA para garantir a continuidade do fluxo e a entrega dos resultados esperados pelo negócio.

### 3. Load (Carregamento)
O carregamento final foi adaptado para a geração de um arquivo JSON (`resultado_final_projeto.json`), simulando o que seria o retorno de uma requisição `PUT` para um banco de dados ou API de destino.

## 📂 Arquivos no Repositório
* `SantanderDevWeek2023.ipynb`: Notebook com todo o código Python desenvolvido.
* `SDW2026.csv`: Fonte de dados inicial.
* `resultado_final_projeto.json`: Resultado final após o processamento ETL.

## 🎓 Conclusão
Este projeto foi fundamental para exercitar a resiliência técnica, lidando com migrações de bibliotecas (OpenAI), gerenciamento de autenticação e adaptação de infraestrutura em tempo real.
