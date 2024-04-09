# **Sistema de Recomendação de Avaliações de Livros**

## Objetivo:

Este projeto tem como objetivo desenvolver um sistema de recomendação capaz de prever avaliações de livros com base nas preferências dos usuários, fornecendo recomendações personalizadas.

## Descrição:

Utilizando técnicas de filtragem colaborativa, este sistema constrói um modelo de rede neural com TensorFlow e Keras para prever as avaliações de livros. O modelo aprende a partir de avaliações anteriores dos usuários, possibilitando recomendações precisas e relevantes.

## **Resumo do Projeto:**

- **Pré-processamento de Dados:** Os dados são limpos e processados, tratando valores ausentes, codificando variáveis categóricas e unindo conjuntos de dados relevantes.

- **Arquitetura do Modelo:** Uma rede neural é projetada com camadas de incorporação para representar usuários e livros, seguidas de camadas densas com dropout para regularização.

- **Treinamento do Modelo:** Os dados são divididos em conjuntos de treinamento e teste, e o modelo é treinado com a função de perda de erro quadrático médio e o otimizador Adam.

- **Avaliação do Modelo:** O desempenho do modelo é avaliado no conjunto de teste, medindo a perda de teste para determinar a precisão.

- **Geração de Recomendações:** Uma função é desenvolvida para gerar recomendações de livros para usuários específicos, prevendo as avaliações de todos os livros e classificando as previsões para identificar as principais recomendações.

## Dependências:

- pandas
- numpy
- scikit-learn
- TensorFlow
- Keras

Este projeto utiliza dados disponíveis publicamente no Kaggle. Você pode encontrar mais informações sobre o conjunto de dados [aqui]([https://www.kaggle.com](https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset)).

## Contribuição
Contribuições são bem-vindas! Por favor, sinta-se à vontade para abrir um problema ou enviar um pull request.

