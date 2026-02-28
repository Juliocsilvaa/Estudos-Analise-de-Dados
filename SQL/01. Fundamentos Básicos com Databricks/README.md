# 📚 Estudo de SQL com Databricks

Este projeto foi desenvolvido como estudo dos **fundamentos de SQL**, utilizando o ambiente **Databricks** como plataforma de execução e organização dos dados.

O desenvolvimento deste projeto foi orientado pelo conteúdo educacional da Jornada de Dados ([GitHub: linkJornadadeDados](https://github.com/lvgalvao/IntensivoSQLnoDatabricks)). A partir dessa base teórica, implementei uma aplicação prática dos conceitos em um pipeline estruturado de transformação de dados, adotando a arquitetura Medallion como padrão de organização e governança das camadas (Bronze, Silver e Gold).

Essa abordagem permitiu consolidar o aprendizado por meio da aplicação direta em um fluxo de engenharia de dados com separação clara de responsabilidades, tratamento incremental e refinamento progressivo dos dados.


## 🎯 Objetivo

- Compreender os fundamentos da linguagem SQL;
- Aplicar consultas em ambiente distribuído (Databricks);
- Trabalhar com manipulação, filtragem e agregação de dados;
- Estruturar camadas de transformação utilizando a regra Medallion;
- Consolidar a lógica de pipeline de dados em ambiente analítico.



## 🧠 Fundamentos de SQL Explorados

Durante o estudo foram aplicados comandos essenciais da linguagem:

### 📌 Consulta e Seleção
- `SELECT`
- `FROM`
- `WHERE`
- `ORDER BY`
- `LIMIT`

### 📌 Agregações
- `COUNT()`
- `SUM()`
- `AVG()`
- `MIN()`
- `MAX()`
- `GROUP BY`
- `HAVING`

### 📌 Transformações
- `CAST`
- `CASE WHEN`
- `CONCAT`
- `CONCAT_WS`

## 📌 Estruturação de Dados
- `CREATE TABLE`
- `CREATE OR REPLACE TABLE`
- `WITH` (CTEs)
- Subqueries


## ⚙️ Ambiente Utilizado

- Databricks
- SQL
- Estrutura de Workspace em camadas
- Notebooks para execução das queries
