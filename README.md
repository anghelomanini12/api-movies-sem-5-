# EVALUACIÓN SEMANA 5 - TESTING MOVIE API

El entregable consiste en crear los tests para la API de movie realizada en el 3.

Debe haber como mínimo estos 19 tests:

# Actors
GET /actors
POST /actors
DELETE  /actors/:id
PUT /actors/:id

# Genres
GET /genres
POST /genres
DELETE  /genres/:id
PUT /genres/:id

# Directors
GET /directors
POST /directors
DELETE  /directors/:id
PUT /directors/:id

# Movies
GET /movies
POST /movies
DELETE  /movies/:id
PUT /movies/:id
POST /movies/:id/actors
POST /movies/:id/directors
POST /movies/:id/genres

# CRITERIOS DE EVALUACIÓN:

Hay 19 test, cada uno vale 0.53 pts




# Template de Servidor Express y Sequelize

Este es un template básico para un servidor Express con sequelize con configuraciones comunes. Utiliza las siguientes librerías:

* cors (v2.8.5): Middleware para permitir solicitudes HTTP desde diferentes dominios.

* dotenv (v16.3.2): Carga variables de entorno desde un archivo .env.

* express (v4.18.2): Marco web minimalista para la construcción de aplicaciones web y API.

* helmet (v7.1.0): Middleware que ayuda a proteger las aplicaciones Express configurando varios encabezados HTTP.

* pg (v8.11.3): Controlador de PostgreSQL para Node.js.

* pg-hstore (v2.3.4): Serializador/deserializador para datos JSON y hstore en PostgreSQL.

* sequelize (v6.35.2): ORM para interactuar con bases de datos relacionales.




