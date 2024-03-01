<h1>
    <a href="https://www.dio.me/">
     <img align="center" width="60px" src="https://hermes.dio.me/lab_projects/badges/619af8f8-d138-4e40-9d48-fec7b318e44d.png"></a>
    <span> 
Azure Cognitive Search: Utilizando AI Search para indexação e consulta de Dados</span>
</h1>

## Descrição do Projeto

Este projeto foi desenvolvido como parte do curso oferecido pela Digital Innovation One (DIO) em parceria com a Microsoft sobre Análise de Sentimentos com Language Studio no Azure AI
 
 Objetivo:

O objetivo principal deste projeto é explorar os recursos do Azure AI Search para explorar índices, criando uma solução de mineração de conhecimento para facilitar na busca por insights. 

## Tecnologia Utilizadas
- Azure AI Search
- Azure AI services
- Storage Account

[Documentação](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html)

## Passo 1: Criando recurso do Asure AI Search:     


<img align="right" src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/assets/69226200/91203ef2-8fbe-4a53-921d-cf95801c8a92" width=""> 


## Passo 2: Criando recurso do Azure AI services:      

<img align="right" src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/assets/69226200/54bfa119-dd2c-401b-b059-50c9d89abc13" width=""/> ... 

## Passo 3: Criando o storage:      

<img align="right" src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/assets/69226200/04881aa3-5b2a-44f0-8d60-4b00db8b7e99"/> ... 

## Passo 3.1: Permitindo acesso anônimo ao Blob:      
1. Na conta de Armazenamento do Azure que você criou, no painel de menu esquerdo, selecione "Configuration"
2. Altere a a configuração de "Allow Blob anonymous access" para "Enable".


<img align="right" src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/assets/69226200/ed208d9d-5764-4041-b5b7-d7fed2a96115" width=""/> ... 


## Passo 4: Criando o Container:      

Em "Azure Storage" criado, navegue até "Containers" 

<img align="right" src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/assets/69226200/c59c78a0-a8e4-4ce9-a14f-ef529954dc99" width=""/> ...   

No Container criado, faça Upload dos arquivos base
<img align="right" src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/assets/69226200/47d7e432-de43-43db-9176-36f2058010ef" width=""/> ...  

## Passo 5: Importação e indexação dados para o AI SEARCH:      

É preciso importar os dados que foram inseridos e configurados STORAGE, volte para o AI SEARCH e siga os passos abaixo:

<img align="right" src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/assets/69226200/0c9e20b2-5df0-4107-ac94-5707b30b633e" width=""/> ... 

Depois da validação, é preciso fazer algumas configurações. Siga o passo a passo abaixo:

<img  src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/blob/main/P04%20-%20Azure%20Cognitive%20Search%20Utilizando%20AI%20Search%20para%20indexa%C3%A7%C3%A3o%20e%20consulta%20de%20Dados/images/(1).png" width="700">
<img  src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/blob/main/P04%20-%20Azure%20Cognitive%20Search%20Utilizando%20AI%20Search%20para%20indexa%C3%A7%C3%A3o%20e%20consulta%20de%20Dados/images/(2).png" width="700">
<img  src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/blob/main/P04%20-%20Azure%20Cognitive%20Search%20Utilizando%20AI%20Search%20para%20indexa%C3%A7%C3%A3o%20e%20consulta%20de%20Dados/images/(3).png" width="700">
<img  src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/blob/main/P04%20-%20Azure%20Cognitive%20Search%20Utilizando%20AI%20Search%20para%20indexa%C3%A7%C3%A3o%20e%20consulta%20de%20Dados/images/(4).png" width="700">

Clique em "Save enrichments to a knowledge store" e se aparecer a mensagem de erro, clique em "Choose an existing connection" e siga o processo:

<img  src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/blob/main/P04%20-%20Azure%20Cognitive%20Search%20Utilizando%20AI%20Search%20para%20indexa%C3%A7%C3%A3o%20e%20consulta%20de%20Dados/images/(5).png" width="700">

Selecione o "Storage" Criado:

<img  src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/blob/main/P04%20-%20Azure%20Cognitive%20Search%20Utilizando%20AI%20Search%20para%20indexa%C3%A7%C3%A3o%20e%20consulta%20de%20Dados/images/(6).png" width="700">

Crie um Container, escolha o nome e o nível de acesso como "Private"

<img  src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/blob/main/P04%20-%20Azure%20Cognitive%20Search%20Utilizando%20AI%20Search%20para%20indexa%C3%A7%C3%A3o%20e%20consulta%20de%20Dados/images/(7).png" width="500">

