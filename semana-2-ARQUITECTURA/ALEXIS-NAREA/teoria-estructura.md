# Estructura de Nest.js
## Controladores

### Teoría

Son clases decoradas con **@Controller()**, responsables de manejar las solicitudes HTTP y devolver respuestas adecuadas. Cada controlador define un conjunto de rutas y métodos HTTP, conocidos como métodos de acción, que reciben peticiones y ejecutan la lógica correspondiente.

---
### Reflexión
  
Los controladores en Nest.js de basan en patrones de diseño probados para ofrecer una estructura y flexible.
- **Patrón MVC (Modelo-Vista-Controlador):** Los controladores actúan como intermediarios entre la capa de presentación (vistas) y la capa de lógica de negocios (modelos), manejando la interacción con la API.
- **Arquitectura RESTful:** Los métodos de acción se mapean con verbos HTTP **(GET, POST, PUT, DELETE)** para realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) sobre recursos.
- **Inyección de Dependencias:** Los controladores pueden acceder a servicios y otras dependencias mediante inyección, promoviendo la modularidad y la testabilidad.

---
### Analogía
#### Tema: Restaurante
Los controladores de Nest.js pueden compararse con los cajeros de un restaurante. Los clientes **(solicitudes HTTP)** llegan al restaurante y son atendidos por los cajeros **(controladores)**. Los cajeros toman la orden del cliente **(solicitud)** y la envían a la cocina **(servicios)** para que se prepare el pedido. Una vez que el pedido está listo, el cajero **(controlador)** lo entrega al cliente **(respuesta HTTP)**.

---
### Resumen
La estructura modular de Nest.js promueve la organización y la reutilización de código. Controladores, proveedores y servicios trabajan en conjunto para manejar solicitudes, implementar lógica y ofrecer funcionalidades.
Los patrones de diseño y los decoradores simplifican la creación de aplicaciones robustas y escalables.

---
### Referencias 
-  _Controllers | NestJS - A progressive Node.js framework_. (n.d.). Retrieved May 3, 2024, from https://docs.nestjs.com/controllers

- _Mejores prácticas y técnicas avanzadas de NestJS | de Boyinbode Ebenezer Ayomide | Medio_. (n.d.). Retrieved May 3, 2024, from https://medium.com/@boyinbodedev/best-nestjs-practices-and-advanced-techniques-e6d59d85366a
