# Estudio Contable Vélez & Asociados — sitio web

Sitio de una sola página en HTML, CSS y JavaScript, sin frameworks ni dependencias.
Todo vive en `index.html`.

**Demo para revisión del cliente.** Esta versión está publicada con `noindex` para que
no aparezca en buscadores mientras se revisa.

## Pendientes antes de publicar en el dominio real

1. **Número de WhatsApp y teléfono** — reemplazar `5493510000000` (WhatsApp) y
   `+543510000000` / `+54 351 000-0000` (teléfono) en todo el archivo.
2. **Endpoint del formulario** — completar la constante `FORM_ENDPOINT` en el script
   del final con la URL de Formspree, Basin o el backend propio. Mientras esté vacía,
   el formulario valida pero avisa que el envío no está conectado.
3. **`robots`** — en el `<head>`, reemplazar `noindex, nofollow` por
   `index, follow, max-image-preview:large, max-snippet:-1`.
4. **Imagen de Open Graph** — generar `og-velez-asociados.jpg` (1200×630) y subirla a
   la raíz del dominio.
5. **Datos a confirmar** — "15+ años", "48 h de respuesta" y el horario de atención
   (lunes a viernes de 9 a 18 h).
6. **Coordenadas del schema** — son aproximadas a la altura de Ayacucho 395; se pueden
   ajustar con las exactas de Google Maps.

## Datos reales ya cargados

- Dirección: Ayacucho 395, Piso 7 Of. C — X5000 Córdoba, Argentina
- Dominio previsto: www.estudiovyasociados.com.ar

## Estructura de `index.html`

- **CSS** (`<style>` en el `<head>`): 18 bloques numerados, desde los tokens de diseño
  (color, tipografía, espaciado) hasta el responsive.
- **HTML**: hero, métricas, servicios, sociedades, proceso, rubros, estudio, preguntas
  frecuentes, ubicación y contacto.
- **JavaScript** (al final del `<body>`): 10 bloques numerados — header, menú móvil,
  animaciones de scroll, contadores, navegación activa, acordeón, mapa diferido y
  formulario.
- **Datos estructurados**: JSON-LD en el `<head>` con AccountingService, WebSite,
  WebPage, BreadcrumbList y FAQPage.

Desarrollado por ALORA.
