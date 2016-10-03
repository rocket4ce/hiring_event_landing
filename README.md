# HIRING EVENT FRONTEND

#### HOWTO DEV

- `fork and clone`
- `npm install`
- `npm start`
- Abrir [localhost:3010/webpack-dev-server/index.html](http://localhost:3010/webpack-dev-server/index.html)˙

#### Descripción
El proyecto usa webpack para el HMR de css y js, y templates de handlebars para la estructura del html.

#### "Componentes"
- [/src/template/index.hbs](/src/template/index.hbs) - Contiene la estructura principal de proyecto.
- [/src/template/body.hbs](/src/template/body.hbs) - Componente Body.

Se pueden crear más archivos `.hbs` En caso de requerir más "componentes".
Para crear "sub-componentes" es posible crear carpetas, pero es necesario agregar la nueva carpeta al archivo [webpack.config.js](/webpack.config.js) dentro del loader de handlebars.
