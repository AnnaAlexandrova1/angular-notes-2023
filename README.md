# Angular заметки

Для того, чтобы пделать формы, есть модуль FormsModule, его нужно добавить в ngModule
`<input type="text" [(ngModel)]="name">
<p>{{name}}</p>`


## Подключить Bootstrap или что-то еще 
Установить 
Добавть в файл angular.json заивисмость из папки
` "styles": [
              "node_modules/bootstrap/dist/css/bootstrap.min.css",
              "src/styles.css"
            ],`




This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 15.2.6.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.
