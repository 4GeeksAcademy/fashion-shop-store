# AGENTS.md

## Proyecto
Prototipo visual de tienda online para una marca de moda francesa, con Home, catálogo, producto, carrito y checkout.

## Stack y estructura
Usar HTML semántico y CSS con Tailwind compilado. No añadir JavaScript. `server.py` sirve `index.html` mediante Flask. Añadir datos estructurados Schema.org con microdatos HTML.

## Convenciones
Mantener estilos consistentes y reutilizar navbar y footer. Enlazar las vistas entre sí y asegurar contenido indexable.

## Reglas de dominio
El checkout muestra datos personales, dirección de entrega y pago con tarjeta. Carrito, filtros y pago son demostrativos; usar productos y precios de ejemplo.

## Formas de trabajar
Diseñar mobile first y aplicar buenas prácticas de accesibilidad. No dar una tarea por terminada hasta que Lighthouse Accessibility supere 80 puntos; si no, corregir y volver a evaluar.

## Límites
No implementar backend, pagos reales ni comportamiento dinámico que requiera JavaScript.

## Verificación
Ejecutar `python3 server.py`; comprobar enlaces, estilos y vistas en móvil, tablet y escritorio. Ejecutar Lighthouse Accessibility y exigir una puntuación superior a 80.
