# Laboratorio 01

## **Máster Front End - Módulo 01 - Layout - Laboratorio Avanzado**
Una conocida casa cinematográfica quiere crear su propia plataforma on-line para servir sus producciones, a la que van a llamar WARNER LIVE.

Nos han solicitado una prueba de maquetación de un primer diseño,
del resultado de la prueba dependerá pasar a la siguiente fase de selección

- Fuente utilizada: Jost (https://fonts.google.com/specimen/Jost?preview.text=warner+live&preview.text_type=custom)
- Color de fondo de la plataforma: #141414
- Se adjunta carpeta de trabajo con la base de HTML (puede ser modificado al gusto) y las imágenes, carátulas
y logo, que se pueden modificar/añadir.
- Se aporta los requisitos de diseño base, con libertad de creatividad.

#### Explicación:
- Para esta prueba de maquetación he utilizado flex.
- Utilizando SASS he creado distintas variables (colores y breakpoints), mixins e incluso un bucle para ocultar las dos películas más vistas cuando pasan de 5 a 3, ocultando por ello la película 4 y 5.
- Para el diseño responsivo he utilizado dos breakpoints:
    * $breakpoint-tablet: 1280px;
    * $breakpoint-mobile: 720px;
En ellos se producen cambios como la ocultación del nombre de la plataforma o las películas top pasan de 5 a 3.

Para ejecutar este laboratorio usar los comandos: npm install y después: npm run dev

Josemi Toribio