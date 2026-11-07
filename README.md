# NOVA IRIS UI: showcase

Librería de componentes **Angular 21** con Playground interactivo. Este repositorio es una vitrina pública; el código fuente es privado.

📦 npm: [`@chrisdesign95/nova-iris-ui`](https://www.npmjs.com/package/@chrisdesign95/nova-iris-ui)

## Características

- Componentes standalone con **Signals**, **zoneless** y **OnPush**.
- Tokens CSS `--nv-*` y temas **Light / Dark**.
- Cada componente es un *secondary entry point* independiente (tree-shaking real).
- Compatible con Reactive Forms, `ngModel` y `[(value)]`.
- Accesibilidad: semántica nativa, `aria-*` y navegación por teclado.
- Playground interactivo para explorar variantes y estados.
- Publicación automática en npm al subir una etiqueta de versión.

## Componentes

Button · Input · Textarea · Checkbox · Radio · Switch · Tag · Badge · Chip · Avatar · Card · Dialog · Data Table (búsqueda, filtros, orden, paginación y estados loading/empty/error).

## Stack

Angular 21 · TypeScript estricto · SCSS · Vitest · npm.

## Ejemplo

```html
<nv-data-table [dataSource]="rows" [columns]="cols" [actions]="actions" />
```

## Contacto

[Christian Castro](https://github.com/chrisdesing1995) · fernandochris1995@gmail.com
