# landing-page-leonardo

Página de Leonardo Melo, compositor y pianista. Es un solo archivo, `index.html`, con imágenes en `img/` y sin build.

- **Local:** `python3 -m http.server 8080` y abrir http://localhost:8080
- **Despliegue:** cada push a `main` publica `index.html` e `img/` en GitHub Pages (`.github/workflows/deploy.yml`). Requiere **Settings → Pages → Source: GitHub Actions**.
- **Pendiente — formulario de contacto:** usa Web3Forms con una clave de ejemplo (`PEGAR-AQUI-LA-ACCESS-KEY`), así que hoy todo envío falla y muestra el correo de Leonardo. Falta elegir el servicio definitivo.
