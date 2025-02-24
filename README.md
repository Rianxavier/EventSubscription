# NLW Connect - API de Inscrição em Eventos

Este projeto foi desenvolvido durante a **NLW Connect** da Rocketseat. A aplicação consiste em uma **API Rest em Java** utilizando **Spring Boot** e **Maven**, permitindo a inscrição de usuários em eventos e a criação de um ranking com base nas indicações.

## 🚀 Tecnologias Utilizadas

O projeto foi construído com as seguintes tecnologias:

- **Java** - Linguagem principal da aplicação
- **Spring Boot** - Framework para construção da API
- **Maven** - Gerenciamento de dependências
- **JPA e JDBC** - Integração com o banco de dados **MySQL**
- **Postman** - Testes das requisições

## 📌 Funcionalidades Implementadas

- Cadastro de usuários no evento
- Sistema de indicações de novos participantes
- Ranking dos usuários que mais convidaram pessoas
- Integração com banco de dados MySQL

## 🔧 Como Executar o Projeto

### Pré-requisitos

Para rodar o projeto localmente, você precisará ter instalado:

- **Java 17+**
- **Maven**
- **MySQL** (ou outro banco de dados relacional configurado no `application.properties`)

### Passos para execução

1. **Clone o repositório:**

   ```sh
   git clone https://github.com/seu-usuario/nlw-connect-api.git
   cd nlw-connect-api
   ```

2. **Configure o banco de dados**

   - Atualize as credenciais no arquivo `application.properties`.

3. **Instale as dependências:**

   ```sh
   mvn install
   ```

4. **Execute a aplicação:**

   ```sh
   mvn spring-boot:run
   ```

5. **Testar os endpoints:**

   - Utilize **Postman** ou outra ferramenta de testes para consumir a API.

## 📜 Licença

Este projeto foi desenvolvido para fins educacionais durante a NLW da Rocketseat.
