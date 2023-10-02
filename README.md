proyecto realizado en :

angular version 16
ngx bootstrap version 11

requisitos:
node v16.16.0

este proyecto implementa guard para el manejo de la verificacion de rutas
utiliza interceptor al realizar las peticiones Http para mostrar una animacion mientras se espera una respuesta de parte de las API
tambien se usaron reactive Forms para los formularios de inicio de sesion, editar y crear
creacion de servicios para el consumo de APIs(https://jsonplaceholder.typicode.com/posts) de donde se obtine la informacion
se utiliza sessionstorage para el manejo de sesiones
se implementa el lazyloading para las diferentes paginas y mejorar el rendimiento en la carga de la pagina
impemantacion del framework css bootstrap(system grid, alerts, buttons, tables, navbar, modals) 

# DemoAngular

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.2.4.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
