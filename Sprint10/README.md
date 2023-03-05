
# Projeto de Previsão de Recuperação de Ouro

Este projeto tem como objetivo construir um modelo de previsão de recuperação de ouro a partir de minério bruto, utilizando dados fornecidos pelo cliente. O projeto é dividido em três partes principais: preparação de dados, análise de dados e construção do modelo.

## Preparação dos dados

Nesta etapa, foram realizadas as seguintes tarefas:

- Abertura dos arquivos e estudo dos dados;
- Verificação da exatidão dos dados;
- Análise das características não disponíveis no conjunto de teste;
- Pré-processamento de dados.

## Análise de Dados

Nesta etapa, foram realizadas as seguintes tarefas:

- Observação da mudança da concentração de metais (Au, Ag, Pb) dependendo do estágio de purificação;
- Comparação das distribuições de tamanho de partícula de minério no conjunto de treinamento e no conjunto de teste;
- Consideração das concentrações totais de todas as substâncias em diferentes estágios.

## Construção do Modelo

Nesta etapa, foram realizadas as seguintes tarefas:

- Criação de uma função para calcular o valor final sMAPE;
- Treinamento de modelos diferentes;
- Avaliação dos modelos usando validação cruzada;
- Escolha do melhor modelo e teste usando a amostra de teste.

## Métricas de Avaliação
Foram utilizadas as seguintes fórmulas para métricas de avaliação:

- Recuperação de Ouro: MAE (Mean Absolute Error);
- sMAPE (symmetric mean absolute percentage error)

## Stack utilizada

O projeto foi desenvolvido utilizando a linguagem Python e as seguintes bibliotecas:

- Pandas
- Numpy
- Seaborn
- matplotlib
- sklearn

## Resultados

O valor de SMAPE calculado neste projeto é uma medida de desempenho do modelo utilizado para prever a recuperação de ouro. Esse valor indica o quão precisas foram as previsões em relação aos valores reais. Quanto menor o valor de SMAPE, melhor é o desempenho do modelo. Se o valor calculado for alto, pode ser necessário realizar ajustes no modelo ou selecionar características diferentes para melhorar a precisão das previsões. 

Pela análise realizada e o valor de SMAPE_FINAL obtido, concluímos que este projeto foi bem sucedido em prever a recuperação de ouro utilizando técnicas de aprendizado de máquina.

## Autores

- [@evaristomat](https://www.github.com/evaristomat)

