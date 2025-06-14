# Go-API

API REST para gerenciamento de tarefas (ToDo) desenvolvida em Golang, utilizando MongoDB como banco de dados.

## Sumário

- [Descrição](#descrição)
- [Requisitos](#requisitos)
- [Instalação](#instalação)
- [Configuração](#configuração)
- [Execução](#execução)
- [Endpoints](#endpoints)
- [Exemplos de Requisição](#exemplos-de-requisição)
- [Licença](#licença)

## Descrição

Esta API permite criar, listar, buscar, atualizar e deletar tarefas. Cada tarefa possui um título e um conteúdo.

## Requisitos

- Go 1.24.1 ou superior
- MongoDB Atlas ou local
- Variável de ambiente `MONGODB_URI` configurada

## Instalação

Clone o repositório e instale as dependências:

```sh
git clone https://github.com/seu-usuario/go-api.git
cd go-api
go mod tidy