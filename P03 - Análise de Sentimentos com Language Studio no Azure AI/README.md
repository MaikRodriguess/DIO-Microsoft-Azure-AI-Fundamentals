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

<img width="300" alt="Captura de tela 2024-02-13 123935" src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/assets/69226200/ab05c044-ce55-4c11-a817-c8033b7ae55f">

Fonte: Azure AI Language 

**Sentence 1**

<img width="500" alt="Captura de tela 2024-02-13 125810" src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/assets/69226200/9709660b-2ad6-4ebf-8c03-3692a198022c">


Fonte: Azure AI Language 

**Sentence 2**


<img width="500" alt="Captura de tela 2024-02-13 130201" src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/assets/69226200/92548971-5901-401c-9967-4eca1b9b3d52">

Fonte: Azure AI Language 

### Analise de texto Negativo 😒
> O texto de entrada abaixo é uma avaliação com 0% positiva, 0% Neutro e 100% Negativa. O documento foi classificado como Negativo.

**Document sentiment**

<img width="300" alt="Captura de tela 2024-02-13 130506" src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/assets/69226200/fb91ad9a-016f-4674-9969-0a9fe61bdd79">


Fonte: Azure AI Language 

**Sentence 1**

<img width="500" alt="Captura de tela 2024-02-13 130532" src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/assets/69226200/656d3f45-f88d-45c9-a4ce-ff7d4a513140">


Fonte: Azure AI Language 

**Sentence 2**

<img width="500" alt="Captura de tela 2024-02-13 130613" src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/assets/69226200/4e74f8cc-e1ab-44af-a50b-76e87abee7a9">


### Analise de texto Mista 🤔
> O texto de entrada abaixo é uma avaliação com 25% positiva, 14% Neutro e 61% Negativa. O documento foi classificado como Misto.

**Document sentiment**

<img width="300" alt="Captura de tela 2024-02-13 131811" src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/assets/69226200/550987a7-7345-4b9b-84cd-02d6d177d23e">


Fonte: Azure AI Language 

**Sentence 1**

<img width="500" alt="Captura de tela 2024-02-13 131905" src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/assets/69226200/56e07de6-4fad-4c06-b269-9084fdffcd98">


Fonte: Azure AI Language 

**Sentence 2**

<img width="500" alt="Captura de tela 2024-02-13 131940" src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/assets/69226200/478e6e1a-20b7-4e86-b6be-9a411ca346ea">

Fonte: Azure AI Language 

**Sentence 3**

<img width="500" alt="Captura de tela 2024-02-13 132015" src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/assets/69226200/dc31617a-5e83-46be-9f43-17aeb911aaa2">

Fonte: Azure AI Language 

**Fontes:**
- https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html
