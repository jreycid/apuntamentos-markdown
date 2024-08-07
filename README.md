# Titorial de Markdown

Benvido, aquí aprenderás a sintaxe básica desta linguaxe de marcado.

> [!TIP]
> Markdown é o formato usado por defecto en GitHub e case calquera ferramenta relacionada co mundo da programación. Isto significa que se es programador necesitarás Markdown na túa vida dun xeito ou doutro.

*******
Táboa de contidos
 1. [Que é Markdown?](#que-é-markdown)
 2. [Por que empregar Markdown?](#por-que-empregar-Markdown)
 3. [Editores Markdown](#editores-markdown)
 4. [Sintaxe básica de Markdown](#sintaxe-básica-de-markdown)

*******
 
## Que é Markdown?  
De acordo coa Wikipedia:  
 
  >*Markdown é unha linguaxe de marcado lixeira creada por John Gruber que busca conseguir a máxima lexibilidade e publicabilidade tanto na súa forma de entrada como de saída, inspirándose en moitas convencións existentes para marcar mensaxes de correo electrónico mediante texto simple. Distribúese baixo a licenza BSD e distribúese como compoñente (ou polo menos dispoñible) en diferentes sistemas de xestión de contidos (CMS). Markdown converte o texto marcado en documentos XHTML usando html2text creado por Aaron Swartz. Markdown foi implementado orixinalmente en Perl por Gruber, pero desde entón foi traducido a multitude de linguaxes de programación, incluíndo PHP, Python, Ruby, Java e Common Lisp.* 

É dicir, Markdown é unha linguaxe de marcado coa que pode engadir formato a documentos de texto plano.  
A día de hoxe é unha das linguaxes de marcado máis empregadas, xa que é sinxela, lixeira e fácil de aprender, incluso para quenes non teñen un perfil técnico.

Probablemente o maoir problema de Markdown sexa que carece dun estándar ben definido. Isto débese a que o seu creador está en contra da definición dun estándar, xa que considera que parte do éxito de Markdown débese a posibilidade de adaptalo e engadirlle funcións segundo as necesidades de cada quen (flavours). Este feito provoca fragmentación e algúns problemas de incompatibilidade, xa que distintas organizacións escriben as súas propias versións para corrixir algúns detalles ou engadir novas funcionalidades que fagan que se adapte mellor ás súas necesidades. Esta guía centrarase principalmente na propia versión de Github, xa que engade algunhas funcións moi útiles para programadores.

Podes consultar unha lista dalgunhas variacións premendo [aquí.](https://github.com/jgm/CommonMark/wiki/Markdown-Flavors).

## Por que empregar Markdown?
Por que é:
 
 * **Sinxelo** : O erro máis común ao escribir con HTML, por máis básico que sexa, é non pechar unha etiqueta correctamente. Con Markdown, este tipo de erros diminúen porque, pola sinxeleza de escritura, dunha ollada podemos identificar os caracteres de formato asociados ao texto e, polo tanto, poder corrixir os erros antes de executar o código.
  * **Curva de aprendizaxe rápida** : A sintaxe de Markdown e sinxela e intuitiva, comparada por exemplo con HTML. Isto significa que podes aprendelo en pouco tempo. 
 * **Limpo** : A saída dun ficheiro Markdown é limpa, non dificulta a lectura do texto. De feito, deseñar unha sintaxe que permitise que o texto poidera ser lexible sen ser renderizado foi un dos obxectivos do autor.
 * **Versátil** : Permite crear documentos, notas, libros, documentación, correos electrónicos e mesmo os textos de calquera sitio web. De feito, todo o texto deste titorial foi escrito usando Markdown.
 * **Portable** : É independiente da plataforma na que o executes, xa que podes crear documentos de Markdown en calquera sistema operativo. Ademais, ficheiros Markdown pódense abrir con calquera editor de texto. Se creaches un documento cun editor pero despois cambias de opinión e prefires usar outro, podes abrir o documento no novo editor sen realizar ningunha conversión.

## Editores Markdown
Se ben se pode empregar calquera editor para escribir Markdown, as seguintes ferramentas dedicadas son especialmente recomendables, ademais de gratuitas.

 * **[*Editor markdown*](https://editormarkdown.com/)** : Funciona sen rexistro previo e é de código aberto. O sitio web está dividido en dúas áreas, no lado esquerdo escribes o teu texto en formato Markdown e na parte dereita podes ver en tempo real a saída do documento xa formateado.  
Pode exportar o resultado do seu traballo en HTML, HTML + CSS, Markdown e PDF e almacenalo no teu propio ordenador. Ademais, permite importar ficheiros desde local, GitHub, BitBucket e DropBox e gardar o resultado tanto en GitHuib como en DropBox.
 * **[*Stackedit*](https://stackedit.io)** : Editor de Markdown en liña gratuíto cargado de funcións útiles como por exemplo unha barra de ferramentas visual para o formato (negriña, énfase, listas, etc.). Pode sincronizarse con servizos de almacenamento na nube como Dropbox e Google Drive, e importar ficheiros desde un URL ou o disco duro do teu ordenador. Outra característica útil deste editor é que pode converter HTML en Markdown.
 * **[*Remarkable*](https://remarkableapp.github.io/)** : Conta con versión para Linux, a versión para Windows está en desenvolvemento. O sitio web está dividido en dúas áreas, no lado esquerdo escribes o teu texto en formato Markdown e na parte dereita podes ver en tempo real a saída do documento xa formateado. Emprega a variación de Markdown de GitHub, admite CSS e permite exportar a HTML, e PDF.
* **[*Macdown*](http://macdown.uranusjr.com/)** : Editor de código aberto para macOS, lanzado baixo a licenza MIT.
* **[*Gitbook*](http://www.gitbook.com/)** : É moito mais que un editor. GitBook é unha excelente ferramenta para crear documentación de proxectos e libros técnicos usando Markdown e Git/GitHub, de maneira que sexan facilmente editables e abertos a contribucións.

Ademais, moitas aplicacións de notas como [*Notion*](https://www.notion.so/es-es), [*Trello*](https://trello.com/es), [*Todoist*](https://todoist.com/es), [*Bear*](https://bear.app/) ou [*TakeNote*](https://takenote.dev/app) aceptan o uso de Markdown.

## Sintaxe básica de Markdown  
Podes atopar a sintaxe completa definida polo propio John Gruber [na súa páxina](https://daringfireball.net/projects/markdown/syntax). Así que considera a seguinte táboa como un resumo coa sintaxe básica de Markdown.

| Formato        | Sintaxe     | Exemplo |
| ------|-----|-----|
| Cabeceira	| \#, \##, \###, \####, \#####, \###### (desde h1 a h6) 	|  <h3>Isto é un encabezado h3</h3>	|
| Cursiva  	| \*Texto\* 	| *Isto é cursiva* 	|
| Negriña	| \*\*Texto\*\* 	| **Isto é negriña** 	|
| Salto de liña 	| Dobre espazo + enter 	|  	|
| Cambio de parágrafo 	| Liña en branco 	|  	|
| Texto cruzado 	| \~~Texto\~~ 	| ~~Texto cruzado~~ 	|
| Pre formato 	| Comeza cada liña con, dous espazos ou máis para, amosar o texto, e x a c t a m e n t e, coma, ti, o escr.i.b.ic.h.e.s.|
| Cita	| \> Texto citado 	|  <blockquote>Exercer o poder corrompe; someterse ao poder degrada.</blockquote> 	|
| Pé de páxina  	| Texto que contén a ligazón ao pé de páxina \[^1\].   \[^1\]: Pé de páxina. | ![](http://imgur.com/pmeBr28.png) |
| Ligazón | \[Descripción do texto\](url) 	| Unha [Ligazón](http://www.github.com) 	|
| Imaxe 	| \![Descripción\](url da imaxe) 	| ![image](http://i.imgur.com/hRLuez2.png) 	|
| Ligazón + imaxe	| \[\![Descrición\](url á imaxe)\](url da páxina)\] 	| [![click](http://i.imgur.com/hRLuez2.png)](https://www.youtube.com) 	|
| Lista non ordenada	| \* Item1     \*Item 2 	| <ul><li>item1</li><li>item2</li><li>item3</li><li>item4</li></ul> 	|
| Lista ordenada 	| 1. Item a    2. Item b 	| <ol><li>itema</li><li>itemb</li><li>itemc</li><li>itemd</li></ol>  	|
| Lista combinada 	| 1. Item 1      * item 1a 	|  <ol><li>itema</li></ol><ul><li> item1</li></ul>	|
| Código 	| \`Inserta código\` 	| ```console.log("Ola Mundo!");``` 	|
| Bloque de código/ Realtado de sintaxe 	| \`\`\`inserta código\`\`\` 	|  (#notas-útiles)
| Táboa 	| \| As táboas   \|      son      \|  xeniais \| \|\----------\|\:\-------------\:\|------\:\| \| col 1 é\|  aliñada á esquerda \| $1600 \| | ![](http://i.imgur.com/EItt7mh.png) |


## Notas útiles:
 * Para escapar caracteres en Markdown emprégase a barra invertida \
 * Para engadir fragmentos de código nunha linguaxe concreta e resaltalos, engádense 3 backticks antes (xunto co identificador do idioma), e despois do bloque de código:
   
   ```rust
   // Ola Mundo en Rust
   fn main() {
       println!("¡Ola, Mundo!");
   }
   ```
 * Os vídeos de Youtube non se poden engadir directamente, pero podes engadir unha imaxe cunha ligazón ao vídeo do seguinte xeito:
  ```html
  <a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
  " target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" 
  alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>
  ```
 * Markdown soporta Emojis :laughing: :laughing: :kissing_heart: :innocent: :green_heart: ( consulta algunos emojis [aquí](http://www.emoji-cheat-sheet.com/) )
 * Calquera URL (coma http://www.github.com/) será convertida automáticamente nunha ligazón activa.
 * Se queres practicar Markdown, podes facelo online [aquí](http://www.markdowntutorial.com).

