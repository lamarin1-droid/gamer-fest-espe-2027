# GAMER FEST ESPE 2027

Landing page responsiva (Mobile First) de un evento gamer universitario hipotético, creada con HTML5 y Bootstrap 5.3 como práctica de Programación Web. Las fechas, los premios y los auspiciantes son demostrativos.

**Autor:** [tu nombre]
**Asignatura:** [nombre de la asignatura]
**Fecha:** 28/10/2026

## Cómo abrirlo

1. Descarga o clona el repositorio.
2. Abre `index.html` en un navegador moderno (Chrome, Edge o Firefox).

No necesita instalación ni servidor.

## Dependencias

- **Bootstrap 5.3:** viene incluido en la carpeta `bootstrap/`, por lo que los estilos y el menú del teléfono funcionan sin conexión.
- **Mapa de Google Maps:** necesita Internet. Si no carga, la página conserva la descripción de la ubicación y un enlace alternativo.
- **Imágenes:** están en la carpeta `imagenes/`, no dependen de Internet.

## Estructura del proyecto

```
gamerfest/
├── index.html
├── README.md
├── imagenes/
└── bootstrap/
    ├── css/bootstrap.min.css
    └── js/bootstrap.bundle.min.js
```

## Secciones de la página

1. Encabezado con menú de navegación (se colapsa en el teléfono).
2. Inicio: invitación, datos del evento y botón de inscripción.
3. Categorías: Shooter 5v5, Peleas 1v1, MOBA y Juegos móviles.
4. Premios: podio con teclado, audífonos y mouse gamer.
5. Auspiciantes: tres marcas ficticias.
6. Ubicación: mapa del campus Belisario Quevedo.
7. Inscripción: espacio reservado para el formulario.
8. Pie de página con enlaces demostrativos a Instagram, Facebook y TikTok.

## Diseño

- Enfoque Mobile First con la grilla y las utilidades de Bootstrap.
- Pensado para anchos de 375 px (teléfono) y 1440 px (portátil).
- El diseño usa clases de Bootstrap. Solo el menú de navegación y el fondo de la sección de inicio tienen ajustes de estilo propios, dentro de `index.html`.

## Estado del proyecto

- El formulario de inscripción, sus validaciones y su confirmación (RF-06, RF-07 y RF-08) están pendientes. El espacio en la página ya está reservado.
- Los enlaces de redes sociales son demostrativos y no dirigen a cuentas reales.

## Cómo comprobar el diseño responsivo

1. Abre `index.html` en el navegador.
2. Presiona F12 y activa la vista de dispositivos.
3. Prueba con 375 px de ancho (teléfono) y con 1440 px (portátil).

## Control de versiones

El proyecto se mantiene con Git en el repositorio `gamer-fest-espe-2027`, con commits que describen cada cambio.
