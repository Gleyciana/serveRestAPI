# Bootcamp #01 Qualiters Club
Teste de API Test do manual a CI/CD


## O que é
Este reporsitório foi criado para o bootcamp de Teste de API Rest

## Tecnologias utilizadas
- Postman versão web

- Node version v18.16.1

- Newman v5.3.2

- Newman-reporter-html


## Documentações

- Doc da API: [Consulte Swagger].(https://serverest.dev/#/)

## Como instalar o ambiente

- Primeiro: instale o node em seu computador [baixe aqui].(https://nodejs.org/en/download)

- egundo : realize a instalação do newman de forma global [baixe aqui a dependencia].(https://www.npmjs.com/package/newman)
 
- Terceiro: realize a instalação da dependencia dos relatórios (opcional) [newman-reporter-html].(https://www.npmjs.com/package/newman-reporter-html)

## Como rodar os testes

### Pelo Postman web ou desktop
- Import a collection e o environment
- Execute os testes de forma manual ou automatizada

### Pelo newman
- Abra o seu console de preferência
- Execute a seguinte linha de comando para rodar os testes 
 ```
 newman run ServeRest.postman_collection.json -e serveRest_env.postman_environment.json -r cli
```
- Execute os testes com relatório
 ```
 newman run ServeRest.postman_collection.json -e serveRest_env.postman_environment.json -r cli,htmlextra
```


## Report

Se você optou por rodar os testes com o report htmlextra, você gerou um arquivo html com o resultado dos testes e para verificar as validações você pode abrir a pasta **newman** que foi criada no local em que os arquivos de collection e environment se encontram.


## Entre em contato

email:gleycianacsombra@gmail.com

linkedin: https://www.linkedin.com/in/gleyciana-campelo/




