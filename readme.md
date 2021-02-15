![Built With Stencil](https://img.shields.io/badge/-Built%20With%20Stencil-16161d.svg?logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4KPCEtLSBHZW5lcmF0b3I6IEFkb2JlIElsbHVzdHJhdG9yIDE5LjIuMSwgU1ZHIEV4cG9ydCBQbHVnLUluIC4gU1ZHIFZlcnNpb246IDYuMDAgQnVpbGQgMCkgIC0tPgo8c3ZnIHZlcnNpb249IjEuMSIgaWQ9IkxheWVyXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4IgoJIHZpZXdCb3g9IjAgMCA1MTIgNTEyIiBzdHlsZT0iZW5hYmxlLWJhY2tncm91bmQ6bmV3IDAgMCA1MTIgNTEyOyIgeG1sOnNwYWNlPSJwcmVzZXJ2ZSI%2BCjxzdHlsZSB0eXBlPSJ0ZXh0L2NzcyI%2BCgkuc3Qwe2ZpbGw6I0ZGRkZGRjt9Cjwvc3R5bGU%2BCjxwYXRoIGNsYXNzPSJzdDAiIGQ9Ik00MjQuNywzNzMuOWMwLDM3LjYtNTUuMSw2OC42LTkyLjcsNjguNkgxODAuNGMtMzcuOSwwLTkyLjctMzAuNy05Mi43LTY4LjZ2LTMuNmgzMzYuOVYzNzMuOXoiLz4KPHBhdGggY2xhc3M9InN0MCIgZD0iTTQyNC43LDI5Mi4xSDE4MC40Yy0zNy42LDAtOTIuNy0zMS05Mi43LTY4LjZ2LTMuNkgzMzJjMzcuNiwwLDkyLjcsMzEsOTIuNyw2OC42VjI5Mi4xeiIvPgo8cGF0aCBjbGFzcz0ic3QwIiBkPSJNNDI0LjcsMTQxLjdIODcuN3YtMy42YzAtMzcuNiw1NC44LTY4LjYsOTIuNy02OC42SDMzMmMzNy45LDAsOTIuNywzMC43LDkyLjcsNjguNlYxNDEuN3oiLz4KPC9zdmc%2BCg%3D%3D&colorA=16161d&style=flat-square)

# Kontur Branding

This repo contain universal components for branding Kontur products:
- `<kontur-logo></kontur-logo>` [(docs)](https://github.com/konturio/kontur-branding/tree/main/src/components/kontur-logo)
- `<kontur-spinner></kontur-spinner>`[(docs)](https://github.com/konturio/kontur-branding/tree/main/src/components/kontur-spinner)

# Based on Stencil

Stencil is a compiler for building fast web apps using Web Components.

Stencil combines the best concepts of the most popular frontend frameworks into a compile-time rather than run-time tool.  
Stencil generates 100% standards-based Web Components that run in any browser supporting the Custom Elements v1 spec, so they work in any major framework or with no framework at all.

## How to use this components
### Script tag

- Put a script tag in the head of your index.html similar to this `<script src='https://unpkg.com/@konturio/kontur-branding/dist/component_name@1.0.0/component_name.esm.js'></script>`, where `component_name` must be replaced with name of component from [list above](#kontur-branding) (you can omit the version (@1.0.0) if you want to always use the latest version).
- Then you can use the element anywhere in your template, JSX, HTML etc

### React, Vue, Angular or Ember App
- Run `npm install @konturio/kontur-branding --save`
- Go to this [instruction](https://stenciljs.com/docs/overview) and select framework from list

### Any other app (universal method)
- Run `npm install @konturio/kontur-branding --save`
- Put a script tag in the head of your index.html similar to this `<script src='node_modules/@konturio/kontur-branding/dist/component_name.esm.js'></script>` where `component_name` must be replaced with name of component from [list above](#kontur-branding) 
- Then you can use the element anywhere in your template, JSX, html etc

### In a stencil-starter app
- Run `npm install @konturio/kontur-branding --save`
- Add an import to the npm packages `import '@konturio/kontur-branding'`
- Then you can use the element anywhere in your template, JSX, html etc


## How to develop

To start run:

```bash
npm install
npm start
```

To build the component for production, run:

```bash
npm run build
```

To run the unit tests for the components, run:

```bash
npm test
```

To create new one component run
```bash
npm generate
```

## Naming Components

When creating new component tags, use `kontur` in the component name (ex: `<kontur-logo>`)
