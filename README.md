# My Precious Spa API

## Descripción
La API REST de My Precious Spa es una aplicación cliente desarrollada por un Full Stack Developer para satisfacer las necesidades puntuales de los usuarios de la tienda de joyas My Precious Spa. Esta API permite a los usuarios interactuar de forma eficiente, mantenible y eficaz con la tienda, brindando funcionalidades como límite de recursos, filtrado por campos, paginación, ordenamiento y una estructura de datos HATEOAS.

## Requisitos
Para ejecutar esta API, deberás seguir los siguientes pasos:

1. Ejecutar el siguiente script SQL en tu terminal psql para crear la base de datos y la tabla que utilizaremos:
sql
Copy code
-- Script SQL
2. Clonar el repositorio de la API desde GitHub.

3. Instalar las dependencias del proyecto ejecutando el siguiente comando:
npm install

4. Configurar las variables de entorno necesarias, como la conexión a la base de datos y las claves de API, siguiendo el archivo .env.example.

5. Ejecutar la API mediante el siguiente comando:
npm start

## Funcionalidades

La API REST de My Precious Spa proporciona las siguientes funcionalidades:

Límite de recursos: Los usuarios pueden especificar el número máximo de recursos que desean obtener en una sola solicitud.

Filtro de recursos por campos: Los usuarios pueden filtrar los recursos según diferentes campos, lo que les permite realizar búsquedas específicas.

Paginación: Los usuarios pueden obtener los recursos de forma paginada, especificando el número de página y la cantidad de recursos por página.

Ordenamiento: Los usuarios pueden ordenar los recursos según un campo específico, en orden ascendente o descendente.

Estructura de datos HATEOAS: La API proporciona una estructura de datos HATEOAS (Hypermedia as the Engine of Application State) que incluye enlaces relacionados a los recursos, lo que permite a los clientes navegar y descubrir las diferentes acciones disponibles.

¡Gracias por utilizar la API REST de My Precious Spa! Esperamos que esta aplicación cliente moderna y dinámica sea de gran ayuda para la tienda de joyas. Si tienes alguna pregunta o sugerencia, no dudes en comunicarte con nosotros.
