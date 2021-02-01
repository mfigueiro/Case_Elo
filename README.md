# Case_Elo

## 636020 - Data Scientist (Information Retrieval)

## Descrição do Problema

Você deve construir uma `text-based search engine` que retorne os produtos mais relevantes para uma dada query de um usuário. Você pode utilizar a linguagem que preferir mas não pode utilizar `search engines` prontas (como Solr ou ElasticSearch) como parte de sua solução.

## Parte 1 - Construção do Índice

Nessa etapa você deve armazenar os produtos em uma estrutura de dados eficiente para que possam ser recuperados no futuro. Você deve implementar essa estrutura de dados utilizando as estruturas de dados nativas da linguagem escolhida. Caso seja necessário fazer algum processamento de linguagem natural, sinta-se livre para utilizar bibliotecas de terceiros.

## Parte 2 - Ranking

Uma parte importante de qualquer `search engine` é retornar os documentos mais relevantes para uma dada `query`. Nessa etapa você deve desenvolver um algoritmo ou modelo para ordenar por relevância os produtos recuperados do índice. Você pode utilizar os campos `search_page` e `position` para avaliar a qualidade do seu `ranking`. Nessa etapa, caso seja necessário, você pode utilizar bibliotecas de terceiros.
