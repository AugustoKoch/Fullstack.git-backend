# Fullstack.git-backend

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)

Este projeto é uma API para gravação, edição e listagem de usuários e livros em um sistema de biblioteca, foi feita usando Java, Java Spring e MySQL como banco de dados.

A API foi feita para avaliação na matéria de Fullstack.

## Pré-requisitos

Antes de começar, certifique-se de ter o seguinte instalado:

1. Java (JDK) 11
2. Maven 3.9.6
3. MySQL Workbench 8
4. MySQL Server 8


## Instalação

1. Clone o repositório:

   ```bash
   git clone https://github.com/AugustoKoch/Fullstack.git-backend.git

2. Navegue para o diretório do projeto

   ```bash
   cd Fullstack.git-backend

3. Configure o banco de dados:

   Crie um banco de dados MySQL e configure as credenciais no arquivo application.properties:

   ```bash
   spring.datasource.url=jdbc:mysql://localhost:3306/nome_do_banco_de_dados
   spring.datasource.username=usuario
   spring.datasource.password=senha

4. Compile e execute a aplicação:

   ```bash
   mvn spring-boot:run

A API ficará disponível em http://localhost:8080/api