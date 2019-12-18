# Goty

Aquest projecte s´ha generat amb [Angular CLI](https://github.com/angular/angular-cli) version 8.3.3.

# Utilitza "goty-backend" [https://github.com/enricsarra/goty-backend]

## Creat amb **ng new goty**
- node_modules añadidos:  **bootstrap**, **jquery**, **popper** and defined in **angular.json**
- node_modules añadidos: **npm install @swimlane/ngx-charts --save** **npm install sweetalert2  --save**, **npm install angularfire --save**, **npm install  firebase --save**
- No es puja a github el directori /src/environments

## goty backend
- goty utilitza **goty-backend** per a consultar i actualitzar la db **goty**

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

## Gráficos ngx-charts

**Repositorio ngx-charts:** [<https://github.com/swimlane/ngx-charts]>

En la documentación/introducciónI tenemos el código StackBlitz [<https://swimlane.gitbook.io/ngx-charts/]> como ejemplo.

En la documentación/installing

- **npm install @swimlane/ngx-charts --save**

**Ejemplo vertical bar char
- Código StackBlitz [<https://stackblitz.com/edit/vertical-bar-chart?embed=1&file=app/app.component.ts]>
- Copiar contenido de *app.component.html* de StackBlitz a el componente que estamos trabajando
- Copiamos el siguiente código de *app.module.ts* 
    - *import { BrowserAnimationsModule } from '@angular/platform-browser/animations'*;
    - *import { NgxChartsModule } fro*m '@swimlane/ngx-charts*
- y lo pegamos en nuestro módulo *components.module.ts*. A continuación los importamos en "imports" 
- Copiar contenido de *class AppComponent* [<https://stackblitz.com/edit/vertical-bar-chart?embed=1&file=app/app.component.ts]> en *app.component.ts* de StackBlitz a el componente que estamos trabajando
- Copiar contenido de *data.ts* de StackBlitz a el componente que estamos trabajando
- ngx-charts (swimlane) demo: [<https://swimlane.github.io/ngx-charts/#/ngx-charts/bar-horizontal>]
- ngx-charts (swimlane) documentación: [<https://swimlane.gitbook.io/ngx-charts/]>

## Working with **goty**
- *cd goty-backend*
    - *firebase serve*     
        - Emulador arrancado (http://localhost:5000)
- *cd goty*
    - *ng server*   
        -  Emulador arrancado (http://localhost:4200)