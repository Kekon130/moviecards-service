# TRABAJO FINAL NTEGRACIÓN CONTINUA EN EL DESARROLLO ÁGIL
# Moviecards-Service - Sergio Plaza Gonzalo

A lo largo de este documento voy a explicar los cambios que he realizado en el código con el objetivo de completar el trabajo final.

La url donde esta alojado el servicio es [moviecards-service-plaza.azurewebsites.net](moviecards-service-plaza.azurewebsites.net)

## Despliegue en azure
Siguiendo las indicaciones de la práctica 5 de la asignatura cree un nuevo App Service en azure y configuré Azure para que usara mi proyecto como fuente del código.

## Fecha de muerte de los Actores
Para incluir la fecha de muerte de los Actores realicé las siguientes modificaciones:

  1. Añadí un nuevo atributo al módelo `Actor.java` llamado `deathDate` además de sus getters y sus setters.

  2. Modifiqué las pruebas de integración para que incluyesen este nuevo atributo.

  3. Modifiqué las pruebas unitarias del modelo `Actor.java` para añadir un nuevo test para el atributo `deathDate`

Para ver mas detalles consultar [este commit](https://github.com/Kekon130/moviecards-service/commit/cf9d11a41c76b779bdd77ae44c27b9006b936856) 