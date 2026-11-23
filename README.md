# EXCHANGE · Prototipo web

Versión navegable en HTML del **Flow 1** de la página *Web - Landing page* del archivo de Figma de EXCHANGE.

Cada pantalla es una imagen exportada de Figma con zonas clicables en las mismas posiciones que las conexiones del prototipo. Incluye las transiciones automáticas (pantallas de carga y confirmación).

## Cómo usarlo

- Haz clic en los botones como en el prototipo de Figma.
- Haz clic en cualquier zona vacía (o pulsa **H**) para ver dónde se puede hacer clic.
- **↺ Inicio** (o la tecla **R**) vuelve a la landing.
- Las flechas de atrás y adelante del navegador funcionan.

## Publicar con GitHub Pages

1. Sube el contenido de esta carpeta a un repositorio (con `index.html` en la raíz).
2. En el repositorio ve a **Settings → Pages**.
3. En *Build and deployment*, elige **Deploy from a branch**, rama `main`, carpeta `/ (root)` y guarda.
4. Al cabo de un minuto el sitio queda en `https://<tu-usuario>.github.io/<nombre-del-repo>/`.

## Estructura

```
index.html   página y lógica de navegación (sin dependencias)
img/         una imagen por pantalla
.nojekyll    hace que GitHub Pages sirva los archivos tal cual
```
