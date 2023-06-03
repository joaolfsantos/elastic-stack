# Elastic Stack com Docker-Compose

Este repositório contém um arquivo docker-compose.yml que permite executar o Elastic Stack (Elasticsearch, APM Server e Kibana) em contêineres Docker para monitorar o desempenho de aplicações.

## Pré-requisitos

- Docker Desktop ou Docker Engine com Docker-Compose instalado e configurado

## Como usar

1. Clone este repositório ou faça o download do arquivo docker-compose.yml
2. Abra um terminal e navegue até a pasta onde está o arquivo docker-compose.yml
3. Execute o comando `docker-compose up -d` para iniciar os contêineres em segundo plano
4. Aguarde alguns minutos até que os contêineres estejam prontos
5. Acesse o Kibana no navegador pelo endereço http://localhost:5601

## Fontes

Baseado nas seguintes fontes:

- [Getting started with the Elastic Stack and Docker-Compose](https://www.elastic.co/blog/getting-started-with-the-elastic-stack-and-docker-compose) 
- [Install Elasticsearch with Docker](https://www.elastic.co/guide/en/elasticsearch/reference/current/docker.html)

Espero que isso tenha sido útil para você. 😊
