# Página web de servicios de edición de video — David

Sitio estático en HTML, CSS y JavaScript, preparado para GitHub Pages.

## Antes de publicar

Abre `index.html` y cambia estos marcadores por tus datos reales:

1. `TU_CORREO@EJEMPLO.COM` (aparece en el enlace de correo y su texto visible).
2. `5210000000000` en el enlace de WhatsApp: reemplázalo por tu número internacional, solo dígitos, sin `+`, espacios ni guiones. Para México, normalmente se usa el código de país `52` seguido del número.
3. `https://www.youtube.com/` por el enlace de tu lista de reproducción de portafolio.
4. `https://drive.google.com/` por el enlace de tu carpeta de Google Drive. En Drive, configura el acceso para que las personas con el enlace puedan verla, si quieres que los clientes puedan abrirla.

También puedes ajustar el texto de servicios para que describa solo lo que ofreces realmente.

## Publicar en GitHub Pages

1. Entra en https://github.com e inicia sesión.
2. Pulsa **New repository**.
3. Ponle un nombre, por ejemplo `editor-video`. Puedes dejarlo **Public** para que la publicación sea sencilla.
4. Crea el repositorio.
5. Dentro del repositorio, pulsa **Add file → Upload files**.
6. Sube `index.html`, `style.css` y `script.js` directamente a la raíz del repositorio. No subas solo la carpeta que los contiene; los tres archivos deben quedar al mismo nivel.
7. Pulsa **Commit changes**.
8. Abre **Settings → Pages**.
9. En **Build and deployment**, selecciona **Deploy from a branch**.
10. En **Branch**, elige `main` y la carpeta `/(root)`, y pulsa **Save**.
11. Espera unos minutos y vuelve a **Settings → Pages**. GitHub mostrará la dirección pública, normalmente `https://TUUSUARIO.github.io/editor-video/`.

Si el repositorio se llama exactamente `TUUSUARIO.github.io`, la dirección será `https://TUUSUARIO.github.io/`.

## Probar antes de publicar

Abre `index.html` en el navegador para revisar el diseño. Los enlaces de contacto y portafolio son marcadores hasta que los reemplaces por tus datos reales.

## Notas

- GitHub Pages publica archivos estáticos; no hay backend ni formularios que guarden datos.
- El botón de correo abre la aplicación de correo del visitante mediante `mailto:`.
- El botón de WhatsApp abre una conversación mediante `wa.me`.
- La fuente se carga desde Google Fonts; si no está disponible, el navegador usa una fuente alternativa.
