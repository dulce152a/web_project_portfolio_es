# Portafolio personal — Sprint 4

Página responsiva creada con HTML y CSS a partir del diseño de TripleTen. Incluye la foto y presentación de Dulce Agra, su correo público y los enlaces de su proyecto de cafetería. Conserva la segunda tarjeta y las redes sociales del ejemplo hasta recibir sus datos. El fondo es #111111 y el acento es lavanda #B69CFF.

## Funcionalidad

- Perfil con presentación y enlaces.
- Lista de habilidades y herramientas.
- Dos tarjetas de proyectos con tecnologías y enlaces.
- Sección de contacto; «Hablemos» lleva a ella y el correo utiliza `mailto:`.
- Adaptación a escritorio, tableta y móvil.

## Tecnologías y técnicas

HTML semántico, CSS, Flexbox y media queries en 1023px y 767px. Fuentes Open Sans y Archivo Black conectadas localmente en WOFF2 y WOFF. Imágenes comprimidas con `object-fit`, tarjetas con `aspect-ratio: 16 / 9`, velos con `linear-gradient` y luces de fondo con `radial-gradient` posicionadas con `calc()`.

La página no utiliza JavaScript, librerías de interfaz ni procesos de compilación.

## Estructura

- `index.html`: contenido de la página.
- `styles/`: normalización y estilos.
- `fonts/`: fuentes locales.
- `images/`: fotografías, miniaturas e iconos del diseño.

## Abrir el proyecto

Abrir `index.html` en un navegador o utilizar Live Server en VS Code.

## Referencia

[Diseño de TripleTen en Figma](https://www.figma.com/design/dn1orMXtOpzUFfwZY9mghh/Sprint-4-Proyecto-de-Portafolio?node-id=0-1)

## GitHub Pages

Pendiente de publicación y de añadir el enlace público verificado. El repositorio remoto de esta copia todavía corresponde a la cafetería; falta confirmar el repositorio del portafolio.

## Pendientes de la versión de ejemplo

- Los enlaces del CV, de la segunda tarjeta y de las redes sociales conservan `href="#"` hasta disponer de sus destinos. El perfil de GitHub y los dos enlaces de la cafetería ya están conectados.
- Correo público: `nextlevelxds@gmail.com`. Perfil: https://github.com/dulce152a. JavaScript se presenta como próximo paso de aprendizaje.
- Terminar la comparación visual de tableta, comprobar las tolerancias de medidas de la lista oficial y revisar en Firefox. El acceso al navegador se interrumpió durante la revisión final.
- Publicar en GitHub Pages, añadir aquí su URL y realizar la entrega en TripleTen.

## Comprobaciones realizadas en la versión base

- Se visualizaron las versiones de escritorio y móvil en Chrome.
- No se detectaron imágenes rotas ni desplazamiento horizontal en las mediciones de 320, 470, 665, 767, 999, 1022, 1024, 1100, 1440 y 1500 píxeles. El zoom del navegador redondeó las medidas solicitadas de 768 y 1023 píxeles; queda pendiente verificarlas exactamente.
- Las fuentes locales cargaron correctamente.
- Se revisaron los marcos de referencia de escritorio, tableta, móvil y hover en Figma.

La versión personalizada también se revisó visualmente en escritorio y móvil. No se detectaron imágenes rotas ni desbordamientos en 320, 470, 665, 767, 999, 1100, 1440 y 1500 píxeles. Sigue pendiente la comprobación exacta de tableta, la comparación de tolerancias y Firefox.
