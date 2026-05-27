# 02_Funciones_Basicas

### Nota de Versión:
Este documento describe el estado actual de las funcionalidades interactivas de la aplicación web. Toda la lógica reactiva, el estado y el manejo del DOM están construidos con **Alpine.js**, consumiendo datos desde archivos JSON de forma dinámica.

---

### Archivos:

`index.html`: Contiene toda la estructura visual, la lógica reactiva con **Alpine.js**, y el manejo dinámico del progreso, navegación y modales de la aplicación.

`main.css`: Archivo con los estilos de la aplicación, el diseño del mapa horizontal, modales y el mini-framework de columnas y contenedores.

`/data`: Carpeta que almacena los archivos `.json` con toda la información y base de datos (preguntas, categorías, retos finales y explicaciones) consumida por la aplicación.

`/images`: Carpeta con los recursos gráficos (planetas, asteroides, iconos y fondos) de la aplicación, en formato optimizado **_webp_**.

`/videos`: Carpeta destinada a los archivos `.webm` (ej. `lore_1.webm`, `lore_2.webm`) usados para las transiciones cinematográficas entre asignaturas.

---

### PS:
La base de datos de esta aplicación está separada en múltiples archivos `.json` ubicados en el directorio `/data`. Para agregar nuevas preguntas, cambiar respuestas, explicaciones o configurar el reto final, solo es necesario editar dichos archivos, manteniendo el frontend (`index.html`) intacto.
