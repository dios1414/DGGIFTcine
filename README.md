# DG GIFT Cine — nueva interfaz

Esta es una versión nueva e independiente del creador DG GIFT, con una presentación inspirada en plataformas de streaming.

## Archivos
- `index.html`: creador de la película/serie.
- `styles.css`: diseño adaptable a celular y computadora.
- `app.js`: pasos, vista previa, carga de medios, exportación HTML y QR.

## Cómo probar
1. Descomprimí el ZIP.
2. Dejá los tres archivos juntos en la misma carpeta.
3. Abrí `index.html` en Chrome.
4. Completá los 8 pasos y tocá **Crear y descargar mi película**.

## Qué incluye
- Selector de serie o película.
- Título, descripción, destinatario, año y género.
- Foto de portada.
- Hasta 20 fotos convertidas en capítulos con títulos editables.
- Música MP3 incorporada en el regalo.
- Video final incorporado en el regalo.
- Vista previa estilo streaming.
- Descarga de un HTML autónomo.
- Generador de QR para el enlace público.

## Publicar en Cloudflare Pages
Subí `index.html`, `styles.css` y `app.js` juntos a la raíz de tu repositorio de GitHub y conectalo a Cloudflare Pages. Para un sitio estático, dejá el comando de compilación vacío y el directorio de salida como `/`.

Cuando generes un regalo, se descarga un HTML independiente. Para tener un enlace y QR público, publicá ese HTML como sitio/archivo accesible y pegá su URL en el generador de QR.

## Importante
Las fotos, el MP3 y el video se incorporan dentro del HTML descargado. Por eso, cuanto más grandes sean los archivos, más pesado será el regalo. Para un resultado ágil, usá fotos optimizadas y un video corto comprimido. El navegador puede exigir que la persona toque Reproducir antes de permitir audio.


## Efectos cinematográficos añadidos
- Pantalla de apertura con identidad DG y animación de entrada.
- La música comienza al tocar «Comenzar la película» (los navegadores requieren interacción del usuario).
- Los capítulos aparecen con una animación suave al entrar en pantalla.
