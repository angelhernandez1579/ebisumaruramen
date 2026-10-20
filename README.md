# Ebisumaru Ramen · Propuesta web

Página estática (HTML, CSS y JS, sin dependencias ni build). Las fotos y el logo vienen del menú del restaurante.

## Estructura
- `index.html`: la página completa. El menú (precios, nombres, descripciones) está en el objeto `D` dentro del `<script>` al final.
- `assets/`: imágenes en WebP.
- `.nojekyll`: evita que GitHub Pages procese el sitio con Jekyll.

## Publicar en GitHub Pages
1. Crea un repositorio y sube todo el contenido de esta carpeta a la raíz (incluye `.nojekyll`).
2. En el repositorio: Settings > Pages > Build and deployment > Source: "Deploy from a branch".
3. Elige la rama `main` y la carpeta `/ (root)`, y guarda.
4. En uno o dos minutos la página queda en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

## Pendiente antes de entregar al cliente
- Dirección, horario, teléfono e Instagram (texto subrayado en la sección "Ven a comer").
- Enlaces de los botones de WhatsApp y Uber Eats.
- Quitar la franja amarilla de propuesta (`<div class="demo">`).
- Confirmar que cada foto corresponde a su platillo y el precio del Yakimeshi Karague.
