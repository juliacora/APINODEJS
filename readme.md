# Documentação da API
Definir local do computador para criar a pasta do projeto
```
mkdir NOME_DO_PROJETO
```
Acessar a pasta do projeto
```
cd NOME_DO_PROJETO
```
Abrir pasta no vs
```
code .
```
Iniciar gerenciador de pacotes node
```
npm init -y
```
Criar arquivo .gitignore
```
touch .gitignore
```
Criar arquivo .env
```
touch .env
```
Instalar pacotes para rodar a API
```
npm i express nodemon dotenv
```
* express: será o servidor pai
* nodemon: irá atualizar os arquivos alterados sem parar o servidor
* dotenv: gerenciador de variaveis de ambiente

Adicionar pastas e arquivos no .gitignore
```
node_modules
.env
```