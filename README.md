# To-Do List
__________________________________
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![Apache Maven](https://img.shields.io/badge/Apache%20Maven-C71A36?style=for-the-badge&logo=Apache%20Maven&logoColor=white)

Este projeto é uma aplicação backend de **lista de tarefas** desenvolvida em **Java**, utilizando o **Spring Boot** e gerenciada com **Apache Maven**. A aplicação permite ao usuário criar, visualizar, editar e excluir tarefas, além de marcar tarefas como concluídas.

---

## 🚀 Funcionalidades

- ✅ Adicionar novas tarefas com **descrição** e **prazo**
- ✏️ Editar detalhes das tarefas existentes
- 📌 Marcar tarefas como **concluídas**
- 🗑️ Excluir tarefas da lista
- 📋 Listar todas as tarefas ou filtrar por status

---

## 🛠️ Tecnologias Utilizadas

- **Java 17**
- **Spring Boot**
- **Spring Web**
- **Spring Data JPA**
- **H2 Database** (ou outro banco relacional à sua escolha)
- **Apache Maven**
- **Lombok** (para reduzir boilerplate)
- **Swagger/OpenAPI** (opcional para documentação da API)

---

## 📦 Como Executar o Projeto

### Pré-requisitos

- Java 17+
- Maven 3.8+

### Passos

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/todo-list-api.git
cd todo-list-api

# Compile e execute
./mvnw spring-boot:run
