# Microservicio de Configuración (Config Server) - Spring Cloud

Este es un microservicio de configuración implementado utilizando Spring Cloud Config Server. Proporciona una solución centralizada para la gestión y distribución de la configuración a través de múltiples microservicios en un entorno de arquitectura de microservicios.

## Funcionalidades

- **Gestión centralizada de la configuración:** Permite almacenar la configuración en un repositorio centralizado (como Git) y distribuirla a múltiples microservicios.
- **Configuración basada en entornos:** Admite la configuración basada en entornos, lo que permite tener diferentes configuraciones para diferentes entornos (por ejemplo, desarrollo, prueba, producción).
- **Actualización dinámica de la configuración:** Proporciona la capacidad de actualizar la configuración en tiempo de ejecución sin necesidad de reiniciar los microservicios.
- **Seguridad:** Integración con mecanismos de seguridad como autenticación y autorización para proteger la configuración sensible.

## Tecnologías Utilizadas

- Java
- Spring Boot
- Spring Cloud Config Server
- Git (o cualquier otro repositorio de configuración compatible)

## Configuración

Para usar este microservicio de configuración en tu proyecto, simplemente conéctalo como cliente de Spring Cloud Config en tu aplicación y especifica la URL del servidor de configuración en las propiedades de la aplicación.

## Uso

1. Clona este repositorio en tu entorno local.
2. Configura tus propiedades de la aplicación en los archivos YAML o properties en el repositorio de configuración.
3. Inicia el servicio de configuración (`Config Server`) ejecutando la aplicación Spring Boot.
4. Conecta tus microservicios como clientes de Spring Cloud Config para acceder a la configuración centralizada.

## Contribución

Si encuentras algún error o deseas contribuir con nuevas características, siéntete libre de crear un pull request o abrir un issue en este repositorio.

## Autor

Patricia
