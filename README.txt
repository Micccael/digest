DIGEST - PROTOTIPO PWA
======================

Contenido:
- index.html: aplicación.
- manifest.webmanifest: configuración instalable.
- sw.js: caché para uso offline después de la primera carga.
- icon.svg: ícono.

FUNCIONES
- Comidas con varios alimentos e ingredientes por registro, cada uno con su cantidad.
- Síntomas múltiples, síntomas personalizados e intensidad Ligero / Moderado / Intenso.
- Actividad con duración e intensidad.
- Medicamentos, dosis y estado de toma.
- Historial por fecha, eliminación de registros.
- Exportación CSV y copia de seguridad JSON / restauración.
- Almacenamiento local del navegador.

IMPORTANTE
Para instalarla como PWA en iPhone, debe estar publicada en una dirección HTTPS.
Abrí esa dirección en Safari > botón Compartir > Añadir a pantalla de inicio.

Los datos quedan guardados en el navegador de ese dispositivo. No se sincronizan entre
dispositivos ni se envían a un servidor. Exportá copias de seguridad periódicamente.

PUBLICACIÓN
Podés alojar estos archivos en un hosting estático HTTPS (por ejemplo, GitHub Pages).
El service worker requiere HTTPS (o localhost para pruebas).
