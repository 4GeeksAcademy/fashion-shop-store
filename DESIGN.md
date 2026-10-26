# Diseño

## Dirección visual
Estética editorial contemporánea: protagonismo del producto, fotografía cuidada y una interfaz sobria, práctica y consistente. La tienda debe facilitar la navegación y comparación de prendas, sin parecer una página promocional genérica.

## Shell
- **Cabecera compartida:** franja informativa opcional, logo, búsqueda, cuenta y carrito; debajo, navegación por categorías.
- **Contenido:** ancho máximo de 1440 px, márgenes adaptables y secciones claramente diferenciadas.
- **Footer compartido:** categorías, enlaces legales y contacto.
- En móvil, reorganizar la cabecera y conservar navegación accesible sin JavaScript.

## Tipografía
- **Titulares:** Cormorant Garamond, con Georgia como alternativa.
- **Texto e interfaz:** Manrope, con una alternativa sans-serif del sistema.
- Usar jerarquías claras y tamaños explícitos; no escalar tipografía con el ancho de pantalla.
- Preferir fuentes locales si están disponibles.

## Colores
Definir los colores como variables CSS:
- Fondo: `#FAFAF8`
- Superficie: `#FFFFFF`
- Texto principal: `#202320`
- Texto secundario: `#5D655F`
- Acciones principales: `#C84A34`
- Acento secundario: `#355C4A`
- Bordes: `#D8DDD9`
- Foco visible: `#1D6F6D`

Mantener contraste legible y no depender solo del color para comunicar estados.

## Iconografía
Usar iconos Lucide como SVG estático, sin dependencias de JavaScript. Mantener trazo y tamaño consistentes. Los botones de solo icono necesitan nombre accesible y un área interactiva cómoda.

## Componentes y vistas
- **Productos:** tarjetas repetibles con fotografía, nombre, precio y enlace al detalle; evitar marcos decorativos innecesarios.
- **Inicio:** campaña con fotografía real del producto, seguida de nuevos lanzamientos y más vendidos.
- **Catálogo:** filtros visuales y cuadrícula de cuatro columnas en escritorio, tres en tablet y dos en móvil; mostrar 20 productos de ejemplo.
- **Producto:** imagen y detalles en dos columnas en escritorio, apilados en móvil.
- **Carrito:** lista de productos y resumen claramente diferenciados; apilados en móvil.
- **Checkout:** tres secciones ordenadas para datos personales, entrega y pago.

## Responsive y accesibilidad
Diseñar mobile first y ampliar con media queries. Usar HTML semántico, etiquetas asociadas a los campos, textos alternativos descriptivos, foco visible y navegación por teclado. Evitar solapamientos y mantener controles táctiles cómodos.

## Límite del prototipo
Usar solo HTML y CSS, sin backend ni pagos reales. Los filtros, cantidades, totales y acciones del carrito son estáticos; no presentarlos como operaciones funcionales.
