# Propuesta IA · Pérez y Pérez Abogados

Sitio estático con propuesta comercial: 2 charlas, coaching y hoja de ruta ejecutiva, diseñado por Orbital Lab.

## Estructura del repo
- `web/` → versión de trabajo local (HTML/CSS, rutas relativas a `../assets`)
- `assets/` → logos, video, imágenes
- `docs/` → versión lista para GitHub Pages (copias de HTML/CSS + `assets`)

## Ver en local
1. Abre `docs/index.html` en el navegador (click-doble o con un servidor estático).
2. Alternativa: usa “Live Server” en VS Code sobre la carpeta `docs/`.

## Publicar en GitHub Pages
1. Sube el repo a GitHub (main o cualquier rama).
2. En Settings → Pages:
   - Source: “Deploy from a branch”
   - Branch: `main` (o la rama que uses)
   - Folder: `/docs`
3. Guarda. La URL quedará como: `https://<usuario>.github.io/<repo>/`.

Opcional (dominio propio):
- Edita `docs/CNAME` y coloca tu dominio, por ejemplo: `pyp.orbitallab.ai`.
- En el DNS, crea un CNAME que apunte a `<usuario>.github.io`.

## Edición de contenido
- HTML principal: `web/index.html` (o `docs/index.html` si prefieres editar directamente lo publicado).
- Estilos: `web/styles.css` y `docs/styles.css`.
- Imágenes/videos: `assets/` (en Pages se usan las copias dentro de `docs/assets`).

Tras cambios en `web/`, copia al sitio publicado:
- Copia `web/index.html` a `docs/index.html` y ajusta rutas si añades nuevos recursos.
- Copia/actualiza `assets/` en `docs/assets/` cuando agregues nuevas imágenes o videos.

## Notas
- CTAs usan WhatsApp con mensaje prellenado.
- Se respetan preferencias de “reduced motion”.
- El retrato del consultor está en `docs/assets/consultor/julian.png` con fallback a `assets/consultor/placeholder.svg`.

## Créditos
Orbital Lab — orbitallab.ai
