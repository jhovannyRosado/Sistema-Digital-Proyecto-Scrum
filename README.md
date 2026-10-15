# Sistema Digital - Proyecto Scrum

## Nombre del Sistema
Sistema Digital para la Gestión y Consulta de Información Académica

## Objetivo
Desarrollar un sistema digital que centralice la gestión de información académica, facilitando la organización, consulta y seguimiento de requisitos bajo metodología Scrum.

## Problema que Resuelve
Falta de organización centralizada de la información académica, manejo manual de documentos, pérdida de trazabilidad y dificultad para el seguimiento del avance del proyecto.

## Funcionalidades Principales
1. Gestión de usuarios y roles
2. Gestión de requisitos académicos
3. Consulta de información organizada
4. Dashboard de avance del proyecto
5. Documentación y control de versiones

## Arquitectura Seleccionada
Arquitectura en Capas con patrón MVC y enfoque Cliente-Servidor. Permite separación de responsabilidades, escalabilidad y mantenibilidad.

## Organización Frontend y Backend
**Frontend (Cliente):** Es la parte visual con la que interactúa el usuario. Su responsabilidad es renderizar la interfaz, gestionar la experiencia del usuario (UX), validar formularios y consumir los servicios del backend. Está ubicado en la carpeta /frontend.

**Backend (Servidor):** Es el cerebro del sistema. Su responsabilidad es procesar la lógica de negocio, gestionar la autenticación, aplicar las reglas de validación y gestionar los datos. Está ubicado en la carpeta /backend.

**Comunicación:** La comunicación se realiza mediante API REST. El frontend envía peticiones HTTP (GET, POST, PUT, DELETE) en formato JSON al backend. El backend procesa la petición y devuelve una respuesta JSON que el frontend muestra al usuario.

## Herramientas Utilizadas
- Git para el control de versiones
- GitHub para alojar el repositorio
- GitHub Issues para el seguimiento de incidencias y tareas
- GitHub Projects para organizar el avance del proyecto
- Markdown para la documentación técnica

## Estado Actual del Proyecto
Versión v0.1.0 - Versión inicial controlada. Repositorio organizado con estructura frontend/backend, documentación base y gestión de avance con Projects e Issues. 4 commits versionados en main.

## Registro de 5 Cambios o Avances
1. Creación del repositorio y estructura inicial del proyecto Scrum.
2. Definición de la arquitectura inicial del sistema.
3. Implementación de la estructura base frontend/backend en el repositorio.
4. Configuración del tablero de Projects y creación de 16 Issues para seguimiento.
5. Actualización final del README.md con cierre técnico v0.1.0

## Nota Técnica de Versión v0.1.0
**Contiene:** MVP organizado, estructura frontend/backend, documentación técnica completa, tablero de seguimiento.
**Cambios controlados:** 5 commits principales versionados en rama main.
**Pendiente:** Validaciones avanzadas, reportes y despliegue a producción.
**Próximo paso:** v0.2.0 enfocada en revisión de tareas prioritarias y verificación de componentes.
