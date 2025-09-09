
# Portfolio de Ilustración (GitHub Pages)

## Cómo publicarlo
1. Crea tu cuenta en https://github.com (si no tienes).
2. Crea un repositorio llamado **tusuario.github.io** (cambia *tusuario* por tu usuario real).
3. Sube todo el contenido de esta carpeta (los archivos y directorios).
4. Ve a **Settings → Pages** y asegúrate de que la rama `main` y carpeta `/root` están seleccionadas.
5. Tu web quedará en `https://tusuario.github.io` en unos minutos.

## Cambios básicos
- Reemplaza **TuNombre** por tu nombre (buscar y reemplazar en archivos `.html`).
- Cambia el correo en `contacto.html` o en `assets/js/script.js`:
  ```js
  const YOUR_EMAIL = "tuemail@gmail.com";
  ```
- Reemplaza las imágenes en `assets/images/galeria*/` con tus obras (pueden ser .jpg/.png/.webp). Mantén los nombres o actualiza las rutas en HTML si los cambias.

## SEO / Google
- En cada archivo `.html` ajusta `<title>` y `<meta name="description">`.
- Cambia `sitemap.xml` y `robots.txt` para que usen tu dominio real:
  - Busca `https://example.com` y reemplázalo por tu `https://tusuario.github.io` o tu dominio propio.
- (Opcional) Registra tu sitio en Google Search Console para indexación más rápida.

## Galerías
- Clic en miniatura abre lightbox.
- Navegación por **flechas del teclado**, **botones** o **gesto deslizar** en móvil.
- Para añadir más imágenes, duplica una línea `<figure>` y una línea `<div class="slide">` en el HTML de la galería correspondiente y ajusta el contador `X / N` en el lightbox si cambias el total.

## Licencia
Este proyecto es tuyo para usar, modificar y publicar.
