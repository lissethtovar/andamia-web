# andamia-web

Sitio corporativo de **Andamia SpA**, publicado en `https://andamia.io` con GitHub Pages.

Estático, sin dependencias. `estilos.css` son los tokens del sistema visual Señal (copiados de `cumbra-legal`).

## Publicar

1. Repositorio público `lissethtovar/andamia-web`, rama `main`, carpeta `/ (root)`.
2. Settings → Pages → Custom domain: `andamia.io` (el archivo `CNAME` ya lo declara). Activar «Enforce HTTPS» cuando el certificado esté emitido.
3. DNS en Cloudflare (**solo DNS, nube gris**; no tocar los registros MX de iCloud):
   - `A    andamia.io  185.199.108.153`
   - `A    andamia.io  185.199.109.153`
   - `A    andamia.io  185.199.110.153`
   - `A    andamia.io  185.199.111.153`
   - `CNAME www        lissethtovar.github.io`
