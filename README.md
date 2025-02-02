# API REST de Gestión de Usuarios

Este proyecto es una **API REST** desarrollada en **Node.js** que permite gestionar usuarios en una base de datos. Proporciona operaciones básicas como crear, leer, actualizar y eliminar usuarios (CRUD). Está diseñada para ser utilizada como backend en aplicaciones web o móviles.

## Características principales
- **Operaciones CRUD**: Crear, leer, actualizar y eliminar usuarios.
- **Autenticación**: Soporte para autenticación de usuarios (si está implementada).
- **Base de datos**: Utiliza una base de datos (por ejemplo, MongoDB, MySQL, etc.) para almacenar la información de los usuarios.
- **Manejo de errores**: Respuestas claras y manejables en caso de errores.
- **Validación de datos**: Validación de los datos de entrada para garantizar la integridad de la información.

# Actualización registro de peticiones HTTP
Se ha añadido un middleware en `app.js` que registra en la consola todas las peticiones HTTP recibidas por el servidor. Esto facilita la depuración y el seguimiento de las solicitudes.