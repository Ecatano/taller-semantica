Taller de Investigación: Fundamentos de HTML
Nombre del Estudiante: [Edin Aleix Cataño Sadarriaga]

1. Anatomía de una Etiqueta HTML
Etiqueta de Apertura y Cierre
¿Qué es una etiqueta de apertura?

Una etiqueta de apertura es el elemento que marca el inicio de un componente HTML y define qué tipo de contenido se va a presentar y tiene unas características. Siempre inicia con delimitada por los símbolos < > < como contenedor >

¿Qué es una etiqueta de cierre?

Una etiqueta de cierre es el elemento que marca el final de un componente HTML y le dice al navegador que termine de interpretar ese tipo de elemento, su característica está delimitada por los símbolos </ y 

Atributos
¿Qué es un atributo y para qué sirve? Da un ejemplo.
Un atributo es información adicional que se incluye dentro de una etiqueta de apertura HTML para modificar, configurar o proporcionar datos extra sobre ese elemento. Sirve para  modificar el comportamiento del elemento, proporcionar información adicional al navegador, establecer propiedades específicas (tamaño, color, ubicación, etc.), hacer que los elementos sean más accesibles,conectar elementos con CSS y JavaScript. 
Emplo: Atributo src en imágenes: <img src="logo.png" alt="Logo de la empresa" width="200" height="100">

Escribe tu respuesta aquí, incluyendo un ejemplo de código como <a href="https://google.com">Ir a Google</a> y explicando qué hace el atributo href.
El atributo href (hypertext reference = referencia de hipertexto) define el destino al que llevará el enlace cuando el usuario haga clic en él.

2. El Poder de la Semántica
HTML Semántico
¿Qué es el HTML Semántico y por qué es tan importante?

El HTML Semántico es el uso de etiquetas HTML que tienen significado específico y describen claramente el propósito y contenido de cada sección de una página web, en lugar de solo definir su apariencia visual.

Características del HTML Semántico: 
•	Las etiquetas comunican qué tipo de contenido contienen
•	Describe la estructura lógica del documento
•	Va más allá de solo "cómo se ve" para explicar "qué significa"
•	Utiliza etiquetas como <header>, <nav>, <main>, <article>, <section>, <aside>, <footer>
Es importante por la  Accesibilidad:
•	Los lectores de pantalla pueden navegar mejor el contenido
•	Usuarios con discapacidades pueden entender la estructura de la página
•	Facilita la navegación por teclado
•	Hace el contenido más inclusivo para todos los usua
 Para el SEO (Posicionamiento en Buscadores):
•	Los motores de búsqueda entienden mejor el contenido
•	Google puede identificar qué partes son más importantes
•	Mejora el ranking en resultados de búsqueda
•	Facilita la indexación correcta del contenido


Diccionario de Etiquetas Semánticas
**Diccionario de Etiquetas Semánticas**

1: `<header>`:Define el encabezado de una página o sección. Contiene información introductoria como títulos, logos, navegación principal o metadatos. Puede aparecer múltiples veces en una página.

2: `<nav>`:Representa una sección de navegación que contiene enlaces a otras páginas o secciones dentro del mismo sitio. Incluye menús principales, breadcrumbs o índices de contenido.

3: `<main>`:Identifica el contenido principal y único de la página. Solo debe existir uno por documento y contiene el tema central, excluyendo elementos repetitivos como headers, footers o sidebars.

4: `<section>`:Agrupa contenido temáticamente relacionado que puede tener su propio encabezado. Representa una sección distinta de un documento, como capítulos, pestañas o bloques de contenido específico.

5: `<article>`:Envuelve contenido independiente y autosuficiente que podría distribuirse por separado. Ideal para artículos de blog, noticias, comentarios o publicaciones que tienen sentido por sí mismas.

6: `<aside>`:Contiene información complementaria o secundaria relacionada con el contenido principal. Incluye sidebars, información adicional, publicidad o contenido tangencial.

7: `<footer>`:Define el pie de página de un documento o sección. Contiene información de cierre como derechos de autor, enlaces de contacto, información legal o navegación secundaria.

8: `<figure>`:Agrupa contenido multimedia (imágenes, diagramas, códigos) que ilustra o complementa el texto principal, generalmente con una descripción asociada.

9: `<figcaption>`:Proporciona una leyenda o descripción para el contenido dentro de un elemento `<figure>`. Explica o describe el contenido multimedia.

10: `<time>`:Representa fechas, horas o períodos de tiempo específicos de manera que las máquinas puedan interpretarlos correctamente.

11: `<mark>`:Resalta o marca texto que es relevante en un contexto particular, como resultados de búsqueda o información importante para el usuario actual.

12: `<details>`:Crea un widget interactivo que el usuario puede abrir o cerrar para revelar información adicional. Útil para FAQ o contenido expandible.

13: `<summary>`: Define el encabezado visible de un elemento `<details>`. Es lo que el usuario ve antes de expandir el contenido adicional.

14: `<address>`:Proporciona información de contacto del autor o propietario del documento o sección más cercana, como direcciones físicas, emails o teléfonos.

15: `<blockquote>`:Indica que el contenido es una cita extendida de otra fuente. Generalmente se usa para citas largas que ocupan párrafos completos.

16: `<cite>`:Referencia el título de una obra creativa (libro, artículo, película, etc.) o la fuente de una cita o información.

17: `<code>`:Identifica fragmentos de código de programación dentro del texto, mostrándolo generalmente en una fuente monoespaciada.

18: `<pre>`: Preserva el formato original del texto, incluyendo espacios y saltos de línea. Ideal para código, ASCII art o texto preformateado.

19: `<strong>`:Indica que el texto tiene una importancia fuerte o seriedad, generalmente mostrado en negrita pero con significado semántico de énfasis.

20: `<em>`:Enfatiza texto de manera que cambia el significado de la oración, típicamente mostrado en cursiva pero con propósito semántico de énfasis.