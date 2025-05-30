# 🧪 Testes Unitários 

## 🎯 Objetivo

Implementar e validar testes unitários para o controlador de usuários em uma aplicação Spring Boot, utilizando **JUnit 5** e **Mockito**.

## 🛠️ Tecnologias Utilizadas

- Java 11+
- Spring Boot
- Spring Web
- Spring Data JPA
- MariaDB
- JUnit 5
- Mockito

## ▶️ Como Executar

1. Configure o banco de dados MariaDB e atualize as credenciais no arquivo `application.properties`.
2. Rode a aplicação com:

## ✅ Sobre os Testes

- Os testes estão na pasta: `src/test/java`
- Foco no controlador de usuários (`UserController`)
- Uso de **Mockito** para simular interações com o serviço (`UserService`)
- Testes cobrem casos de sucesso e falhas

## 📌 Resultados

- Todos os testes foram executados com sucesso
- Comportamentos esperados validados com entradas válidas e inválidas
- Testes independentes do banco de dados graças ao uso de mocks

