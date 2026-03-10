===============================================================
  xx_disWeb26 — Proyecto de Diseño Web
  Tema: Animales Domésticos
  Metodología Principal: CSS Grid + Flexbox + Bootstrap 5
===============================================================

INSTRUCCIONES PARA EJECUTAR LA PÁGINA
---------------------------------------
1. Descomprimir el archivo xx_disWeb26.zip en una carpeta local.
2. Abrir el archivo index.html con cualquier navegador web moderno
   (Chrome, Firefox, Edge, Safari).
3. NO se requiere servidor web — funciona abriendo directamente
   el archivo desde el sistema de archivos local.
4. Asegurarse de tener conexión a internet para:
   - Cargar Bootstrap desde CDN
   - Cargar fuentes de Google Fonts
   - Reproducir videos de YouTube (enlazados, no descargados)
   - Reproducir audios desde URLs externas

ESTRUCTURA DE ARCHIVOS
-----------------------
xx_disWeb26/
├── index.html          → Página principal
├── carrusel.html       → Carrusel de animales (cargado en iframe)
├── footer_grid.html    → Footer grid del equipo (cargado en iframe)
├── README.txt          → Este archivo
└── css/
    └── styles.css      → Estilos principales

PARTICULARIDADES DEL DISEÑO
------------------------------

1. METODOLOGÍA GRID (punto 4 y 5):
   - El mosaico de audios y videos usa CSS Grid con 3 columnas.
   - El footer del equipo usa CSS Grid 2 filas × 4 columnas.
   - Ambos se adaptan en mobile a 1 o 2 columnas.

2. CARRUSEL INFINITO (punto 2):
   - carrusel.html contiene 4 cards de animales (Perro, Gato,
     Hámster, Conejo) duplicadas para crear un loop infinito.
   - Animación CSS pura con @keyframes scrollCards.
   - Se pausa al hacer hover sobre el carrusel.

3. NAVBAR CON TOOLTIPS (punto 3):
   - La barra de navegación usa Bootstrap Navbar.
   - Cada ítem tiene data-bs-toggle="tooltip" con descripción.
   - Tooltips inicializados via JavaScript al cargar la página.

4. CUENTO (punto 6):
   - ::first-letter: Drop cap con fuente "Abril Fatface",
     tamaño 4.5rem, color naranja con sombra.
   - ::first-line: Fuente "Abril Fatface", color azul primario.

5. ARCOÍRIS DE LETRAS (punto 7):
   - Fuente especial: "Pacifico" de Google Fonts.
   - Cada letra en un <span> con color diferente del espectro.
   - Animación @keyframes bounce con delay escalonado por letra.

6. FAVICON (punto 8):
   - Emoji 🏫 (aula de clase) como favicon SVG inline en el <head>.

7. MULTIMEDIA (punto 9):
   - Todos los videos son iframes de YouTube (enlaces externos).
   - Todos los audios son enlaces a URLs de freesoundslibrary.
   - Ningún archivo de audio/video está almacenado en la carpeta.

8. RESPONSIVE DESIGN (punto 10):
   - Breakpoint principal: 576px (móvil).
   - En móvil: elementos se apilan (grid → 1 columna).
   - Color de fondo del body cambia a #fff3e0 (naranja claro).
   - Color de fondo del footer cambia a #880e4f (rosa oscuro).
   - Tamaño de letra del equipo cambia a 0.5rem.
   - Tamaño general de letra se reduce.

9. IFRAMES (obligatorio):
   - carrusel.html se proyecta en iframe en index.html.
   - footer_grid.html se proyecta en iframe en el footer.

10. EXTRAS:
    - Tooltips Bootstrap en todos los ítems del menú.
    - Animaciones hover en cards multimedia y footer.
    - Gradiente en header hero.
    - Sticky navbar.

INTEGRANTES DEL GRUPO
-----------------------
1. Ana García        — Diseñadora UI
2. Carlos López      — Desarrollador Frontend
3. Valentina Ruiz    — Contenido & Media
4. Miguel Torres     — Responsive Design
5. Sofía Martínez    — QA & Testing
6. Diego Herrera     — Animaciones CSS
7. Laura Jiménez     — Documentación
8. Andrés Morales    — Líder del Proyecto

===============================================================
