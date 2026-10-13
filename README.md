# NEXUS GIFT — storefront de regalos gamer

Sitio estático preparado para GitHub Pages, con diseño responsive, animaciones y flujo de selección de juego/plataforma/username.

## Publicar en GitHub Pages
1. Subí el contenido del ZIP a un repositorio.
2. En **Settings → Pages**, seleccioná la rama principal y la carpeta `/ (root)`.
3. Guardá y esperá la publicación.

## Importante sobre pagos
Este proyecto es un frontend estático: no procesa pagos ni verifica transacciones. La tarjeta Visa terminada en 5258 es solo una representación visual y no está conectada a una cuenta bancaria. Al continuar, se abre la tienda oficial del juego; la pantalla final aclara que el pago debe completarse allí. Para cobrar dentro de este sitio, integrá un proveedor de pagos real (por ejemplo, Mercado Pago Checkout Pro) con backend y credenciales seguras. Nunca guardes números de tarjeta ni credenciales en el frontend.

## Precios y disponibilidad
Los importes en USD son referencias de las tiendas oficiales consultadas al preparar el sitio y pueden variar por región, impuestos o cambios de catálogo. GTA VI y FC 27 están sujetos a disponibilidad y políticas de regalo de cada plataforma. Los enlaces de compra están en `app.js`.

## Personalización
- `index.html`: contenido, estructura y productos destacados.
- `styles.css`: diseño visual, responsive y animaciones.
- `app.js`: precios de referencia, enlaces oficiales y flujo de selección.

Las imágenes de portada remotas pueden cambiar o no estar disponibles; el diseño muestra fondos estilizados de respaldo. Para producción, alojá imágenes con licencia o recursos de prensa autorizados dentro del repositorio.
