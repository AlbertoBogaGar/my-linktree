# Linktree con Astro

Este proyecto es una implementación personalizada de un Linktree utilizando la plantilla por defecto de [Astro](https://astro.build/). A continuación, se detalla el proceso que he seguido para crear y desplegar este proyecto.

## Pasos para Crear el Proyecto

### 1. Crear el Proyecto con Astro

Primero, abrí la terminal y ejecuté el siguiente comando para crear un nuevo proyecto con Astro:

```bash
npm create astro@latest
````
Seguí las instrucciones en la terminal para configurar el proyecto
Es importante que escojas la opcion de "Include sample files".

### 2 . Modifica la estructura del proyecto

Una vez creado el proyecto, realicé algunos cambios en la estructura del archivo card.astro:

- Creé un array con los enlaces de los proyectos que quería incluir en mi Linktree.
- Utilicé la función map() para recorrer este array y generar automáticamente los elementos HTML correspondientes.

### 3 . Personaliza los estilos que necesites 
- Cambia el title en el layout
- Modifica el fondo y otros elementos de estilo que necesites

### 4 . Construye el proyecto 
```bash
npm run build
```
Con  este comando se creará una carpeta llamada dist. 
 ### 5 . Despliega el proyecto 
 Puedes desplegar el proyeccto donde quieras, yo recomiendo Netlify ya que arrastrando la carpeta dist ya puedes desplegar. 
 
https://app.netlify.com/drop

