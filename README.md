#  Dinofibra - Web Oficial

Proyecto frontend multipágina para **Dinofibra**, una marca mexicana de cereal funcional diseñado para mejorar la salud digestiva y metabólica. El sitio web destaca por su estilo visual retro/brutalista, alto contraste y navegación intuitiva. Puedes ver la pàgina en https://alanarrietaf.github.io/dinoFibra/ .

##  Sobre el Proyecto

Este sitio web fue desarrollado como una interfaz estática (sin backend ni base de datos) enfocada completamente en la experiencia de usuario (UI/UX), la responsividad y la fidelidad a la identidad gráfica de la marca. 

El diseño utiliza una paleta de colores característica (fondo amarillo y tipografía oscura) combinada con fuentes pixeladas para evocar un estilo clásico y directo.

##  Tecnologías Utilizadas

* **HTML5:** Estructuración semántica multipágina (`index.html`, `about.html`, `tabla.html`).
* **CSS3 Puro (Vanilla):** * Uso de **Flexbox** y **CSS Grid** para la maquetación de tarjetas, hero section y tablas.
    * Implementación de variables CSS (`:root`) para mantener la consistencia en la paleta de colores.
    * Media queries para un diseño 100% responsivo (adaptable a dispositivos móviles).
    * Filtros CSS (`grayscale`, `sepia`) aplicados a iframes de Google Maps para mantener la coherencia estética.
* **Google Fonts:** Integración de tipografías `VT323` y `Share Tech Mono`.

##  Estructura del Proyecto

El repositorio está organizado de la siguiente manera para un fácil despliegue en plataformas como GitHub Pages:

```text
/
├── index.html       # Homepage (Hero, marquesina, y grid de ingredientes)
├── about.html       # Filosofía, visión, misión y mapa interactivo
├── tabla.html       # Declaración nutrimental detallada (formato clásico FDA)
├── README.md        # Documentación del proyecto
├── css/
│   └── style.css    # Hoja de estilos global compartida
└── assets/          # Directorio de recursos gráficos (imágenes PNG/JPEG)
