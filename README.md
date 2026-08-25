# Activá tu marca — landing de planes CREW CO

Landing standalone (un solo `index.html`, sin build) con el checklist de los 6 servicios, carrito en vivo y CTA a WhatsApp.

## Cómo verla ahora
Abrí `index.html` haciendo doble clic — se abre en tu navegador tal cual se va a ver en producción (usa fuentes de Google Fonts y GSAP/Lenis por CDN, así que necesitás conexión a internet para verla con las animaciones).

## Cómo publicarla en GitHub Pages
1. Creá un repo nuevo en GitHub (ej. `crewco-activa-tu-marca`) o agregá esta carpeta a uno existente.
2. Subí `index.html` (y este `README.md` si querés) a la rama `main`.
3. En el repo: **Settings → Pages → Source → Deploy from a branch → main / (root)**.
4. En un par de minutos queda publicada en `https://aldisaligari.github.io/nombre-del-repo/`.

## Qué es editable directo en el archivo
- Array `SERVICES` (arriba del `<script>`): nombre, tagline y acciones incluidas de cada uno de los 6 servicios.
- `WHATSAPP_NUMBER`: número al que se manda el mensaje del checklist.
- El mensaje de WhatsApp se arma solo, uniendo los nombres de los servicios tildados.

## Integración con crewco.site
Cuando migremos el sitio completo, esta página pasa a vivir en el mismo dominio (sin aparecer en el nav). Mientras tanto, el CTA "Activá tu marca" de la página Agencia puede apuntar directo a esta URL de GitHub Pages.
