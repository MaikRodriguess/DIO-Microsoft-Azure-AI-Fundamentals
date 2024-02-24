
# Previsão com Azure Machine Learning 
<p align="center">
 <img src="https://github.com/MaikRodriguess/dio-azureml-project/assets/69226200/027c9dc4-536a-4fef-8902-01e43e112675" width="150" > 
</p>


## Introdução
Este projeto é uma aplicação prática de aprendizado de máquina que utiliza um conjunto de dados históricos de aluguel de bicicletas para treinar um modelo preditivo. 

## Objetivo 
O objetivo principal é prever o número de aluguéis de bicicletas esperados em um determinado dia, levando em consideração características sazonais e meteorológicas


 **Fonte**: [Microsoft Learn](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html#use-automated-machine-learning-to-train-a-model).



## Processo

 1. **Criação do Modelo de Previsão**: Utilizando o Azure Machine Learning, um modelo de previsão foi criado. Este modelo foi treinado com um conjunto de dados específico para garantir a precisão das previsões.

### Predicted vs. True
<img width="450" alt="image" src="https://github.com/MaikRodriguess/dio-azureml-project/assets/69226200/4e2fd82a-8b7a-43f3-8dda-21c84c3b984f">
  
O gráfico compara os valores previstos com os valores verdadeiros.

Fonte: Azure machine Learn

### Residuals Histogram
<img width="450" alt="image" src="https://github.com/MaikRodriguess/dio-azureml-project/assets/69226200/4163335f-b666-48f0-8bb6-f702fbd8a83b">

O gráfico de resíduos mostra os resíduos (as diferenças entre os valores previstos e reais) como um histograma.

Fonte: Azure machine Learn


 2. **Configuração dos Pontos de Extremidade(endpoint)**: Após a criação do modelo, os pontos de extremidade foram configurados. Isso permite que o modelo seja acessado e utilizado para previsões.

### JSON Endpoint 
<img width="250" alt="image" src="https://github.com/MaikRodriguess/dio-azureml-project/assets/69226200/6ad9c989-91eb-48c9-99ec-e39b312094db">


Dados de entrada para testar o endpoint 

Fonte: Azure machine Learn

### JSON Results 
<img width="400" alt="image" src="https://github.com/MaikRodriguess/dio-azureml-project/assets/69226200/546c9f5d-3c00-43d2-96c6-8add25fd870e">




O modelo prevê o número de alugueis de bicicletas esperados num determinado dia, com base em características sazonais e meteorológicas .

Fonte: Azure machine Learn
