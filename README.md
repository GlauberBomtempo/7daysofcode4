# 7DaysOfCode - Desafio de Classificação com Regressão Logística

Este projeto faz parte de um desafio de aprendizado onde aplicamos um pipeline simples de classificação supervisionada utilizando **Regressão Logística**.

## 📌 Objetivo
O objetivo é treinar um modelo de regressão logística em um conjunto de dados previamente limpo, avaliando o desempenho nos conjuntos de validação e teste e interpretando a importância das variáveis por meio dos coeficientes do modelo.

## 🚀 Etapas principais
- Carregamento e preparação dos dados
- Divisão em **treino**, **validação** e **teste**
- Treinamento de um modelo de **Regressão Logística** com scikit-learn
- Avaliação da acurácia e métricas de classificação
- Extração e análise dos coeficientes da regressão para interpretabilidade

## 📚 Bibliotecas utilizadas
- `pandas`
- `numpy`
- `scikit-learn`

## 📝 Como rodar
1. Instale as bibliotecas necessárias:
```bash
pip install pandas numpy scikit-learn

2. Execute o notebook 7daysofcode4.ipynb em seu ambiente Jupyter Notebook ou Databricks.

3. Analise as métricas de desempenho e a tabela de coeficientes ao final do notebook.

📈 Resultados esperados
Relatórios de classificação para validação e teste

Tabela com os coeficientes das variáveis, permitindo interpretação do peso de cada variável na decisão do modelo.

⚠️ Observação
O dataset utilizado possui desbalanceamento de classes, o que impacta diretamente nas métricas — ajustes como balanceamento ou outras abordagens podem ser considerados para melhorias.

Projeto desenvolvido por Gláuber Lopes Bomtempo
