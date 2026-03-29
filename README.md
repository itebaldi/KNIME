# Sentiment Classification with KNIME

Projeto de classificação de sentimento binário com **KNIME**, utilizando a base **Sentiment Labelled Sentences (UCI)**.

## Objetivo

Construir um fluxo de mineração de texto capaz de classificar frases curtas como:

- **positive**
- **negative**

O pipeline inclui:

- leitura dos dados
- pré-processamento textual
- representação vetorial
- divisão em treino e teste
- treinamento de modelos
- avaliação dos resultados

## Como rodar

1. Abra o projeto no **KNIME Analytics Platform**
2. No primeiro nó, **CSV Reader**, atualize o caminho do arquivo de entrada para:

`project/sentiment+labelled+sentences/sentiment labelled sentences/yelp_labelled.txt`

3. Execute o workflow

## Observação

A atualização do path no **CSV Reader** é necessária para que o projeto consiga importar corretamente a base de dados.