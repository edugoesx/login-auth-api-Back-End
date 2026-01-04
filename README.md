# 🛡️ Auth API - Spring Boot & JWT

Este repositório contém o backend de uma aplicação Fullstack de autenticação. O projeto foi desenvolvido para consolidar conhecimentos em segurança de APIs, gerenciamento de tokens e arquitetura REST com Java.

## 🚀 Tecnologias Utilizadas

* **Java** (versão 17 ou superior)
* **Spring Boot** (Framework principal)
* **Spring Security** (Gerenciamento de autenticação e autorização)
* **JWT (JSON Web Token)** (Geração e validação de tokens seguros)
* **Maven** (Gerenciador de dependências)

## ⚙️ Funcionalidades

* **Autenticação Stateless:** Utilização de JWT para sessões seguras sem estado no servidor.
* **Cadastro de Usuários:** Endpoint público para registro de novos usuários.
* **Login Seguro:** Validação de credenciais e retorno de Token JWT.
* **Padrão DTO:** Uso de *Data Transfer Objects* para separar a camada de domínio da camada de apresentação (Request/Response).
* **AuthController:** Controlador dedicado para gerenciar o fluxo de entrada e registro.

## 🛠️ Como executar

1. Clone este repositório:
   git clone https://github.com/edugoesx/login-auth-api-Back-End
   
2. Acesse a pasta do projeto:

cd login-auth-api

3. Configure as variáveis de ambiente ou o arquivo application.properties com as credenciais do seu banco de dados.

4. Execute a aplicação via Maven:
./mvnw spring-boot:run

5. A API estará rodando em http://localhost:8080 (ou a porta configurada).
