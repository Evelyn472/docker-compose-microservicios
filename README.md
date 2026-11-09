# Proyecto de Microservicios — Gestión Académica

## Descripción
Proyecto académico desarrollado para implementar una arquitectura de microservicios orientada a la gestión de información académica.

El sistema organiza sus funcionalidades en servicios independientes que se comunican mediante una arquitectura distribuida.

## Componentes del proyecto

- **API Gateway:** punto de entrada para las solicitudes.
- **Eureka Server:** registro y descubrimiento de servicios.
- **MS Asistencia:** gestión de asistencia.
- **MS Comunicaciones:** gestión de comunicaciones.
- **MS Cursos:** gestión de cursos.
- **MS Horarios:** gestión de horarios.
- **MS Profesores:** gestión de profesores.

## Tecnologías y herramientas

- Java
- Spring Boot
- Spring Cloud / Eureka
- API Gateway
- Docker Compose
- Bases de datos: configuración pendiente de verificar.

## Ejecución

El proyecto incluye un archivo `docker-compose.yml` para coordinar los servicios.

Antes de ejecutar, se deben revisar las variables de entorno, conexiones de bases de datos y puertos configurados.

## Objetivo académico

Aplicar conocimientos de desarrollo backend, arquitectura de microservicios, comunicación entre servicios y despliegue de aplicaciones.

**Tipo de proyecto:** Académico.
