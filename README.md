This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 10.1.6.

# Instruções para instalação e execução do projeto em Angular - FILMES:

## Executar os comandos abaixo:

 npm install<br />
 npm install -g @angular/cli@10.1.6 <br /> 
 /*para ver aversão do angular instalada*/
 ng version<br />
 <br />ng new filmes<br />
 /*entrar ma pasta filmes e executar o commando a baixo*/
 cd filmes<br /> 
 <br />ng serve ou ng s -o <br />

## Configurar o arquivo DB.json ou Filmes.json

A pasta dados está localizada na raiz do projeto, e dentro o arquivo .JSON com os Filmes nomeado como db.json, ainda dentro da pasta dados abra o git bash e execute os comandos abaixo:<br /> 
/*Servidor JSON é um módulo de nó que você pode usar para criar serviços JSON REST de demonstração em poucos minutos*/
<br />npm install -g json-server <br />  
/*para iniciar o serviço*/
<br />json-server --watch db.json <br /> 
