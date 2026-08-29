<div align="center">

<h1>João Batista de Macedo Junior</h1>

<p><b>Engenharia de Dados</b> &nbsp;·&nbsp; Pipelines de ponta a ponta em Python, SQL, Airflow, dbt e AWS</p>

<p>
<a href="https://www.linkedin.com/in/joaobatistamjr"><img src="https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:joaobatistademacedojunior97@gmail.com"><img src="https://img.shields.io/badge/EMAIL-0D1117?style=for-the-badge&logo=gmail&logoColor=00BFFF" /></a>
<img src="https://img.shields.io/badge/Curitiba,_PR_%E2%80%94_Brasil-0D1117?style=for-the-badge&logo=googlemaps&logoColor=00BFFF" />
</p>

<p>
<img src="https://img.shields.io/badge/Python-0D1117?style=for-the-badge&logo=python&logoColor=00BFFF" />
<img src="https://img.shields.io/badge/SQL-0D1117?style=for-the-badge&logo=postgresql&logoColor=00BFFF" />
<img src="https://img.shields.io/badge/dbt-0D1117?style=for-the-badge&logo=dbt&logoColor=00BFFF" />
<img src="https://img.shields.io/badge/Airflow-0D1117?style=for-the-badge&logo=apacheairflow&logoColor=00BFFF" />
<img src="https://img.shields.io/badge/Docker-0D1117?style=for-the-badge&logo=docker&logoColor=00BFFF" />
<img src="https://img.shields.io/badge/AWS-0D1117?style=for-the-badge&logo=amazonwebservices&logoColor=00BFFF" />
<img src="https://img.shields.io/badge/PostgreSQL-0D1117?style=for-the-badge&logo=postgresql&logoColor=00BFFF" />
</p>

</div>

## Projetos

Todos com README documentando arquitetura, decisões e trade-offs.

### [job-market-pipeline](https://github.com/Jx-dev-c/job-market-pipeline)

Pipeline end-to-end sobre o mercado de vagas de tecnologia, rodando na AWS dentro do free tier.

APIs públicas → S3 → Glue/Athena → dbt → Airflow → Metabase, com CI no GitHub Actions executando lint, testes e `dbt build` a cada push.

`Python` `Airflow` `dbt` `AWS (S3, Glue, Athena)` `GitHub Actions` `Metabase`

### [br-socioeconomic-pipeline](https://github.com/Jx-dev-c/br-socioeconomic-pipeline)

População estimada dos 5.571 municípios brasileiros, extraída da API do IBGE.

Extração em Python, carga em Postgres, modelagem em star schema no dbt com testes de qualidade, orquestração em Airflow e visualização em Metabase — todo o ambiente sobe em Docker.

`Python` `PostgreSQL` `dbt` `Airflow` `Docker` `Metabase`

### [nyc-taxi-lakehouse](https://github.com/Jx-dev-c/nyc-taxi-lakehouse)

Lakehouse local sobre o dataset NYC TLC Taxi Trips, em três camadas: raw → trusted → refined.

Ingestão e processamento em Python com DuckDB, transformações modeladas em dbt.

`Python` `DuckDB` `dbt`

### [SchoolApi](https://github.com/Jx-dev-c/SchoolApi) + [school-app](https://github.com/Jx-dev-c/school-app)

Sistema de gestão escolar completo — API REST em ASP.NET Core e frontend em Angular. Construído para entender o lado onde os dados nascem, antes de chegarem ao pipeline.

`C#` `ASP.NET Core` `Angular` `TypeScript`

## Sobre

Estudante de Ciência da Computação construindo carreira em engenharia de dados na prática. Meu critério para dar um projeto por concluído é ele rodar de ponta a ponta, com orquestração, testes e documentação — não um notebook com o resultado certo.

Hoje trabalho com plantas do estado e os relatórios mensais de produção em SAP, Excel e Power BI. Antes disso, analisei contestações de faturas na Vivo e atuei com automação e dados na Nova Gestão.

Bacharelado em Ciência da Computação pela Universidade Cruzeiro do Sul, com conclusão prevista para dezembro de 2027.

Também trabalho com BigQuery, Power BI, DuckDB, pytest e pandas.

## Contato

Aberto a oportunidades júnior em Engenharia e Analytics de Dados.

- **LinkedIn:** [joaobatistamjr](https://www.linkedin.com/in/joaobatistamjr)
- **E-mail:** joaobatistademacedojunior97@gmail.com

<sub><b>In English:</b> I build end-to-end data pipelines — ingestion, orchestration, transformation, modeling and visualization — with Python, SQL, dbt, Airflow, Docker and AWS. Featured project: <a href="https://github.com/Jx-dev-c/job-market-pipeline">job-market-pipeline</a>, a tech job-market data pipeline running on AWS with CI. Open to junior data engineering roles.</sub>
