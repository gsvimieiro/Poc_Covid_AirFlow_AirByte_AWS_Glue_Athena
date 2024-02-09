# Poc_Covid_AirFlow_AirByte_AWS_Glue_Athena

Este pequeno projeto foi baseado no curso ministrado pelo Giuliano (Data Engineering usando a Modern Data Stack da Stack Academy - https://stack-academy.memberkit.com.br/)

Estudo de caso COVID utilizando Airbyte para extração, Airflow como orquestrador, AWS Glue/Krawler para catalogar, inferir o schema e realizar transformação e por fim Athena para análise. 

![image](https://github.com/gsvimieiro/POC_Covid_AirFlow_AirByte_AWS_Glue_Athena/assets/25323854/a6960143-f077-4be2-80aa-2c3fc60d55a6)


Tarefas :

- Setar permissões do Gitpod para o GitHub - OK
- Subir Airbyte via Docker - OK
    - Dar fork no github do airbyte, criar uma branch (branch_airbyte)
    - git clone -b branch_airbyte https://github.com/gsvimieiro/airbyte.git

- Subir Airflow via Docker - OK
- Criar conta na AWS - OK
- Na AWS
    - Criar o repositório
    - Criar dentro do repositorio as pastas raw e processed
- No Airbyte :
    - Preparar a extração dos CSV's COVID
    - Configurar o target S3
- No Airflow :
    - Criar as DAG'S de orquestração
