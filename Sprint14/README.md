# Film Junky Union - Classificação de Resenhas de Filmes
Este projeto tem como objetivo criar um modelo para classificar resenhas de filmes como positivas ou negativas, utilizando um conjunto de dados de resenhas do IMDB com rotulagem de polaridade. A Film Junky Union é uma nova comunidade para entusiastas de filmes clássicos e está desenvolvendo esse sistema para filtrar e categorizar resenhas de filmes.

## Conjunto de Dados
O conjunto de dados utilizado neste projeto consiste em 50.000 resenhas de filmes do IMDB, dividido igualmente em um conjunto de treinamento e um conjunto de teste. Cada resenha é rotulada com uma polaridade: 0 para negativa e 1 para positiva.

## Pré-processamento de Dados
O pré-processamento de dados envolveu a remoção de stop words, pontuações, tags HTML e caracteres especiais. As palavras foram transformadas em minúsculas e foi realizada a lematização das palavras para reduzir as diferentes variações de uma mesma palavra.

## Análise Exploratória de Dados
A análise exploratória de dados revelou um desequilíbrio na distribuição de classes no conjunto de dados. Das 50.000 resenhas, 25.000 são positivas e 25.000 são negativas. Esse desequilíbrio pode impactar na performance do modelo, especialmente em relação à classificação da classe minoritária.

## Treinamento de Modelos
Foram treinados três modelos diferentes para o conjunto de dados de treinamento:

- Regressão Logística
- Random Forest
- Rede Neural
- Teste de Modelos
- Os modelos foram testados para o conjunto de dados de teste e avaliados com base na métrica F1, que é uma média harmônica da precisão e recall.

## Classificação de Resenhas
Algumas resenhas foram escritas para testar os modelos e classificar como positivas ou negativas.

## Autores

- [@evaristomat](https://www.github.com/evaristomat)

