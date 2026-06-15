# Projeto de BI e Analytics - Olist E-commerce

Este projeto foi desenvolvido para a disciplina Projeto em Business Intelligence e Analytics - Fase 2.

O objetivo é implementar uma solução de Business Intelligence e Analytics para análise de desempenho comercial em um e-commerce varejista, utilizando a base pública da Olist.

## Base de dados

A base utilizada foi a Olist Brazilian E-Commerce Public Dataset, composta por dados de pedidos, pagamentos, itens dos pedidos e avaliações de clientes.

Foram utilizadas principalmente as seguintes tabelas:

- olist_orders_dataset
- olist_order_payments_dataset
- olist_order_items_dataset
- olist_order_reviews_dataset

## Ferramentas utilizadas

- Google Colab
- Python
- Pandas
- Scikit-learn
- Power BI
- GitHub

## KPIs analisados

Os principais indicadores definidos para o projeto foram:

- Faturamento total
- Total de pedidos
- Ticket médio
- Faturamento mensal
- Prazo médio de entrega
- Taxa de atraso
- Nota média de avaliação

## Arquitetura da solução

A solução foi estruturada em uma pipeline simples:

Base Olist → Google Colab/Python → Limpeza e tratamento dos dados → Base consolidada CSV → Power BI → Dashboards → Análise preditiva → GitHub

## Solução de BI

A solução de BI foi implementada no Power BI, com a criação de dashboards para acompanhamento dos principais indicadores de negócio.

O dashboard apresenta:

- Cards com os KPIs principais
- Evolução do faturamento mensal
- Volume de pedidos por mês
- Prazo médio de entrega por mês
- Nota média de avaliação por mês
- Taxa de atraso por mês
- Filtro por ano

## Solução de Analytics

A etapa de Analytics foi desenvolvida no Google Colab, utilizando Python e aprendizado de máquina.

Foi criado um modelo de regressão linear para previsão do faturamento mensal com base nos dados históricos.

O modelo gerou uma comparação entre faturamento real e faturamento previsto, permitindo avaliar tendências e apoiar a tomada de decisão.

## Estrutura do repositório

```text
data/processed/
Bases tratadas utilizadas no projeto

notebooks/
Notebook com preparação, limpeza, tratamento e análise preditiva

dashboard/
Arquivo do Power BI com os dashboards

reports/
Relatório final e apresentação executiva
