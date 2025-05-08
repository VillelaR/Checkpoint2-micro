# 🩺 API REST - Sistema de Agendamento Médico com Spring Boot

Este projeto é uma API desenvolvida com **Java 17** e **Spring Boot**, voltada para o gerenciamento de **pacientes**, **profissionais da saúde** e **consultas médicas**. A aplicação foi criada com fins educacionais e segue os princípios de APIs RESTful, utilizando dados armazenados em memória.

---

## 🚀 Funcionalidades da Aplicação

- 👤 Cadastro, edição, visualização e exclusão de pacientes
- 🩻 Gestão completa de profissionais de saúde
- 📅 Agendamento e gerenciamento de consultas (opcional)
- 📑 Documentação da API disponível via Swagger UI

---

## 📋 Requisitos para execução

Antes de rodar o projeto, você precisa ter instalado:

- ✅ Java 17 ou superior
- ✅ Maven 3.6 ou mais recente
- ✅ Uma IDE de sua preferência (IntelliJ IDEA, Eclipse, VS Code)

---

# 🧹 Estrutura do Projeto

```
src/main/java/br/com/fiap/checkpoint1/
│
├── controller/       # Controladores da API (REST)
├── dto/              # Data Transfer Objects (DTOs) de entrada e saída
├── model/            # Modelos (Entidades) de Paciente, Profissional e Consulta
├── service/          # Serviços de negócios (regras e persistência em memória)
└── Checkpoint1Application.java  # Classe principal (Spring Boot Starter)
```

---

# 🔗 Referências

- [Documentação do SpringDoc OpenAPI](https://springdoc.org/)
- [Java 17 Download](https://www.oracle.com/java/technologies/downloads/)
- [Spring Boot Documentation](https://spring.io/projects/spring-boot)
- [Swagger OpenAPI 3.0](https://swagger.io/specification/)

---

# Observações Finais

- Este projeto foi desenvolvido como parte de um exercício acadêmico para praticar a construção de APIs REST utilizando Java com o framework Spring Boot.
- Todos os dados são armazenados **em memória**, ou seja, não há persistência em banco de dados externo neste estágio do projeto.
- A estrutura foi baseada em um modelo lógico voltado ao agendamento de consultas em uma clínica médica.
- Pode ser expandido facilmente para incluir autenticação, integração com bancos de dados relacionais (como PostgreSQL ou MySQL), cache e muito mais.
- Recomendado para estudantes e iniciantes que desejam consolidar conhecimentos em **Java, Spring e design de APIs**.

---