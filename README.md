# AssistantsReport

## Descripción

**AssistantsReport** es un sistema desarrollado en Java para la gestión de reportes, estructurado bajo una arquitectura en capas que separa:

- Lógica de negocio  
- Acceso a datos  
- Interfaz de usuario  

El proyecto utiliza:
- JDBC para la conexión con PostgreSQL  
- Patrón DAO para la persistencia  
- Organización modular para facilitar mantenimiento y escalabilidad  

---

## Arquitectura

El sistema sigue una arquitectura en capas:

- **Capa de presentación** → Interfaz gráfica  
- **Capa lógica** → Procesamiento y reglas de negocio  
- **Capa de persistencia** → Acceso a base de datos (DAO + Conexión)  

---

## Documentación UML

La documentación del sistema incluye diagramas UML elaborados con **Astah**, lo que permite una mejor comprensión de:

- Estructura del sistema  
- Relaciones entre clases  
- Diseño general  

Además, el repositorio incluye el archivo:


DiagramaClases.puml


---

## Instalación de Astah Professional

Para visualizar o modificar los diagramas UML, se recomienda utilizar **Astah Professional**.

### Pasos de instalación:

1. Ir a la página oficial:  
   https://astah.net/downloads/

2. Seleccionar **Astah Professional**

3. Descargar el instalador según tu sistema operativo:
   - Windows  
   - macOS  
   - Linux  

4. Ejecutar el instalador

5. Seguir las instrucciones de instalación

6. Iniciar la aplicación:
   - Activar versión de prueba  
   - O ingresar licencia válida  

---

## Requisitos del Proyecto

- Java JDK  
- PostgreSQL  
- JavaFX SDK  

### Librerías incluidas:

- PostgreSQL JDBC Driver (`postgresql-42.7.7.jar`)  
- jBCrypt (`jbcrypt-0.4.jar`)  

---

## Objetivo del Proyecto

Este sistema está orientado a prácticas académicas de ingeniería de software, aplicando:

- Buenas prácticas de desarrollo  
- Principios de diseño  
- Separación de responsabilidades  
- Documentación formal mediante UML  

---

## Autor

Proyecto académico desarrollado como parte de formación en Ingeniería de Software.
