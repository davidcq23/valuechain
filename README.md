# Value Chain — Sitio web

Sitio estático de una sola página (HTML, CSS y JavaScript sin dependencias).

## Estructura

```
index.html        Página completa
assets/           Logotipos de Value Chain (SVG y PNG)
```

## Publicar en GoDaddy (cPanel)

1. Entra a cPanel → Administrador de archivos → `public_html`.
2. Sube `index.html` y la carpeta `assets/` (o el .zip y descomprímelo ahí).

## Publicar con GitHub Pages

Settings → Pages → Source: rama `main`, carpeta `/ (root)`.

## Pendiente de completar

- Los logos de clientes (Solfin y Coopesanramón) se cargan desde sus sitios oficiales. Para no depender de ellos, guarda los archivos en `assets/` y cambia el `src` de cada `<img>` en la sección `#clientes`.
