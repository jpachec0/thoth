# Arquitetura

Este documento descreve a arquitetura em nível de produto. Detalhes de implementação, estrutura interna de classes, banco de dados e código-fonte são privados.

## Visão Geral

O THOTH é uma aplicação web server-side, com interface renderizada no servidor e persistência em banco de dados relacional.

## Componentes Principais

- Interface web para usuários finais.
- Camada de controle de rotas e requisições.
- Camada de regras de negócio.
- Camada de persistência.
- Banco de dados relacional.
- Geração de relatórios em PDF.
- Controle de autenticação e autorização.

## Tecnologias

- Java.
- Spring Boot.
- Thymeleaf.
- Spring Security.
- JPA/Hibernate.
- MySQL.
- iTextPDF.
- Docker.

## Implantação

O sistema pode ser empacotado em containers Docker, permitindo execução local sem instalação direta de Java ou MySQL no computador final.

Em uma instalação local, a aplicação e o banco rodam em containers separados, preservando os dados em volume Docker.

## Privacidade da Implementação

Este repositório não contém:

- Código-fonte.
- Modelagem detalhada do banco.
- Scripts internos de deploy.
- Arquivos de ambiente.
- Credenciais.
- Regras privadas de implementação.
