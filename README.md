This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 10.1.6.

# Instruções para instalação e execução do projeto em Angular - FILMES:

## Executar os comandos abaixo:

 npm install
 npm install -g @angular/cli@10.1.6 <br /> 
 ng version<br /> /*para ver aversão do angular instalada*/
 ng new filmes<br />
 cd filmes<br /> /*entrar ma pasta filmes e executar o commando a baixo*/
 ng serve ou ng s -o <br />

## Configurar o arquivo DB.json ou Filmes.json

A pasta dados está localizada na raiz do projeto, e dentro o arquivo .JSON com os Filmes nomeado como db.json, ainda dentro da pasta dados abra o git bash e execute os comandos abaixo:<br /> 

npm install -g json-server <br />  /*Servidor JSON é um módulo de nó que você pode usar para criar serviços JSON REST de demonstração em poucos minutos*/
json-server --watch db.json <br /> /*para iniciar o serviço*/
