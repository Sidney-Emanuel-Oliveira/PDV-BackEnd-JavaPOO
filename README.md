# PDV-BackEnd-JavaPOO

BackEnd do projeto do PDV-Posto-Combustível

## 🚀 Tecnologias

- Java 17
- Spring Boot 3.2.5
- PostgreSQL
- Maven
- Swagger/OpenAPI
- Spring Data JPA

## 📋 Pré-requisitos

- Java JDK 17 ou superior
- PostgreSQL instalado e rodando
- Maven (ou usar o mvnw incluído)

## 🔧 Configuração

1. Clone o repositório:
```bash
git clone https://github.com/Sidney-Emanuel-Oliveira/PDV-BackEnd-JavaPOO.git
cd PDV-BackEnd-JavaPOO
```

2. Configure o banco de dados PostgreSQL:
   - Crie um banco chamado `pdvpostocombustivel`
   - Copie o arquivo `.env.example` para `.env` (ou edite `application.properties`)
   - Configure suas credenciais do PostgreSQL

3. Execute os scripts SQL da pasta `_docs_e_scripts`:
   - `PASSO1_CRIAR_BANCO.sql`
   - `PASSO2_CRIAR_TABELAS_E_DADOS.sql`

## ▶️ Como executar

```bash
mvn clean install
mvn spring-boot:run
```

Ou usando o Maven Wrapper:
```bash
./mvnw clean install
./mvnw spring-boot:run
```

O servidor estará disponível em: `http://localhost:8080`

## 📚 Documentação da API

Após iniciar o servidor, acesse:
- Swagger UI: `http://localhost:8080/swagger-ui.html`
- API Docs: `http://localhost:8080/api-docs`

## 🔗 Frontend

O frontend deste projeto está disponível em: [PDV-FrontEnd-JavaPOO](https://github.com/Sidney-Emanuel-Oliveira/PDV-FrontEnd-JavaPOO)

## 📝 Licença

Este projeto está sob a licença MIT.

