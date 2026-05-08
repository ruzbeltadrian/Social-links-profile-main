# Social-links-profile-main
Social-links-profile-main
# Frontend Mentor - Social links profile solution

Esta es una solución al [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page.
- View the optimal layout depending on their device's screen size.

### Screenshot

![Mi Solución](./screenshot.jpg) 
*(Nota: Recuerda tomar la captura de tu pantalla y guardarla como screenshot.jpg en tu carpeta)*

### Links

- Solution URL: [Tu URL de GitHub aquí]
- Live Site URL: [Tu URL de GitHub Pages o Vercel aquí]

## My process

### Built with

- **Semantic HTML5 markup**: Cambié el uso de divs por etiquetas `<button>` para mejorar la accesibilidad.
- **CSS Custom Properties (:root)**: Para una gestión de colores centralizada y profesional.
- **Flexbox**: Utilizado para centrar la tarjeta y organizar los elementos internos en columnas.
- **Mobile-first workflow**: Ajustes específicos para asegurar que el diseño sea práctico en celulares.

### What I learned

Lo más valioso de este proyecto fue aprender a trabajar con un flujo de diseño práctico. Aprendí a utilizar `:root` para mantener mi código limpio y organizado, lo que facilita enormemente los cambios globales de estilo.

También aprendí a resetear los estilos por defecto de los botones para que coincidan con el diseño, y a manejar el desbordamiento de contenido usando `height: auto`.

Aquí un ejemplo de cómo implementé el cambio de color de texto basado en el estado del padre:

```css
/* Cambio de color del texto cuando se hace hover en el botón */
.boxoptions:hover .boxoptiondesc {
    color: var(--bg-1);
    transition: color 0.3s ease;
}
