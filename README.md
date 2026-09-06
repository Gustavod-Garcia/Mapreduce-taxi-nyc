# Atividade MapReduce — Análise de Viagens de Táxi NYC (2024)

Trabalho da disciplina Processamento de Dados Massivos (IESB), Prof. Alexandre Roriz.

## Objetivo
Aplicar o paradigma MapReduce (mapper → shuffle → reducer) para responder 6 perguntas
sobre uma amostra de viagens de táxi amarelo de Nova York em 2024.

## Estrutura do repositório
- `notebook/` — notebook Jupyter (Google Colab) com todo o processamento
- `data/` — dicionário de dados oficial (TLC)
- `resultados/` — saída de cada uma das 6 questões

## Questões respondidas
1. Número de viagens por tipo de pagamento
2. Receita total por tipo de pagamento
3. Tarifa média cobrada nas viagens
4. Data e hora da viagem mais longa
5. Quantidade de viagens por hora
6. Distância total percorrida por hora

## Dataset
Amostra de 1.000.000 de viagens de táxi amarelo de NY (2024), fornecida pelo professor.
CSV não incluído no repositório por tamanho.

## Como executar
1. Abra `notebook/mapreduce_taxi_nyc.ipynb` no Google Colab
2. Faça upload do CSV quando solicitado
3. Execute todas as células em ordem (Ambiente de execução → Executar tudo)
