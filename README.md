# Tienda Urbana — Pre-Entrega

## Propósito
Este proyecto es una página web demostrativa para una tienda de productos urbanos. Incluye una presentación, catálogo de productos, reseñas de clientes y formulario de contacto.

## Slider integrado
Debajo de los tres productos originales aparece un carrusel con seis ilustraciones SVG nuevas de 800 × 500 px. Se adapta al ancho disponible sin deformar las imágenes.

Incluye avance automático cada 4,5 segundos, flechas, indicadores, pausa, navegación con las flechas del teclado y deslizamiento táctil. Se pausa al pasar el mouse, al enfocar sus controles o al ocultar la pestaña. Respeta la preferencia de movimiento reducido.

- `slider-productos/slider.html`: carrusel y comportamiento.
- `slider-productos/productos/`: seis imágenes SVG editables.
- `styles.css`: estilos de la página y del marco del carrusel.

Los productos nuevos son ilustraciones demostrativas. No se agregaron precios ni enlaces de compra.
El formulario conserva el endpoint Formspree del proyecto recibido; esta actualización no verifica la recepción de mensajes.

## Paleta de colores
La página usa azul noche, superficies azul pizarra, textos claros y acentos verde lima a juego con los productos. La paleta se puede ajustar desde las variables al inicio de `styles.css`.
