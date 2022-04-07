# HTML_course
HTML Course by Platzi

**Content**

* [Web Developer Fundamentals](https://github.com/isabelyb/HTML_course#web-developer-fundamentals)
* [HTML: anatomía de una página web](https://github.com/isabelyb/HTML_course#html-anatom%C3%ADa-de-una-p%C3%A1gina-web)


## Web Developer Fundamentals

El **Frontend** debe saber de código que entienda el navegador (HTML, CSS y JavaScript) para poder usar algunos frameworks o librerías que expanden sus capacidades para crear cualquier tipo de interfaces de usuarios. React, Redux, Angular, Bootstrap, Foundation, LESS, Sass, Stylus y PostCSS son algunos de ellos.

El **Backend** trabaja en el lado del servidor, es el responsable de manejar toda la lógica que hay detrás de una petición dada por el navegador hacia el servidor. Usa varios lenguajes de programación (Node.js, Python, PHP, Ruby, GO, Java, .NET entre otros) Cada uno de estos lenguajes tiene sus propios frameworks como:

- Django (Python)
- Lavarel (PHP)
- Rails (Ruby)
- Express (JavaScript)
- Spring (Java)

El **Backend** también tiene en cuenta la infraestructura donde va a realizarse el deploy de su aplicación (esto también puede ser tarea de un **DevOps**, un perfil dedicado a la infraestructura), con tecnologías como:

- Google Cloud
- DigitalOcean
- AWS
- Heroku

### ¿Qué es deploy?

Puede significar muchas cosas, dependiendo del ambiente y de la tecnología usada. Sin embargo, los significados que más se refieren a la práctica y pueden resumir su función son: implantar, colocar en posición, habilitar para uso o, simplemente, publicar.

**Bases de datos** son las encargadas de almacenar toda la información del proyecto. Los principales tipos son:

Bases de datos relacionales (MySQL. Postgres)
Bases de datos no relacionales (mongoDB)


## HTML: anatomía de una página web

HTML (HyperText Markup Language) es un lenguaje de marcado de texto. Se utiliza para darle una estructura al sitio web que estás visitando.

Estructura básica de HTML en una página Web

* **Container:** contenedor principal
* **Header:** cabecera de la página. Aquí usualmente encuentras el logo y el menú de navegación del sitio.
* **Main content:** estructura principal. Por ejemplo, el feed o lista de publicaciones de una red social.
* **Sidebar:** contenido secundario de una página, que usualmente se encuentra a los lados del contenido principal (o main).
* **Footer:** pie de página. Esto se encuentra al fondo del sitio web, salvo en casos de sitios web donde el scroll (o navegación hacia abajo) es infinito, por ende, no tendría sentido ponerlo al fondo.

### Index y su estructura básica: Head

En el *head* van todos los archivos importantes para que el proyecto funcione correctamente, algunos como: Estilos, fuentes, descripciones, librerías… 
Es la parte no visible de nuestra página.

### Index y su estructura básica: Body

El *body* es la etiqueta que identifica la parte visible del sitio web.

* Etiquetas contenedoras: Llevan etiquetas dentro y generan la estructura de sitio web.
    * header: cabecera del documento.


* Etiquetas de contenido: Llevan texto, video, imágenes... cualquier cosa que se pueda renderizar en el navegador.

💡 Es muy importante usar HTML semántico y no llenar todo de <div> para que el sitio sea mejor interpretado por el navegador y, por lo tanto, más accesible.

Etiquetas del cuerpo del documento (body):
article: diferencia partes del contenido que pueden vivir por sí mismas.
nav: para hacer menús de navegación.
aside: contenido menos relevante, como publicidad, etc.
section: sirve para diferenciar las secciones principales del contenido.

footer: pie de página del documento.
h1 - h6: títulos de nuestro sitio web.
table: tablas de contenidos, similar a la estructura de las hojas de calculo.
ul y ol: listas de items.
div: cualquier división para organizar el contenido.
h1 a h6: son etiquetas para indicar títulos con un estilo que destaca del resto.
article: es la parte de nuestro contenido que puede vivir por sí mismo. Pueden haber tantos artícle como proyectos o eventos tenga nuestro portafolio.
p: define el texto de un párrafo.
small: aplica una apariencia de texto reducido en tamaño.
strong: aplica al texto un formato de negritas.
a: corresponde a un ancla o enlace a una url interna o externa del documento.
img: con esta etiqueta podemos enlazar imágenes en el documento.
figure: le da un contexto semántico a las imágenes.
