# Java Google Books API

Este projeto é um exercício em **Java** que utiliza as classes `HttpClient`, `HttpRequest` e `HttpResponse` para consumir a **API do Google Books**.

O programa solicita ao usuário o **título de um livro** e realiza uma consulta à API, exibindo no terminal as **informações retornadas** sobre o livro em formato JSON.

## 🛠 Tecnologias utilizadas
- Java 11 ou superior
- Google Books API
- java.net.http

## 📌 Como funciona
1. O usuário digita o título de um livro
2. O programa monta a URL de consulta com o parâmetro de busca
3. Uma requisição HTTP GET é enviada para a API do Google Books
4. A resposta da API é exibida no terminal

## 🎯 Objetivo
Projeto desenvolvido para fins de estudo, com foco em:
- Consumo de APIs REST em Java
- Uso das classes HTTP nativas da linguagem
- Manipulação de parâmetros em URLs
- Integração com serviços externos

## 📚 Observação
A API do Google Books retorna os dados em formato JSON, contendo informações como título, autores e descrição, dependendo do resultado da busca.
