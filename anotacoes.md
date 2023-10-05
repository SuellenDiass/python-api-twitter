
Consumindo a API do Twitter com Python

Observações instalei as dependencias atualizadas:

Primeiro instale o poetry no python:
comando: pip install poetry
comando: poetry init
comando para atualizar o arquivo poetry.lock de acordo com as dependências especificadas no pyproject.toml: poetry lock 
comando: poetry install (cria um ambiente virtual)
comando: poetry shell (ativa ambiente virtual no terminal)
comando: deactivate (desativa o ambiente virtual)
Depois de instalar as dependências, execute os seguintes comandos para rodar a aplicação.


[tool.poetry]
name = "dio-twitter-py"
version = "2.0.0"
description = "teste"
authors = ["Suellen <suellen.diass@yahoo.com.br>"]
readme = "README.md"

[tool.poetry.dependencies]
python = "^3.11"
tweepy = "^4.14.0"
pymongo = "^4.5.0"


[build-system]
requires = ["poetry-core"]
build-backend = "poetry.core.masonry.api"


Dependencias que o projeto tem:
contruir uma api teste
consumir uma api rest de terceiro:twitter
salvar dados em algum banco: mongodb
stop innplementando

Arquivo poetry lock : verifica se as dependências estão nas versões corretas
Arquivo setup.cfg: referente a PEP8 convenção dos codigos
Aquivo editorconfig: determina o estilo de formatação
Arquivo docker-compose: um arquivo descritor, facilita o comando para o docker
Arquivo pyrpoject.toml:
Arquivo pytest.ini: 
Arquivo main.py:

# dio-twitter-py

Projeto criado durante o living code [Consumindo a API do Twitter com Python](https://docs.google.com/presentation/d/11DkkyQUIloVQLm8i6hN6w3xyUaP4WSRE/edit?usp=sharing&ouid=102662434190974209165&rtpof=true&sd=true).

## Tecnologias 📚

- Python 3.8.x
- FastAPI
- MongoDB

## Requisitos ✋

- Docker
- Docker compose

## Instalação 💽

Instale o [Docker](https://www.docker.com) e [Docker compose](https://docs.docker.com/compose/) no seu computador.

## Rodando a aplicação 🛸

```sh
poetry shell
python main.py
```

Acesso o [Swagger UI](http://localhost:8000/docs) para listar todos os endpoints.

Use `Ctrl+C` para finalizar o processo servidor.

## Rodando os testes 🧪

```sh
poetry shell
pytest
```
