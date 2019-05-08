# Iniciando com DevOps Java

Este é um exemplo simples baseado no template heroku para aplicações java

## Deploying
Para realizar ao deploy seguir os seguintes passos:
 - Realizar o clone do repositório
 - Configurar o travis-ci para habilitar o deploy do repositório clonado
 - Botão settings
 - Em Environment Variables adicionar
    - HEROKU_API_KEY
    - O valor copiar a sua chave da sua conta no heroku
 - Editar o arquivo .travis.yml do seu repositorio
 - alterar o nome do app no deploy do heroku
    - app: [nome_da_sua_aplicacao]
