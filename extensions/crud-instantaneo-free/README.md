# CRUD Instantaneo Free - Gerador de CRUD PT-BR para Node.js

Gere CRUD Node.js em segundos no VS Code, em portugues, sem repeticao manual.

## O que esta extensao gera

- Model
- Controller
- Rotas
- SQL basico

## Como usar

1. Abra uma pasta de projeto no VS Code.
2. Abra a Command Palette e rode: CRUD Instantaneo Free: Gerar arquivos.
3. Informe o nome da entidade (exemplo: Produto).
4. Informe campos no formato nome:tipo separados por virgula.

Exemplo de campos:

nome:string,preco:decimal,ativo:boolean

Saida gerada:

- generated/entidade/models
- generated/entidade/controllers
- generated/entidade/routes
- generated/entidade/sql

## Para quem e

- Dev iniciante em API REST
- Freelancer que quer acelerar setup
- Quem quer testar o fluxo antes da versao Pro

## Limites da versao Free

- Suporte a Node.js
- Ate 5 campos por entidade

## Versao Pro

Se voce precisa de Node.js, C# e PHP, sem limite de campos e com configuracao de pasta de saida, use a versao Pro.

## Comando da extensao

- crudInstantaneoFree.gerar

## Palavras-chave

crud, nodejs, express, sql, gerador crud, pt-br, portugues, api, scaffolding

## Changelog

Veja o historico em CHANGELOG.md.
