# PellBella — Paquete de despliegue para Netlify (v9)

## 📦 Qué hay en esta carpeta (todo lo necesario para publicar)

| Archivo | Uso |
|---|---|
| `index.html` | El sitio completo (versión v9) — Netlify lo reconoce automáticamente como página principal |
| `logo-pellbellacr-full.png` | Logo en la barra superior y el footer |
| `favicon-pellbella.png` | Ícono de la pestaña del navegador |
| `logo-pellbella-dark-bg.png` | Símbolo compacto (uso libre) |
| `logo-pellbella-light-bg.png` | Logo para fondo blanco (papelería, no se usa en el sitio) |
| `emsella.jpg` / `emsculpt.jpg` / `exilis.jpg` / `exilite.jpg` / `lymphastim.jpg` | Fotos de los equipos BTL |
| `maxima-seguridad-btl.mp4` | Video "Sobre PellBella" |
| `maxima-seguridad-btl-poster.jpg` | Miniatura del video (versión nítida, mejorada) |
| `Incontinencia_antes.png` / `Incontinencia_despues.png` | Caso real — Piso Pélvico / EMSELLA |

## ❌ Todavía faltan estas 4 imágenes (el sitio no se rompe, muestra un ícono/emoji de respaldo)

| Archivo que falta | Dónde aparece |
|---|---|
| `Diastasis_antes.png` | Caso real — Cuerpo / EMSCULPT ("Antes") |
| `Diastasis_despues.png` | Caso real — Cuerpo / EMSCULPT ("Después") |
| `Flacidez_antes.png` | Caso real — Flacidez / EXILIS ULTRA 360 ("Antes") |
| `Flacidez_despues.png` | Caso real — Flacidez / EXILIS ULTRA 360 ("Después") |

Súbelas después directo a Netlify (arrastrando a la carpeta del sitio) con esos nombres exactos y se conectan solas — no requieren tocar el código.

## 🎥 Videos (no van archivos, son links externos ya configurados)

| Equipo | Plataforma | Nota |
|---|---|---|
| EMSCULPT | YouTube (`iTuHxaBVcyU`) | Ya funciona |
| VANQUISH ME | YouTube (`kfPHrolDtJA`) | Ya funciona |
| EXILIS ULTRA 360 | YouTube (`MUsCYCSyxNk`) | Ya funciona |
| EMSELLA | YouTube (`uaX_bG5FHnk`) | Ya funciona |
| Máxima seguridad con BTL | Video propio (`maxima-seguridad-btl.mp4`) | Incluido en esta carpeta |

Estos IDs de YouTube son videos genéricos de ejemplo (no del canal propio de PellBella). Si más adelante suben sus propios videos a YouTube, se reemplazan buscando `data-vid="ID_VIEJO"` en el código y cambiando el ID.

## 🔗 Otros servicios externos (requieren que el sitio esté en línea con https, no como archivo local)

- **Siku** — sincroniza el calendario de citas en tiempo real
- **Google Maps** — mapa embebido de la ubicación (Plaza del Prado, Curridabat)
- **WhatsApp** — todos los botones y mensajes usan +506 7054 9299
- **Google Fonts** — Cormorant Garamond y DM Sans

## 🚀 Cómo publicar en Netlify (el método más simple: arrastrar y soltar)

1. Ve a [app.netlify.com](https://app.netlify.com) e inicia sesión (o crea cuenta gratis)
2. En el dashboard, busca la zona que dice **"Drag and drop your site output folder here"** (o "Deploys" → arrastra ahí)
3. **Descomprime este ZIP** en tu computadora primero
4. **Arrastra la carpeta completa** (o selecciona todos los archivos de adentro) a esa zona de Netlify
5. Netlify publica el sitio en 10-30 segundos y te da un link tipo `https://nombre-random.netlify.app`
6. (Opcional) En **Site settings → Change site name**, puedes ponerle un nombre más lindo, ej. `pellbellacr.netlify.app`
7. (Opcional) En **Domain settings**, puedes conectar un dominio propio (ej. `pellbellacr.com`) si ya lo tienes comprado

## ✅ Después de publicar, revisa que:

- El logo cargue en la barra superior
- Las fotos de los equipos se vean
- El calendario de Agenda muestre los horarios (esto necesita conexión a internet real, no funciona abriendo el archivo local)
- Los 4 videos de YouTube reproduzcan al hacer clic
- Los botones de WhatsApp abran con el número correcto
