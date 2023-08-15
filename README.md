# Análise de Sentimento em Textos

Este é um projeto de análise de sentimento em textos utilizando processamento de linguagem natural retirados do Twitter e um modelo de regressão logística. 
O objetivo deste projeto é classificar textos como positivos ou negativos com base no sentimento expresso no texto.


**Como Usar***

- Instale as bibliotecas necessárias
- Coloque o conjunto de dados CSV (`sentimentos_tweet.csv`) na mesma pasta que o código.
- Execute o arquivo `analise_sentimento.ipynb` para realizar a análise de sentimento.


**Funcionalidades**

- Carrega um conjunto de dados contendo textos e rótulos de sentimento.
- Realiza pré-processamento nos textos, incluindo remoção de pontuações, conversão para minúsculas, **tokenização e stemming**.
- Cria uma matriz de frequência de palavras usando a técnica **CountVectorizer**.
- Divide os dados em conjuntos de treinamento e teste.
- Treina um modelo de **regressão logística** para a classificação de sentimento.
- Avalia a precisão do modelo e exibe a matriz de confusão.
- Permite a classificação de novos textos inseridos pelo usuário.


