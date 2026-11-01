# DEXX WEB SITE

Sitio web estático (un solo archivo: `index.html`). No necesita instalar nada.

## Cómo cambiar tus enlaces
Abre `index.html` y busca (al final del archivo, dentro de `<script>`) estas listas:

- `SERVERS`: tus servidores de Discord (`n` nombre, `d` descripción, `u` enlace de invitación).
- `OPTIMIZER`: enlace de descarga de DEXX Optimizer (`u`) y su texto de versión (`d`).
- `SCANNERS`: scanners para PC, iPhone y Android (`u` es el enlace de descarga de cada uno).

Los enlaces que empiezan con `https://discord.gg/TU-INVITACION` y `https://ejemplo.com` son de relleno: reemplázalos por los reales.

## Publicar
1. Sube esta carpeta a un repositorio de GitHub (`index.html` en la raíz).
2. En tu hosting, apunta al repositorio o sube `index.html` a la carpeta pública (por ejemplo `public_html`).
3. Para GitHub Pages: Settings → Pages → Deploy from a branch → `main` / `(root)`.
