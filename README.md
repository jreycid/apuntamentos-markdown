# Titorial de Markdown

Benvido, aquí aprenderás os conceptos básicos desta linguaxe de marcado.

> [!TIP]
> Markdown é o formato usado por defecto en GitHub e case calquera ferramenta relacionada co mundo da programación. Isto significa que si eres programador necesitarás Markdown na túa vida dun xeito ou doutro.

*******
Táboa de contidos
 1. [Que é Markdown?](#que-é-markdown)
 2. [Por qué empregar Markdown?](#porque)
 3. [Herramientas para Markdown](#herramientas-para-markdown)
 4. [Sintaxis de Markdown](#sintaxis-de-markdown)

*******
 
## Que é Markdown?  
Dacordo coa Wikipedia:  
 
  >*Markdown é unha linguaxe de marcado lixeira creada por John Gruber que busca conseguir a máxima lexibilidade e publicabilidade tanto na súa forma de entrada como de saída, inspirándose en moitas convencións existentes para marcar mensaxes de correo electrónico mediante texto simple. Distribúese baixo a licenza BSD e distribúese como compoñente (ou polo menos dispoñible) en diferentes sistemas de xestión de contidos (CMS). Markdown converte o texto marcado en documentos XHTML usando html2text creado por Aaron Swartz. Markdown foi implementado orixinalmente en Perl por Gruber, pero desde entón foi traducido a multitude de linguaxes de programación, incluíndo PHP, Python, Ruby, Java e Common Lisp.* 

Dito de maneira mais sinxela, Markdown é un formato de texto (con extension .md) sinxelo para escribir documentos estructurados.  
Grazas a súa facilidade de escritura e lexibilidade, atópase amplamente extendido para escritura de todo tipo de documentación técnica.

<div id='porque'/>  

*Non hai un estándar de Markdown ben definido. Isto provocou fragmentación, xa que varios fabricantes escriben as súas propias versións do idioma para corrixir detalles ou engadir funcións que faltan... Hai unha lista dalgunhas versións dispoñibles [aquí.](https://github.com/jgm/CommonMark/wiki/Markdown-Flavors).*

Esta guía centrarase principalmente na propia versión de Github.

## Por que empregar Markdown?
Por que é:
 
 * **Sinxelo** : O erro máis común ao escribir con HTML, por máis básico que sexa, é non pechar unha etiqueta correctamente. Con Markdown, este tipo de erros diminúen porque, pola sinxeleza de escritura, dunha ollada podemos identificar os caracteres de formato asociados ao texto e, polo tanto, poder corrixir os erros antes de executar o código.
  * **Curva de aprendizaxe rápida** : A sintaxe de Markdown e sinxela e intuitiva, comparada por exemplo con HTML. Isto significa que podes aprendelo en pouco tempo. 
 * **Limpo** : A saída dun ficheiro Markdown é limpa, non dificulta a lectura do texto. De feito, deseñar unha sintaxe que permitise que o texto poidera ser lexible sen ser renderizado foi un dos obxectivos do autor.
 * **Versátil** : Permite crear documentos, notas, libros, documentación, correos electrónicos e mesmo os textos de calquera sitio web. De feito, todo o texto deste titorial foi escrito usando Markdown.
 * **Portable** : É independiente da plataforma na que o executes, xa que podes crear documentos de Markdown en calquera sistema operativo. Ademais, ficheiros Markdown pódense abrir con calquera editor de texto. Se creaches un documento cun editor pero despois cambias de opinión e prefires usar outro, podes abrir o documento no novo editor sen realizar ningunha conversión.
<br></br>

## Herramientas para Markdown
Como se dijo anteriormente, cualquier editor puede ser usado para escribir Markdon. De cualquier forma, hay algunas herramientas que pueden ser útiles a la hora de editar Markdown.

 * **[*Stackedit*](https://stackedit.io)** : De acuerdo, puedes dejar de leer ahora mismo. Da click al link y empieza a tu viaje a Markdown de la manera más fácil posible. Únicamente escribe texto normal y usa tu mouse, click click, hecho. Es bueno, pero te hará dependiente y muchos desarrolladores prefieren los teclados.
 * **[*Dillinger*](http://dillinger.io/)** : Herramienta online, soporta vista previa en edición(pantalla dividida) y puedes exportar a HTML. Nada especial, pero muy bien hecho y útil.
 * **[*Typora*](https://www.typora.io/)** : Disponible para Mac y Windows, minimalista, libre de distracciones, vista previa sin interrupciones, cargado con muchas características como imágenes, listas, tablas, bloques de código, bloques de expresiones matemáticas, YAML, texto preliminar, tablas de contenido..., etc.
 * **[*Atom*](https://atom.io/)** : Editor muy popular y altamente configurable (tal vez lo estés usando), ¡Sí!, es versátil. ¿Soporte para markdown?, es una pequeña parte del editor, pero ya viene incluida.
 * **[*Minimalist Markdown*](https://chrome.google.com/webstore/detail/minimalist-markdown-edito/pghodfjepegmciihfhdipmimghiakcjf?hl=en)** : App de Chrome. Funciona en todos lados si tienes Chrome instalado (es mi favorita).
 * **[*Macdown*](http://macdown.uranusjr.com/)** : Lo mejor para Mac.
 * **[*MarkdownPad*](http://markdownpad.com/)** : Lo mejor para Windows.
 * **[*Remarkable*](https://remarkableapp.github.io/)** : Lo mejor para Linux. 
 * **[*GITBOOK*](http://www.gitbook.com/)** : GitBook es una moderna caja de herramientas. Hace escribir y colaborar fácil. Soporta Markdown y está relacionado con nuestro querido Github.
 

## Sintaxis de Markdown  
Toda la sintaxis se puede encontrar [acá](https://daringfireball.net/projects/markdown/syntax) . Cuestaun poco escribir sintaxis en texto (ya que será parseada y formateada), así que por favor considera esta tabla de abajo como la sintaxis básica de Markdown.  


| Formato        | Syntaxis     | Ejemplo |
| ------|-----|-----|
| Itálica  	| \*Texto\* 	| *Esto es itálica* 	|
| Negritas	| \*\*Negritas\*\* 	| **Esto es negritas** 	|
| Links inline 	| \[Descripción del texto\](url acá) 	| Un [link](http://www.github.com) 	|
| Imágenes 	| \![Descripción\](url a la imagen) 	| Una imagen ![image](http://i.imgur.com/hRLuez2.png) 	|
| Link + imágenes 	| \[\![Descripción\](url a la imagen)\](url a una página)\] 	| Haz  [![click](http://i.imgur.com/hRLuez2.png)](https://www.youtube.com) 	|
| Pies de página  	| Tengo más \[^1\] que decir.   \[^1\]: dilo acá. 	| <a href="#section1">Oye, por favor lee esta nota debajo de esta tabla. 	|
| Salto de línea 	| Doble espacio + enter 	|  	|
| Listas no ordenadas	| \* Item1     \*Item 2 	| <ul><li>item1</li><li>item2</li><li>item3</li><li>item4</li></ul> 	|
| Listas ordenadas 	| 1. Item a    2. Item b 	| <ol><li>itema</li><li>itemb</li><li>itemc</li><li>itemd</li></ol>  	|
| Listas combinadas 	| 1. Item 1      * item 1a 	|  <ol><li>itema</li></ol><ul><li> item1</li></ul>	|
| Cita	| \> Texto citado 	|  <blockquote>Mantente insatisfecho, mantente humilde.</blockquote> 	|
| Pre formato 	| Empieza cada línea con, dos espacios o más para, hacer el texto verse, e x a c t a m e e n t e, como, tú, lo escr.i.b.e.s.|
| Código 	| \`Inserta código\` 	| `cout<<"Hello world";` 	|
| Bloque de código/ Realtado de sintaxis 	| \`\`\`inserta código\`\`\` 	|  <a href="#section1">Oye, por favor lee la nota debajo de esta tabla.
| Encabezados	| \#, \##, \###, \####, \#####, \###### (desde h1 a h6) 	|  <h3>Esto es un encabezado h3</h3>	|
| Texto tachado 	| \~~Inserta texto acá\~~ 	| ~~Morí~~ 	|
| Tablas 	| \| Las tablas   \|      son      \|  geniales \| \|\----------\|\:\-------------\:\|------\:\| \| col 1 es\|  alineada a la izquierda \| $1600 \| | ![](http://i.imgur.com/EItt7mh.png) |

 <br></br>
 <p id="section1">Nota: **Nota al pie** de hecho, no se ve correctamente en una tabla (y en vista previa de Github).
Pero es parecida [a](http://i.imgur.com/pmeBr28.png)
   <br></br>
   Lo mismo va para **bloques de código/resaltado de sintaxis**. 
Se ve como ![esta imagen](http://i.imgur.com/z8KrxAz.png).</p>

Estas características dependen de cada versión de markdown.

## Notas útiles:
 * Markdown permite usar diagonal  invertida para generar caracteres que de otra forma serían reconocidos por la sintaxis especial. Un caracter muy usado comúnmente como escape es \     
`Luego, \*ESTO\*  no es itálica, sin embargo está precedido literalmente por asteriscos.`
 * Los videos de Youtube requieren un poco más de trabajo adicional.
  ```
  No pueden ser agregados diretamente, sin embargo, puedes agregar una imágen con un link al video de la siguiente manera:
  <a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
  " target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" 
  alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>
  ```
 * Markdown soporta Emojis :laughing: :laughing: :kissing_heart: :innocent: :green_heart: ( consulta algunos emojis [aquí](http://www.emoji-cheat-sheet.com/) )
 * Puedes usar la etiqueta \<br/> para forzar un salto de línea.
 * Doble espacio y enter si quieres agregar una nueva línea.
 * Ver no es tan bueno como practicar. Puedes crear un archivo markdown para que practiques o hacerlo online [aquí](http://www.markdowntutorial.com).
 *  Notas al pie y resaltado de sintaxis no son parte de la versión original de Markdown y solo son soportadas por ciertas versiones. (Retroalimentación de [Sean Brody](https://goo.gl/ASZwEn))
 *  Cualquier URL (como http://www.github.com/) será convertida en un link activo.  
 *  El soporte a las tablas de Markdon está diseñado para soportar la mayoría de tablas para la mayoría de personas; no cubre todas las tablas para todas las personas. Si necesitas tablas más complejas necesitarás herramientas específicamente diseñadas para ello o escribirlas a mano.  
