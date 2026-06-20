# Cook.

> Meu Livro de Receitas Pessoal

Aplicação web desenvolvida com Spring Boot para cadastro e gerenciamento de receitas culinárias. O sistema permite organizar receitas por categoria, pesquisar receitas cadastradas e marcar favoritas para acesso rápido.

Projeto desenvolvido como atividade prática da disciplina de Programação para Servidores Web.

---

## 🚀 Tecnologias Utilizadas

* Java 17
* Spring Boot
* Spring MVC
* Thymeleaf
* Spring Data JPA
* H2 Database
* Maven
* Bootstrap 5

---

## ✨ Funcionalidades

* Cadastro de usuários
* Login e logout
* Cadastro de receitas
* Edição de receitas
* Exclusão de receitas
* Visualização detalhada das receitas
* Busca por nome
* Filtro por categoria
* Sistema de favoritos
* Dados iniciais carregados automaticamente

---

## 📂 Estrutura do Projeto

```text
src
├── main
│   ├── java
│   │   └── br/edu/ifms/cook
│   │       ├── controller      # Controladores da aplicação
│   │       ├── dto             # Objetos de transferência de dados
│   │       ├── entity          # Entidades JPA
│   │       ├── repository      # Acesso ao banco de dados
│   │       ├── service         # Regras de negócio
│   │       └── CookApplication.java
│   │
│   └── resources
│       ├── static
│       │   ├── css             # Arquivos de estilo
│       │   └── img             # Imagens da aplicação
│       │
│       ├── templates           # Páginas Thymeleaf
│       │   ├── auth
│       │   ├── fragments
│       │   └── receita
│       │
│       ├── application.properties
│       └── data.sql
---

## ▶️ Como Executar

### Pré-requisitos

* Java 17 ou superior
* Maven

### Clonar o repositório

```bash
git clone https://github.com/RhafaelyReis/cook.git
cd cook
```

### Executar a aplicação

```bash
mvn spring-boot:run
```

Acesse:

```text
http://localhost:8080
```

---

## 🗄️ Banco de Dados H2

O projeto utiliza H2 Database para armazenamento dos dados.

Console do H2:

```text
http://localhost:8080/h2-console
```

Configurações de acesso:

```text
JDBC URL: jdbc:h2:file:./data/cookdb
User: sa
Password:
```

---

## 📚 Conceitos Aplicados

* Arquitetura MVC
* Injeção de Dependência
* CRUD Completo
* Sessões HTTP
* Persistência com JPA/Hibernate
* Relacionamentos entre entidades
* Templates com Thymeleaf

---

## 👩‍💻 Autora

**Rhafaely Reis**

GitHub: https://github.com/RhafaelyReis
