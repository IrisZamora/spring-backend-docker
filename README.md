# Proyecto API REST - Spring Boot + Docker

Este proyecto es una API REST desarrollada en Java 21 con Spring Boot y PostgreSQL. La aplicación permite realizar operaciones CRUD sobre una base de datos.

# Tecnologías utilizadas

- Java 21
- Spring Boot
- PostgreSQL
- Docker y Docker Compose
- Maven


# Ejecución con Docker Compose

# Requisitos previos

- Tener instalado:
  - Docker desktop
  - TablePlus (Para hacer la conexion a la base de datos de forma local)
  - Postman (Para hacer las pruebas del lado del cliente)
  - crear archivo .env basado en el archivo .env.template

# Comando para correr el proyecto: 
  Compilará la imagen del backend, levantará PostgreSQL y dejará la API escuchando en http://localhost:8080
  - docker-compose up --build 

