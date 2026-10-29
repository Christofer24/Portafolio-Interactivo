# Portafolio Interactivo — Arcilla Viva

Landing page de un taller de cerámica ficticio. Práctica Calificada 3 de Hojas de Estilo en Cascada Avanzado.

## Tecnologías
- HTML5
- Bootstrap 5.3.3 (CDN)
- CSS puro (`css/style.css`)

## Bootstrap
Navbar colapsable (`navbar-expand-md`), grid (`container`, `row`, `col-sm-12 col-md-*`), formulario (`form-control`, `form-label`, `mb-3`) y botones (`btn btn-primary`, `btn btn-secondary`, `d-grid gap-2`).

## Transformaciones 2D (con `transition`)
| Caja | Efecto en `:hover` |
|------|--------------------|
| Serie Mar | `rotate(6deg)` |
| Serie Sol | `scale(1.1)` |
| Serie Tierra | `translateY(-12px) skewX(-6deg)` |

## Transformación 3D
Tarjeta "Jarrón Luna": el contenedor usa `perspective`, la tarjeta usa `transform-style: preserve-3d` y al hacer hover aplica `rotateX(12deg) rotateY(180deg)`. Las caras usan `backface-visibility: hidden`.

## Animaciones (`@keyframes`)
- `girar`: rueda de alfarero, loader de página y mini spinner del botón Enviar (`infinite`, `linear`).
- `deslizar`: el título del hero entra desde la izquierda (`1s`, `ease-out`, `1` iteración).
- `latido`: el punto del logo cambia de tamaño y color (`2s`, `infinite`, `ease-in-out`).
- `ocultar`: desvanece el loader de página.

## Cómo ejecutarlo
Abre `index.html` en el navegador.
