# Foro Hub - REST API
Foro Hub es una REST API que simula diversos endpoints de un foro, incluyendo el inicio de sesión de usuarios, la creación de tópicos, su actualización y su eliminación lógica en una base de datos. Este proyecto forma parte de la formación de ALura Latam ONE (Oracle Next Education).

## ¿Cómo funciona?
Esta aplicación utiliza Spring Framework para la creación y seguridad de endpoints, y JWT para la autenticación de los usuarios. Una vez que el usuario envía la petición de inicio de sesión a la ruta correspondiente, puede acceder a los métodos relacionados con los tópicos, como consultar, crear, actualizar y borrar.

Cada tópico creado por los usuarios se guarda en una base de datos MySQL. Cuando un usuario consulta o actualiza un tópico, se muestra el nombre del autor de la creación o actualización. Por último, un usuario puede borrar un tópico, pero para mantener la integridad de la base de datos y la persistencia de los datos, este borrado es solo de forma lógica.

## Instalación
1. [Descargue o clone el proyecto.](https://github.com/IsaacCuautle/Foro-Hub/releases/download/v1.0.0/Foro-Hub.zip)
2. Inicie el proyecto en el IDE de su preferencia.
3. Instale las dependencias necesarias desde el archivo pom.xml.
4. Configure las propiedades del proyecto.
5. Inicie el proyecto.

> Recuerde que debe contar con una instalación de MySQL para las bases de datos.

## Imagenes del proyecto

<img width="500rem" src="https://github.com/IsaacCuautle/Foro-Hub/assets/65583500/bf4ef284-face-41a0-8e24-799c2865e9f8">
<img width="500rem" src="https://github.com/IsaacCuautle/Foro-Hub/assets/65583500/b375a75a-c105-4b46-9d9a-25ec582bfdd5">
<img width="500rem" src="https://github.com/IsaacCuautle/Foro-Hub/assets/65583500/b4e97d11-dd26-4012-9731-afd488254d1d">
<img width="500rem" src="https://github.com/IsaacCuautle/Foro-Hub/assets/65583500/05ee96c7-e3df-4eab-b4bf-eaadb474ec52">



## Herramientas y tecnologias utilizadas
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white) ![IntelliJ IDEA](https://img.shields.io/badge/IntelliJIDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)
