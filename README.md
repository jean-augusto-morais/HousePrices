# HousePrices

# Previsão de Preços de Casas

Este repositório contém um projeto de machine learning para prever os preços de casas com base em um conjunto de dados de características das propriedades. O projeto utiliza algoritmos de aprendizado supervisionado para treinar modelos que podem prever o preço de uma casa com base em várias características, como tamanho, localização, número de quartos, entre outras.

## Sumário

- [Introdução](#introdução)
- [Conjunto de Dados](#conjunto-de-dados)
- [Pré-processamento](#pré-processamento)
- [Modelagem](#modelagem)
- [Avaliação](#avaliação)


## Introdução

Este projeto foi desenvolvido para demonstrar o uso de técnicas de aprendizado de máquina na previsão de preços de imóveis. O objetivo é construir um modelo preditivo que, dado um conjunto de características de uma casa, possa estimar seu preço de venda com precisão.

## Conjunto de Dados

Os dados foram obtidos do [https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview] e foram tratados para remover inconsistências e outliers antes da modelagem.

## Pré-processamento

O pré-processamento dos dados inclui as seguintes etapas:

1. **Tratamento de valores ausentes**: Substituição de valores ausentes por medianas ou modos das variáveis.
2. **Normalização/Escala**: Normalização das características para que todas estejam na mesma escala.
3. **Codificação de variáveis categóricas**: Transformação de variáveis categóricas em variáveis numéricas usando one-hot encoding.
4. **Divisão dos dados**: Divisão dos dados em conjuntos de treino e teste.

## Modelagem

Foram utilizados vários algoritmos de machine learning para treinar os modelos preditivos, incluindo:

- **Regressão Linear**
- **Árvores de Decisão**
- **Random Forest**


Cada modelo foi ajustado e avaliado para determinar o melhor desempenho na previsão de preços.

## Avaliação

Os modelos foram avaliados utilizando métricas como:

- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**
- **R² (Coeficiente de Determinação)**

Os resultados dessas métricas são apresentados e comparados para selecionar o melhor modelo.
