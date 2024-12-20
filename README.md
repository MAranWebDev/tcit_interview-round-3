# TCIT Challenge Full-Stack Semi Senior & Junior - Interview Round 3 (React, Node.js, PostgreSQL)

## Uso

- link client: http://localhost/
- link api: http://localhost/api/posts
- descarga, instala y arranca docker desktop: https://www.docker.com/get-started/
- prueba la aplicación con los siguientes comandos:

      iniciar app - ` docker-compose up -d app `

      crear base de datos - ` docker exec --user=node reactnode_server_1 bash -c "npm run migrate:latest" `

      destruir app - ` docker-compose down -v `

## Requerimientos

#### Descripción

- El trabajo consiste en crear una pequeña aplicación en react, con Redux, que maneje Posts.
- Sólo se debe llamar al endpoint que entrega la lista completa de posts una sola vez por cada vez que se cargue la vista.

#### Ejemplo Visual

![visual sample](/readme.png)

#### Los Posts deben tener

- Nombre
- Descrpición

#### Buenas prácticas

- JSON camel-case
- JS camel-case

#### Funcionalidades aplicación web hecha con React y Redux

- Insertar posts
- Eliminar posts
- Listar posts
- Filtrar posts por nombre localmente

#### Estructura

- Formulario
- Filtro
- Lista

#### Backend (API JSON) en Node.js

- Crear posts: Deberá retornar el post creado
- Eliminar posts: Deberá retornar el post eliminado
- Obtener lista de posts: Deberá retornar todos los posts
- BD en postgreSQL
