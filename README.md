# Projeto Rotten Tomatoes Microsserviços

## Estrutura do projeto
Esse projeto é baseado em uma aquitetura de Microsserviços e depende de outros 2 projetos pra funcionar

- [Serviço de Filmes](https://github.com/zul9an9/movie)
- [Serviço de Review](https://github.com/zul9an9/review)

Segue abaixo o diagrama:

![Diagrama da solução](./img/diagrama.png)

## Configuração

MOVIE_SERVICE_URI => URL de acesso ao serviço de listagem de filmes

REVIEW_SERVICE_URI => URL de acesso ao serviço de listagem de reviews

Exemplo:

MOVIE_SERVICE_URI: http://movies:8181

REVIEW_SERVICE_URI: http://review:80


# rotten-potatoes-ms
