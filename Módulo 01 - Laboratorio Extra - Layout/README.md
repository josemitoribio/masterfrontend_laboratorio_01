# Laboratorio 01

## **Máster Front End - Módulo 01 - Layout - Laboratorio Extra**

Vamos a crear un Layout para una aplicación, que contendrá:
##### Header:
- Toolbar con un input de texto para búsquedas y nombre del usuario logado.
- Barra con el nombre de la aplicación.
##### Nav:
- Menú con varias opciones de navegación
##### Main:
- Contenido con la información principal de la aplicación. - Fondo diferente de blanco.
##### Footer:
- Texto de la compañía, al final de la página (aunque el contenido no ocupe todo el alto)

#### Explicación:
- Para esta prueba de maquetación he utilizado grid area para poder combinarlo con flex.
- Utilizando SASS he creado distintas variables (colores y breakpoints) y mixins para algunos estilos.
- Para el diseño responsivo he utilizado un $breakpoint-mobile: 768px;

He aplicado las consideraciones a tener en cuenta para las media queries:

- No perder en ninguna resolución la barra de navegación al hacer scroll.
- En resoluciones pequeñas (hasta 768px de ancho):
    - Contenido a ocultar:
    - Barra superior con input de búsqueda y nombre de usuario 
    - Título del menú
- Cambiar menú a la parte superior, bajo el header.
- Cambiar la organización del contenido principal para visualizarlo sin problemas.

Para ejecutar este laboratorio usar los comandos: npm install y después: npm run dev

Josemi Toribio