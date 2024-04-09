
# Desafio-dio-Explorando-Padroes-Projetos-Java

(Desafio-dio-Explorando-Padroes-Projetos-Java-CRUD-Mário)



# 📃 Desafio Padrões de Projeto

Repositório para resposta de Desafio de Padrões de Projeto do Bootcamp de Java e SpringBoot da DIO.



## ☑️ Objetivos do Desafio

Praticar diferentes Padrões de Projetos utilizados no dia a dia dos desenvolvedores e fazer um projeto prático que incorpora os padrões apresentados em aula. São eles:

- Facade
- Singleton
- Strategy



## 📂 Distribuição das Pastas

**Padrões de Projeto**: Pasta com as atividades de prática relacionadas aos assuntos vistos em aula.

**lab-padroes-projeto-spring**: Pasta com o desafio de projeto, que consiste em criar uma lista de pessoas adiquirindo seus endereços pela API Via Cep.


## ✔️ Tecnologias Utilizadas

- Java
- Spring Framework
- Swagger
- API Via Cep
- - Módulos do SpringBoot utilizados:
    - Spring Web, Spring Data JPA, H2 Database (banco de dados em memória), Open Feign (Client Rest Declarativo), Swagger (documentação).

==============================================================================================================================================================





## Sobre o Desafio

Padrões de Projeto são "soluções consolidadas para problemas recorrentes" no desenvolvimento de software. Eles podem ser categorizados em três grupos principais:

* **Padrões Criacionais:**

  Relacionados a instanciação de um ou múltiplos objetos. Principal objetivo é criar objetos. Um exemplo é o Singleton, que garante que uma classe tenha apenas uma instância.


* **Padrões Comportamentais:**

  Conseguir definir ou até obrigar determinados comportamentos da estrutura de código; implementar soluções para inferir comportamentos numa determinada estrutura. 
* Ex.: Strategy.

    * *ChatGPT*: Tratam do comportamento das classes e objetos. O Strategy é um exemplo, pois permite definir diferentes algoritmos para resolver o mesmo problema.
  

* **Padrões Estruturais:**


  Transformações de informação, orquestrar eventuais integrações com sistemas externos. Ex.: Facade.

    * *ChatGPT*: Lidam com a composição de classes e objetos. O Facade é um exemplo, pois fornece uma interface simplificada para um conjunto de subsistemas.



========================================================================================================================================================

# CRUD de Clientes

![spring](https://img.shields.io/badge/-Spring_Boot-white?style=for-the-badge&logo=Spring-Boot&color=6DB33F&logoColor=white)
![swagger](https://img.shields.io/badge/-Swagger-white?style=for-the-badge&logo=swagger&color=85EA2D&logoColor=white)

Este é um projeto Spring Boot desenvolvido como parte do curso **Explorando Padrões de Projetos na Prática com Java** durante o **bootcamp Explorando Padrões de Projetos na Prática com Java**. 
O projeto é um exemplo de um aplicativo de gerenciamento de clientes que realiza operações CRUD (Create, Read, Update, Delete) usando Spring Boot, JPA para persistência de dados em um banco de dados H2, 
Lombok para melhorar a produtividade no desenvolvimento, Springdoc OpenAPI para documentação da API e Spring Cloud OpenFeign para consumo da API Via Cep.

## Recursos

- **Spring Boot**: Um framework Java para construção de aplicativos web e serviços RESTful.
- **JPA (Java Persistence API)**: Uma API de persistência de dados que facilita o armazenamento e recuperação de objetos em um banco de dados relacional.
- **H2 Database**: Um banco de dados relacional em memória para simplificar o desenvolvimento e os testes.
- **Lombok**: Uma biblioteca que simplifica a criação de classes Java, reduzindo a necessidade de escrever código boilerplate.
- **Springdoc OpenAPI Starter WebMvc UI**: Uma ferramenta para gerar automaticamente documentação interativa da API usando a especificação OpenAPI.
- **Spring Cloud OpenFeign**: Uma biblioteca para simplificar a criação de clientes REST para consumir APIs externas, como a API `Via Cep`.

## Como executar o projeto

1. Clone este repositório para o seu ambiente de desenvolvimento:

```bash
git clone https://github.com/SilvioCavalcantiBonfim/CRUD-de-Clientes.git
```
2. Navegue até o diretório do projeto:

```bash
cd CRUD-de-Clientes
```
3. Execute o aplicativo Spring Boot usando o Maven:

```bash
mvn spring-boot:run
```
O aplicativo estará disponível em http://localhost:8080. Você pode acessar a documentação da API em http://localhost:8080/swagger-ui.html.

## Endpoints da API

A API oferece os seguintes endpoints para gerenciamento de clientes:

- `GET /api/clients`: Retorna todos os clientes.

- `GET /api/clients/{id}`: Retorna um cliente pelo ID.
- `POST /api/clients`: Cria um novo cliente.
- `PUT /api/clients/{id}`: Atualiza um cliente existente pelo ID.
- `DELETE /api/clients/{id}`: Exclui um cliente pelo ID.

## Documentação da API

A documentação da API é gerada automaticamente usando o Springdoc OpenAPI. Você pode acessá-la em http://localhost:8080/swagger-ui.html após iniciar o aplicativo.

## Consumindo a API Via Cep

Este projeto utiliza o Spring Cloud OpenFeign para consumir a API Via Cep. A integração está configurada para buscar informações de endereço com base no CEP informado.

## Contribuições

Contribuições são bem-vindas! Se você quiser contribuir para este projeto, sinta-se à vontade para abrir um pull request.

## Autor

Mário Pereira lacerda (ADAPTADO PARA EXERC. DESAFIO)

<p align="right"><a href="#"> 🔝 Voltar ao Topo 🔝 </a></p>
