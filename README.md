# Projeto Titanic: Análise e Modelagem de Dados

Este é um projeto de análise e modelagem de dados do Titanic, com o objetivo de prever quais passageiros sobreviveram ao naufrágio. O projeto é baseado em um famoso dataset disponível no Kaggle, contendo informações sobre passageiros do Titanic, como idade, sexo, classe da cabine, entre outras.

## Objetivo

O objetivo deste projeto é criar um modelo preditivo que possa prever com precisão quais passageiros sobreviveriam ao naufrágio do Titanic, utilizando técnicas de análise e modelagem de dados.

## Etapas do Projeto

O projeto será dividido em três etapas principais:

1. **Análise Exploratória dos Dados:** Nesta etapa, vamos explorar os dados, identificando características dos passageiros e relações entre as variáveis. Isso nos ajudará a entender melhor os dados e identificar possíveis problemas que possam afetar a modelagem.

2. **Pré-processamento dos Dados:** Na etapa de pré-processamento, iremos tratar os dados faltantes, transformar variáveis categóricas em numéricas e criar novas features que possam melhorar o desempenho dos modelos preditivos.

3. **Modelagem:** Na etapa de modelagem, construiremos diferentes modelos e avaliaremos seus desempenhos a partir das métricas. Isso nos permitirá selecionar o melhor modelo para prever a sobrevivência dos passageiros.

## Importação de Bibliotecas e Dados

Neste projeto, utilizaremos diversas bibliotecas Python, incluindo Pandas, NumPy, Matplotlib, Seaborn e Scikit-Learn para manipulação de dados, visualização e modelagem. Também importaremos o conjunto de dados do Titanic e os dados de teste. 

## Análise Exploratória dos Dados

Na etapa de análise exploratória dos dados, começamos por verificar as dimensões, tipos de dados e valores faltantes nos conjuntos de treinamento e teste. Analisamos as colunas disponíveis, como PassengerId, Survived, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin e Embarked, e identificamos a presença de valores nulos em algumas colunas.

Além disso, realizamos análises estatísticas descritivas para entender a distribuição das variáveis numéricas, como idade, classe e tarifa. Também exploramos gráficos para visualizar a distribuição de gênero, a relação entre a classe e a sobrevivência, o porto de embarque e a idade dos sobreviventes.

## Pré-processamento dos Dados

Na etapa de pré-processamento, tratamos os valores faltantes preenchendo-os com médias ou modas apropriadas. Removemos colunas que não são relevantes para a análise, como "Cabin" e "Ticket". Além disso, transformamos variáveis categóricas em numéricas, como o gênero e o porto de embarque.

Também extraímos os títulos dos nomes dos passageiros, calculamos a média de idade por título e criamos uma nova variável para representar o tamanho da família a bordo.

## Modelagem

Na etapa de modelagem, construímos diversos modelos de machine learning, como Random Forest, K-Nearest Neighbors (KNN) e Decision Tree, para prever a sobrevivência dos passageiros. Utilizamos técnicas de seleção de atributos e validação cruzada para avaliar o desempenho dos modelos.

## Matriz de Correlação

Realizamos uma análise de correlação entre as variáveis numéricas para entender as relações entre elas. Isso nos ajuda a identificar quais variáveis estão mais fortemente correlacionadas com a sobrevivência.

## Conclusão

Este projeto tem como objetivo explorar e modelar os dados do Titanic para prever a sobrevivência dos passageiros. Ao final, teremos um modelo preditivo capaz de fazer previsões com base nas informações disponíveis.
