# Analise de texto com Language Studio 

## Descrição do Projeto
Este projeto foi desenvolvido como parte do curso oferecido pela Digital Innovation One (DIO) sobre Análise de Sentimentos com Language Studio no Azure AI

## Objetivo
O objetivo principal deste projeto é explorar os recursos do language studio para analisar algumas sentenças de texto. Podendo identificar frases-chave, determinar quais avaliações são positivas e quais são negativas ou analisar o texto da avaliação em busca de menções a entidades conhecidas, como locais ou pessoas. Os textos apresentados nos testes servem como exemplos simulados de respostas obtidas em uma pesquisa de satisfação, todas referentes ao portal da Digital Innovation One (DIO).

## Tecnologias Utilizadas
- Azure AI Language 

### Azure AI Language
- O Azure AI Language é um serviço gerenciado para desenvolver aplicações de processamento de linguagem natural. Ele permite identificar termos e frases-chave, analisar sentimentos, resumir textos e construir interfaces conversacionais. 

## Testes Realizado:
* Os testes foram realizados com base em 4 (quatro) princípios avaliadores de respostas: Positivas, Negativas, Neutras e Mistas. Abaixo estão os Outputs(Saidas/Analises) com base nas respostas de satisfação.  
  
### Analise de texto Positivo 😁
> O texto de entrada abaixo é uma avaliação com 98% positiva, 1% Neutro e 1% Negativa. O documento foi classificado como Positivo.

**Document sentiment**

<img width="300" alt="image" src="https://github.com/MaikRodriguess/dio-azure-language-project/assets/69226200/4e510b29-d35a-4fca-8cbf-4cc492d6700d">

Fonte: Azure AI Language 

**Sentence 1**

<img width="500" alt="image" src="https://github.com/MaikRodriguess/dio-azure-language-project/assets/69226200/ced38bd0-53c0-47bc-a28d-7295cb86898d">

Fonte: Azure AI Language 

**Sentence 2**

<img width="500" alt="image" src="https://github.com/MaikRodriguess/dio-azure-language-project/assets/69226200/ab7f0556-ca34-45ec-933d-6f9a1ecb4042">

Fonte: Azure AI Language 

### Analise de texto Negativo 😒
> O texto de entrada abaixo é uma avaliação com 0% positiva, 0% Neutro e 100% Negativa. O documento foi classificado como Negativo.

**Document sentiment**

<img width="300" alt="image" src="https://github.com/MaikRodriguess/dio-azure-language-project/assets/69226200/7136f5ec-8622-4acc-8511-246da64e5551">

Fonte: Azure AI Language 

**Sentence 1**

<img width="500" alt="image" src="https://github.com/MaikRodriguess/dio-azure-language-project/assets/69226200/b142d301-ab60-44c9-8111-a73238f59fd9">

Fonte: Azure AI Language 

**Sentence 2**

<img width="500" alt="image" src="https://github.com/MaikRodriguess/dio-azure-language-project/assets/69226200/d1195c78-771c-4999-988d-0a35e4d9016a">

### Analise de texto Mista 🤔
> O texto de entrada abaixo é uma avaliação com 25% positiva, 14% Neutro e 61% Negativa. O documento foi classificado como Misto.

**Document sentiment**

<img width="300" alt="image" src="https://github.com/MaikRodriguess/dio-azure-language-project/assets/69226200/5f682ea8-f8af-4b57-bee9-b69b12c2aaa2">

Fonte: Azure AI Language 

**Sentence 1**

<img width="500" alt="image" src="https://github.com/MaikRodriguess/dio-azure-language-project/assets/69226200/335e1881-e4e2-452f-944c-7eceaa35c1cb">

Fonte: Azure AI Language 

**Sentence 2**

<img width="500" alt="image" src="https://github.com/MaikRodriguess/dio-azure-language-project/assets/69226200/96117cc0-906a-48d8-a3c7-7d72e1f131bc">

Fonte: Azure AI Language 

**Sentence 3**

<img width="500" alt="image" src="https://github.com/MaikRodriguess/dio-azure-language-project/assets/69226200/f06f32b3-bc94-43c7-8e1b-4a9e40c43599">

Fonte: Azure AI Language 

**Fontes:**
- https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html
