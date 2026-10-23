# Distribuidora JAGA — Sitio web informativo (borrador)

Versión informativa del sitio de Distribuidora JAGA: sin tienda, sin carrito, sin pago en línea y sin precios. Cada producto se consulta por WhatsApp o por teléfono (8600-5421).

## Páginas

| Archivo | Página |
| --- | --- |
| `index.html` | Visor del sitio |
| `inicio.html` | Inicio |
| `marcas.html` | Marcas afiliadas y sus productos |
| `nosotros.html` | Nosotros |
| `contacto.html` | Contacto y preguntas frecuentes |

`img/` contiene fotos y logos en WebP. Cada página HTML incluye su propio CSS y JavaScript; no requiere instalación ni compilación. Esta versión usa el mismo código que el sitio con tienda con `MODO_INFO=true`.

## Ver en local

Abre `index.html` o `inicio.html` en el navegador (las fuentes Saira y Poppins se cargan desde Google Fonts; Crocker va incluida).

## Antes de publicar el sitio oficial

- Quitar `<meta name="robots" content="noindex, nofollow">` de las páginas y borrar `robots.txt` y `_headers`.
- Quitar el aviso amarillo "Propuesta de diseño".
- Confirmar la licencia web de la tipografía Crocker.
- Reemplazar productos y testimonios de ejemplo por datos reales.
- Conectar el envío del formulario de contacto.
