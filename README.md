# API de Gerenciamento de Produtos

## Descrição
API REST para gerenciamento de produtos de um pequeno e-commerce, desenvolvida com FastAPI, SQLAlchemy e PostgreSQL.

## Tecnologias
- FastAPI
- SQLAlchemy
- PostgreSQL
- Pytest
- Docker

## Instruções para subir o banco de teste com Docker

```bash
# Subir apenas o banco de teste
docker-compose up -d db_test

# Verificar se o banco está saudável
docker-compose ps

# Para subir os dois bancos (dev e test)
docker-compose up -d