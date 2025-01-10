

---

# Argus - Gerenciamento Condominial

[![Java Version](https://img.shields.io/badge/Java-23-orange?style=flat-square)][java-url]  
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.0-brightgreen?style=flat-square)][spring-url]

**Argus** é um aplicativo para gerenciamento condominial projetado para facilitar a administração de condomínios, oferecendo funcionalidades como gestão de usuários, comunicações internas, reservas de áreas comuns, entre outros. O foco é entregar uma solução eficiente, segura e intuitiva para síndicos e moradores.

![](header.png)

## Instalação

### Requisitos
Antes de começar, certifique-se de ter os seguintes itens instalados:
- Uma IDE de preferência (**IntelliJ IDEA** recomendada)
- **JDK 23**
- **Maven**

### Passos para Instalação
1. Clone o repositório:
   ```bash
   git clone https://github.com/ProjetoARGUS/ArgusAPI.git
   ```
2. Acesse o diretório do projeto:
   ```bash
   cd ArgusAPI
   ```
3. Execute os testes para verificar a integridade da aplicação:
   ```bash
   mvn test
   ```
4. Inicie o projeto:
   ```bash
   mvn spring-boot:run
   ```

## Tecnologias Utilizadas

O projeto **Argus** utiliza as seguintes tecnologias:
- **Java 23**
- **Spring Boot**
- **Spring Security**
- **Java Data JPA**
- **PostgreSQL**
- **Docker**
- **JUnit**
- **AWS**
- **RabbitMQ** para mensageria
- **H2** (para testes)
- **JWT** (Json Web Tokens) para autenticação e segurança

## Exemplo de Uso

O Argus oferece diversas funcionalidades para a gestão condominial, como:
- Criação e gerenciamento de usuários.
- Comunicações internas seguras.
- Reservas de áreas comuns com disponibilidade em tempo real.

Abaixo, um exemplo básico de uso para rodar a aplicação:

```bash
mvn spring-boot:run
```

Para mais exemplos e funcionalidades, consulte a [Wiki][wiki].

## Configuração para Desenvolvimento

1. Clone o repositório:
   ```bash
   git clone https://github.com/ProjetoARGUS/ArgusAPI.git
   ```
2. Acesse o diretório do projeto:
   ```bash
   cd ArgusAPI
   ```
3. Execute os testes:
   ```bash
   mvn test
   ```

---

## Histórico de Lançamentos

- **0.0.1**
    - versão beta.



## Meta

**Equipe do Projeto Argus** – [@ProjetoArgus](https://twitter.com/ProjetoArgus)  
Distribuído sob a licença [GNU General Public License v3.0](./LICENSE.md).

[Repositório Oficial](https://github.com/ProjetoARGUS/ArgusAPI/)

## Como Contribuir

1. Faça um fork do projeto (<https://github.com/ProjetoARGUS/ArgusAPI/fork>).
2. Crie sua branch para o recurso (`git checkout -b feature/fooBar`).
3. Commit suas mudanças (`git commit -am 'Adicionei fooBar'`).
4. Envie para sua branch (`git push origin feature/fooBar`).
5. Crie um novo Pull Request.

<!-- Markdown link & img dfn's -->
[java-url]: https://www.oracle.com/java/technologies/javase-downloads.html
[spring-url]: https://spring.io/projects/spring-boot
[wiki]: https://github.com/ProjetoARGUS/ArgusAPI/wiki

--- 
