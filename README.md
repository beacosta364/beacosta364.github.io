# beacosta364.github.io

# MyFirstPage

Este repositorio contiene mis primeros pasos en la electiva de desarrollo de aplicaciones web, iniciando con con html, css y javascript. 

para clonar este repositorio es necesarioa segurarde de tener Git instalado
Descárgalo desde: https://git-scm.com/

o verifica si esta instalado ejecutando en la terminal CMD:  git --version

el codigo fue desarrollado en Visual Studio code.

1. Clonar el repositorio
Abre la terminal CMD o, Open git bash here con clik derecho dentro de alguna carpeta y ejecuta:

git clone https://github.com/beacosta364/MyFirstPage.git


2. ingresa a la carpeta clonada con: cd beacosta364.github.io

3.  Usa el sigiuiente comando para ingresar al editor de codigo Visual Studio Code:  code .




Taller Introducción Aplicaciones Web
Brayan Estein Acosta Achinte.
Parte Teórica:

1. ¿Qué es HTML y cuál es su función en la web?
“HTML (HyperText Markup Language) “lenguaje de marcado de hipertexto” es el lenguaje estándar utilizado para crear y estructurar páginas web. Sirve para definir el contenido y la estructura de una página web mediante el uso de etiquetas y elementos que permiten la inclusión de texto, imágenes, enlaces, vídeos y otros recursos multimedia. HTML proporciona la base sobre la cual se construyen la mayoría de las páginas web por no decir todas, permitiendo a los navegadores interpretar y mostrar el contenido de manera correcta. Además, HTML se utiliza en conjunto con CSS y JavaScript para mejorar el diseño y la funcionalidad de los sitios web, proporcionando una experiencia de usuario más rica y dinámica.” (Cursos Femxa, 2024)
2. ¿Qué es una etiqueta HTML y menciona las etiquetas más comunes?
“Una etiqueta HTML es un elemento fundamental del lenguaje HTML que se utiliza para definir y estructurar el contenido de una página web. Las etiquetas HTML están compuestas por un nombre de etiqueta encerrado entre corchetes angulares < >, y generalmente vienen en pares: una etiqueta de apertura y una etiqueta de cierre, con el contenido ubicado entre ellas. Por ejemplo, <p> es una etiqueta de apertura para un párrafo y </p> es la etiqueta de cierre. Algunas etiquetas no requieren cierre, como <img> para insertar imágenes. Las etiquetas HTML indican a los navegadores cómo deben mostrar y estructurar el contenido, como texto, imágenes, enlaces y otros elementos multimedia.” (Cursos Femxa, 2024)
Entre las etiquetas más comunes utilizadas para la creación de páginas están la siguientes:
<html>: Define el inicio y el final de un documento HTML.
<head>: Contiene metadatos sobre el documento, como el título y enlaces a hojas de estilo.
<title>: Especifica el título de la página que aparece en la pestaña del navegador.
<body>: Contiene el contenido visible de la página, como texto, imágenes y enlaces.
<h1> a <h6>: Encabezados de diferentes niveles, siendo <h1> el más importante.
<p>: Define un párrafo de texto.
<a>: Crea un enlace a otra página o recurso.
<img>: Inserta una imagen en la página.
3. ¿Qué es un atributo de una etiqueta HTML y menciona los más comunes?
“Los atributos en el lenguaje de marcado de hipertexto (HTML), son elementos que permiten incorporar características adicionales al agregarlas a las etiquetas HTML para modificar su comportamiento o apariencia. Son como pequeños ajustes que le permiten personalizar cómo se muestra un elemento en la página web.

