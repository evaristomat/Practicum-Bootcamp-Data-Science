
# Projeto de Análise Preditiva do Beta Bank

Este é um projeto de análise preditiva que visa prever se um cliente do Beta Bank deixará o banco em breve. O objetivo é construir um modelo com o valor máximo possível de F1, uma métrica que combina precisão e recall.

## Preparação dos dados

Antes de treinar o modelo, foi realizada uma preparação dos dados, que incluiu as seguintes etapas:

- Análise exploratória dos dados
- Tratamento de valores ausentes e outliers
- Codificação dos dados categóricos
- Normalização dos dados numéricos
- Separação dos dados em conjuntos de treinamento, validação e teste

## Treinamento do modelo

Para treinar o modelo, foram testadas diferentes abordagens, incluindo a Regressão Logística e o Random Forest. Também foram utilizadas técnicas de correção de desequilíbrio de classe, como oversampling e undersampling. Os hiperparâmetros dos modelos foram ajustados usando Grid Search e Random Search.

## Avaliação do modelo

O desempenho do modelo foi avaliado usando as métricas F1 e AUC-ROC. O valor F1 foi a métrica principal, uma vez que é importante equilibrar a precisão e o recall. A AUC-ROC foi utilizada para medir a capacidade do modelo de distinguir entre as classes positivas e negativas.

## Stack utilizada

O projeto foi desenvolvido utilizando a linguagem Python e as seguintes bibliotecas:

- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

## Resultados

A partir do projeto apresentado, foi construído um modelo de classificação para prever se um cliente de um banco deixará o banco em breve. O conjunto de dados utilizado foi o conjunto "Churn", que contém informações sobre o comportamento passado dos clientes e as rescisões de contratos com o banco. Foi realizada uma análise exploratória dos dados, onde foram verificados os valores ausentes, as distribuições das variáveis numéricas e categóricas e a correlação entre as variáveis e a classe alvo. Além disso, o conjunto de dados foi dividido em treino e teste e os modelos de Logistic Regression, Decision Tree e Random Forest foram treinados e otimizados usando o método de validação cruzada GridSearchCV. O modelo foi avaliado usando as métricas F1 e AUC-ROC. Os resultados obtidos foram satisfatórios, com um valor de F1 de 0,63 e uma AUC-ROC de 0,86. Em conclusão, o modelo construído foi capaz de prever com uma boa acurácia se um cliente deixará o banco em breve, sendo um recurso valioso para a empresa Beta Bank em sua estratégia de retenção de clientes.

## Autores

- [@evaristomat](https://www.github.com/evaristomat)

