# Pruebas aplicaciones web
> [!NOTE]
> Este aplicativo esta hecho para uso libre, acontinuación su función:

## Descripción
Para este proyecto, El área de desarrollo ha agregado una nueva función en la API de Urban.Grocers, así que te pasaron una nueva versión de la API para que la pruebes. Aquí están los requisitos del back-end, La nueva funcionalidad cubre varias áreas:
Ejecutado segun la parametrización de los requerimientos de la app, de acuerdo a la información de la prueba se debe ejecutar lo siguiente:

1. Trabajar con los kits: la capacidad de agregar comestibles a un kit. El endpoint es POST /api/v1/kits/{id}/products. El endpoint devolverá 400 Bad Request (Solicitud no válida) cuando la longitud de la lista de productos resultante (no las cantidades acumuladas de cada producto) sea superior a 30.
2. Consultar los servicios de entrega: la capacidad de comprobar si el servicio de entrega Order and Go está disponible y cuánto cuesta. El endpoint es POST /order-and-go/v1/delivery.
3. Consultar la parte "Couriers" (Servicios de entrega) de apiDoc y la sección de cálculo del precio de entrega en los requisitos.
4. Analiza los requisitos para la nueva funcionalidad del back-end de Urban.Grocers. Estudiar la documentación de la API en Apidoc.
5. Diseñar casos de pruebas en una lista de comprobación para cubrir la funcionalidad que se esta probando.
6. Crear una lista de comprobación segun los requerimientos
7. Prueba la API a través de Postman 
8. Crear informes de errores a Jira si es necesario.

> [!TIP]
> Estos son los requisitos para poder ejecutar la app

# Diseño de pruebas para la funcion "Agregar licencia de conducir".
- Se requiere tener instalado postamn localmente.
- Tener enlace de acceso al servidor que despliega la aplicación web.
- Seguir la url que despliega la aplicación en postman como servidor de solicitudes.
- De acuerdo a la documentación y los requerimientos realizar las peticiones a la aplicación.

# Tecnologias usadas:
- Postman
- Pruebas Manuales
- Pruebas funcionales
- Pruebas no funcionales

> [!IMPORTANT]
> Para validar la información contenida requieres leer esto:

## Ejecución de Pruebas 
1. Clona el repositorio localmente.
2. Visualizar el archivo correspondiente a listas de comprobación entregas Urban Grocers.
4. Visualizar el archivo correspondiente a listas de comprobación productos Urban Grocers.

> [!IMPORTANT]
> Estado del proyecto

## Estado:
- Completado

## Presentado por:
- Leonardo Lombana Contento

## Proyecto parte del sprint 4 - Pruebas de Api con postman
## Grupo 12 bootcamp QA Engineer - Tripleten
