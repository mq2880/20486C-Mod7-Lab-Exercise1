# Module 7: Using Entity Framework Core in ASP.NET Core

## Lab: Using Entity Framework Core in ASP.NET Core

1. **Nombres y apellidos:** Francisco Javier Moreno Quevedo
2. **Fecha:** 27/11/2020
3. **Resumen del Ejercicio:** Añadir los componentes necesarios para hacer funcional la aplicacion de venta de CupCakes 1/3 
4. **Dificultad o problemas presentados y como se resolvieron:** Ninguna



- Ejercicio 1: Adding Entity Framework Core 

  - Creamos la clase **Cupcake** y **Bakery** en el modelo
  - Añadimos propiedades y las decoramos para su visualización
  - Creamos la clase CupcakeContext que hereda de DbContext
  - Configuramos el proyecto para que pueda usar SQLLite.
  - Configuramos el Middleware
  - Creamos el metodo **OnModelCreating** que poblará de datos las clases que hemos creado