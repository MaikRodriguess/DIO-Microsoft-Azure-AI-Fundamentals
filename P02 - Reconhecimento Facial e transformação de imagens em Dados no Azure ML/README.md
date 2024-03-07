
<h1>
  <a href="https://www.dio.me/">
    <img align="center" width="60px" src="https://hermes.dio.me/lab_projects/badges/f38a62b8-2880-4fd2-82ff-ba263ce97cdb.png"></a>
         Reconhecimento Facial e Transformação de Imagens em Dados no Azure ML
</h1>

## Descrição do Projeto
Este projeto foi desenvolvido como parte do curso oferecido pela Digital Innovation One (DIO) sobre Reconhecimento Facial e Transformação de Imagens em Dados utilizando o Azure Machine Learning.

## Objetivo
O objetivo principal deste projeto é explorar e testar as ferramentas de reconhecimento facial, bem como transformar imagens em dados utilizando a plataforma Microsoft Azure

## Tecnologias Utilizadas
- Azure AI Vision

### Azure AI Vision 
- o Azure AI Vision é um serviço unificado que oferece capacidades inovadoras de visão computacional, como marcação de imagem predefinida, extração de texto com OCR (reconhecimento óptico de caracteres) e reconhecimento facial responsável.

## Testes Realizados:

### 💬Adicione legendas às imagens
> A função "Add caption to images" do Azure Vision AI permite analisar uma imagem e gerar uma frase legível por humanos que descreve seu conteúdo. O algoritmo retorna várias descrições com base em recursos visuais diferentes e cada descrição é classificada por nível de confiança.

<img src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/blob/main/P02%20-%20Reconhecimento%20Facial%20e%20transforma%C3%A7%C3%A3o%20de%20imagens%20em%20Dados%20no%20Azure%20ML/output/Adicione%20legendas%20%C3%A0s%20imagens.png" width="500">
Fonte: Azure AI Vision Studio

### 😁 Detectar rostos em uma imagem
> A função "Detect faces in an image" no Azure Vision AI, permite fazer a detecção faces em imagens. Para casos positivos, retorna as coordenadas da caixa delimitadora que mostram sua localização. Também cria rótulos de textos dizendo se o rosto detectado está ou não com uma máscara facial. 

<img src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/blob/main/P02%20-%20Reconhecimento%20Facial%20e%20transforma%C3%A7%C3%A3o%20de%20imagens%20em%20Dados%20no%20Azure%20ML/output/Detectar%20rostos%20em%20uma%20imagem.png" width="500">
Fonte: Azure AI Vision Studio

### 📜 Extrair texto de imagens 
> A função "Extract text from images" usará o serviço Azure AI para explorar os recursos de reconhecimento óptico de caracteres do Azure AI Vision. Você usará o Vision Studio para experimentar a extração de texto de imagens, sem precisar escrever nenhum código.

**Imagem 1**
<img src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/blob/main/P02%20-%20Reconhecimento%20Facial%20e%20transforma%C3%A7%C3%A3o%20de%20imagens%20em%20Dados%20no%20Azure%20ML/output/Extrair%20texto%20de%20imagens%201.png" wdth="500">
Fonte: Azure AI Vision Studio

**Imagem 2**
<img src="https://github.com/MaikRodriguess/dio-microsoft-azure-ai-fundamentals/blob/main/P02%20-%20Reconhecimento%20Facial%20e%20transforma%C3%A7%C3%A3o%20de%20imagens%20em%20Dados%20no%20Azure%20ML/output/Extrair%20texto%20de%20imagens%202.png" wdth="500">
Fonte: Azure AI Vision Studio

**Fontes:**
- [Analyze images in Vision Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/03-image-analysis.html)
- [Read text in Vision Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/05-ocr.html)
- [Detect faces in Vision Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/04-face.html)
