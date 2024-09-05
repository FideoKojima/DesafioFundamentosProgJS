# Encuentra tu Superhero

[Enlace Directo al Proyecto](https://desafio-fundamentos-prog-js.vercel.app/)

Este proyecto es una aplicación web que permite a los usuarios buscar y consultar información sobre sus superhéroes favoritos utilizando la Superhero API. El objetivo es proporcionar estadísticas y datos detallados de los superhéroes en una interfaz fácil de usar y visualmente atractiva.

## Tabla de Contenidos

- [Características](#características)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Instalación](#instalación)
- [Uso](#uso)
- [Contribuciones](#contribuciones)
- [Licencia](#licencia)
- [Contacto](#contacto)

## Características

- Búsqueda de superhéroes mediante su ID.
- Visualización de datos como nombre, biografía, apariencia, ocupaciones y relaciones.
- Gráfico de torta interactivo que muestra las estadísticas de poder de los superhéroes.
- Validación de entradas para asegurar que el ID ingresado sea válido.
- Manejo de errores y mensajes de alerta para mejorar la experiencia del usuario.

## Tecnologías Utilizadas

- **HTML5**: Estructura básica de la aplicación web.
- **CSS3** (SASS y Bootstrap 5.3.3): Estilización y diseño responsivo.
- **JavaScript** (jQuery y CanvasJS): Lógica de la aplicación, manipulación del DOM y gráficos.
- **Superhero API**: Fuente de datos para la información de los superhéroes.
- **FontAwesome 6.5.2**: Íconos para mejorar la interfaz de usuario.

## Estructura del Proyecto


### Estructura del Proyecto

```plaintext
assets/
├── css/
│   └── style.css
├── img/
│   ├── favicon.ico
│   ├── sh1.jpg
│   └── sh2.jpg
├── js/
│   ├── scripts.js
│   ├── jQuery.limpiar.js
│   ├── jQuery.graficoCanvasJS.js
│   ├── jQuery.generateCard.js
│   ├── jQuery.filtroInfoCardInvalido.js
│   ├── jQuery.filtroInfoCardVacio.js
│   └── jQuery.filtroRemoverTituloVacio.js
├── index.html
└── README.md

```

### Archivos Principales

- `index.html`: Contiene la estructura HTML del proyecto.
- `style.css`: Archivo CSS para la estilización de la aplicación.
- `scripts.js`: Archivo JavaScript principal que controla la interacción de la aplicación.
- Varios plugins jQuery personalizados que manejan la manipulación del DOM y la validación de datos.

## Instalación

### Prerrequisitos

Asegúrate de tener instalado un navegador moderno y conexión a internet para cargar las bibliotecas CDN y la API.

### Pasos

1. Clona el repositorio o descarga los archivos del proyecto.
2. Abre el archivo `index.html` en tu navegador.

## Uso

1. En la página de inicio, verás un campo de entrada donde puedes introducir el ID de un superhéroe (consulta la [tabla de índices de superhéroes](https://www.superheroapi.com/ids.html) para conocer los IDs).
2. Presiona el botón "Consultar" para buscar la información del superhéroe.
3. La información y las estadísticas del superhéroe se mostrarán en la página junto con un gráfico de torta de sus poderes, si están disponibles.

## Contribuciones

Las contribuciones son bienvenidas. Si tienes alguna mejora o corrección, sigue estos pasos:

1. Haz un fork del proyecto.
2. Crea una nueva rama (`git checkout -b mejora/tu-mejora`).
3. Realiza los cambios necesarios y haz commit (`git commit -m 'Agrega tu mejora'`).
4. Haz push a la rama (`git push origin mejora/tu-mejora`).
5. Crea un Pull Request.

## Contacto

Luis Suarez - [Email](mailto:suarezluis.ea@gmail.com)

