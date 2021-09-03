# Comenzando

## Prerequisitos

Descarga e instala [Node.js](https://nodejs.org/en/)

## Inicio rápido

```
npx create-vuepress-site
```
    Project Name
    Description
    Maintainer Email
    Maintainer Name
    Repository URL

## Instalación Manual

Crea una carpeta docs con una plantilla de ejemplo básico

1 Crea un directorio y entra en él
```
mkdir vuepress-starter && cd vuepress-starter
```
2 Inicia el **package manager**
```
npm init
```
3 Instala VuePress localmente (modo desarrollo)
```
npm install -D vuepress
```
4 Crea tu primer documento
```
mkdir docs && echo '# Hello VuePress' > docs/README.md
```
6 Inicia la página en un servdor local utiliza el comando **sudo** la primera vez
```
npm run dev
```

## Configuración

### Sidebar

```
sidebar: 'auto'
````
Muestra los títulos y subtítulos ordenadamente en el sidebar

### Base

```
base: '/vuepress/'
````
Si subimos el proyecto a la web a través de **github** como un repositorio 

## GitHub

1 Crea un nuevo repositorio **/vuepress/**

2 Seleccionalo como un branch **gh-pages**

3 En **Settings** (configuración) selecciona en **GitHub Pages** el **Branch: gh-pages** y la carpeta **root**, finalmente guárdalo **Save**