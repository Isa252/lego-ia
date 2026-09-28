# PUC-SP — IA e Machine Learning: ANN com LEGO

Isabela Groke Gomes, Caroline Guimarães Campos
## Sobre a atividade

Esta atividade tem como objetivo utilizar **Inteligência Artificial e Machine Learning** para estimar os preços de conjuntos LEGO que não possuem essa informação no conjunto de dados.

Para isso, foi utilizada uma **Rede Neural Artificial (ANN)**, implementada com o `MLPRegressor` da biblioteca Scikit-Learn.

O modelo utiliza características dos conjuntos, como:

* Ano de lançamento;
* Tema e subtema;
* Categoria;
* Quantidade de peças;
* Quantidade de minifiguras;
* Idade mínima recomendada.

Os dados que possuem preço são utilizados para treinar e avaliar o modelo. Após a avaliação, a rede neural é treinada novamente com os preços conhecidos e utilizada para **preencher os preços ausentes**.

O desempenho do modelo também é avaliado para entender o quanto suas previsões se aproximam dos preços reais e quais características dos conjuntos mais influenciam os resultados.

## Tecnologias utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* MLPRegressor (ANN)

## Objetivo

Aplicar uma técnica de **Machine Learning supervisionado** para realizar a previsão de preços e completar os dados ausentes do conjunto de dados de LEGO.
