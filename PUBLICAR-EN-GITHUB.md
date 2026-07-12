# Publicar la Genealogía bíblica en GitHub Pages (~5 minutos)

Los 6 archivos de esta carpeta (Genealogia-PWA) son todo lo que hay que subir.

## 1. Crear el repositorio
1. Entra en https://github.com (crea cuenta gratis si no tienes).
2. Botón verde **New** (o https://github.com/new).
3. Repository name: `genealogia-biblica` (o el que quieras).
4. Deja **Public** marcado (Pages gratis requiere repo público).
5. NO marques "Add a README". Pulsa **Create repository**.

## 2. Subir los archivos
1. En la página del repo recién creado, pulsa el enlace **uploading an existing file**.
2. Arrastra los 6 archivos de la carpeta Genealogia-PWA
   (index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png, LEEME.md).
   ⚠️ Arrastra los ARCHIVOS, no la carpeta: index.html debe quedar en la raíz del repo.
3. Abajo, pulsa **Commit changes**. (index.html pesa ~2,5 MB; tarda unos segundos.)

## 3. Activar GitHub Pages
1. En el repo: **Settings** (pestaña de arriba) → **Pages** (menú izquierdo).
2. En "Build and deployment" → Source: **Deploy from a branch**.
3. Branch: **main** — carpeta **/ (root)** → **Save**.
4. Espera 1-2 minutos y recarga esa página: aparecerá la URL, del estilo
   `https://TU-USUARIO.github.io/genealogia-biblica/`

## 4. Instalarla
- **Escritorio (Chrome/Edge):** abre la URL → icono de instalar en la barra de
  direcciones (un monitor con flecha) → "Instalar".
- **Android:** abre la URL en Chrome → menú ⋮ → "Añadir a pantalla de inicio".
- **iPhone/iPad:** Safari → botón compartir → "Añadir a pantalla de inicio".

Una vez abierta con conexión, queda guardada y funciona también sin internet.

## Actualizaciones futuras
Cuando la genealogía se regenere: en el repo pulsa sobre `index.html` →
icono del lápiz no hace falta; mejor **Add file → Upload files** y arrastra el
`index.html` nuevo (sobrescribe al hacer commit). La app se actualiza sola en
1-2 minutos; los usuarios la reciben al abrirla con conexión.
