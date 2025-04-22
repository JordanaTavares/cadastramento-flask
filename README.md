# Aplicação de Cadastro com Flask

Projeto desenvolvido para a aula de Desenvolvimento Seguro, o objetivo era criar uma aplicação de registro, incluindo autenticação de usuários e verificação de dados nos formulários.

## Executando com Docker

Siga os passos abaixo para subir a aplicação Flask usando Docker:

### 1. Clone este repositório

Use o comando abaixo para clonar o projeto:

```bash
git clone https://github.com/jordanatavares/cadastramento-flask.git
```
### 2. Crie a imagem Docker

Dentro da pasta do projeto, execute:
```bash
docker build -t cadastramento-flask .
```
### 3. Inicie o container
```bash
docker run -p 5000:5000 cadastramento-flask
```
### 4. Abra o navegador

Rode a aplicação com:
```bash
http://localhost:5000
```
