MINI SÚPER EITHAN POS V11.1
===========================

Versión PWA estática lista para GitHub Pages.

FUNCIONES ACTIVAS
- Caja/POS con carrito y cobro en efectivo, transferencia, tarjeta y fiado.
- Inventario con productos, costo, precio, stock mínimo y edición.
- Buscador por nombre, categoría y código.
- Escáner por cámara cuando el navegador soporta BarcodeDetector + entrada manual.
- Compras, gastos y fiados.
- Cierre de caja.
- Reportes de ventas, ganancia y productos más vendidos.
- Recibos para imprimir y compartir desde el iPhone.
- Exportación/importación de respaldo JSON.
- Exportación CSV de ventas.
- PWA instalable y funcionamiento local mediante localStorage/service worker.

SUBIR A GITHUB PAGES
1. Extrae este ZIP.
2. En tu repositorio, entra a Add file > Upload files.
3. Sube TODO el contenido de esta carpeta (index.html, manifest.webmanifest, sw.js y assets).
4. Ve a Settings > Pages.
5. Source: Deploy from a branch.
6. Branch: main y carpeta /(root).
7. Save.
8. Abre la URL de GitHub Pages.

IMPORTANTE
- En iPhone, la cámara requiere permiso del navegador y normalmente HTTPS (GitHub Pages lo proporciona).
- Web Bluetooth no está habilitado de forma general en Safari iPhone. La app usa imprimir/compartir del sistema y acepta lectores que actúan como teclado para el campo de código.
- Los datos se guardan en el navegador del dispositivo. Usa Exportar respaldo periódicamente.
