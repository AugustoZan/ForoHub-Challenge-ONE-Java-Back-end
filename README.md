# Foro Hub
==========

## Descripción
Foro Hub es una aplicación web que simula las funcionalidades de un foro en línea. Permite a los usuarios registrarse, iniciar sesión y crear tópicos de discusión. La aplicación utiliza Spring Framework y JWT para la autenticación y seguridad.

## Características
### Registro de usuarios
### Inicio de sesión con autenticación JWT
### Creación de tópicos de discusión
### Gestión de usuarios y tópicos

## Tecnologías utilizadas
* Spring Framework
* Spring Security
* JWT (JSON Web Tokens)
* MySQL

## Instalación
### Requisitos previos
* Java 11 o superior
* Spring Framework 2.3.0 o superior
* MySQL 8.0 o superior

### Pasos de instalación
1. Clona el repositorio utilizando el comando `git clone https://github.com/IsaacCuautle/Foro-Hub.git`
2. Importa el proyecto en tu IDE favorito (Eclipse, IntelliJ, etc.)
3. Configura la base de datos MySQL creando una base de datos llamada `foro_hub` y un usuario con permisos de lectura y escritura
4. Edita el archivo `application.properties` para configurar la conexión a la base de datos
5. Ejecuta la aplicación utilizando el comando `mvn spring-boot:run`

## Uso
### Registro de usuarios
Envía una solicitud POST a `http://localhost:8080/api/register` con un cuerpo JSON que contenga la información del usuario (username, password, email)
La aplicación devuelve un token JWT que debe ser utilizado en las solicitudes subsiguientes

### Inicio de sesión
Envía una solicitud POST a `http://localhost:8080/api/login` con un cuerpo JSON que contenga las credenciales del usuario (username, password)
La aplicación devuelve un token JWT que debe ser utilizado en las solicitudes subsiguientes

### Creación de tópicos
Envía una solicitud POST a `http://localhost:8080/api/topics` con un cuerpo JSON que contenga la información del tópico (title, content)
La aplicación devuelve el tópico creado con su ID asociado

### Gestión de usuarios y tópicos
Utiliza las solicitudes GET, POST, PUT y DELETE para gestionar los usuarios y tópicos
