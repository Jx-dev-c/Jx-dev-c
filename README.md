## Olá, eu sou o João 👋

**Engenheiro de Dados** em Curitiba. Eu levo o dado do começo ao fim: da API ou do CSV bruto até o número que alguém usa para decidir. No caminho tem testes, documentação e um dashboard que conta a história.

- 🏗️ **Pipelines:** ingestão, orquestração, transformação e modelagem com Databricks, dbt, Airflow e AWS.
- 📊 **BI:** Power BI com DAX e visuais próprios em TypeScript e three.js, como mapas e cidades em 3D com dados reais.
- 💻 **Aplicações:** APIs em C#/.NET e front-ends em Angular que consomem esses dados.
- 🎯 **Procurando:** oportunidades em Engenharia de Dados e Analytics Engineering.

---

### ⭐ Em destaque: Olist Lakehouse + Olist City 3D

[![Olist City: cidade isométrica 3D com os KPIs do e-commerce Olist](https://raw.githubusercontent.com/Jx-dev-c/olist-lakehouse-databricks-powerbi/main/docs/img/olist_city_noite.png)](https://jx-dev-c.github.io/olist-lakehouse-databricks-powerbi/olist-city/)

**Pipeline no Databricks:** ~100 mil pedidos do e-commerce Olist em arquitetura medalhão (Auto Loader, PySpark, Unity Catalog), com 20 testes de qualidade que bloqueiam o job se algo estiver errado.

**Power BI:**
- KPIs com comparativos;
- insights que se reescrevem a cada filtro;
- **visuais 3D próprios**: na Olist City, cada prédio é uma área do negócio.

[📂 Repositório](https://github.com/Jx-dev-c/olist-lakehouse-databricks-powerbi) · [🌐 Abrir a cidade ao vivo](https://jx-dev-c.github.io/olist-lakehouse-databricks-powerbi/olist-city/)

---

### 🗂️ Projetos

| Projeto | Resultado | Stack |
|---|---|---|
| **[olist-lakehouse-databricks-powerbi](https://github.com/Jx-dev-c/olist-lakehouse-databricks-powerbi)** | 98 mil pedidos válidos e R$ 15,7 mi de receita em modelo estrela + RFM. Dashboard com insights dinâmicos e visuais 3D | Databricks · PySpark · Power BI · three.js |
| **[job-market-pipeline](https://github.com/Jx-dev-c/job-market-pipeline)** | ~970 vagas por dia de 3 APIs públicas → S3 → Glue/Athena → dbt (15 modelos, 57 testes). CI no GitHub Actions, dentro do free tier da AWS | Python · Airflow · dbt · AWS |
| **[clima-capitais-pipeline](https://github.com/Jx-dev-c/clima-capitais-pipeline)** | 1,4 milhão de medições horárias das 27 capitais, 69 testes de dados e [dashboard publicado](https://jx-dev-c.github.io/clima-capitais-pipeline/) | Python · Parquet · DuckDB · dbt · Angular |
| **[br-socioeconomic-pipeline](https://github.com/Jx-dev-c/br-socioeconomic-pipeline)** | Os 5.571 municípios brasileiros (API do IBGE) em star schema, com carga idempotente | Python · Airflow · dbt · PostgreSQL · Metabase |
| **[nyc-taxi-lakehouse](https://github.com/Jx-dev-c/nyc-taxi-lakehouse)** | ~3 milhões de corridas em camadas raw → trusted → refined | Python · DuckDB · dbt · Parquet |
| **[SchoolApi](https://github.com/Jx-dev-c/SchoolApi)** + **[school-app](https://github.com/Jx-dev-c/school-app)** | API REST de gerenciamento escolar e o front-end que a consome | C# · ASP.NET Core · EF Core · PostgreSQL · Angular |

---

### 🧭 Como eu trabalho

- **Dado testado antes de virar gráfico.** Testes de qualidade e de dbt em todos os pipelines. No Olist, uma falha de qualidade interrompe o job antes de chegar ao BI.
- **Número que bate.** No dashboard do Olist, cada métrica tem definição escrita e é conferida contra o SQL do lakehouse. Se a amostra é pequena, o insight avisa em vez de concluir.
- **Custo zero quando dá.** Free tier da AWS, Databricks Free Edition, DuckDB local e GitHub Pages.
- **Decisão documentada.** Cada README explica o porquê das escolhas, os trade-offs e os problemas reais do caminho.

---

### 🛠️ Stack

**Dados:**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat&logo=databricks&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat&logo=dbt&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat&logo=duckdb&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS_(S3·Glue·Athena)-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

**BI e visualização:**
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![three.js](https://img.shields.io/badge/three.js-000000?style=flat&logo=threedotjs&logoColor=white)
![Metabase](https://img.shields.io/badge/Metabase-509EE3?style=flat&logo=metabase&logoColor=white)

**Desenvolvimento:**
![C#](https://img.shields.io/badge/C%23_/_.NET-512BD4?style=flat&logo=dotnet&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

---

### 📫 Contato

📧 joaojrdevc@gmail.com · 💼 [LinkedIn](https://www.linkedin.com/in/joaobatistamjr) · 📍 Curitiba, PR

<details>
<summary><b>🇺🇸 In English</b></summary>

Data engineer based in Curitiba, Brazil. I take data end to end: from a raw API or CSV to the number someone uses to make a decision, with tests, documentation and a dashboard that tells the story.

- **Pipelines:** Databricks (PySpark, Auto Loader, Unity Catalog), dbt, Airflow, AWS (S3, Glue, Athena), DuckDB.
- **BI:** Power BI (DAX), plus custom visuals built in TypeScript and three.js, including a 3D "city" where each building is a business area, fed by real lakehouse data.
- **Apps:** C#/.NET APIs and Angular front-ends.

Featured: [olist-lakehouse-databricks-powerbi](https://github.com/Jx-dev-c/olist-lakehouse-databricks-powerbi) ([live demo](https://jx-dev-c.github.io/olist-lakehouse-databricks-powerbi/olist-city/)), job-market-pipeline and clima-capitais-pipeline. Open to data engineering roles.

</details>
