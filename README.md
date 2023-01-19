# API DE LIVROS - CRUD

## 👉 Índice 

* [Api de Livros - CRUD](#api-de-livros---crud)
* [Índice](#-índice)
* [Descrição do Projeto](#-descrição-do-projeto)
* [Instalação](#-instalacao)
* [Execução](#-execução)
* [Aprendizados](#-aprendizados)
* [Autores](#-autores)

## 💬 Descrição do projeto
  
Neste repositório deixo minha primeira api, um CRUD de livros.

## ⬇️ Instalação

Acesse o site [python.org](http://python.org) e faça download de acordo com o seu sistema operacional. Ao instalar, não se esqueça de selecionar a caixa “Add Python 3.8 to PATH”.

Na Prompt de Comando realizaremos o próximo passo. Execute “pip install notebook” e “jupyter notebook”. Ou podemos simplesmente instalar a extensão “python” no Visual Studio e codar por lá.

Ainda no Terminal, instale o framework Flask para a execução do projeto, com pip install flask.

## 🤔 Aprendizados

Uma api é um lugar para disponibilizar recursos e/funcionalidades

Para o programa funcionar inicialmente você deve baixar o **postman**, usamos para ****requisições e consulta de api.

Para criar uma api é necessário definir as principais etapas: objetivo, URL base, endpoints e os quais são os recursos.

Nesse exemplo:

#1 OBJETIVO: Criar uma api de disponibiliza a consulta, criação, edição e exclusão de livros

#2 URL BASE (local que estaremos fazendo as requisições): local host

#3 ENDPOINTS (tipos de funcionalidades que será adicionados na api):

- localhost/livros (GET)
- localhost/livros/id (POST)
- localhost/livros/id (GET)
- localhost/livro/id (PUT)
- localhost/livros/id (DELETE)

#4 QUAIS RECURSOS - Livros

Podemos usar tanto o Django quanto o Flask para a criação de api. Por ser mais simples que o Django e este projeto ter um intuito mais introdutório, usarei o Flask (framework) para a criação. Usamos o comando pip install flask, para baixar o framework, assim que o Python for instalado e configurado corretamente.

## 👥 Autores

- [@GabiCmg](https://github.com/GabiCmg)
