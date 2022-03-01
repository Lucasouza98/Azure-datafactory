# Azure Data Factory

Fluxo de criação do Pipeline:
1 - Realizei a ingestão dos dados HTTPS para o Data lake na pasta RAW com o arquivo bruto.
2 - Realizei o tratamento ETL por via do Data Flow deste arquivo e coloquei em uma pasta GOLD do Data Lake
3 - Realizei a carga da pasta GOLD para o Servidor Azure SQL criado.
4 - Agora está pronto para ser tratado no Power BI para analises de Dados.
