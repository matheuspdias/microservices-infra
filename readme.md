# Microservices Infrastructure

Infraestrutura base para microserviços utilizando RabbitMQ.

## 📦 Serviços inclusos

- RabbitMQ (fila e exchange)
- RabbitMQ Management (painel admin)

## ▶️ Como usar

### 1. Clonar o projeto

```bash
git clone https://github.com/matheuspdias/microservices-infra.git
cd microservices-infra
```

### 2. Subir a infraestrutura

```bash
docker compose up -d
```

### 3. Acessar o RabbitMQ Management

O painel de administração do RabbitMQ estará disponível em:

```
http://localhost:15672
```

**Credenciais padrão:**
- Usuário: `rabbit`
- Senha: `rabbit`

### 4. Rodar os microserviços

Para rodar o **producer** e o microserviço de **users**, acesse os repositórios abaixo. Cada um contém as instruções específicas de como executar:

- **Producer**: https://github.com/matheuspdias/ms-producer
- **Users Service**: https://github.com/matheuspdias/ms-users
