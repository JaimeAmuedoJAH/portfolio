One-page portfolio en HTML/CSS/JS vanilla, listo para GitHub Pages. Muestra perfil de Data Analyst y Desarrollador de Apps Móviles, proyectos, formación y contacto.

## Demo
- Producción: <https://JaimeAmuedoJAH.github.io/portfolio> <!-- reemplaza -->
- Repositorio: <https://github.com/JaimeAmuedoJAH/`portfolio`> <!-- o el repo actual -->

## Estructura
```
.
├── index.html   # Maquetación principal
├── styles.css   # Estilos, variables y responsive
├── script.js    # Scroll suave, menú móvil, animaciones
└── assets/      # (opcional) imágenes/recursos locales
```

## Características
- Diseño one-page moderno y minimalista.
- Secciones: Hero, Proyectos, Sobre mí, Formación/Conocimientos, Contacto.
- Responsive (móvil, tablet, desktop) con navegación suave.
- Sin dependencias ni build: solo HTML, CSS y JS.

## Tecnologías
- HTML5 semántico
- CSS3 (variables, grid/flex, animaciones)
- JavaScript ES6 (IntersectionObserver para animaciones y resaltar secciones)

## Uso local
1) Clona el repo  
`git clone https://github.com/JaimeAmuedoJAH/portfolio.git`
2) Abre `index.html` en tu navegador (doble clic o `live server`).

## Personalización rápida
- Texto/perfil: editar sección Hero y Sobre mí en `index.html`.
- Proyectos: cards en la sección “Proyectos”.
- Formación/Tech stack: secciones `#extra` y `#extra-2`.
- Contacto: emails, links y CTA en la sección “Contáctame”.
- Colores/tipografía: variables en `styles.css` (`:root`).
- Foto del hero: actualizar `src` de `.hero__photo img` en `index.html`.

## Despliegue en GitHub Pages
1) Sube a una rama (`main` por ejemplo).  
2) En Settings → Pages: Source = Deploy from a branch → `main` → `/ (root)`.  
3) Guarda; espera a que genere la URL.

## Contacto
- [![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jaimeamuedo@gmail.com)
- [![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jaime-amuedo-a432bb354/)
