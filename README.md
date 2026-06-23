# Dr. Jorge — Landing de contacto

Página de contacto para **Dr. Jorge** (cliente: `dr.jorgereyes.cirujano`), **Cirujano Gastrointestinal y Laparoscópico** en León, Guanajuato. Optimizada para aparecer en resultados de búsqueda de Google como página de contacto.

Sitio de un solo archivo: [`index.html`](index.html) (HTML + CSS + JS embebidos, sin dependencias de build).

## Datos reales (del perfil de Instagram @dr.jorgereyes.cirujano)
- **Nombre completo:** Dr. Jorge Reyes Sánchez (en el hero se muestra "Dr. Jorge")
- **Especialidad:** Cirujano Gastrointestinal y Laparoscopista
- **Certificación:** Colegio Mexicano de Cirugía General
- **Teléfono / WhatsApp:** +52 477 541 5614 (`tel:+524775415614`, `https://wa.me/524775415614`)
- **Sedes:** León (Clínica del Parque) e Irapuato (Médica Insurgentes)
- **Paleta:** verde sage/olivo `#6F8F4E`, bosque `#3C5132`, crema `#F3EEE1` (tomada de las gráficas de marca de IG)

## Fotos reales (ya integradas en `assets/`)
- `assets/dr-jorge-hero.jpg` — hero (Dr. Jorge en quirófano), optimizada a ~1000px.
- `assets/cirugia-precision.jpg` — sección Especialidad.
- `assets/equipo-quirofano.jpg` — sección Por qué elegirme.
Las ilustraciones SVG placeholder fueron reemplazadas por estas fotos.

## Pendientes por confirmar (marcados con `*` o "por confirmar")
- **Direcciones exactas** de las 2 sedes (calle y número).
- **Correo de contacto.**
- **Estadísticas:** cifras ilustrativas marcadas con `*`.
- **Testimonios:** de ejemplo, reemplazar por reseñas reales.

## Cómo personalizar
- **Color verde:** todo el tema vive en las variables CSS al inicio del `<style>` (`:root`). Cambia `--brand`, `--brand-dark`, `--brand-light`, etc. en una línea.
- **Foto:** descomenta el `<img>` dentro de `.photo-card` y coloca el archivo en `assets/`.
- **Datos de contacto:** busca `524775415614` para el teléfono y los bloques "Próximamente" para ubicación/correo.

## Cómo verlo
Abre `index.html` en el navegador, o sirve la carpeta:
```
npx serve .
```

## Despliegue sugerido
GitHub Pages / Netlify / Vercel (sitio estático). Para GitHub Pages: Settings → Pages → rama `main` / carpeta raíz.
