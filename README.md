# EngC_CadeMeuCarroApp

## Pré-Requisitos

- Docker
- NodeJs
- Postgresql

## Inicializando Container

###### Primeiramente vamos inicializar nosso docker, após ter instalado, e criar um container do postgresql com as seguintes informações:

`name = cmc-7`
`host = 5437`

Ficando da forma no Linux:

`sudo docker run --name cmc-7 -e POSTGRES_PASSWORD=admin -e POSTGRES_USER=admin -p 5432:5433 -d postgres `

Logo após, execute o comando `sudo docker ps` para verificar se o container está sendo executado.

## Inicializando o NestJs

#### Na pasta backend você encontrará os arquivos da API, apenas execute os comandos no terminal dentro da pasta 'backend':

`npm install`
`npm run start:dev`