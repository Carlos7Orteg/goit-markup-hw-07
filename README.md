# goit-markup-hw-07

- Estructura de archivos del proyecto.

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

- Critesrios de aceptación:

  - Proyecto:

    - La refactorización del código HTML del proyecto se realiza utilizando la metodología BEM.
    - La refactorización del código CSS del proyecto se realiza utilizando el preprocesador SASS.
    - En la raíz del proyecto, hay una carpeta sass, que contiene todas las hojas de estilo del
      preprocesador.
    - En la carpeta sass hay archivo main.scss - el archivo principal en el que se importan todos
      los fragmentos de SASS (partials, archivos \_nombre.scss).
    - La paleta de colores de diseño y los conjuntos de fuentes se presentan como variables en el
      archivo variables.scss, en la carpeta sass/utils. Se pueden utilizar variables CSS o SASS
      (opcionalmente).
    - Para cada componente, se crea una hoja de estilo de fragmentos separada en la carpeta
      sass/components. Por ejemplo \_page-header.scss, \_logo.scss y etc.
    - En los archivos index.html y portfolio.html hay un archivo de estilo minificado enlazado
      main.min.css de la carpeta css.

  - Marcado:

    - Nomenclatura adecuada de clases de bloques según la metodología BEM.
    - Nomenclatura adecuada de clases de elementos según la metodología BEM.
    - Nomenclatura adecuada de clases de modificadores según la metodología BEM.
    - Nomenclatura adecuada de clases 'mixin' según metodología BEM.
    - Los nombres de las clases de BEM son claros y descriptivos, todos son en inglés.

  - Diseño:

    - Se utiliza el selector de anidamiento.
    - La anidación máxima de los selectores es de 2 niveles.
    - El operador de concatenación (&) e usa para describir pseudo-clases y pseudo-elementos.
