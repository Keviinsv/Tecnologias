# Sistema de Gestión de Tareas (Todo-list)

## Descripción
Este proyecto es un sistema de gestión de tareas (Todo-list)
que permite a los usuarios registrarse, iniciar sesión y gestionar 
sus tareas de forma sencilla. El backend está desarrollado con Node.js 
y utiliza SQLite como base de datos para almacenar los datos de los usuarios y las tareas. 
El frontend es una interfaz simple desarrollada con HTML que permite a los usuarios interactuar con el sistema.

## Propósito
El objetivo de este proyecto es proporcionar una aplicación básica
de gestión de tareas con funcionalidades como la creación,
edición, eliminación, y visualización de tareas.
Además, implementa un sistema de autenticación de usuarios
para proteger las operaciones relacionadas con las tareas.

## Instalación

1. Clona este repositorio en tu máquina local:
   ```bash
   git clone https://github.com/tu_usuario/todo-list.git
   cd todo-list
   npm install (Librerias necesarias)
   1.1 Y para ejecutar el proyecto localmente ocupa el siguiente codigo:
   node (El nombre de tu servidor).js

# Uso del Sistema
Regístrate en el sistema usando el formulario de registro.
Inicia sesión con tus credenciales.
Añade, edita o elimina tus tareas desde la interfaz.
Filtra las tareas por estado: completadas o pendientes.

# Rutas de la API
POST /api/register: Registrar un nuevo usuario.
POST /api/login: Iniciar sesión.
GET /api/tasks: Obtener todas las tareas del usuario autenticado.
POST /api/tasks: Crear una nueva tarea.
PUT /api/tasks/: Actualizar una tarea.
DELETE /api/tasks/: Eliminar una tarea.

# Autenticación
El sistema utiliza JWT (JSON Web Tokens) para la autenticación de usuarios.
Los usuarios deben estar autenticados para acceder a las rutas relacionadas con las tareas.
Se protege el acceso a las tareas con un middleware de autenticación.

# Tecnologías Utilizadas
Node.js: Entorno de ejecución del servidor.
Express: Framework para gestionar rutas y middleware.
SQLite: Base de datos para almacenar usuarios y tareas.
bcrypt: Librería para encriptar contraseñas.
JWT (JSON Web Tokens): Sistema de autenticación basado en tokens.


Este `README.md` cubre todos los aspectos solicitados, incluyendo la descripción del proyecto, las instrucciones
de instalación y ejecución, los detalles sobre la autenticación, las rutas de la API,
y las tecnologías utilizadas. Puedes adaptarlo según tus necesidades.
