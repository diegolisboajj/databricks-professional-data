# 📘 Referências de Estudo — Databricks

Repositório com links, artigos e documentações úteis para estudo e preparação para a certificação **Databricks Data Engineer**.

---

## 📑 Sumário
- [🚀 Como começar](#-como-começar)
- [🧠 Artigos recomendados](#-artigos-recomendados)
  - [🔹 Geral](#-geral)
  - [🔹 Structured Streaming](#-structured-streaming)
  - [🔹 CDC e CDF](#-cdc-e-cdf)
  - [🔹 Controle de acesso](#-controle-de-acesso)
  - [🔹 Delta Lake](#-delta-lake)
  - [🔹 MLflow](#-mlflow)
  - [🔹 API, SDK e CLI](#-api-sdk-e-cli)
  - [🔹 Interface (UI)](#-interface-ui)
  - [🔹 Notebooks](#-notebooks)
  - [🔹 SQL (Uniões e Estruturas Aninhadas)](#-sql-uniões-e-estruturas-aninhadas)
- [📗 Livro de Engenharia de Dados](#-livro-de-engenharia-de-dados)

---

## 🚀 Como começar

### 🎓 Visão geral da certificação  
[Databricks Data Engineer Professional Certification](https://www.databricks.com/learn/certification/data-engineer-professional)

### 📚 Repositório principal  
[Plano de aprendizado Databricks (Customer Academy)](https://customer-academy.databricks.com/learn/learning_plan/view/69/data-engineer-learning-plan-public)

### 📖 Documentação oficial  
[Documentação Databricks](https://docs.databricks.com/en/index.html)

---

## 🧠 Artigos recomendados

### 🔹 Geral
- [Transações ACID no Lakehouse](https://docs.databricks.com/en/lakehouse/acid.html)  
- [Arquitetura Medallion](https://docs.databricks.com/en/lakehouse/medallion.html)  
- [Plano de aprendizado — Lakehouse Fundamentals](https://customer-academy.databricks.com/learn/learning_plan/view/215/databricks-lakehouse-fundamentals-learning-plan)

---

### 🔹 Structured Streaming
- [Boas práticas para streaming em produção](https://www.databricks.com/blog/2022/12/12/streaming-production-collected-best-practices.html)  
- [API withWatermark (PySpark)](https://spark.apache.org/docs/3.1.1/api/python/reference/api/pyspark.sql.DataFrame.withWatermark.html)  
- [Structured Streaming + Delta Lake (GCP Docs)](https://docs.gcp.databricks.com/structured-streaming/delta-lake.html#language-python)  
- [Joins entre stream e dados estáticos](https://docs.databricks.com/structured-streaming/delta-lake.html#performing-stream-static-joins)  
- [Joins entre streams no Apache Spark 2.3](https://www.databricks.com/blog/2018/03/13/introducing-stream-stream-joins-in-apache-spark-2-3.html)

---

### 🔹 CDC e CDF
- [Operação Delta MERGE](https://docs.databricks.com/delta/merge.html)  
- [Referência SQL MERGE INTO](https://docs.databricks.com/sql/language-manual/delta-merge-into.html)  
- [Simplificando CDC com Delta Change Data Feed](https://www.databricks.com/blog/2021/06/09/how-to-simplify-cdc-with-delta-lakes-change-data-feed.html)  
- [Dimensões de mudança lenta (Wikipedia)](https://en.wikipedia.org/wiki/Slowly_changing_dimension)  
- [Documentação Delta Change Data Feed](https://docs.databricks.com/delta/delta-change-data-feed.html)

---

### 🔹 Controle de acesso
- [Gerenciamento de segredos](https://docs.databricks.com/security/secrets/index.html)  
- [Permissões em clusters (Cluster ACLs)](https://docs.databricks.com/en/security/auth-authz/access-control/cluster-acl.html)  
- [Permissões de segredos (Secret ACLs)](https://docs.databricks.com/security/auth-authz/access-control/secret-acl.html#permission-levels)  
- [Permissões de jobs (Jobs ACLs)](https://docs.databricks.com/security/auth-authz/access-control/jobs-acl.html#job-permissions)

---

### 🔹 Delta Lake
- [Explorando o log de transações do Delta Lake](https://www.databricks.com/blog/2019/08/21/diving-into-delta-lake-unpacking-the-transaction-log.html)  
- [Ajuste de tamanho de arquivos](https://docs.databricks.com/delta/tune-file-size.html)  
- [Data Skipping](https://docs.databricks.com/delta/data-skipping.html)  
- [Clonagem de tabelas Delta](https://docs.databricks.com/delta/clone.html)  
- [Histórico de tabelas](https://docs.databricks.com/delta/history.html)  
- [Ajuste automático de tamanho de arquivo](https://docs.databricks.com/delta/tune-file-size.html#autotune-file-size-based-on-workload)  
- [Tabelas gerenciadas e não gerenciadas](https://docs.databricks.com/en/lakehouse/data-objects.html#what-is-an-unmanaged-table)  
- [Particionamento de tabelas](https://docs.databricks.com/tables/partitions.html)  
- [Sintaxe CREATE TABLE USING](https://docs.databricks.com/en/sql/language-manual/sql-ref-syntax-ddl-create-table-using.html)  
- [Restrições em tabelas (CHECK constraints)](https://docs.databricks.com/tables/constraints.html#set-a-check-constraint-in-databricks)  
- [Compactação automática para Delta Lake](https://docs.databricks.com/delta/tune-file-size.html#auto-compaction-for-delta-lake-on-databricks)

---

### 🔹 MLflow
- [Modelos MLflow](https://docs.databricks.com/en/mlflow/models.html)

---

### 🔹 API, SDK e CLI
- [Monitoramento de execuções de jobs](https://docs.databricks.com/en/workflows/jobs/monitor-job-runs.html)  
- [Tutorial de CLI](https://docs.databricks.com/en/dev-tools/cli/tutorial.html)

---

### 🔹 Interface (UI)
- [Interface Web do Apache Spark](https://spark.apache.org/docs/latest/web-ui.html)

---

### 🔹 Notebooks
- [Importar e exportar notebooks](https://docs.databricks.com/en/notebooks/notebook-export-import.html#convert-a-file-to-a-notebook)  
- [YouTube: Fundamentos do Databricks Notebook](https://www.youtube.com/watch?v=cxb4hnKLnYU)  
- [YouTube: Visão geral do workspace Databricks](https://www.youtube.com/watch?v=pQZEXkHSnls)

---

### 🔹 SQL (Uniões e Estruturas Aninhadas)
- [Operações de conjunto (UNION, INTERSECT, etc.)](https://docs.databricks.com/en/sql/language-manual/sql-ref-syntax-qry-select-setops.html)  
- [Dados semiestruturados](https://docs.databricks.com/en/optimizations/semi-structured.html)  
- [Função EXPLODE](https://docs.databricks.com/en/sql/language-manual/functions/explode.html)

---

## 📗 Livro de Engenharia de Dados
- [📘 The Big Book of Data Engineering (2ª edição)](https://www.databricks.com/resources/ebook/big-book-data-engineering-2nd-edition)

---

> 💡 **Dica:** Organize seus estudos dividindo os temas por semana (por exemplo: Delta Lake em uma semana, Structured Streaming na seguinte).  
>  
> Use este repositório como ponto central para suas anotações e notebooks de prática.
