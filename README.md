# MeanBackEnd
Recibe las peticiones CRUD http soble localhost en el puerto 3000 y las materializa sobre la MongoDB.
Para descargar la parte cliente, hay que clonar también el proyecto mean_users_frontend.

## Pasos instalación
Una vez clonado el proyecto, tenderemos que hacer un `npm install`, para carga de las dependencia indicadas en package.json


## Arranque del servidor

1. Arrancar dbmongo. La base de datos y colecciones se crean automáticamente si no existen.
2. `node ./bin/www` o `npm start` (ver package.json)


## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
