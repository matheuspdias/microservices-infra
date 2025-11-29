# Microservices Infrastructure

Infraestrutura base para microserviços utilizando RabbitMQ.

## 📦 Serviços inclusos

- RabbitMQ (fila e exchange)
- RabbitMQ Management (painel admin)

## ▶️ Como usar

### 1. Subir a infraestrutura

```bash
docker compose up -d
```

### 2. Rodar os microserviços

Para rodar o **producer** e o microserviço de **users**, acesse os repositórios abaixo. Cada um contém as instruções específicas de como executar:

- **Producer**: https://github.com/matheuspdias/ms-producer
- **Users Service**: https://github.com/matheuspdias/ms-users
