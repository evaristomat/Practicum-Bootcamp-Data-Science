
# Oleobrás Mining Company - Projeto de Seleção de Locais para Novos Poços de Petróleo

Este projeto tem como objetivo auxiliar a empresa Oleobrás na escolha do melhor local para a perfuração de novos poços de petróleo, com base em dados coletados sobre amostras de petróleo em três regiões diferentes.

## Preparação dos dados

- Coleta e preparação dos dados;
- Treinamento e teste do modelo para cada região;
- Preparação para o cálculo de lucro;
- Cálculo do lucro para um conjunto de poços de petróleo selecionados e predições do modelo;
- Cálculo de riscos e lucro para cada região, utilizando a técnica de bootstrapping com 1000 amostras.

## Stack utilizada

O projeto foi desenvolvido utilizando a linguagem Python e as seguintes bibliotecas:

- Pandas
- Numpy
- Seaborn

## Resultados

O projeto Oleobrás teve como objetivo encontrar a melhor região para a construção de um novo poço de petróleo pela empresa. Para isso, foram coletados os parâmetros de poços de petróleo em três regiões diferentes e um modelo de regressão linear foi treinado para predizer o volume de reservas em novos poços. A região com o maior lucro total foi escolhida com base nos poços de petróleo selecionados. A técnica de Bootstrapping também foi utilizada para analisar o lucro potencial e os riscos associados. 

A partir da análise dos resultados obtidos no projeto, podemos concluir que o modelo de regressão linear utilizado apresentou um bom desempenho na região 1, um desempenho mediano na região 0 e uma baixa capacidade de previsão na região 2. Isso foi verificado pelas métricas de avaliação MSE e R², que medem o erro quadrático médio e a capacidade de explicação dos dados, respectivamente.

Após treinar e validar o modelo, analisamos os resultados e chegamos à conclusão de que a região 1 é a mais promissora em termos de margem de lucro e em termos de risco de prejuízo é a menor.

## Autores

- [@evaristomat](https://www.github.com/evaristomat)

