# Galería de Arte Interactiva 3D

Este es un proyecto de galería de arte interactiva en 3D, creado utilizando Bolt.new y tecnologías de inteligencia artificial para ofrecer una experiencia única y envolvente.

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/)

> 🎨 **Artista digital?** ¡Elimina este archivo y empieza a crear algo increíble!

![Galería de Arte](![image](https://github.com/user-attachments/assets/e062ecaa-4b17-4e44-93ad-3e35d81be45a))

## 🚀 Estructura del Proyecto

Dentro de tu proyecto de Bolt.new, verás las siguientes carpetas y archivos:

/ ├── public/ │ └── favicon.svg ├── src/ │ ├── components/ │ │ └── ArtworkCard.astro │ ├── layouts/ │ │ └── MainLayout.astro │ └── pages/ │ └── index.astro └── package.json


Bolt.new busca archivos .astro en el directorio `src/pages/`. Cada página se expone como una ruta según su nombre de archivo.

No hay nada especial en `src/components/`, pero es donde nos gusta colocar cualquier componente de Astro/React/Vue/Svelte/Preact.

Cualquier recurso estático, como imágenes, puede colocarse en el directorio `public/`.

## 🧞 Comandos

Todos los comandos se ejecutan desde la raíz del proyecto, desde una terminal:

| Comando                  | Acción                                           |
| :----------------------- | :----------------------------------------------- |
| npm install              | Instala las dependencias                         |
| npm run dev              | Inicia el servidor de desarrollo local en localhost:4321 |
| npm run build            | Construye tu sitio de producción en ./dist/     |
| npm run preview          | Previsualiza tu construcción localmente antes de desplegar |
| npm run bolt ...         | Ejecuta comandos CLI como bolt add, bolt check |
| npm run bolt -- --help   | Obtén ayuda usando la CLI de Bolt.new           |

## 👀 ¿Quieres intentarlo por tu cuenta? ?

Accede a [bolt.new](https://docs.bolt.new) y usa los tokens gratuitamente.
