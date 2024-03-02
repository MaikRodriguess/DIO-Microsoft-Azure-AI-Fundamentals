

<h1>
<img  align="center" width="60px" src="https://hermes.dio.me/lab_projects/badges/87d332d0-5198-4a2f-b159-38c8c2976954.png">
Trabalhando com Machine Learning na Prática no Azure ML
</h1>

## Introdução
Este projeto é uma aplicação prática de aprendizado de máquina que utiliza um conjunto de dados históricos de aluguel de bicicletas para treinar um modelo preditivo. 

## Objetivo 
O objetivo principal é prever o número de aluguéis de bicicletas esperados em um determinado dia, levando em consideração características sazonais e meteorológicas


 **Fonte**: [Microsoft Learn](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html#use-automated-machine-learning-to-train-a-model).



## Processo

 1. **Criação do Modelo de Previsão**: Utilizando o Azure Machine Learning, um modelo de previsão foi criado. Este modelo foi treinado com um conjunto de dados específico para garantir a precisão das previsões.

### Predicted vs. True

  <img width="450" alt="Captura de tela 2024-02-01 161617" src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/assets/69226200/1e89bb3e-ddb6-4553-a8d1-45c932dd6c0a">

O gráfico compara os valores previstos com os valores verdadeiros.

Fonte: Azure machine Learn

### Residuals Histogram

<img width="450" alt="Captura de tela 2024-02-01 161458" src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/assets/69226200/fdbe4352-1095-4936-b90e-f725ba18c7af">

O gráfico de resíduos mostra os resíduos (as diferenças entre os valores previstos e reais) como um histograma.

Fonte: Azure machine Learn


 2. **Configuração dos Pontos de Extremidade(endpoint)**: Após a criação do modelo, os pontos de extremidade foram configurados. Isso permite que o modelo seja acessado e utilizado para previsões.

### JSON Endpoint 

<img width="250" alt="Captura de tela 2024-02-01 162713" src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/assets/69226200/efc75c5f-c67f-43c7-9936-a54b7717708f">

Dados de entrada referente a um dia para prever os aluguel de bicicletas.   

Fonte: Azure machine Learn

### JSON Results 

<img width="400" alt="Captura de tela 2024-02-01 164442" src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/assets/69226200/8e4a356c-0420-429c-b386-8be304a86c19">




O modelo prevê o número de alugueis de bicicletas esperados num determinado dia, com base em características sazonais e meteorológicas .

Fonte: Azure machine Learn