Los atributos se colocan en las etiquetas HTML y generalmente constan de un nombre y un valor, separados por un signo igual (=).”
•	"class" y "id": Asignan clases e identificadores a elementos para aplicar estilos o referenciar en CSS y JavaScript.
•	style: Permite aplicar estilos en línea directamente al elemento.
•	"src" y "alt" (en elementos <img>): src especifica la fuente de la imagen, mientras que alt proporciona texto alternativo para accesibilidad.
•	href (en elementos <a>): Especifica la URL de destino para un enlace.
•	"width" y "height" (en elementos <img>): Ajustan el ancho y la altura de una imagen.
•	"colspan" y "rowspan" (en celdas de tablas): Combina celdas en tablas, especificando el número de columnas o filas que debe abarcar.
•	"placeholder" (en campos de entrada de formularios): Proporciona un texto de ejemplo dentro del campo de entrada.
•	"disabled" (en botones u otros elementos): Desactiva la interactividad del elemento.
•	"value" (en campos de entrada de formularios): Define un valor predeterminado para el campo de entrada.
•	name (en campos de entrada de formularios): Define el nombre del campo de entrada. Es importante para enviar datos a través de formularios.
•	type (en campos de entrada de formularios): Especifica el tipo de campo de entrada, como texto, contraseña, checkbox, etc.
•	checked (en campos de entrada tipo checkbox o radio): Indica que un elemento checkbox o radio debe estar marcado por defecto.
•	readonly (en campos de entrada de formularios): Hace que un campo de entrada sea de solo lectura, el usuario no puede editarlo.
•	required (en campos de entrada de formularios): Obliga al usuario a completar el campo antes de enviar el formulario.
Estos atributos desempeñan funciones clave en la personalización y funcionalidad de las páginas web.   (APINEM, 2024). 
4. ¿Qué es CSS y cómo se utiliza para el diseño web?
“CSS son las siglas en inglés para «hojas de estilo en cascada» (Cascading Style Sheets). Básicamente, es un lenguaje que maneja el diseño y presentación de las páginas web, es decir, cómo lucen cuando un usuario las visita. Funciona junto con el lenguaje HTML que se encarga del contenido básico de los sitios.
Se les denomina hojas de estilo «en cascada» porque puedes tener varias y una de ellas con las propiedades heredadas (o «en cascada») de otras.
Sirve para crear reglas para decirle a tu sitio web cómo quieres mostrar la información y guardar los comandos para elementos de estilo (como fuentes, colores, tamaños, etc.) separados de los que configuran el contenido.

Además, puedes crear formatos específicos útiles para comunicar tus ideas y producir experiencias más agradables, en el aspecto visual, para los usuarios del sitio web.” (HubSpot, 2024).
5. ¿Qué es una propiedad en CSS y menciona las propiedades más comunes?
	“las propiedades en CSS son estilos que se emplean en los selectores que especifican los profesionales. En CSS se escriben antes los valores que los conjuntos de reglas y se separan de los valores de las propiedades mediante dos puntos. 
Diferentes selectores y elementos en HTML tienen distintas propiedades asignadas en CSS. Algunas de ellas son universales y se pueden usar en todo tipo de selectores mientras que otras tan solo funcionan con elementos específicos y en determinadas condiciones.” (Tokio School, 2024).
•	color – Define el color del texto de un elemento.
•	font-size – Establece el tamaño del texto.
•	font-family – Permite elegir la fuente del texto.
•	text-align – Alinea el texto (izquierda, centro, derecha, justificado).
•	background-color – Cambia el color de fondo del elemento.
•	width y height – Determinan el ancho y alto del elemento.
•	margin – Agrega espacio exterior alrededor del elemento.
•	padding – Agrega espacio interno dentro del elemento.
•	border – Agrega un borde alrededor del elemento.
•	display – Controla cómo se muestra el elemento (block, inline, none, etc.).
•	position – Define la posición del elemento en la página (relative, absolute, fixed, etc.).
•	overflow – Controla cómo manejar el contenido que se desborda de su contenedor.
•	z-index – Define qué elementos se colocan encima de otros.
•	opacity – Controla la transparencia del elemento.
•	box-shadow – Agrega sombras alrededor del elemento.
(MGPanel, 2024).

6. ¿Qué es un selector en CSS y cuales tipos existen?
	En CSS, un selector es un patrón que identifica uno o más elementos HTML a los que se les aplicarán estilos específicos. “Un selector CSS es la primera parte de una regla CSS. Es un patrón de elementos y otros términos que indican al navegador qué elementos HTML se seleccionan para aplicarles una regla que incluye los valores de las propiedades CSS. El elemento o los elementos seleccionados por el selector se denominan sujeto del selector.” (Mozilla Developer Network, 2024)
