# Japón 2027

Cuaderno de viaje a Japón del 30 de julio al 28 de agosto de 2027.

Web estática de un solo archivo (`index.html`) pensada para GitHub Pages.

## Secciones

- Ruta: diagrama de la línea Tokio → Hokkaido → Osaka → Kioto → Alpes → Hiroshima y calendario
- Día a día: plan de los 30 días con enlaces a Google Maps y notas personales
- Transporte: pases JR regionales y todos los trayectos con coste
- Alojamientos: zona, tipo, precio orientativo y búsqueda en Booking para cada parada
- Presupuesto: calculadora editable por persona
- Preparativos: lista ordenada por fecha límite
- Consejos: calor, Obon, tifones, ahorro, etiqueta y frases útiles

## Publicar en GitHub Pages

Settings → Pages → Source: "Deploy from a branch" → rama `main`, carpeta `/ (root)`.

La web quedará en `https://fearthefoca3.github.io/Japon2027/`.

## Editar el contenido

Todo el contenido está en los objetos `STAYS`, `ROUTE`, `DAYS`, `LEGS`, `PASSES`, `CHECK` y `TIPS` al principio del `<script>` de `index.html`.

Las notas, la lista de preparativos y el presupuesto se guardan en el navegador de cada dispositivo (localStorage).
