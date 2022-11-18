# Driven-Ops

Um exercicio prático onde:

- Dockerizei uma aplicação
- Realizei deploy automatico, atraves do github action, na AWS (EC2)
- Criei uma DNS
- Criei uma regra para aceitar apenas pull request que passarem em todos os testes

## Deploy

[Link do deploy](http://driven-ops.ml/)

## Variaveis de ambiente

### Back-end

- `DATABASE_URL`
  - Ex: postgresql://postgres:1234@localhost:5432/driven_ops
- `POSTGRES_USER`
  - Ex: postgres
- `POSTGRES_PASSWORD`
  - 1234
- `POSTGRES_DB`
  - driven_ops
