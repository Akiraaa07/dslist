# DSList
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/Akiraaa07/dslist/blob/main/LICENSE)

##  Sobre o projeto
O **DSList** é uma aplicação **back-end** desenvolvida durante o **Intensivão Java Spring** promovido pela [DevSuperior](https://devsuperior.com.br/).  
O sistema permite gerenciar coleções de jogos, possibilitando listagem, organização e manipulação de dados de forma eficiente.

---

##  Modelo Conceitual
![Modelo Conceitual](https://github.com/user-attachments/assets/2344801f-9655-45d6-b64f-8389002ee11e)

---

## Tecnologias utilizadas

### Back-end
- Java 11+
- Spring Boot
- JPA / Hibernate
- Maven
- SQL

### Banco de Dados
- H2 Database (ambiente de testes)
- PostgreSQL (ambiente de produção)

---
## Funcionalidades da API
A aplicação disponibiliza os seguintes endpoints REST:

### Games
- **GET /games** → Retorna a lista de todos os jogos cadastrados.
  <img width="1918" height="1037" alt="image" src="https://github.com/user-attachments/assets/925844e9-913d-4266-a378-87e9f4b2fb68" />
  
- **GET /games/{id}** → Retorna os detalhes de um jogo específico pelo seu `id`.
  <img width="1920" height="1040" alt="image" src="https://github.com/user-attachments/assets/5ee670e0-060c-48d1-9fd3-54d85293a9db" />


### Lists
- **GET /lists** → Retorna todas as listas de jogos.
  <img width="1920" height="1040" alt="image" src="https://github.com/user-attachments/assets/47792332-dd93-4678-87d1-cdf22ecb8249" />

- **GET /lists/{id}/games** → Retorna os jogos pertencentes a uma lista específica.
  <img width="1920" height="1039" alt="image" src="https://github.com/user-attachments/assets/a7e3e3ed-08c4-4e84-81e2-de9d10858f6c" />

- **POST /lists/{id}/replacement** → Altera a posição de jogos dentro de uma lista.
  <img width="1920" height="1039" alt="image" src="https://github.com/user-attachments/assets/ebe7e6da-f30d-4f4c-976a-20110213a59c" />
  Lista após alteração:
  <img width="1920" height="1040" alt="image" src="https://github.com/user-attachments/assets/00efb186-b412-41da-a15d-0be5fa167f9b" />

---

## Como executar o projeto

### Pré-requisitos
- [Java 11+](https://www.oracle.com/java/technologies/javase/jdk11-archive-downloads.html) instalado

###  Passo a passo
```bash
# Clonar o repositório
git clone https://github.com/devsuperior/sds1-wmazoni

# Acessar a pasta do projeto backend
cd backend

# Executar a aplicação
./mvnw spring-boot:run
```

## Autor
Igor Akira Bortolini Tateishi

https://www.linkedin.com/in/igor-akira-dev/
