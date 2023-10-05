 <p> <h1 align="center">Consumindo a API do Twitter com Python</h1></p>


### Consumindo a API do Twitter com Python usando o Tweep
   Projeto em anexo desenvolvido pelo mentor Guilherme Carvalho/Python Consultant, Oak Solution
   Arquivo back-pyproject.toml, é o arquivo original, criei pyproject.toml com as versões atuais já que o curso apresenta uma versão mais antiga. Mas o propósito de ter criado essa versão atualizado foi para fins de entendimento o assunto proposto.
   Por está usando windwos 8 não teve como fazer os testes com docker, mas a didática do curso foi ótima.

---

## Projeto de Consumo da API do Twitter em Python

 Ao longo do desenvolvimento deste projeto, aprendemos  diversos conceitos e habilidades essenciais para a programação e o desenvolvimento de aplicativos. 

### Tecnologias Utilizadas 📚

- **Python 3.8.x:**  Aprendemos os fundamentos da linguagem Python, incluindo estruturas de dados, funções, loops e condicionais.

- **FastAPI:** Utilizaremos o FastAPI para criar uma API web eficiente em Python. Criando rotas, definir modelos de dados, validar entradas e gerar documentação automática usando o Swagger.

- **Tweepy:** Utilizaremos a biblioteca Tweepy para simplificar a interação com a API do Twitter. Você aprenderá como instalar, configurar e utilizar bibliotecas externas para simplificar tarefas complexas.

- **MongoDB:** Integramos  o MongoDB, um banco de dados NoSQL, para armazenar e recuperar dados. Aprendemos a configurar um banco de dados, executar consultas e manipular documentos JSON.

- **Docker e Docker Compose:** Utilizamos o Docker e o Docker Compose para criar ambientes de desenvolvimento isolados. Isso mostrará como gerenciar dependências e ambientes de forma eficaz.

- **Testes Automatizados:** Aprendemos  como configurar e executar testes automatizados com o pytest para garantir a qualidade do código e identificar erros.

- **Documentação de API:** Utilizamos o Swagger para gerar documentação automática da API, ensinando como criar APIs bem documentadas.

### Passos para Começar ✋

1. **Instale o Docker e o Docker Compose:** Certifique-se de que o Docker e o Docker Compose estejam instalados no seu computador.

2. **Ambiente Virtual com Poetry:** Utilize o Poetry para criar um ambiente virtual. Isso ajudará a gerenciar dependências Python de forma eficaz. Siga os comandos abaixo:

   ```sh
   pip install poetry  # Instala o Poetry
   poetry init  # Inicializa o projeto com o Poetry
   poetry lock  # Atualiza o arquivo poetry.lock com as dependências
   poetry install  # Cria um ambiente virtual
   poetry shell  # Ativa o ambiente virtual no terminal
   deactivate  # Desativa o ambiente virtual quando não estiver em uso
   ```

3. **Execute a Aplicação:** Execute os seguintes comandos para rodar a aplicação:

   ```sh
   poetry shell  # Ativa o ambiente virtual
   python main.py  # Inicia o servidor da aplicação
   ```

4. **Acesse a Documentação:** Acesse o [Swagger UI](http://localhost:8000/docs) para explorar todos os endpoints da API que você irá criar.

5. **Rodando Testes 🧪:** Para executar os testes automatizados, siga os comandos abaixo:

   ```sh
   poetry shell  # Ativa o ambiente virtual
   pytest  # Executa os testes
   ```

Este projeto abrange desde os conceitos básicos da programação em Python até a criação de uma API funcional que interage com serviços externos e armazena dados em um banco de dados. Ele também enfatiza boas práticas de desenvolvimento, convenções de codificação e controle de versão.

#### Curso Formação Python Developer da Dio.me administrado pelo mentor Guilherme Carvalho/Python Consultant, Oak Solution

[DIO](https://www.dio.me/).
