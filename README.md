# Storio Marketplace

Por Alexandre Magno e Gustavo Pacheco

## O que é?

O Storio Marketplace é um sistema de vitrine e venda de produtos virtual, destacando itens, parceiros e ofertas para clientes, além de proporcionar features de gerenciamento conveniente. Tudo é feito à base da conveniência - facilitando a interatividade de tanto usuários quanto administradores.

## Microserviços

### Usuários:

- [Account](https://github.com/alemagno10/platform.store.account)
- [Account-resource](https://github.com/alemagno10/platform.store.account-resource)

### Autenticação:

- [Auth](https://github.com/alemagno10/platform.store.auth)
- [Auth-resource](https://github.com/alemagno10/platform.store.auth-resource)

### Parceiros:

- [Partner](https://github.com/alemagno10/platform.store.partner)
- [Partner-resource](https://github.com/alemagno10/platform.store.partner-resource)

### Produtos:

- [Products](https://github.com/gustavolp1/platform.store.products)
- [Products-resource](https://github.com/gustavolp1/platform.store.products)

### [Gateway](https://github.com/alemagno10/platform.store.gateway)

### [Discovery](https://github.com/alemagno10/platform.store.discovery)

### [OPS](https://github.com/alemagno10/platform.store.ops)

### [Docker](https://github.com/alemagno10/platform.store.docker-api)

## Como rodar?

Siga as instruções a seguir:

### Pré-requisitos

Instale os seguintes programas, se ainda não os tiver:

- [Java JDK](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)
- [Apache Maven](https://maven.apache.org/download.cgi)
- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

### Docker

1. Clone o repositório de docker:

```git clone https://github.com/alemagno10/platform.store.docker-api```

2. Entre na pasta do repositório:

```cd platform.store.docker-api```

3. Execute o comando:

```docker-compose up```

### Maven

1. Clone o repositório:

```git clone https://github.com/alemagno10/platform.store```

2. Entre na pasta do repositório:

```cd platform.store```

3. Execute o comando:

```mvn spring-boot:run```