# Marea Estudio

Web de Marea Estudio, estudio de diseño y desarrollo web en Cambrils (Biel Torres y Marxal Rofes).

Es una web estática de un solo archivo (`index.html`): fuentes, imágenes y código van incluidos, sin dependencias externas ni cookies.

## Publicar en Netlify

1. En Netlify: **Add new site → Import an existing project → GitHub** y elige este repositorio.
2. No hace falta comando de build. El directorio de publicación es la raíz (ya está en `netlify.toml`).
3. Deploy.

## Pendiente de rellenar en `index.html`

- `window.__BRAND__`: `instagram` y `email` (activan sus botones). WhatsApp ya configurado.
- Textos legales: buscar `[PENDIENTE` (titular, NIF, domicilio, email, hosting).
- Cuando haya dominio: `canonical`, `og:url` y `og:image` en el `<head>`, y el `Sitemap:` en `robots.txt`.
