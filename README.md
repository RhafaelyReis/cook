# Cook.
> Meu Livro de Receitas Pessoal

Aplicação web para cadastro e gerenciamento de receitas culinárias, 
desenvolvida com Spring Boot como projeto prático da disciplina de 
Engenharia de Software II.

## Tecnologias

- Java 17 + Spring Boot 4
- Spring MVC + Thymeleaf
- Spring Data JPA + H2
- Bean Validation
- Maven

## Como executar

**Pré-requisitos:** Java 17+ e Maven instalados.

```bash
git clone https://github.com/RhafaelyReis/cook.git
cd cook
mvn spring-boot:run
```

Acesse `http://localhost:8080`

O console do banco H2 fica em `http://localhost:8080/h2-console`
- JDBC URL: `jdbc:h2:mem:cookdb`
- User: `sa` / Senha: *(vazio)*

## Funcionalidades

- Cadastro, edição e exclusão de receitas
- Busca por nome
- Filtro por categoria
- Dados de exemplo carregados automaticamente

## Estrutura

```
src/main/java/com/cook/
├── controller/
├── model/
├── repository/
└── service/
```
