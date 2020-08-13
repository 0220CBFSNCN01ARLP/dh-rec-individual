# Ejercicio Recuperatorio

## Descripcion

Este proyecto es un fork de la demo que mostramos en la comision de 0220CBFSNCN01ARLP.

La intencion de este repositorio es proveer un punto de partida para una evaluacion individual
como ultima instancia para la aprovacion del curso.

## Ejercitacion

La idea es que a partir de este proyecto, puedas implementar una extension basandote en el siguiente diseño:

![Diagrama Entidad-Relacion](docs/der.jpg?raw=true)

Las entidades en las que te tenes que concentrar en implementar son: `Serie`, `Season` y `Episode`, asi como tambien las tablas pivot necesarias y las asociaciones con las entidades ya implementadas.

En particular, esperamos que implementes:

-   Modelos de Sequelize para estas entidades
-   Migracion de la base de datos agregando dichas entidades y las asociaciones necesarias
-   Controladores para los nuevas entidades con funciones para un CRUD completo de estas entidades y sus rutas en formato de WebAPI
-   Validaciones para las rutas de creacion y actualizacion de todas las entidades.

Para este ejercicio, **no es necesario** que implementes:

-   Frontend de ningun tipo relacionado a las nuevas entidades.
-   Actualizaciones al frontend ya implementado para tener en cuenta estas nuevas entidades.

## Tips

-   Hace uso de los materiales publicados en Playground para ayudarte a implementar estos requerimientos.
-   Basate en las entidades que ya están implementadas como ejemplo para las nuevas.
-   Para ayudarte a implementar y probar la WebAPI, recordá que disponés de [Postman](https://www.postman.com/)
-   Cualquier duda que tengas, no dudes en consultarnos por Slack / Discord

## Instalacion y arranque

```sh
npm install

mysql -u root < ./database/migrations/01-movies-202007131726.sql

npm start
```