*	Selector universal (*): Selecciona todos los elementos de la página.
*	Selector de tipo o etiqueta (elemento): Aplica estilos a todas las etiquetas HTML de un mismo tipo.
*	Selector de clase (.nombre-clase): Aplica estilos a los elementos que tengan una clase específica.
*	Selector de ID (#id): Aplica estilos a un único elemento con un identificador (id).
*	Selector de atributo ([atributo]): Aplica estilos a los elementos que tienen un atributo específico.
*	Selector descendiente (elemento1 elemento2): Aplica estilos a los elementos dentro de otro elemento.
*	Selector hijo (elemento1 > elemento2): Selecciona solo los elementos que son hijos directos de otro.
*	Selector adyacente (elemento1 + elemento2): Selecciona el primer elemento que sigue inmediatamente a otro.
*	Selector de hermano general (elemento1 ~ elemento2): Selecciona todos los elementos hermanos de un mismo tipo después de otro.
(ENIUN, 2024).
7. ¿Qué es JavaScript y cómo añade la interactividad a las páginas web?
“JavaScript es un lenguaje de programación esencial para el desarrollo web, conocido por su capacidad para crear contenido dinámico e interactivo. Es un lenguaje de programación interpretado, ligero y dinámico que se utiliza principalmente para crear contenido interactivo y dinámico en páginas web. Es uno de los lenguajes esenciales en el desarrollo web junto con HTML y CSS.”   (APINEM, 2024).
“JavaScript le permite agregar elementos interactivos a su sitio web, como botones, formularios, controles deslizantes y menús. Estos elementos interactivos mejoran la participación del usuario y hacen que el sitio web sea más fácil de usar.” (FasterCapital, 2024).
Las tareas típicas de JavaScript en el front-end incluyen:
-	Validación de formularios: Verificar que los datos ingresados por el usuario en los formularios sean correctos antes de enviarlos al servidor.
-	Manipulación del DOM: Agregar, eliminar o modificar elementos HTML en la página web dinámicamente para actualizar la interfaz de usuario.
-	Manejo de eventos e interactivad en tiempo real: Capturar y responder a eventos del usuario, como clics de ratón, pulsaciones de teclas y desplazamientos de scroll.
-	Animaciones y efectos visuales: Crear animaciones suaves y efectos visuales atractivos para mejorar la experiencia del usuario.
-	Comunicación con servidores: Realizar solicitudes HTTP asíncronas (AJAX) para cargar datos o interactuar con servicios web sin necesidad de recargar toda la página.
(WebAquí, 2024).
8. ¿Cuáles son los tipos de datos primitivos en Javascript?
“En JavaScript hay 6 tipos de datos primitivos: string, number, bigint, boolean, undefined y symbol. También hay null, que aparentemente es primitivo, pero de hecho es un caso especial para cada Object: y cualquier tipo estructurado se deriva de null por la Cadena de prototipos.
La mayoría de las veces, un valor primitivo se representa directamente en el nivel más bajo de la implementación del lenguaje.
Todos los primitivos son inmutables, es decir, no se pueden modificar.” (Mozilla Developer Network, 2024).
string: Representa cadenas de texto.
number: Representa valores numéricos, tanto enteros como de punto flotante.
bigint: Permite representar números enteros de tamaño arbitrario, más allá del límite de Number.
boolean: Representa valores lógicos, true o false.
undefined: Indica que una variable ha sido declarada pero no se le ha asignado un valor.
symbol: Representa identificadores únicos e inmutables, útiles para propiedades de objetos que necesitan ser únicas.
null: Representa la ausencia intencional de cualquier valor u objeto. 
9. ¿Cómo funcionan las estructuras de control de flujo como if, else, switch y bucles en
Javascript?
“Las estructuras de control de flujo, son instrucciones que nos permiten evaluar si se puede cumplir una condición o no, incluso nos puede ayudar a evaluarla n cantidad de veces.
Los condicionales if, else, nos permiten evaluar si una condición cumple o no con lo que estemos evaluando. Su sintaxis es muy sencilla, podemos evaluar si la condición es verdadera o falsa. Incluso añadir una condición intermedia en el caso de que no se cumpla la primera condición y se deban evaluar más.”
If (condición){…}else{…}

“Switch permite evaluar una expresión e intenta igual el valor de esa expresión a una etiqueta llamada case, que es el caso a evaluar. En el caso de que la condición se cumpla o lo que tiene el case, se ejecuta la sentencia que este en ese caso.”  (Marely, 2024).
En el switch se usa una sentencia llamada “break”, esta nos permite salir de la condición que se está evaluando.


switch(tipoFruta) {
    case "Naranjas":
        console.log("Las Naranjas cuestan $5");
        break;
    case "Manzanas":
        console.log("Las Manzanas cuestan $10");
        break;
    case "Fresas":
        console.log("Las Fresas cuestan $15");
        break;
    default:
        console.log("Disculpa, no tenemos ese tipo de fruta: ", tipoFruta);
        break;
}
“Los bucles o loops:
Se le pueden llamar, ciclos, bucles o loops, en ellos se evalúa una condición n veces hasta que esta se cumpla. En estos podemos encontrar los for, while, entre otros. (Marely, 2024).
For:
Un bucle for se repite como mencione hasta que la condición que se está evaluando se cumpla.
While:
Ejecuta una sentencia mientras la condición que se esté evaluando sea verdadera.” (Marely, 2024).

10. ¿Por qué es importante usar nombres significativos para variables y métodos?
	Los nombres de variables juegan un papel esencial en la claridad y la comprensión del código.
“Claridad: un nombre de variable descriptivo comunica el propósito y el contenido de la variable de manera clara. Esto facilita la comprensión del código, tanto para ti como para otros desarrolladores que puedan trabajar en él.
Mantenibilidad: un código con nombres de variables significativos es más fácil de mantener y actualizar en el futuro. Cuando regreses a tu código después de un tiempo, podrás recordar más fácilmente lo que hace cada variable.
Colaboración: en proyectos colaborativos, los nombres de variables significativos son esenciales para que los miembros del equipo comprendan el código de los demás y colaboren de manera eficiente.
Prevención de errores: nombres confusos o ambiguos de variables pueden llevar a errores difíciles de rastrear. Un buen nombre de variable reduce la probabilidad de cometer errores.
Legibilidad del código: un código con nombres de variables significativos es más legible y más fácil de seguir. Esto acelera la depuración y mejora la calidad general del código.
Comunicación efectiva: los nombres de variables bien elegidos actúan como una forma de comunicación entre los desarrolladores. Ayudan a transmitir la intención del programador y a evitar malentendidos.
Facilita el aprendizaje: cuando los desarrolladores novatos estudian código bien nombrado, pueden aprender más rápido y comprender los conceptos con mayor facilidad.” (KeepCoding, 2024).

11. ¿Qué es una variable de entorno y por qué son importantes para Javascript o la
programación en general?
Las variables de entorno permiten configurar aplicaciones sin necesidad de cambiar el código. Separan los datos externos de la lógica de la aplicación
Las variables de entorno son valores nombrados dinámicos que pueden afectar cómo se comportan los procesos en ejecución en una computadora. Algunas propiedades clave de las variables de entorno son: 
Nombradas: Tienen nombres descriptivos como APP_MODE y DB_URL.
Externas: Los valores se establecen fuera del código de la aplicación a través de archivos, líneas de comandos y sistemas.
Dinámicas: Pueden actualizar variables sin reiniciar aplicaciones.
Configuradas: El código depende de variables, pero no las define.
Desacopladas: No es necesario modificar las configuraciones de código una vez que se establecen las variables.   (DreamHost, 2024).
12. ¿Qué son las herramientas de desarrollo de Chrome y cómo se accede a ellas?
“Las Herramientas para desarrolladores de Chrome son un conjunto de herramientas para desarrolladores web que están integradas directamente en el navegador Google Chrome. Herramientas para desarrolladores te permite editar páginas sobre la marcha y diagnosticar problemas con rapidez, lo que te ayuda a crear mejores sitios web en menos tiempo.” (Google Developers, 2024). 
Cómo acceder a las Herramientas para desarrolladores de Chrome:
Usando el menú contextual: Haz clic derecho en cualquier parte de la página web y selecciona "Inspeccionar" o "Inspeccionar elemento".
Atajos de teclado: En Windows/Linux: presiona Ctrl + Shift + I.
En macOS: presiona Cmd + Option + I.
Desde el menú de Chrome: Haz clic en el ícono de tres puntos verticales en la esquina superior derecha del navegador.
Selecciona "Más herramientas" y luego "Herramientas para desarrolladores".
Una vez abiertas, las Herramientas para desarrolladores ofrecen diversas pestañas y paneles que permiten inspeccionar el HTML y CSS de la página, depurar JavaScript, analizar el rendimiento.
13. ¿Qué se puede hacer en el panel "Elements" de las herramientas de desarrollo?
El panel "Elements" de las Herramientas para desarrolladores de Chrome es una herramienta clave para inspeccionar y modificar en tiempo real la estructura y estilo de una página web. Permite interactuar con el HTML y CSS, facilitando la depuración y diseño. Sus funciones incluyen la inspección del DOM para explorar la jerarquía de los elementos HTML, la edición en vivo del HTML y CSS, y la visualización de estilos aplicados, lo que ayuda a identificar conflictos de diseño. Además, permite simular la visualización en dispositivos móviles y depurar eventos y scripts mediante la consola.
14. ¿Cómo se utiliza el panel "Console" de las herramientas de desarrollo y para qué es
útil?
El panel "Console" de las Herramientas para desarrolladores de Chrome es esencial para interactuar con el código JavaScript de una página web. Permite registrar mensajes, ejecutar comandos y depurar el comportamiento de la página en tiempo real. Sus funciones principales incluyen el registro de mensajes mediante métodos como console.log(), console.error() y console.warn(), la ejecución interactiva de código JavaScript, la depuración de errores con detalles sobre el tipo y ubicación del problema, y la inspección de objetos y variables en tiempo real. Es una herramienta para facilitar la depuración y análisis del código. Se puede acceder mediante atajos de teclado o desde el menú de Chrome.
15. ¿Qué información se puede obtener del panel "Network" y por qué es importante?
El panel "Network" de las Herramientas para desarrolladores de Chrome es esencial para analizar la actividad de red de una página web, permitiendo inspeccionar solicitudes y respuestas de recursos para mejorar el rendimiento y optimizar la carga de la página. Muestra una lista de todas las solicitudes de recursos (HTML, CSS, JavaScript, imágenes, fuentes, etc.) y proporciona detalles como encabezados HTTP, tiempos de carga, tamaño de los recursos y el contenido de las respuestas. También ofrece herramientas para filtrar solicitudes, buscar recursos específicos y simular diferentes condiciones de red. Es crucial para diagnosticar problemas de rendimiento, optimizar recursos y verificar la integridad de los recursos cargados.

Fuentes bibliográficas 
Cursos Femxa. (2024). Qué es HTML y para qué sirve. Recuperado de https://www.cursosfemxa.es/blog/estudiar-html
APINEM. (2024). Atributos HTML. Recuperado de https://www.apinem.com/atributos-html/
HubSpot. (2024). ¿Qué es CSS y cómo se utiliza? Recuperado de https://blog.hubspot.es/website/que-es-css
Tokio School. (2024). Propiedades CSS. Recuperado de https://www.tokioschool.com/noticias/propiedades-css/
MGPanel. (2024). ¿Conoces cuáles son las propiedades más utilizadas en CSS? Recuperado de https://blog.mgpanel.org/post/-conoces-cuales-son-las-propiedades-mas-utilizadas-en-css-
Mozilla Developer Network (MDN). (2024). Selectores básicos en CSS. Recuperado de https://developer.mozilla.org/es/docs/Learn_web_development/Core/Styling_basics/Basic_selectors
ENIUN. (2024). Selectores CSS: Tipos y usos. Recuperado de https://www.eniun.com/selectores-css-tipos/
APINEM. (2024). ¿Qué es JavaScript, para qué sirve y cómo funciona? Recuperado de https://www.apinem.com/que-es-javascript-para-que-sirve-y-como-funciona/
FasterCapital. (2024). Libera el poder de JavaScript y crea sitios web interactivos. Recuperado de https://fastercapital.com/es/contenido/Libera-el-poder-de-javascript-y-crea-sitios-web-interactivos.html
WebAquí. (2024). ¿Qué es JavaScript? Recuperado de https://webaqui.com/que-es-javascript/
Mozilla Developer Network (MDN). (2024). Tipo de datos primitivos en JavaScript. Recuperado de https://developer.mozilla.org/es/docs/Glossary/Primitive
Marely, V. (2024). Estructuras de control de flujo en JavaScript. Recuperado de https://vanessamarely.medium.com/estructuras-de-control-de-flujo-en-javascript-c848337a5c02
KeepCoding. (2024). Nombrar variables significativas: ejemplos. Recuperado de https://keepcoding.io/blog/nombrar-variables-significativas-ejemplos/
DreamHost. (2024). Variables de entorno: Guía para principiantes. Recuperado de https://www.dreamhost.com/blog/es/variables-entorno-guia-principiantes/
Google Developers. (2024). Herramientas para desarrolladores de Chrome (Chrome DevTools). Recuperado de https://developer.chrome.com/docs/devtools?hl=es-419
