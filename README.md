# Project: Demo DAO JDBC

Este é um projeto desenvolvido como parte de meus estudos sobre a integração de aplicações Java com bancos de dados utilizando **JDBC (Java Database Connectivity)**. Ele tem como objetivo demonstrar a implementação manual de um padrão **DAO (Data Access Object)** para realizar operações CRUD.

## 💡 Objetivos
- Explorar o uso do JDBC para interagir com um banco de dados relacional.
- Implementar o padrão DAO manualmente para abstrair operações de persistência.
- Demonstrar como realizar operações CRUD com SQL em Java.

## 🛠️ Tecnologias Utilizadas
- **Java 17**: Linguagem principal.
- **JDBC**: Interface Java para comunicação com bancos de dados.
- **MySQL**: Banco de dados utilizado no projeto.
- **SQL**: Linguagem para manipulação de dados no banco.
- **Maven**: Gerenciador de dependências e build.

## 📂 Estrutura do Projeto
- **Entities**: Representação das tabelas do banco de dados como classes Java.
- **DAO Interfaces**: Definição dos métodos de persistência.
- **DAO Implementations**: Implementação das operações CRUD utilizando JDBC.
- **DB**: Configurações de conexão e utilitários para o banco de dados.

## 📝 Funcionalidades Implementadas
1. Conexão com o banco de dados utilizando JDBC.
2. Operações CRUD:
   - **Create**: Inserção de dados no banco.
   - **Read**: Consulta de registros.
   - **Update**: Atualização de dados.
   - **Delete**: Exclusão de registros.
3. Gerenciamento manual de transações.
4. Implementação de um padrão DAO para separação das responsabilidades.

## 🔗 Como Executar
1. **Clone o repositório**:
   ```bash
   git clone https://github.com/JoaoSobrinhoMoD/demo-dao-jdbc.git
   
## 🛡️ Considerações Finais
Este projeto foi inspirado e desenvolvido com base no curso Java COMPLETO Programação Orientada a Objetos + Projetos do Prof. Nelio Alves. Ele foi essencial para aprofundar meu entendimento de como interagir diretamente com bancos de dados utilizando Java e JDBC.
