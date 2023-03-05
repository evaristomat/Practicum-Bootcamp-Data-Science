
# Taxi Corrida Maluca - Projeto de Predição de Pedidos de Táxi em Aeroportos

Este projeto tem como objetivo desenvolver um modelo de predição de quantidade de pedidos de táxi para a próxima hora em aeroportos, com base em dados históricos de pedidos coletados pela empresa Taxi Corrida Maluca.

## Dados

Os dados estão armazenados no arquivo "taxi.csv" e contêm informações sobre a quantidade de pedidos de táxi em aeroportos a cada 10 minutos, durante o período de janeiro de 2018 a agosto de 2018. Para criar uma nova amostra com uma hora de diferença, foram selecionados apenas os dados de hora cheia (00 minutos) de cada observação.

A coluna "num_orders" representa a quantidade de pedidos de táxi em cada observação.

## Análise dos Dados

Antes de treinar os modelos, foram realizadas análises exploratórias nos dados para entender melhor as características e padrões dos pedidos de táxi nos aeroportos. Foram observados, por exemplo, padrões sazonais (com aumento da demanda em determinados meses) e uma tendência de crescimento no número de pedidos ao longo do tempo.

## Modelos

Foram treinados diferentes modelos de Machine Learning para realizar a predição da quantidade de pedidos de táxi para a próxima hora. Os modelos foram avaliados com base na métrica REQM (Root Mean Squared Error), e foram utilizados diferentes hiperparâmetros para otimizar o desempenho dos modelos.

Os modelos testados foram:

- Regressão Linear
- Random Forest
- XGBoost

## Stack utilizada

O projeto foi desenvolvido utilizando a linguagem Python e as seguintes bibliotecas:

- Pandas
- Numpy
- Seaborn
- matplotlib
- sklearn

## Autores

- [@evaristomat](https://www.github.com/evaristomat)

