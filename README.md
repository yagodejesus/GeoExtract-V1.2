Como Usar o GeoExtract

O GeoExtract é uma aplicação que extrai países, continentes e coordenadas geográficas (latitude e longitude) de textos em arquivos Excel. Ele utiliza técnicas de correspondência fuzzy para identificar países e continentes, além de geocodificação para obter as coordenadas.

Como instalar: Basta baixar a pasta da aplicação e iniciar o arquivo "GeoExtract.EXE"

Como Usar a Aplicação
1. Selecionar o Arquivo Excel
Ao abrir a aplicação, clique no botão "Selecionar Arquivo".

Escolha um arquivo Excel (.xlsx ou .xls) que contenha os textos que você deseja analisar.

2. Selecionar a Coluna para Análise
Após selecionar o arquivo, uma nova janela será aberta.

Escolha a coluna que contém os textos a serem analisados no menu suspenso.

Clique em "Iniciar" para começar o processamento.

3. Acompanhar o Progresso
O progresso da análise será exibido na barra de progresso.

Os resultados serão mostrados em tempo real na caixa de texto abaixo:

Países Encontrados: Lista de países identificados no texto.

Continentes Encontrados: Lista de continentes associados aos países.

Coordenadas Encontradas: Latitude e longitude dos países identificados.

4. Parar o Processamento (Opcional)
Se desejar interromper o processamento, clique no botão "Parar".

5. Salvar os Resultados
Após o processamento, clique em "Salvar Resultados".

Um novo arquivo Excel chamado resultado_paises_continentes.xlsx será gerado na pasta do projeto, contendo:

A coluna original analisada.

Colunas adicionais com os países, continentes e coordenadas encontrados.

Exemplo de Uso
Arquivo de Entrada (dados.xlsx):

Texto
Eu visitei o Brasil e a Argentina.
A França é um país da Europa.
O Japão e a China estão na Ásia.

Arquivo de Saída (resultado_paises_continentes.xlsx):

Texto	Países Encontrados	Continentes Encontrados	Coordenadas Encontradas
Eu visitei o Brasil e a Argentina.	Brasil, Argentina	South America	Brasil: -14.2350, -51.9253; Argentina: -38.4161, -63.6167

A França é um país da Europa.	França	Europe	França: 46.2276, 2.2137

O Japão e a China estão na Ásia.	Japão, China	Asia	Japão: 36.2048, 138.2529; China: 35.8617, 104.1954

