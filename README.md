# Previsão de Preço de Casa com Regressão Linear Simples

## Descrição do Projeto

Este projeto tem como objetivo prever o preço de uma casa com base em seu tamanho em metros quadrados utilizando Regressão Linear Simples. Foi utilizado um conjunto de dados simulado com as variáveis **Tamanho** e **Preço** para treinar e avaliar o modelo.

## Objetivos
- Criar um dataset simulado para análise.
- Treinar um modelo de Regressão Linear Simples para prever o preço das casas.
- Avaliar a performance do modelo utilizando **Erro Quadrático Médio (MSE)** e **Coeficiente de Determinação (R²)**.
- Visualizar os resultados e a relação entre o tamanho da casa e o preço previsto.

## Tecnologias Utilizadas
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Numpy

## Metodologia

1. **Geração dos Dados**: Criamos um dataset simulado com duas colunas: **Tamanho** (em metros quadrados) e **Preço** (em moeda local).
2. **Divisão dos Dados**: O dataset foi dividido em dois subconjuntos: **treino** (para ajuste do modelo) e **teste** (para validação).
3. **Treinamento do Modelo**: Um modelo de Regressão Linear Simples foi ajustado utilizando os dados de treino.
4. **Avaliação do Modelo**: A performance do modelo foi avaliada com as métricas **MSE** (Erro Quadrático Médio) e **R²** (Coeficiente de Determinação).
5. **Visualização dos Resultados**: A relação entre **Tamanho** e **Preço** foi visualizada em um gráfico, juntamente com a linha de regressão gerada pelo modelo.

## Resultados

- O modelo conseguiu prever o preço das casas com base no tamanho com uma boa precisão.
- A avaliação com **MSE** e **R²** indicou o desempenho adequado do modelo, com uma linha de regressão que reflete a tendência entre as variáveis.
- A visualização gráfica mostrou a correspondência entre os preços reais e os preços previstos pelo modelo.
