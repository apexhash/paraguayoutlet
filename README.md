# Paraguay Outlet — demostración para GitHub Pages

Tienda demostrativa en HTML estático: estructura, estilos y filtros están dentro de `index.html`. El logo principal, el icono, las imágenes sociales y las fotos de producto están en el mismo nivel que `index.html`, sin carpetas de assets ni dependencias. Para GitHub Pages, sube `index.html`, `README.md`, `TODO.md`, `manus-routes.json`, los recursos gráficos y las imágenes WebP a la raíz del repositorio. No hace falta instalar dependencias. En GitHub, activa **Settings → Pages** y publica desde la rama y raíz elegidas.

## Nueva identidad visual

- `paraguay-outlet-logo-principal.png`: logo horizontal en PNG con fondo transparente, colores azul, rojo y blanco y referencias sutiles a las banderas de Paraguay y Estados Unidos. En el encabezado y el pie se muestra sobre un respaldo blanco para mantener el contraste.
- `paraguay-outlet-logo-icon.png`: emblema compacto cuadrado utilizado como favicon del sitio.
- `paraguay-outlet-instagram-perfil.png`: avatar cuadrado con el emblema PO y el nombre completo, preparado para el recorte circular de Instagram.
- `paraguay-outlet-facebook-portada.png`: portada panorámica coordinada con el nuevo logo, conservando el fondo textil y la frase “ROPA · MODA · ACCESORIOS”.

Las piezas sociales mantienen la paleta blanca, roja y azul y no usan tonos dorados. Facebook puede recortar la portada de forma distinta según el dispositivo; por eso el logo permanece centrado en el área segura.

## Antes de usarla como tienda real

- Los siete importes de las tarjetas son **precios de muestra**, variados entre **Gs. 235.000 y Gs. 250.000**. Actualízalos con tus precios reales y verifica talles, colores y disponibilidad.
- El botón principal, el acceso flotante y las consultas de producto abren directamente [WhatsApp Paraguay Outlet](https://wa.me/595971813022). Los botones de cada prenda preparan una pregunta con el nombre del producto.
- En el pie se muestran Instagram, TikTok y Facebook como redes de la tienda, pero todavía no enlazan a perfiles específicos porque no se proporcionaron las URL de usuario. Añade tus enlaces reales en `index.html` cuando los tengas.
- Las fotos de producto son material ilustrativo recopilado en una búsqueda de imágenes y algunas provienen de las fotos de producto de esta conversación. Verifica los derechos de uso comercial o reemplázalas por fotografías propias antes de operar la tienda públicamente.
- No incluye pagos, inventario conectado ni gestión de pedidos; es un escaparate visual de demostración.

## Imágenes de productos

Las fotos de muestra están en la raíz: `hero-ck-3d.webp`, `calvin-klein-tee.webp`, `tommy-hilfiger-tee.webp`, `abercrombie-polo-pack.webp`, `polo-ralph-lauren-shorts.webp`, `pantalon-everyday.webp`, `polo-ralph-lauren-socks.webp` y `polo-ralph-lauren-kepi.webp`.

`manus-routes.json` sirve para declarar la ruta de vista previa de Manus; no es necesario para GitHub Pages. `manus-webdev.json` es metadato del proyecto Manus y se excluye del paquete portable para GitHub.

## Vista previa local

Ejecuta `python3 -m http.server 8000` en esta carpeta y abre `http://localhost:8000`.
