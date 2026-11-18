# Introducción paso a paso al framework web [Flask]

**Curso y código (septiembre de 2026)**: 👉 **[https://stahe.github.io/ales-flask-sept-2026/](https://stahe.github.io/ales-flask-sept-2026/)**

## Autor

El código y el curso fueron escritos íntegramente por **Claude**, la IA de Anthropic, que es la **autora única**, a petición de Serge Tahé.

## Descripción general

Este curso ofrece una guía paso a paso para construir una aplicación web MVC con el framework **Flask** (Python). Las páginas HTML las genera el servidor mediante vistas **Jinja2**, sin un framework JavaScript del lado del cliente.

Es la continuación del curso [Introducción paso a paso al framework web [Spring MVC](https://stahe.github.io/ales-springmvc-sept-2026/)] y sigue exactamente la misma progresión. Ese curso, a su vez, seguía a los cursos de [ASP.NET Core MVC](https://stahe.github.io/ales-aspnetcoremvc-sept-2026/) y [NestJS](https://stahe.github.io/ales-nestjs-html-sept-2026/). Los ejemplos tienen los mismos números y abordan los mismos temas: un lector familiarizado con alguno de estos cursos puede comparar los frameworks ejemplo por ejemplo.

El curso se divide en dos partes:

- **28 ejemplos breves**, cada uno centrado en un concepto específico:
  - acciones, enrutamiento, respuestas y redirecciones;
  - enlace de parámetros y validación (Pydantic);
  - vistas Jinja2, plantillas y macros;
  - formularios WTForms, patrón Post/Redirect/Get y protección CSRF;
  - internacionalización;
  - ámbitos de datos;
  - ciclo de vida de la solicitud;
  - autenticación JWT, roles y CAPTCHA;
  - arquitectura en capas con SQLAlchemy y MySQL.
- **Un caso de estudio completo**: *RdvMedecins*, una aplicación de gestión de citas para un consultorio médico. Cuenta con tres roles de usuario (administrador, médicos, pacientes), funciona en francés e inglés y está protegida contra bots. Todos sus archivos están comentados en el curso.

## Tecnologías

Python 3.12+ · Flask 3.1 · Jinja2 · Werkzeug · Flask-WTF / WTForms · Pydantic · SQLAlchemy 2.1 · PyMySQL · PyJWT · bcrypt · Babel · waitress · Bootstrap 5.3 · MySQL 8 / MariaDB

## Requisitos previos

- Python 3.12 o superior;
- Visual Studio Code, con la extensión “Python” de Microsoft;
- MySQL 8 (por ejemplo, con Laragon en Windows) o MariaDB;
- curl.

Las instrucciones de instalación de estas herramientas se proporcionan en los apéndices del curso.

## Contenido del repositorio de código

- `examples/`: los 28 ejemplos, cada uno de los cuales es una pequeña aplicación Flask (puerto 5000);
- `rdvmedecins2-flask/`: el caso de estudio (puerto 8081), con su script SQL y su `README.md`;
- `directory.txt`: la estructura completa de directorios.
