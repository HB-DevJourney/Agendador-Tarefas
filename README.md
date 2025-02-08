# 📅 Agendador de Tarefas - API

O **Agendador de Tarefas** é uma API desenvolvida em **Java 21** e **Spring Boot 3.4.2**, utilizando uma arquitetura de **microsserviços** e o padrão **BFF (Backend for Frontend)**. O projeto foi criado para gerenciar tarefas de forma eficiente, com funcionalidades como autenticação de usuários, agendamento de tarefas, notificações por e-mail e uma camada BFF para otimizar a comunicação com o frontend.

Este projeto está em fase de aprendizagem e pode conter erros ou melhorias a serem implementadas. Sinta-se à vontade para contribuir ou sugerir melhorias!

---

## 🚀 Funcionalidades

A API é dividida em quatro microsserviços principais:

1. **Usuário**:
   - Registro e autenticação de usuários.
   - Gerenciamento de perfis.
   - Segurança com **Spring Security** e **JWT**.

2. **Agendador de Tarefas**:
   - Criação, edição, exclusão e listagem de tarefas.
   - Armazenamento de tarefas no **MongoDB**.

3. **Notificação**:
   - Envio de e-mails para lembrar os usuários de tarefas importantes.

4. **BFF (Backend for Frontend)**:
   - Agregação de dados dos outros microsserviços para otimizar a comunicação com o frontend.
   - Utiliza **OpenFeign** para se comunicar com os demais microsserviços.

---

## 🛠️ Tecnologias Utilizadas

- **Linguagem**: Java 21
- **Framework**: Spring Boot 3.4.2
- **Banco de Dados**:
  - **PostgreSQL**: Para gerenciamento de usuários.
  - **MongoDB**: Para armazenamento de tarefas.
- **Autenticação**: Spring Security com JWT (JSON Web Tokens)
- **Documentação da API**: Swagger/OpenAPI
- **Comunicação entre microsserviços**: OpenFeign
- **Containerização**: Docker (com Dockerfile, mas não publicado no Docker Hub)
- **Ferramentas de Desenvolvimento**: Maven, Git, IntelliJ IDEA

---

## 📚 Documentação da API

A documentação da API está disponível via **Swagger/OpenAPI**. Após iniciar o projeto, acesse:
- **Swagger UI**: `http://localhost:8080/swagger-ui.html`
- **OpenAPI JSON**: `http://localhost:8080/v3/api-docs`

---

## 🔗 Links Úteis

- **Trello (Kanban)**: [Kanban Agendador de Tarefas](https://trello.com/b/igadWkFO/kanban-agendador-de-tarefas)

- **API de Usuário**: [Usuario](https://github.com/HB-DevJourney/usuario)
- **API do Gerenciador**: [Agendador de Tarefas](https://github.com/HB-DevJourney/Agendador-de-Tarefas)
- **API de Notificação**: [Notificacao](https://github.com/HB-DevJourney/Notificacao)
- **API do BFF**: [BFF Agendador de Tarefas](https://github.com/HB-DevJourney/BFF-Agendador-de-Tarefas)

---

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

