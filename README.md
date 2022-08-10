# Proyecto de ventas con Spring

Backend de una aplicación de ventas con Spring Boot

## Comenzando

Para comenzar clona el proyecto a tu computadora usando el repositorio de GIT

### Pre-requisitos

* Docker
* Java 11
* PostgreSQL (Incluido en el dockerfile)

### Instalación

Ejecuta el archivo de docker

```bash
$ docker-compose up -d
```

Instalar las dependencias

```bash
$ ./mvnw install
```

Ejecuta el proyecto

```bash
$ ./mvnw spring-boot:run
```

## Construido con:

Se usaron las siguientes tecnologías para desarrollar el proyecto:

* [Spring Boot](https://spring.io/projects/spring-boot) - Facilita la creación de aplicaciones independientes basadas en Spring.
* [Maven](https://maven.apache.org/) - Administrador de dependencias.
* [PostgreSQL](https://www.postgresql.org/) - Base de datos
* [Docker](https://www.docker.com/)
