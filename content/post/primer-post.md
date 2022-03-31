---
title: "Primer Post"
date: 2022-03-30T22:50:47-06:00
draft: false
---

Esta es una pagina elaborada con un static site generator

- Fue creada con Hugo de Go
- Fue relativamente rapido y sencillo
# Los pasos son sencillos y son los siguientes
1. Descargar go 1.18
2. Descargar hugo
3. Crear un sitio con
 > `hugo new site nombreDelSitio`
4. Nos cambiamos a la carpeta 
`cd nombreDelSitio`
5. Descargamos el submodulo 
> `Git init` 
- y depsues
 > `git submodule add https://github.com/theNewDynamic/gohugo-theme-ananke.git themes/ananke`
6. Se le añade el theme en el confing.toml 
> `theme='ananke'`
7. Creamos un post 
> `hugo new carpeta/nombre.md`
8. Corremos el servidor
 > `hugo server`
