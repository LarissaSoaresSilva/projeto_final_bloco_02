<p align="center">
  <img src="https://github.com/user-attachments/assets/64d3f6ef-503c-44eb-9f5d-5062fae30c75" alt="Banner do Projeto">
</p>

<h1 align="center">🕹️ Projeto Final - Bloco 02 | Generation Brasil</h1>

<p align="center">
  <img src="https://img.shields.io/badge/status-em%20desenvolvimento-purple?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Java-17-blueviolet?style=for-the-badge&logo=java&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring_Boot-2.7.5-brightgreen?style=for-the-badge&logo=spring&logoColor=white" />
  <img src="https://img.shields.io/badge/Maven-3.8.6-orange?style=for-the-badge&logo=apachemaven&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/Insomnia-4000BF?style=for-the-badge&logo=insomnia&logoColor=white" />
</p>

<p align="center">
  <a href="#descrição-do-projeto">Descrição</a> • 
  <a href="#tecnologias-utilizadas">Tecnologias</a> • 
  <a href="#funcionalidades">Funcionalidades</a> •
  <a href="#estrutura-do-projeto">Estrutura do Projeto</a> • 
  <a href="#como-executar">Excutar Localmente</a> • 
  <a href="#melhorias-futuras">Melhorias</a>
</p>

##

## 📝 Descrição do Projeto

Este projeto consiste em uma aplicação Java desenvolvida como parte do Bloco 02 do curso de formação da Generation Brasil. O objetivo principal é implementar um sistema de gerenciamento de produtos, permitindo operações de CRUD (Create, Read, Update, Delete) com persistência de dados.

## 🚀 Tecnologias Utilizadas

- Java 17

- Maven

- Spring Boot

- JPA/Hibernate

- MySQL

- Insomnia

##

## ⚙️ Funcionalidades

- Cadastro de produtos com atributos como nome, descrição, preço e quantidade.

- Listagem de todos os produtos disponíveis.

- Atualização de informações dos produtos.

- Remoção de produtos do sistema.

- Busca de produtos por nome ou categoria.

- Validações básicas nos campos.  

##

## 📁 Estrutura do Projeto

O projeto segue a estrutura padrão de aplicações Spring Boot:
``` 
projeto_final_bloco_02/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── generation/
│   │   │           └── projeto/
│   │   │               ├── controller/
│   │   │               ├── model/
│   │   │               ├── repository/
│   │   │               └── ProjetoApplication.java
│   │   └── resources/
│   │       ├── application.properties
│   │       └── static/
│   └── test/
├── pom.xml
└── README.md
```
##

## 🛠️ Como Executar

1. Pré-requisitos:

- Java 17 instalado.

- MySQL instalado e em execução.

- IDE de sua preferência (IntelliJ, Eclipse, VS Code).

2. Clone o repositório:
```
git clone https://github.com/LarissaSoaresSilva/projeto_final_bloco_02.git
```
3.Execute a aplicação:
- Via IDE: execute a classe ProjetoApplication.java.

- Via terminal:
```
./mvnw spring-boot:run
```
5. Acesse a aplicação:

A API estará disponível em http://localhost:8080.

##

## 💡 Melhorias Futuras

Integração com banco de dados PostgreSQL

Autenticação com Spring Security

Deploy em nuvem (Heroku, Render ou Railway)

Integração com frontend Angular ou React

##

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests.

##

## 👩🏻‍💻 Desenvolvedora

Feito com 💜 por Larissa Soares!

