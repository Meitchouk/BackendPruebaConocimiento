# Prueba de Conocimiento para Programador Backend en C#

## Objetivo

Evaluar las habilidades del candidato en el desarrollo de aplicaciones backend utilizando C#, Entity Framework, pruebas unitarias con XUnit, y la configuración de entornos con Docker Compose.

---

## Tareas

### Conexión a la Base de Datos
- Configurar una clase `DbContext` para conectarse a una base de datos PostgreSQL utilizando Entity Framework.

### Migración y Data Seed
- Crear una migración que genere una tabla llamada `MarcasAutos` en la base de datos.
- Implementar un mecanismo de **Data Seed** para cargar la tabla con al menos tres ejemplos de marcas de autos.

### API REST - Consumir Datos
- Crear un controlador (`MarcasAutosController`) con un endpoint para obtener todas las marcas de autos desde la base de datos.

### Pruebas Unitarias
- Implementar pruebas unitarias utilizando XUnit para verificar que el endpoint del controlador devuelve los datos esperados.
- Configurar el entorno de prueba, incluyendo un contexto de base de datos en memoria.

### Docker Compose
- Crear un archivo `docker-compose.yml` que configure dos servicios:
  - PostgreSQL para la base de datos.
  - Otro para la API REST.
- Asegurarse de que la API REST pueda conectarse correctamente a la base de datos PostgreSQL.

---

## Instrucciones Adicionales

- Utilice buenas prácticas de codificación y documente su código cuando sea necesario.
- Proporcione comentarios explicativos en el código para mostrar su comprensión del problema.
- La prueba puede ser realizada utilizando cualquier IDE o editor de texto de su elección.
- Envíe el código y los archivos necesarios comprimidos en un archivo ZIP.

---

## Evaluación

Se evaluará en función de su capacidad para:

- Establecer una conexión eficiente a una base de datos PostgreSQL.
- Diseñar y ejecutar migraciones y seed data.
- Desarrollar un API REST para consumir datos desde la base de datos.
- Implementar pruebas unitarias efectivas utilizando XUnit:
  - **Porcentaje de cobertura al 70%.**
- Configurar entornos de desarrollo y pruebas con Docker Compose.
