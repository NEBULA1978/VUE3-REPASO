# repaso

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

# CenaVisigodo.vue

`CenaVisigodo.vue` es un componente Vue que muestra detalles sobre diferentes cenas con reyes godos y sus productos asociados. Este componente es parte de una aplicación que presenta información sobre cenas históricas y productos relacionados.

## Funcionalidades Principales

- Muestra el número de la cena y el rey godo correspondiente.
- Muestra el precio del producto actual.
- Indica si el producto es válido solo para fines de semana o para todos los días de la semana.
- Muestra una oferta si el precio del producto es menor a 100 euros.
- Muestra la imagen correspondiente al producto actual.
- Proporciona un botón para cambiar al siguiente producto.

## Estructura del Componente

El componente se compone de una estructura HTML en la sección de `<template>`, funciones y variables reactivas en la sección `<script setup>`, y estilos en la sección `<style scoped>`.

- Utiliza la librería Vue 3 con las funciones `ref` y `computed` para gestionar el estado y las propiedades calculadas.
- Los datos de los productos se importan desde el módulo `productos.js`.
- La función `siguiente` se encarga de cambiar al siguiente producto, reiniciando el contador cuando se alcanza el último producto.
- Los datos sobre el rey godo, la imagen y el precio con descuento se calculan mediante propiedades reactivas.
- Los estilos están diseñados para centrar el contenido, resaltar los días de la semana y las ofertas, y establecer un diseño agradable y legible.

## Uso

Este componente puede integrarse en una aplicación más grande que presenta información sobre diferentes cenas históricas. Puedes ajustar los estilos y la lógica según las necesidades de tu proyecto.

## Contribución

Si deseas contribuir a este componente o a la aplicación en general, te animamos a crear pull requests y discutir sobre nuevas características o mejoras.

## Licencia

Asegúrate de revisar la licencia del proyecto en el repositorio principal para conocer los términos de uso.

---

**Nota:** Esta descripción está basada en el contenido y la funcionalidad del archivo `CenaVisigodo.vue` proporcionado en el código. Asegúrate de adaptarla según los cambios que realices en el componente o en la aplicación.


### Compile and Minify for Production

```sh
npm run build
```
# VUE3-REPASO
