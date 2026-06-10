# Arquitetura

Este documento descreve a arquitetura em nivel de produto. Detalhes de implementacao, estrutura interna de classes, banco de dados e codigo-fonte sao privados.

## Visao Geral

O THOTH e uma aplicacao web server-side, com interface renderizada no servidor e persistencia em banco de dados relacional.

## Componentes Principais

- Interface web para usuarios finais.
- Camada de controle de rotas e requisicoes.
- Camada de regras de negocio.
- Camada de persistencia.
- Banco de dados relacional.
- Geracao de relatorios em PDF.
- Controle de autenticacao e autorizacao.

## Tecnologias

- Java.
- Spring Boot.
- Thymeleaf.
- Spring Security.
- JPA/Hibernate.
- MySQL.
- iTextPDF.
- Docker.

## Implantacao

O sistema pode ser empacotado em containers Docker, permitindo execucao local sem instalacao direta de Java ou MySQL no computador final.

Em uma instalacao local, a aplicacao e o banco rodam em containers separados, preservando os dados em volume Docker.

## Privacidade da Implementacao

Este repositorio nao contem:

- Codigo-fonte.
- Modelagem detalhada do banco.
- Scripts internos de deploy.
- Arquivos de ambiente.
- Credenciais.
- Regras privadas de implementacao.
