# Driven-Ops

Um exercicio prático onde:

- Dockerizei uma aplicação
- Realizei deploy automatico, atraves do github action, na AWS (EC2)
- Criei uma DNS
- Criei uma regra para aceitar apenas pull request que passarem em todos os testes

## Deploy

[Link do deploy](http://driven-ops.ml/)

## Variaveis de ambiente

### Front-end

- `REACT_APP_BASE_URL`
  - Ex: http://localhost:80/api

### Back-end

- `DATABASE_URL`
  - Ex: postgresql://postgres:1234@db:5432/driven_ops
- `POSTGRES_USER`
  - Ex: postgres
- `POSTGRES_PASSWORD`
  - Ex: 1234
- `POSTGRES_DB`
  - Ex: driven_ops

## Rodar localmente usando o Docker

1 - Vá no diretório do front-end

```bash
  cd projeto23-drivenops/front-end
```

2 - instale as dependencias

```bash
  npm i
```

3 - Vá no diretório do back-end

```bash
  cd projeto23-drivenops/back-end
```

4 - inicie o docker-compose

```bash
  docker-compose up --build -d
```
