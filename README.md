# Vehículos REST (Backend Java - Spring Boot)

## Descripción

Proyecto backend con **Spring Boot** que ofrece una API REST para gestionar vehículos (autos y motos). Permite realizar operaciones CRUD 



## Características

* CRUD completo para vehículos y motos
* Almacenamiento de imágenes en un directorio local
* Conexion con backend


## Requisitos

* **Java 17+**
* **Maven**




# La aplicación se inicia en:
`http://localhost:8080`



## Estructura básica


src/main/java/com/example/
  ─ VehiculosRestApplication.java   # Clase principal
  ─ config                       # Configuración CORS y recursos estáticos
  ─ vehiculos
       ─ controller                # Controladores REST
       ─ dto                       # Objetos de transferencia
       ─ model                 # Entidades JPA
       ─ repository              # Repositorios JPA
       ─ service                   # Lógica de negocio y manejo de archivos


## Endpoints

* `/api/vehiculos` — operaciones CRUD de vehículos.
* `/api/motos` — operaciones CRUD de motos.
* `/uploads` — ruta pública para acceder a imágenes guardadas.


