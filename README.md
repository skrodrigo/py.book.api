# book.py.api

API de Gerenciamento de uma biblioteca pessoal

# Documentação da API

A API Books API é uma API simples para gerenciar um catálogo de livros. Ela fornece operações para listar todos os livros, criar um novo livro, obter um livro pelo ID, atualizar um livro pelo ID e deletar um livro pelo ID.

## Endpoints

- `GET /books`: Lista todos os livros.
- `POST /books`: Cria um novo livro.
- `GET /books/{book_id}`: Obtém um livro pelo ID.
- `PUT /books/{book_id}`: Atualiza um livro pelo ID.
- `DELETE /books/{book_id}`: Deleta um livro pelo ID.

## Schemas

### Book

- `id`: ID do livro (integer).
- `title`: Título do livro (string).
- `author`: Autor do livro (string).

### BookInput

- `id`: ID do livro (integer).
- `title`: Título do livro (string).
- `author`: Autor do livro (string).

## Responses

- `200`: Sucesso.
- `201`: Livro criado.
- `400`: JSON inválido ou campos obrigatórios faltando.
- `404`: Livro não encontrado.

## Servidor

A API está disponível em http://localhost:8000.
