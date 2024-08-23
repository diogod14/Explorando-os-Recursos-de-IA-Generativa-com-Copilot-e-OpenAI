# Explorando-os-Recursos-de-IA-Generativa-com-Copilot-e-OpenAI
Explorando os Recursos de IA Generativa com Copilot e OpenAI


Descrição do Projeto
Neste projeto, utilizamos técnicas de reconhecimento de texto para analisar imagens de borboletas geradas com o Microsoft Copilot no Bing. O objetivo foi criar um portfólio que demonstrasse a capacidade de extrair informações úteis de imagens utilizando ferramentas de OCR (Optical Character Recognition).

Passos Seguidos
1. Criação das Imagens
Para iniciar o projeto, criei quatro imagens decoradas de cachorro utilizando o Microsoft Copilot. Essas imagens foram escolhidas por sua diversidade e riqueza visual.

2. Organização dos Arquivos
As imagens criadas foram organizadas na pasta insumosdo repositório para facilitar o acesso e o processamento. Cada imagem foi cuidadosamente nomeada para responder aos arquivos de texto resultantes.

3. Aplicação de Reconhecimento de Texto
Utilizei o Tesseract OCR para extrair texto das imagens. O processo envolve:

Instalação e Configuração: Instalei o Tesseract OCR e a biblioteca pytesseractno meu ambiente Python, e configurei o caminho do Tesseract no sistema.

Processamento das Imagens: Criei um script Python que carregou as imagens da pasta  inputs, apliquei o Tesseract OCR para extrair o texto e salvar os resultados em arquivos de texto na pasta  output.

Salvamento dos Resultados: Os arquivos de texto resultantes serão armazenados na pasta  output, com cada arquivo correspondente ao texto extraído de uma imagem.

4. Documentação do Projeto
Atualizei ou README.mdpara documentar o processo completo. O README inclui proteção das imagens, do processo de reconhecimento de texto e links para os arquivos de texto na pasta  output.

Insights Adquiridos
Importância do Pré-processamento: O pré-processamento das imagens, como ajuste de contraste e conversão para tons de cinza, pode melhorar significativamente a precisão do OCR.

Desafios com Imagens Complexas: Imagens com detalhes complexos e variados núcleos podem apresentar desafios para o OCR, exigindo ajustes adicionais para obter melhores resultados.

Práticas Aplicações do OCR: O reconhecimento de texto em imagens é útil em diversas aplicações, como digitalização de documentos e remoção de dados para projetos de aprendizagem de máquina.
