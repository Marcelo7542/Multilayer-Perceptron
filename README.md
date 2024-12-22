English description below


Multilayer Perceptron

Este repositório apresenta a minha implementação e análise de algoritmos de classificação e regressão, com ênfase em Redes Neurais Artificiais (MLP), Perceptron (incluindo uma versão manual) 
e outros classificadores baseados em gradiente. 

Os principais conceitos e resultados incluem a utilização dos datasets Iris e California Housing, abordando diferentes técnicas de treinamento, 
validação e métricas de desempenho.

Principais Abordagens e Resultados

1. Classificação com Perceptron e SGDClassifier

Dataset Iris: 

Utilizei este conjunto de dados para classificar se uma amostra pertence ou não a uma determinada classe.

Perceptron: 

Treinamento supervisionado com atualização de pesos utilizando a função de ativação degrau.

SGDClassifier: 

Implementação baseada em gradiente estocástico com penalização configurável.

2. Implementação Manual de Funções de Ativação

Implementei funções como sigmoid, tangente hiperbólica (tanh), ReLU, e degrau para analisar o impacto na convergência do Perceptron.

Predições personalizadas utilizando diferentes funções de ativação foram realizadas para verificar os resultados.

3. Regressão com MLPRegressor

Dataset California Housing: 

Utilizei este conjunto de dados para predizer valores imobiliários com base em atributos como localização, número de quartos, entre outros.

Pipeline de Processamento: 

Inclui normalização dos dados com StandardScaler e uso de um MLP com arquitetura de três camadas escondidas.

Avaliação de Desempenho: 

Métrica utilizada foi o Root Mean Squared Error (RMSE), com resultados satisfatórios na validação.

4. Classificação com MLPClassifier

Dataset Iris: 

Realizei a predição de classes de flores utilizando uma arquitetura similar à regressão.


Resultados Obtidos

Classificação Iris: 

Modelos baseados em Perceptron e MLP alcançaram altos índices de acurácia.

Regressão California Housing: 

O MLPRegressor apresentou resultados precisos, com RMSE abaixo de 0.6.

Funções de Ativação: 

Testes com diferentes funções destacaram o impacto na convergência e desempenho dos modelos.

Métrica de Avaliação: 

Acurácia do modelo foi superior a 93% na validação.





Multilayer Perceptron

This repository showcases my implementation and analysis of classification and regression algorithms, with a focus on Artificial Neural Networks (MLP), 
Perceptron (including a manual version), and other gradient-based classifiers. 

The main concepts and results include the use of the Iris and California Housing datasets, covering various training techniques, validation strategies, and performance metrics.

Key Approaches and Results

1. Classification with Perceptron and SGDClassifier
   
Iris Dataset: 

I used this dataset to classify whether a sample belongs to a specific class.

Perceptron: 

Supervised training with weight updates using the step activation function.

SGDClassifier: 

Implementation based on stochastic gradient descent with configurable regularization.

2. Manual Implementation of Activation Functions

I implemented functions such as sigmoid, hyperbolic tangent (tanh), ReLU, and step to analyze their impact on Perceptron convergence.

Custom predictions using different activation functions were performed to verify the results.

3. Regression with MLPRegressor

California Housing Dataset: 

I used this dataset to predict housing values based on attributes such as location, the number of rooms, and more.

Processing Pipeline: 

Includes data normalization with StandardScaler and an MLP with a three-hidden-layer architecture.

Performance Evaluation: 

The metric used was Root Mean Squared Error (RMSE), with satisfactory results in validation.

4. Classification with MLPClassifier

Iris Dataset: 

I predicted flower classes using an architecture similar to that used for regression.

Evaluation Metric: 

The model's accuracy exceeded 93% in validation.
