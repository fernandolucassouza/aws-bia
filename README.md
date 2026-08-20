## Projeto base para o evento Imersão AWS & IA que irei realizar.

### Período do evento: 01/08 e 02/08/2026 (Online e ao Vivo das 9h30 às 17h30)

[>> Página de Inscrição do evento](https://org.imersaoaws.com.br/github/readme)

#### Para rodar as migrations no container ####
```
docker compose exec server bash -c 'npx sequelize db:migrate'
```

### Comando para executar a Bia via docker 
_Deve estar na raiz do projeto_

```bash
#Subir o projeto
docker compose up -d

#remover os containers 
docker compose down
```
