# 🏭 Predição e Análise de Dados Industriais (Teste Industriall)

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.3+-orange.svg)](https://scikit-learn.org/)

## 📌 Sobre o Projeto
Este repositório contém o desenvolvimento de uma solução de **Data Science** aplicada ao contexto industrial. O objetivo principal é analisar variáveis de sensores e processos para construir um modelo preditivo capaz de identificar falhas no maquinário.

O projeto percorre todo o pipeline de dados: desde a limpeza e tratamento inicial até a seleção de atributos relevantes e a escolha do melhor algoritmo de Machine Learning.

## 🗂️ Estrutura do Repositório
A lógica foi dividida em notebooks modulares para facilitar a manutenção e o entendimento:

* **`data_preparation.ipynb`**: Carregamento, limpeza (tratamento de nulos/duplicados) e tipagem dos dados.
* **`eda.ipynb`**: Análise Exploratória de Dados (Exploratory Data Analysis) com foco em correlações e distribuições.
* **`feature_selection.ipynb`**: Técnicas para redução de dimensionalidade e escolha das variáveis.
* **`modelling.ipynb`**: Treinamento, tunagem de hiperparâmetros e avaliação final do modelo.
* **`/exploratory_plots`**: Gráficos gerados durante a análise inicial.
* **`/modelling_plots`**: Curvas de aprendizado, matriz de confusão e métricas de performance.

## 🛠️ Tecnologias e Ferramentas
* **Linguagem:** Python
* **Bibliotecas Principais:** Pandas, NumPy, Scikit-Learn
* **Visualização:** Matplotlib, Seaborn
* **Versionamento:** Git

## 🚀 Como Executar

### 1. Clonar o repositório
```bash
git clone [https://github.com/ASFischer/teste_industriall.git](https://github.com/ASFischer/teste_industriall.git)
cd teste_industriall