<img  src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/blob/main/P04%20-%20Azure%20Cognitive%20Search%20Utilizando%20AI%20Search%20para%20indexa%C3%A7%C3%A3o%20e%20consulta%20de%20Dados/images/(8).png" width="500">

Selecione o container criado:

<img  src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/blob/main/P04%20-%20Azure%20Cognitive%20Search%20Utilizando%20AI%20Search%20para%20indexa%C3%A7%C3%A3o%20e%20consulta%20de%20Dados/images/(9).png" width="700">

Continue a configuração, e marque as opções abaixo:

<img  src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/blob/main/P04%20-%20Azure%20Cognitive%20Search%20Utilizando%20AI%20Search%20para%20indexa%C3%A7%C3%A3o%20e%20consulta%20de%20Dados/images/(10).png" width="700">

<img  src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/blob/main/P04%20-%20Azure%20Cognitive%20Search%20Utilizando%20AI%20Search%20para%20indexa%C3%A7%C3%A3o%20e%20consulta%20de%20Dados/images/(11).png" width="700">

<img  src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/blob/main/P04%20-%20Azure%20Cognitive%20Search%20Utilizando%20AI%20Search%20para%20indexa%C3%A7%C3%A3o%20e%20consulta%20de%20Dados/images/(12).png" width="700">

<img  src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/blob/main/P04%20-%20Azure%20Cognitive%20Search%20Utilizando%20AI%20Search%20para%20indexa%C3%A7%C3%A3o%20e%20consulta%20de%20Dados/images/(13).png" width="700">

No "Azure Search Service" em "Indexers" entre no index criado:

<img  src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/blob/main/P04%20-%20Azure%20Cognitive%20Search%20Utilizando%20AI%20Search%20para%20indexa%C3%A7%C3%A3o%20e%20consulta%20de%20Dados/images/(14).png" width="700">

<img  src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/blob/main/P04%20-%20Azure%20Cognitive%20Search%20Utilizando%20AI%20Search%20para%20indexa%C3%A7%C3%A3o%20e%20consulta%20de%20Dados/images/(15).png" width="700">

Depois de 1 minuto, clique em "Refresh" para atualizar:

<img  src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/blob/main/P04%20-%20Azure%20Cognitive%20Search%20Utilizando%20AI%20Search%20para%20indexa%C3%A7%C3%A3o%20e%20consulta%20de%20Dados/images/(16).png" width="700">


## Passo 7: Consultando o índice:   

Depois de todas as configurações realizadas, iremos realizar pesquisas com base em tudo que foi indexado, e iremos ultilizar alguns comandos para isso: 

No "Search Service" Criado, vá em "Search explore":

<img  src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/blob/main/P04%20-%20Azure%20Cognitive%20Search%20Utilizando%20AI%20Search%20para%20indexa%C3%A7%C3%A3o%20e%20consulta%20de%20Dados/images/(17).png" width="700">

Vamos fazer algumas pesquisas com base em scripts JSON:

<img  src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/blob/main/P04%20-%20Azure%20Cognitive%20Search%20Utilizando%20AI%20Search%20para%20indexa%C3%A7%C3%A3o%20e%20consulta%20de%20Dados/images/(18).png" width="700">

```
# A consulta pesquisa todos os documentos no índice e filtra revisões com localização em Chicago
{
 "search": "locations:'Chicago'",
 "count": true 
} 
```
<img  src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/blob/main/P04%20-%20Azure%20Cognitive%20Search%20Utilizando%20AI%20Search%20para%20indexa%C3%A7%C3%A3o%20e%20consulta%20de%20Dados/images/(19).png" width="700">

```
# A consulta pesquisa todos os documentos no índice e filtra revisões com sentimento negativo
{
 "search": "sentiment:'negative'",
 "count": true
} 
```

<img  src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/blob/main/P04%20-%20Azure%20Cognitive%20Search%20Utilizando%20AI%20Search%20para%20indexa%C3%A7%C3%A3o%20e%20consulta%20de%20Dados/images/(20).png" width="700">


## Observações finais:      

Eeste projeto destacou a eficácia da plataforma Azure AI na posibilidade de análise de grandes conjuntos de dados. Esta tecnologia demonstrou ser uma ferramenta poderosa para a extração de insights acionáveis, evidenciando o potencial do Azure AI na transformação de dados brutos em informações valiosas.



