# Fini Game

Landing page estática de Fini Game (réplica de https://finanzaschile.cl/fini-game/ sin formularios), lista para GitHub Pages.

- `index.html` — la página.
- `assets/` — CSS, fuentes, imágenes y videos.

## Publicar en GitHub Pages

Settings → Pages → Source: *Deploy from a branch* → `main` / `/ (root)`.

## Link de Google Play

Los botones de descarga usan la clase `js-play-link`. Reemplaza su `href` en `index.html` por el link público de la app en Google Play.

## Ver en local

```bash
python3 -m http.server 8765
```
