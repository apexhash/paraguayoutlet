# Paraguay Outlet — demostración para GitHub Pages

Tienda demostrativa en HTML estático: estructura, estilos y filtros están dentro de `index.html`, y las imágenes WebP se guardan en el mismo nivel, sin carpetas de recursos ni dependencias. Para GitHub Pages, sube `index.html`, este README y las imágenes WebP a la raíz del repositorio. No hace falta instalar dependencias. En GitHub, activa **Settings → Pages** y publica desde la rama y la raíz elegidas.

## Antes de usarla como tienda real

- Los importes de las tarjetas son **precios de muestra**. Actualízalos con tus precios reales y verifica talles, colores y disponibilidad.
- El botón principal, el acceso flotante y las consultas de producto abren directamente [WhatsApp Paraguay Outlet](https://wa.me/595971813022). Los botones de cada prenda preparan una pregunta con el nombre del producto.
- En el pie se muestran Instagram, TikTok y Facebook como redes de la tienda, pero todavía no enlazan a perfiles específicos porque no se proporcionaron las URL de usuario. Añade tus enlaces reales en `index.html` cuando los tengas.
- Las fotos son material ilustrativo recopilado en una búsqueda de imágenes y algunas provienen de las fotos de producto de esta conversación. Verifica los derechos de uso comercial o reemplázalas por fotografías propias antes de operar la tienda públicamente.
- No incluye pagos, inventario conectado ni gestión de pedidos; es un escaparate visual de demostración.

## Archivos de imagen

Todos los recursos visuales están en la raíz: `avatar-po.webp`, `hero-ck-3d.webp`, `calvin-klein-tee.webp`, `tommy-hilfiger-tee.webp`, `abercrombie-polo-pack.webp`, `polo-ralph-lauren-shorts.webp`, `pantalon-everyday.webp`, `polo-ralph-lauren-socks.webp` y `polo-ralph-lauren-kepi.webp`.

`manus-routes.json` sirve para declarar la ruta de vista previa de Manus; no es necesario para GitHub Pages. `manus-webdev.json` es metadato del proyecto Manus y se excluye del paquete portable para GitHub.

## Vista previa local

Ejecuta `python3 -m http.server 8000` en esta carpeta y abre `http://localhost:8000`.
