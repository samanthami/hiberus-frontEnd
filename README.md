# HiberusProyect

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 20.0.2.

## Development server

To start a local development server, run:

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.

## Code scaffolding

Angular CLI includes powerful code scaffolding tools. To generate a new component, run:

```bash
ng generate component component-name
```

For a complete list of available schematics (such as `components`, `directives`, or `pipes`), run:

```bash
ng generate --help
```

## Building

To build the project run:

```bash
ng build
```

This will compile your project and store the build artifacts in the `dist/` directory. By default, the production build optimizes your application for performance and speed.

## Running with Backend

To execute the backend : 

```backend
https://github.com/samanthami/hiberus
```

## Estructura del Proyecto

### Backend

```
/src/main/java
    /com/ejemplo/proyecto
        /controller   # Controladores
        /service      # Lógica de negocio
        /repository   # Acceso a la base de datos
        /model        # Entidades
```

### Frontend

```
/src/app
  /employee
    /components   # Componentes de la aplicación
    /services     # Servicios para interactuar con la API
    /models     # Interfaces y modelos de datos
  /department
    /components   # Componentes de la aplicación
    /services     # Servicios para interactuar con la API
    /models     # Interfaces y modelos de datos
```




## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
