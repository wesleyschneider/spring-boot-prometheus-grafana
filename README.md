# Spring Boot - Prometheus e Grafana

## Prova de conceito

Visualizar dashboards das métricas de uma aplicação Java Spring Boot.

- Micrometer
- Prometheus
- Grafana

## Requisitos

- Java JDK 17
- Apache Maven 3.8.6
- Docker 20+
- Docker Compose 1.25

## Como executar

1. No root do repositório execute `mvn spring-boot:run` para subir a aplicação na porta `8080`
2. Execute `docker-compose up` para subir os containers do Prometheus (porta `9090`) e Grafana (porta `3000`)
3. Acesse o Grafana, logue com as credenciais abaixo:
   Usuário: admin
   Senha: admin
4. Por fim, importe as duas dashboards localizadas na pasta `/grafana-dashboards`
