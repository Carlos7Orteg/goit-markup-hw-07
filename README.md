# goit-markup-hw-07
# Webstudio: Documentación de la actividad

![HTML Icon](https://img.icons8.com/color/48/000000/html-5--v1.png) ![CSS Icon](https://img.icons8.com/color/48/000000/css3.png) ![JavaScript Icon](https://img.icons8.com/color/48/000000/javascript--v1.png) ![SASS Icon](https://img.icons8.com/color/48/000000/sass-avatar.png) ![Normalize Icon](https://img.icons8.com/color/48/000000/checked.png) ![Prettier Icon](https://img.icons8.com/color/48/000000/developer.png)

---

## Índice de Contenido

1. [Introducción](#introducción)
2. [Estructura del sitio web](#estructura-del-sitio-web)
   - Webstudio: Estudio
   - Webstudio: Portafolio
   - Webstudio: Contactos
3. [Visualización](#visualización)
4. [Tecnologías empleadas](#tecnologías-empleadas)
   - HTML
   - CSS
   - JavaScript
   - SASS
   - Modern Normalize
   - .prettierrc
5. [Codificación](#codificación)
6. [Despliegue](#despliegue)

---

## Introducción

El proyecto **Webstudio** es una página de presentación profesional, diseñada para mostrar los servicios, portafolio, y opciones de contacto de un estudio web. La estructura y el estilo se implementan utilizando HTML, CSS, JavaScript, SASS, y BEM para la metodología de nomenclatura de clases.

---

## Estructura del Sitio Web

### Webstudio: Estudio
Contiene información sobre el estudio, su misión y su equipo.

### Webstudio: Portafolio
Una galería de proyectos y estudios de caso, mostrando el trabajo realizado.

### Webstudio: Contactos
Información de contacto y un formulario para consultas de clientes.

---

## Visualización

El sitio se visualiza de manera uniforme en todos los navegadores modernos, utilizando **Modern Normalize** para una base de estilos consistente.

---

## Tecnologías empleadas

- **HTML** - Estructura del contenido.
  ![HTML Icon](https://img.icons8.com/color/48/000000/html-5--v1.png)

- **CSS** - Diseño y estilos visuales.
  ![CSS Icon](https://img.icons8.com/color/48/000000/css3.png)

- **JavaScript** - Funcionalidades interactivas.
  ![JavaScript Icon](https://img.icons8.com/color/48/000000/javascript--v1.png)

- **SASS** - Preprocesador CSS para un diseño escalable.
  ![SASS Icon](https://img.icons8.com/color/48/000000/sass-avatar.png)

- **Modern Normalize** - Normalización de estilos entre navegadores.
  ![Normalize Icon](https://img.icons8.com/color/48/000000/checked.png)

- **Prettier** - Formato de código consistente.
  ![Prettier Icon](https://img.icons8.com/color/48/000000/developer.png)

---

## Codificación

La estructura de archivos y carpetas del proyecto sigue una jerarquía organizada:

  #### goit-markup-hw-07/

  - index.html
  - sass/
    - utils/
      - variables.css
    - components/
    - ... archivos de los componentes
  - CSS/
    - main.min.css
    - ... archivos de los mapas
  - images/
  - ... archivos de las imágenes
    
### Criterios de aceptación

  #### Proyecto

    - La refactorización del código HTML del proyecto se realiza utilizando la metodología **BEM**.
    - La refactorización del código CSS del proyecto se realiza utilizando el preprocesador **SASS**.
    - En la raíz del proyecto, hay una carpeta **SASS**, que contiene todas las hojas de estilo del
      preprocesador.
    - En la carpeta **SASS** hay archivo main.scss - el archivo principal en el que se organizan e importan todos
      los componentes en archivos separados en sass/components/ (partials, archivos \_nombre.scss).
    - La paleta de colores de diseño y los conjuntos de fuentes se presentan como variables en el
      archivo variables.scss, en la carpeta sass/utils. Se pueden utilizar variables CSS o **SASS**
      (opcionalmente).
    - Para cada componente, se crea una hoja de estilo de fragmentos separada en la carpeta
      sass/components. Por ejemplo \_page-header.scss, \_logo.scss y etc.
    - En los archivos index.html y portfolio.html hay un archivo de estilo minificado enlazado
      main.min.css de la carpeta css.

  #### Marcado

    - Nomenclatura adecuada de clases de bloques según la metodología **BEM**.
    - Nomenclatura adecuada de clases de elementos según la metodología **BEM**.
    - Nomenclatura adecuada de clases de modificadores según la metodología **BEM**.
    - Nomenclatura adecuada de clases mixin según metodología **BEM**.
    - Los nombres de las clases de **BEM** son claros y descriptivos, todos son en inglés.

  #### Diseño

    - Se utiliza el selector de anidamiento.
    - La anidación máxima de los selectores es de 2 niveles.
    - El operador de concatenación (&) e usa para describir pseudo-clases y pseudo-elementos.

    ---

## Despliegue

La página está optimizada y lista para su despliegue, con un archivo CSS minificado (main.min.css) enlazado en las páginas HTML del proyecto. Este proyecto está preparado para ejecutarse en entornos de producción.

---

¡Gracias por consultar la documentación del proyecto **Webstudio**!.
