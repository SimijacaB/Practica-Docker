# Dockerización de una API en Java

Este proyecto es una práctica basada en un tutorial para aprender a dockerizar una API desarrollada en Java utilizando un entorno de contenedores Docker. El objetivo es crear una imagen de Docker para la API y facilitar su despliegue y ejecución en cualquier entorno.

## Objetivos del proyecto
- Configurar un entorno Docker para ejecutar una API desarrollada en Java.
- Crear un `Dockerfile` optimizado para aplicaciones Java.
- Implementar un archivo `docker-compose.yml` en caso de requerir servicios adicionales, como bases de datos.
- Ejecutar y probar la API en un contenedor Docker.

## Características principales
1. **Configuración del Dockerfile**  
   El `Dockerfile` incluye instrucciones para empaquetar la aplicación Java, especificar la versión del JDK y definir cómo se ejecutará la API dentro del contenedor.

2. **Compatibilidad con servicios adicionales**  
   Se incluye un archivo `docker-compose.yml` opcional para integrar otros servicios (bases de datos, sistemas de caché, etc.) de manera sencilla.

3. **Ejecución local en contenedor**  
   La API dockerizada puede ejecutarse en el entorno local con comandos básicos de Docker y Docker Compose.

## Estructura del proyecto
```plaintext
├── src/                    # Código fuente de la API
├── target/                 # Archivos generados tras la compilación (jar/war)
├── pom.xml                 # Configuración de Maven
├── Dockerfile              # Configuración para construir la imagen Docker
├── docker-compose.yml      # Orquestación de servicios
└── README.md               # Documentación del proyecto

