# Genealogía bíblica — PWA

Esta carpeta es la versión instalable (PWA) de la genealogía: funciona sin conexión
y se puede "instalar" como aplicación en el móvil o el ordenador.

## Requisito
Una PWA necesita servirse por HTTP/HTTPS (los service workers no funcionan
abriendo el archivo directamente). Dos opciones:

**A) Probar en local** (con Python instalado), desde esta carpeta:

    python -m http.server 8080

y abrir http://localhost:8080 en el navegador.

**B) Publicarla** (gratis): sube el contenido de esta carpeta a GitHub Pages,
Netlify Drop (arrastra la carpeta a https://app.netlify.com/drop) o similar.
Con HTTPS, el navegador ofrecerá "Instalar aplicación" (icono en la barra de
direcciones en escritorio; "Añadir a pantalla de inicio" en el móvil).

## Contenido
- index.html — la genealogía completa (idéntica a Genealogia-biblica.html)
- manifest.webmanifest — nombre, iconos y colores de la app
- sw.js — service worker: red-primero con respaldo offline
- icon-192.png / icon-512.png — iconos de la app

## Actualizaciones
Cuando se regenere la genealogía, basta reemplazar index.html; el service
worker sirve siempre lo último cuando hay conexión y guarda copia para offline.

El archivo Genealogia-biblica.html de la carpeta Genealogía sigue funcionando
como siempre con doble clic — la PWA es una opción adicional, no lo sustituye.
