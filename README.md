# Japón 2027

Cuaderno de viaje a Japón del 30 de julio al 22 de agosto de 2027: llegada a Osaka, Kioto, los Alpes, ryokan en Hakone y 8 días finales en Tokio.

Web estática de un solo archivo (`index.html`) pensada para GitHub Pages.

## Secciones

- Resumen: mosaico de fotos de lo que veréis, mapa de las paradas, la ruta ciudad a ciudad y calendario
- Ciudades y mapas: qué ver en cada ciudad con foto, tiempo, precio y etiqueta, mapa de toda la ciudad y mapa por día
- Día a día: línea de tiempo de cada día (visitar, comer, tren, dormir) con fotos y ruta en Google Maps
- Vuelos y transporte: qué vuelo comprar y cuándo, pases de tren y todos los trayectos
- Alojamientos: una ficha por ciudad con búsqueda en Booking y Airbnb
- Presupuesto: desglose por persona en yenes y euros
- Preparativos y Consejos

## Publicar en GitHub Pages

Settings → Pages → Source: "Deploy from a branch" → rama `main`, carpeta `/ (root)`.

La web quedará en `https://fearthefoca3.github.io/Japon2027/`.

## Editar el contenido

Todo el contenido está en los objetos `SPOTS`, `CITIES`, `DAYS`, `LEGS`, `PASSES`, `CHECK` y `TIPS` al principio del `<script>` de `index.html`.

Las notas, la lista de preparativos y el presupuesto se guardan en el navegador de cada dispositivo (localStorage).
