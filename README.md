# Dr. Jorge — Landing de contacto

Página de contacto para **Dr. Jorge** (cliente: `dr.jorgereyes.cirujano`), **Cirujano Gastrointestinal y Laparoscópico** en León, Guanajuato. Optimizada para aparecer en resultados de búsqueda de Google como página de contacto.

Sitio de un solo archivo: [`index.html`](index.html) (HTML + CSS + JS embebidos, sin dependencias de build).

## Contacto configurado
- **Teléfono / WhatsApp:** +52 477 541 5614 (`tel:+524775415614`, `https://wa.me/524775415614`)
- **Zona de servicio (SEO):** León, Guanajuato

## Pendientes por confirmar (marcados con `*` o "Próximamente")
- **Ubicaciones:** 2 consultorios — direcciones por confirmar.
- **Correo de contacto:** por confirmar.
- **Foto del Dr. Jorge:** placeholder en el hero → reemplazar por `assets/dr-jorge.jpg` (ver comentario en el HTML).
- **Estadísticas y certificaciones:** cifras ilustrativas marcadas con `*`.
- **Testimonios:** de ejemplo, reemplazar por reseñas reales.

## Cómo personalizar
- **Color verde:** todo el tema vive en las variables CSS al inicio del `<style>` (`:root`). Cambia `--brand`, `--brand-dark`, `--brand-light`, etc. en una línea para igualar tu HTML de referencia.
- **Foto:** descomenta el `<img>` dentro de `.photo-card` y coloca el archivo en `assets/`.
- **Datos de contacto:** busca `524775415614` para el teléfono y los bloques "Próximamente" para ubicación/correo.

## Cómo verlo
Abre `index.html` en el navegador, o sirve la carpeta:
```
npx serve .
```

## Despliegue sugerido
GitHub Pages / Netlify / Vercel (sitio estático). Para GitHub Pages: Settings → Pages → rama `main` / carpeta raíz.
