/-- En resumen, de menor a mayor, la especificidad de los selectores es la siguiente:
Selectores establecidos automáticamente por el navegador.
Selector universal (*).
Pseudoselectores y selectores de etiqueta: si existe ambigüedad, la última
propiedad dentro del archivo CSS es la que prevalece.
Clases, pseudoclases y selectores de atributo: si existe ambigüedad, la última
propiedad dentro del archivo CSS es la que prevalece.
Selectores ID.
Estilos inline. --/


 <imput id="tarea" typetext="text" placehotder="introduce la tarea">
 <imput type="submil" value="Agregar tarea">
   
   <h1>Mis Tareas</h1>  
   <hr>
   <ui>
     <li>Aprende desarollar web</li>
     <</ui>
     hola hola hola 
     1 guardar edicion
     2 git...status
     3 git...add . (significa cualquier archibo ".")
     3 git...commit -m "texto"
     4 git push
     5 aveces se añaden:
      Espacio en blanco: &nbsp;
Menor que: &lt;
Mayor que: &gt;
Ampersand: &amp;
Comillas dobles: &quot;
Comillas simples: &apos;
Ejemplo de etiqueta: &lt;body&gt;:
mas  simbolos https://www.toptal.com/designers/htmlarrows/symbols/
<h1>Cabecera 1</h1> tamaño
<p>Esto es un párrafo</p>

Hola
</br>salto de linea
Adiós
<hr></hr> separador
<button>Pulsa</button>

texto preformateado
<pre>
body {
color: red;
}
a {
color:green;
}
</pre>


codigo de texto preformateado
<pre> <cod
e>
x
= 5;
y
= 6;
z
=
x
+ y;
</code>
</pre>

Otras etiquetas relacionadas con código: kbd (para visualizar texto que es entrada de
teclado), samp (para visualizar texto que es salida por pantalla) y var (para visualizar
variables matemáticas). Son etiquetas que añaden diferentes estilos CSS al texto
Samp
Var

formatear texto

<b> Texto resaltado</b></br>
<strong>Texto resaltado con importancia semántica</strong></br>
<i>Texto itálica</i></br>
<em>Texto itálica con importancia semántica</em></br>
<mark>Texto resaltado con color</mark></br>
<small>Texto pequeño</small></br>
<del>Texto tachado</del></br>
<ins>Texto subrayado</ins></br>
<sub>Texto subíndice</sub></br>
<sup>Texto superíndice</sup></br>
<q>Cita</q></br>
<blockquote>Bloque con cita</blockquote></br>
<abbr>Abreviatura</abbr> <!-- abbr sustituye a acronym en HTML5 -->
<address>Dirección de contacto</address></br>
<cite>Juego de Tronos</cite></br>
<bdo dir="rtl">Texto bidireccional</bdo></br> <!-- ltr es el valor por defecto>
<img src="logo.png" alt="Esto es mi logo" width="150px">



para pasar ala pge
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<meta name="keywords" content="html5, curso">
<meta name="Jxhn" content="Mine">
<meta name="description" content="Curso MEAN">
   


     iste otro atributo target que define:
_blank: abre el enlace en una nueva ventana o pestaña.
_self: abre el documento vinculado en la misma ventana, pestaña o frame en la que
se hizo click (es el valor predeterminado).
_top: abre el documento vinculado en todo el cuerpo de la ventana.
_parent: abre la página en el frame padre.
-framename-: abre el documento vinculado en un marco con nombre framename.



https://www.tagindex.net/html/frame/a_target.html para abrir en otras partes de la pagina
 https://caniuse.com/ "para crear diseño de paginas etc"

<frameset><frame src=""> crea un marco
<frameset> conjunto de marcos
<frameset> ejemplo de anidamiento
Extensión<frameset frameborder="0"> borde del marco
Extensión<frameset border=""> grosor del borde del marco
Extensión<frameset bordercolor=""> color del borde del marco
<frame src=""> define un marco
<frame src="" name=""> nombrando el marco
<frame src="" noresize> no permite cambiar el tamaño del marco
<frame src="" scrolling=""> controla el desplazamiento
<frame src="" marginwidth="" marginheight=""> márgenes en el marco
<a href="" target=""> el marco de destino del enlace
<noframes> contenido alternativo para usuarios sin marcos
Ejemplos de diseño de marcos ejemplos de marcos
Marco en línea
<iframe src=""> crea un iframe
<iframe src=""> define un iframe
<iframe src="" width="" height=""> ancho y alto del iframe
<iframe src="" name=""> nombrar el iframe
<iframe src="" frameborder="0"> borde del iframe
<iframe src="" scrolling=""> controla el desplazamiento
<iframe src="" marginwidth="" marginheight=""> márgenes en el iframe
Extensión<iframe src="" allowtransparency="true"> iframe transparente
<iframe src="" align=""> alineación de iframe
Extensión<iframe src="" vspace="" hspace=""> el espacio del iframe
Obsoleto<br clear=""> detener el ajuste de texto
<a href="" target=""> el marco de destino del enlace
Marcas
ObsoletoElementos o atributos obsoletos

ExtensiónElementos de extensión o atributos

También se permite la posibilidad de añadir nuevas etiquetas, aunque no es muy
utilizado.
<script>
document.createElement("myHero")
</script>
<myHero>My Hero Element</myHero>


barra de progreso /disco duro xejempl meter/
        <meter value="2" min="0" max="10">2 out of 10</meter><br>
        <meter value="0.6">60%</meter></strong>
        <progress value="22" max="100"></progress>

Etiqueta article:
Especifica contenido independiente y autónomo.
Un artículo debería tener sentido por sí mismo, y debería ser posible leerlo
independientemente del resto del sitio web.
Ejemplo: post de un foro, noticia, post de un blog, etc.
Es posible anidar etiquetas section dentro de etiquetas article o vicecersa, o
etiquetas section dentro de etiquetas section y de la misma forma para etiquetas
article. Todo depende del contenido.

<article>
    <h1>What Does WWF Do?</h1>
    <p>WWF's mission is to stop the degradation of our planet's natural environment,
    and build a future in which humans live in harmony with nature.</p>
    </article>
--


Etiqueta nav:
Define un conjunto de enlaces de navegación.
Pueden utilizarse varios a lo largo de un documento.
<nav>
<a href="/html/">HTML</a> |
<a href="/css/">CSS</a> |
<a href="/js/">JavaScript</a> |
<a href="/jquery/">jQuery</a>
</nav>

Etiqueta footer:
Un pie de página generalmente contiene el autor del documento, información de
copyright, enlaces a términos de uso, información de contacto, etc.
Únicamente debería existir un único footer en todo el documento.
<footer>
<p>Posted by: Hege Refsnes</p>
<p>Contact information: <a href="mailto:someone@example.com">
someone@example.com</a>.</p>
<address>JFK, 23</address>
</footer>

Los complementos se pueden agregar a páginas web con la etiqueta object o la etiqueta
embed.
80
LOTE 2
<object width="400" height="50" data="img/bookmark.swf"></object> <!--
Soportado por HTML4 y HTML5 -->
<embed width="400" height="50" src="img/bbookmark.swf"></embed> <!--
Únicamente soportado por HTML5 -->
Aunque también permiten incluir otro código HTML o imágenes:
<object width="100%" height="500px" data="snippet.html"></object>
<embed width="100%" height="500px" src="snippet.html">
<object data="audi.jpeg"></object>
<embed src="audi.jpeg">
En ocasiones, elementos externos también son introducidos mediante la etiqueta iframe.
Youtube
<iframe width="420" height="315"
src="https://www.youtube.com/embed/tgbNymZ7vqY"></iframe>




Elemento vídeo:
El atributo controls agrega controles de video, como reproducir, pausar y volumen.
Desde el elemento source se pueden definir distintas fuentes de vídeos. El
navegador seleccionará la compatible.
Para comenzar automáticamente el vídeo, puede utilizarse el atributo autoplay
(parece funcionar en Firefox, pero no en Chrome).
Para reproducir el vídeo en loop, se puede utilizar el atributo loop.
Es una buena idea incluir siempre atributos de ancho y alto. Si el alto y el ancho no
están configurados, la página puede parpadear mientras se carga el video.
Pueden también añadirse elementos de texto, como los subtítulos, mediante la
etiqueta track.
Desde I can use puede accederse a la actual compatibilidad entre navegadores de
los distintos contenedores de vídeo (mp4, ogg, webm).
<video id="video" width="320" height="240" controls="controls" autoplay="autoplay"
loop="loop">
<source src="img/movie.mp4" type="video/mp4">
<source src="img/movie.ogg" type="video/ogg">
<source src="img/movie.webm" type="video/webm">
<track src="subtitles_en.vtt" kind="subtitles" srclang="es" label="Spanish">
Tu navegador no es compatible con la etiqueta vídeo.
</video>
HTML5 define métodos DOM y propiedades que permiten cargar, reproducir y pausar
videos, así como establecer la duración y el volumen. También hay eventos DOM que
avisan cuando un vídeo comienza a reproducirse, está en pausa, etc.
let x = document.getElementById("video");
x.play();
x.pause();
añadir formatos
<audio controls="controls">
<source src="img/horse.ogg" type="audio/ogg">
<source src="img/horse.mp3" type="audio/mpeg">
<source src="img/horse.wav" type="audio/wav">
Tu navegador no es compatible con la etiqueta audio.
</audio>




articulos
Etiqueta details:
Especifica detalles adicionales que el usuario puede mostrar u ocultar a petición.
<details>
<p> - by Refsnes Data. All Rights Reserved.</p>
<p>All content and graphics on this web site are the property of the company Refsnes
Data.</p>
</details>
Etiqueta summary:
Define un encabezado visible para el elemento details. Se puede hacer clic en el
encabezado para mostrar u ocultar los detalles.
<details>
<summary>Copyright 1999-2014.</summary>
<p> - by Refsnes Data. All Rights Reserved.</p>
<p>All content and graphics on this web site are the property of the company Refsnes
Data.</p>
</details>
Etiqueta figure:
Especifica contenido autónomo como ilustraciones, diagramas, fotos, listas de
códigos, etc.
<figure>
<img src="img_pulpit.jpg" alt="The Pulpit Rock" width="304" height="228">
</figure>

<figure>
<img src="img_pulpit.jpg" alt="The Pulpit Rock" width="304" height="228">
<figcaption>Fig1. - A view of the pulpit rock in Norway.</figcaption>
</figure>
Etiqueta main:
Especifica el contenido principal de un documento.
El contenido dentro del elemento main debe ser exclusivo del documento y no debe
ser un descendiente de un elemento article, aside, footer, header o nav.
<main>
<h1>Web Browsers</h1>
<p>Google Chrome, Firefox, and Internet Explorer are the most used browsers today.
</p>
<article>
<h1>Google Chrome</h1>
<p>Google Chrome is a free, open-source web browser developed by Google,
released in 2008.</p>
</article>
<article>
<h1>Internet Explorer</h1>
<p>Internet Explorer is a free web browser from Microsoft, released in 1995.</p>
</article>
<article>
<h1>Mozilla Firefox</h1>
<p>Firefox is a free, open-source web browser from Mozilla, released in 2004.
</p>
</article>
</main>





FECHA HORA

Etiqueta time:
Define una fecha u hora legible por humanos.
El atributo datetime permite representar fechas/horas legibles por las máquinas, de
modo que los los motores de búsqueda pueden producir resultados de búsqueda
más inteligentes, por ejemplo, con recordatorios para calendarios.
<p>Abrimos a las <time>10:00</time> todos los días</p>
<p>Hoy es <time datetime="2008-02-14 20:00">el día de San Valentín</time>.</p>
78

_____________________________________________________________________________________________________________________________________


Formas de insertar código CSS
El código CSS puede añadirse de tres formas distintas:
En línea: utilizando el atributo style en elementos HTML.
Interno: utilizando un elemento style en la sección head.
Externo: utilizando un archivo CSS externo mediante la etiqueta link.
En línea:
<h1 style="color:blue;">Cabecera azul</h1>
Interno:
<!DOCTYPE html>
<html>
<head>
<style>
body {
background-color: powderblue;
}
h1 {
color: blue;
85
LOTE 2
}p
{
color
: red;
}
</style>
</head>
<body>
<h1>Cabecera</h1>
<p>Párrafo</p>
</body>
</html>
Externo:
<!-- index.html --
>
<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="styles.css"
>
</head>
<body>
<h1>Esto es una cabecera</h1>
<p>Esto es un párrafo</p>
</body>
</html>
/* styles.css */
body
{
background
-color
: powderblue;
}
h1
{
color
: blue;
}p
{
86
LOTE 2
color: red;
}






----


<!-- nombres de colores -->
<h1 style="background-color:red">Rojo</h1>
<!-- rgb(red, green, blue) entre 0 y 255 -->
<h1 style="background-color:rgb(255, 99, 71);">255, 99, 71</h1>
<!-- hexadecimal (#rrggbb) con rr (red), gg (green), bb(blue) entre 00 y FF -->
<h1 style="background-color:#ff6347">#ff6347</h1>
<!--
hsl(hue, saturation, lightness, alpha) con tono, saturación, claridad, opacidad
El tono varía de 0 a 360. 0 es rojo, 120 es verde, 240 es azul y 360 vuelve a ser el
rojo
La saturación (intensidad del color) es un valor porcentual, 0% significa un tono de
gris y 100% es el color completo
La claridad es también un porcentaje: 0% es oscuro y el 100% es claro
La opacidad es un número: 0.0 (totalmente transparente) y 1.0 (totalmente opaco)
-->
<h1 style="background-color:hsla(120, 100%, 64%, 0.5);">120, 100%, 64%,
0.5</h1>






























































































trabajo3
<body>
<!-- ... -->
<script>
function myFunction() {
document.getElementById("demo").innerHTML = "Párrafo cambiado";
}

<script>
alert("Hello world!");
</script>



<!-- index.html -->
104
LOTE 2
<script>
alert("Hello world!");
document.write("Hello world!");
console.log("Hello world!")
</script>


// main.js
console.log('Hello world!');
node main.js


/*confirmacion*/
<script>
const conf = confirm("Sí o no");
// true o fase
console.log(conf);
</script>



<script>
// hola
console.log('hola');
108
LOTE 2
// en un lugar de la mancha
console.log('en', 'un', 'lugar', 'de', 'la', 'Mancha');
console.info('Info');
console.warn('Warning');
console.error('Error');
</script>




</script>
</body>


<script>
    // correcto
    const nombre = "Alejandro";
    function saludar() {
    document.write(nombre);
    }
    // error porque Javascript interpretaría:
    // const nombre = "Alejandro" (function saludar() {console.log('Hola'); })()
    const nombre = "Alejandro"
    (function saludar() {
    document.write("Hola");
    })();
    // para evitarlo se añade el punto y coma
    const nombre = "Alejandro";
    (function saludar() {
    document.write("Hola");
    })();
    </script>
    Los espacios en blanco entre asignaciones de variables son permitidos.
    const person1="Hege";
    const person2 = "Hege";
    La función prompt permite pedir información por pantalla en el navegador.
    <script>
    const nombre = prompt("Escriba su nombre", "Escriba aquí");
    110
    LOTE 2
    console.log(nombre);
    </script>
    La función confirm permite pedir confirmación por pantalla en el navegador.
    <script>
    const conf = confirm("Sí o no");
    // true o fase
    console.log(conf);
    </script>

























trabajo 2.2 final
<!DOCTYPE html>
<html lang="es">
<head>
   
    <!DOCTYPE html>
    <html>
    <head>
    <style>
      body {
    background-color: blue:
    }
    h1 {
    color: rgb(59, 46, 162);text-align: center;}
    p{color:  rgb(60, 26, 124);text-align: center;}
    body {
    background-color:rgb(87, 181, 232);
    }  
    
    
</style>
</head>
<head>
         <h1 style="background-color:  rgba(255, 255, 255, 0.701)"><br>Fisioterapia<br><br></h1>
        <h4></h4><pre><p>Abrimos a las <time>10:00</time> todos los días</p></pre> <time datetime="2023-05-19 11:00"></time></h4>
    </head>

<body>
 <p>Hoy es el día de San Valentín</time>.</p>


 <img src="https://www.ucavila.es/wp-content/uploads/2021/03/Fisioterapia-Presencial.jpg" alt="Imagen con figure" width="500" height="450"> <br>
 <img src="https://fisiodomicili.com/wp-content/uploads/2021/11/image.axd_.webp" alt="Imagen con figure" width="304" height="228">
 <figcaption>te ayudamos todo tu proceso</figcaption>
 <img src="https://www.onelifecenter.es/wp-content/uploads/2021/01/Unidad-de-Fisioterapia-compressed-1-scaled.jpg" alt="Imagen con figure" width="304" height="228">
 <figcaption>Entregs y compromiso.</figcaption>

78
<p>Párrafo</p>
</body>
</html>

<border:box></border:box>


























trabajo2.2




<link rel="stylesheet" href="https://www.w3schools.com/html/styles.css">

<style>
    /* Se verán afectados por este estilo todas las etiquetas <p> */
    p {
    text-align: center;
    color: red;
    }
    <style>
#saludo {
text-align: center;
color: red;
}
</style>
<p id="saludo">Hola</p>
<p>Adiós</p>

            <style>
                .saludos {
                text-align: center;
                color: red;
                }
                </style>
                <p class="saludos">Hola</p>
                <p class="saludos">Buenos días</p>
                <!-- nombres de colores -->
<h1 style="background-color:rgb(200, 0, 255)">Rojosdfedfgrfg<br>ddfsfgdfgb<br></h1>
<!-- rgb(red, green, blue) entre 0 y 255 -->
<h1 style="background-color:rgb(255, 71, 184);">255, 99, 71</h1>
<!-- hexadecimal (#rrggbb) con rr (red), gg (green), bb(blue) entre 00 y FF -->
<h1 style="background-color:#5fff47">#ff6347</h1>
<!--
hsl(hue, saturation, lightness, alpha) con tono, saturación, claridad, opacidad
El tono varía de 0 a 360. 0 es rojo, 120 es verde, 240 es azul y 360 vuelve a ser el
rojo
La saturación (intensidad del color) es un valor porcentual, 0% significa un tono de
gris y 100% es el color completo
La claridad es también un porcentaje: 0% es oscuro y el 100% es claro
La opacidad es un número: 0.0 (totalmente transparente) y 1.0 (totalmente opaco)
-->
<h1 style="background-color:hsla(233, 100%, 64%, 0.5);">120, 100%, 64%,
0.5</h1>

--
<style>
    .red-and-bold
    #green {
    color: rgba(101, 103, 101, 0.975);
    }
    89
    LOTE 2
    div {
        font-weight: bold;
    color: red;
    }
    </style>
    <div id="green-and-lighter">
        <!-- orden de la especificidad: #red-and-bold > div > #green-and-lighter -->
        <!-- sin embargo, se aplica la propiedad color del selector #green-and-lighter porque el
        selector más específico (#red-and-bold) indica que se herede esa propiedad -->
        <div id="red-and-bold"> 


            --
    <!-- este div es coincidente con el selector de etiqueta div -->
    <div>Hola</div>
    <!-- este div es coincidente con el selector de etiqueta div y el selector #green -->
    <div id="green">Holaaaa</div>
    <div class="red-and-bold">Holaaaaaa</div>
    <div id="black-and-lighter" class="red-and-bold">Holaaaaaaa</div>
    Si el selector es exactamente el mi

        <!-- se aplica la propiedad font-weight del primer selector div -->
        <!-- NO se aplica la propiedad color del primer selector div -->
        <!-- se aplica la propiedad color del segundo selector div -->
       
            <!-- se aplican las propiedades font-weight y color del selector .red-and-bold -->
            <!-- NO se aplica la propiedad color del segundo selector div -->
           
                <!-- se aplican las propiedades font-weight y color del selector #white-and-bold -->
                <!-- NO se aplican las propiedades font-weight y color del selector .red-and-bold -->
                <!-- NO se aplica la propiedad y color del selector div -->
               
                <style>
                    #green-and-bold {
                    font-weight: bold;
                    color: rgb(235, 33, 164);
                    }
                    92
                    LOTE 2
                    </style>
                    <div id="green-and-bold">
                    <!-- se heredan las propiedades del selector #green-and-bold -->
                    <div>Hola</div>
                    </div>



                    <style>
.centrar {
text-align: center;
}
.red {
color: red;
}
</style>
<!-- aplican los estilos de los selectores .centrar y .red -->
<p class="centrar red">Hola</p>
<!-- aplican los estilos del selector .centrar -->
<p class="centrar">Buenos días</p>
También se pueden agrupar selectores para aplicar los mismos estilos utilizando una coma
para separar los selectores.
<style>
/* afecta a todos los elementos con el atributo class="saludos" o class="red" */
.saludos, .red {
text-align: center;
color: red;
}
</style>
<p class="saludos red">Hola</p>
<p class="saludos">Buenos días</p>
<p class="red">¿Cómo estás?</p>

<style>
    /* se aplica a un elemento p que esté contenido dentro de un elemento div y que no
    necesariamente tiene que ser ancestro directo */
    div p {
    background-color: yellow;
    }
    p {
    background-color: red;
    }
    </style>
    <div id="hola">
    <!-- se aplica la propiedad background-color de la combinación de selectores div p, que
    es más específica que el selector p -->
    <!-- sin embargo, la combinación de selectores div p no sería más específica que otros
    como #hola p o .saludos -->
    <p class="saludos">Buenos días</p>
    </div>
    
    <style>
        div p {
        color: red;
        }
        </style>
        <div>
        <div>NO aplica</div>
        <p>Aplica</p>
        <div>NO aplica</div>
        <article>
        <p>Aplica</p>
        </article>
        <p>Aplica</p>
        </div>





















trabajo 2.1
#Ejercicio: crea una página HTML5 simple con contenido utilizando las etiquetas básicas
header, nav, aside, section, article y footer.

<article>
    <header>
    <h1>La Tegnologia tiene fin?</h1>
    <p><h4>La mentalidad es infinita?</h4></p>
    </header>
    <pre><p>Infinitos mundos y poco tiempo para descubrirlo</p></pre>
    </article>

<nav>
    &nbsp; &nbsp; |&nbsp; &nbsp;<a href="/html/">HTML</a> &nbsp; &nbsp; |&nbsp; &nbsp; &nbsp; &nbsp;  &nbsp; &nbsp; 
    &nbsp; &nbsp; |&nbsp; &nbsp;<a href="/css/">CSS</a> &nbsp; &nbsp;  |&nbsp; &nbsp; &nbsp; &nbsp;  &nbsp; &nbsp; 
    &nbsp; &nbsp; |&nbsp; &nbsp;<a href="/js/">JavaScript</a> &nbsp; &nbsp; |&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 
    &nbsp; &nbsp; |&nbsp; &nbsp;<a href="/jquery/">jQuery</a> 
    </nav>
   
    /* Etiqueta aside:
    Define algún contenido adicional (como una barra lateral).
    Pueden utilizarse varios a lo largo de un documento. */
<p>Index</p>
<aside>
    <h4>Help</h4>
    <p>later....</p>
</aside>

/* Etiqueta section:
Define una sección de datos en el documento.
Una sección es una agrupación temática de contenido, generalmente con un título
(con cabecera). */
<section>
    <h1>Proyect web</h1>
    <p>No sé que poner....</p>
</section>

<article>
    <h1>More info...?</h1>
    <p>contact whit me :) </p>
</article>

<footer>
    <p>Posted by: Jxhnn proyect web</p>
    <p>Contact information: <a href="johnnypc95@gmail.com">
        johnnypc95@gmail.com</a>.</p>
    <address>SPA, VLC</address>Nothing
</footer>


______________________________________________________________________________________________________________________________
</br>
<br>
<br>



#Ejercicio: crea una imagen con las etiquetas figure, img y figcaption.
Ejercicio proyecto final: asocia los diferentes  elementos de las páginas del storyboard
diseñadas con cada elemento semántico de HTML5.

<git><details> <p><h3>Vista desde la montaña mas alta </h3></p>
    <p> - subir/bajar.</p>
    <p>todo contenido que quiera.</p></details> </br>
    
<figure>
        <img src="https://w0.peakpx.com/wallpaper/484/1016/HD-wallpaper-top-of-the-world-landscape-mountain-tree-view.jpg" alt="Imagen con figure" width="304" height="228">
        <figcaption>Fig1. - imagen con figure.</figcaption>
        </figure></br>
             

______________________________________________________________________________________________________________________________
<br>
<br>
<br>

    -jercicio: probar el uso de la etiqueta con un vídeo en diferentes navegadores y
    formatos.
    <git><p><h3>Mario Bros Litle</h3></p>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/0kqfeX4o8Ks" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen>
            <source src="img/movie.mp4" type="video/mp4">
            <source src="img/movie.ogg" type="video/ogg">
            <source src="img/movie.webm" type="video/webm">
            <track src="subtitles_en.vtt" kind="subtitles" srclang="es" label="Spanish">
        </iframe></git></br> </br>
        


 ______________________________________________________________________________________________________________________________<br><br>
   


 -Ejercicio: probar el uso de la etiqueta audio en diferentes navegadores y formatos <br>
    
 <audio controls="controls">
    <source src="img/horse.ogg" type="audio/ogg">
    <source src="img/horse.mp3" type="audio/mpeg">
    <source src="img/horse.wav" type="audio/wav">
    Tu navegador no es compatible con la etiqueta audio.
    </audio> 


______________________________________________________________________________________________________________________________<br><br>


-Ejercicio proyecto final: crea la estructura base de la página principal con etiquetas
semánticas, incluyendo main, section y article.<br><br>

<main>
    <section> <h1>Esta es la zona de section</h1>
    <p>Mostrando similitud
    </p> </section> <article>
    <h1>Esta es la zona de article</h1>
    <p>Mostrando similitud.</p></article>
    </main>





<a href="https://www.corenetworks.es/">Core Networks</a> <!-- Enlace externo -->
<a href="/">Index</a> <!-- Enlace a ruta absoluta -->
<a href="/contacto">Contacto</a> <!-- Enlace a ruta absoluta -->
<a href="contacto">Contacto</a> <!-- Enlace a ruta relativa -->
<!-- index.html -->
<h2 id="C4">Chapter 4</h2>
<!-- index.html -->
<a href="#C4">Saltar al capítulo 4</a>
<!-- otrapagina.html -->
<a href="index.html#C4">Saltar al capítulo 4 de la página index.html</a>
<a href="/">
    <img src="smiley.gif" alt="Página principal">
    </a>
    
  

    --
    https://caniuse.com/ "para crear diseño de paginas etc"

    
<a href="index.html" target="_top">linked text</a>

Attribute	Value	Explanation
target=" "	_blank	the linked page opens in the new window
_top	the linked page opens in the entire window
_self	the linked page opens in the same frame
_parent	the linked page opens in the parent frame
frame name	the linked page opens in the named frame
The target attribute cannot be used with the Strict DTD.

Example
target="_top" (The linked page opens in the entire window)

<p><a href="example_t01.html" target="_top">Entire window</a></p>

Output
Target _top

Example pagenew window

target="_self" (The linked page opens in the same frame)

<p><a href="example_t02.html" target="_self">Same frame</a></p>

Output
Target _self





Example pagenew window

target="_parent" (The linked page opens in the parent frame)

<p><a href="example_t03.html" target="_parent">Parent frame</a></p>

Output
Target _parent

Example pagenew window

About the parent frame

Parent frame

When you load the "child.html" into the B frame, the parent frame of the C frame becomes the B frame.

target="FrameName" (The linked page opens in the named frame)

<ul>
<li><a href="example_t04.html" target="top">B frame</a></li>
<li><a href="example_t04.html" target="main">C frame</a></li>
</ul>

Output
Target name

Example page

--


<video id="video" width="320" height="240" controls="controls" autoplay="autoplay"
        loop="loop">
        <source src="img/movie.mp4" type="video/mp4">
        <source src="img/movie.ogg" type="video/ogg">
        <source src="img/movie.webm" type="video/webm">
        <track src="subtitles_en.vtt" kind="subtitles" srclang="es" label="Spanish">
        Tu navegador no es compatible con la etiqueta vídeo.
        </video>







































1 trabajo..
<!DOCTYPE html>
<html lang="es">
<head>
    <title>Login whit Jxhnn </title>
<link rel="stylesheet" href="styles.css" />
<script src="main.js"></script>

    <strong><h1>My proyect page</h1> <input type="button" value="Like"> 
        <progress value="69" max="100"></progress>
    <pre><p>Name</p> <input type="Name" id="Name"> &nbsp; 
    <p>Password</p> <input type="Password" id="Password">
    <input type="button" value="go!"></br></pre>





</head>
<body> 
    <git> <p><h3>Local</h3></p>
        <img src="C:\Users\Cursos\Desktop\Cursos J\trabajos\prueba 1.png" alt="FotoPrueba1" width="500px" height="450px"></git> </body><br>
    <git> <p><h3>Web</h3></p>
        <br>
      
         <img src="https://w0.peakpx.com/wallpaper/484/1016/HD-wallpaper-top-of-the-world-landscape-mountain-tree-view.jpg" alt="imagen internet" width="500px" height="450px"></git></git></br>
    
    <git><p><h3>Mario Bros Litle</h3></p>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/0kqfeX4o8Ks" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></git></br>
        <p>Maps</p></br>
        <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d13824.027210369431!2d31.1342019!3d29.9792345!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x14584587ac8f291b%3A0x810c2f3fa2a52424!2sGran%20Pir%C3%A1mide%20de%20Guiza!5e0!3m2!1ses!2ses!4v1684409538478!5m2!1ses!2ses" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
        
        
    <br>
    <textarea>"Apuntes"</textarea>
</body>
</html>
<font><inpu type="text"></font>
    

    




































readme..
/-- En resumen, de menor a mayor, la especificidad de los selectores es la siguiente:
Selectores establecidos automáticamente por el navegador.
Selector universal (*).
Pseudoselectores y selectores de etiqueta: si existe ambigüedad, la última
propiedad dentro del archivo CSS es la que prevalece.
Clases, pseudoclases y selectores de atributo: si existe ambigüedad, la última
propiedad dentro del archivo CSS es la que prevalece.
Selectores ID.
Estilos inline. --/


 <imput id="tarea" typetext="text" placehotder="introduce la tarea">
 <imput type="submil" value="Agregar tarea">
   
   <h1>Mis Tareas</h1>  
   <hr>
   <ui>
     <li>Aprende desarollar web</li>
     <</ui>
     hola hola hola 
     1 guardar edicion
     2 git...status
     3 git...add . (significa cualquier archibo ".")
     3 git...commit -m "texto"
     4 git push
     5 aveces se añaden:
      Espacio en blanco: &nbsp;
Menor que: &lt;
Mayor que: &gt;
Ampersand: &amp;
Comillas dobles: &quot;
Comillas simples: &apos;
Ejemplo de etiqueta: &lt;body&gt;:
mas  simbolos https://www.toptal.com/designers/htmlarrows/symbols/
<h1>Cabecera 1</h1> tamaño
<p>Esto es un párrafo</p>

Hola
</br>salto de linea
Adiós
<hr></hr> separador
<button>Pulsa</button>

texto preformateado
<pre>
body {
color: red;
}
a {
color:green;
}
</pre>


codigo de texto preformateado
<pre> <cod
e>
x
= 5;
y
= 6;
z
=
x
+ y;
</code>
</pre>

Otras etiquetas relacionadas con código: kbd (para visualizar texto que es entrada de
teclado), samp (para visualizar texto que es salida por pantalla) y var (para visualizar
variables matemáticas). Son etiquetas que añaden diferentes estilos CSS al texto
Samp
Var

formatear texto

<b> Texto resaltado</b></br>
<strong>Texto resaltado con importancia semántica</strong></br>
<i>Texto itálica</i></br>
<em>Texto itálica con importancia semántica</em></br>
<mark>Texto resaltado con color</mark></br>
<small>Texto pequeño</small></br>
<del>Texto tachado</del></br>
<ins>Texto subrayado</ins></br>
<sub>Texto subíndice</sub></br>
<sup>Texto superíndice</sup></br>
<q>Cita</q></br>
<blockquote>Bloque con cita</blockquote></br>
<abbr>Abreviatura</abbr> <!-- abbr sustituye a acronym en HTML5 -->
<address>Dirección de contacto</address></br>
<cite>Juego de Tronos</cite></br>
<bdo dir="rtl">Texto bidireccional</bdo></br> <!-- ltr es el valor por defecto>
<img src="logo.png" alt="Esto es mi logo" width="150px">



para pasar ala pge
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<meta name="keywords" content="html5, curso">
<meta name="Jxhn" content="Mine">
<meta name="description" content="Curso MEAN">
   


     iste otro atributo target que define:
_blank: abre el enlace en una nueva ventana o pestaña.
_self: abre el documento vinculado en la misma ventana, pestaña o frame en la que
se hizo click (es el valor predeterminado).
_top: abre el documento vinculado en todo el cuerpo de la ventana.
_parent: abre la página en el frame padre.
-framename-: abre el documento vinculado en un marco con nombre framename.



https://www.tagindex.net/html/frame/a_target.html para abrir en otras partes de la pagina
 https://caniuse.com/ "para crear diseño de paginas etc"

<frameset><frame src=""> crea un marco
<frameset> conjunto de marcos
<frameset> ejemplo de anidamiento
Extensión<frameset frameborder="0"> borde del marco
Extensión<frameset border=""> grosor del borde del marco
Extensión<frameset bordercolor=""> color del borde del marco
<frame src=""> define un marco
<frame src="" name=""> nombrando el marco
<frame src="" noresize> no permite cambiar el tamaño del marco
<frame src="" scrolling=""> controla el desplazamiento
<frame src="" marginwidth="" marginheight=""> márgenes en el marco
<a href="" target=""> el marco de destino del enlace
<noframes> contenido alternativo para usuarios sin marcos
Ejemplos de diseño de marcos ejemplos de marcos
Marco en línea
<iframe src=""> crea un iframe
<iframe src=""> define un iframe
<iframe src="" width="" height=""> ancho y alto del iframe
<iframe src="" name=""> nombrar el iframe
<iframe src="" frameborder="0"> borde del iframe
<iframe src="" scrolling=""> controla el desplazamiento
<iframe src="" marginwidth="" marginheight=""> márgenes en el iframe
Extensión<iframe src="" allowtransparency="true"> iframe transparente
<iframe src="" align=""> alineación de iframe
Extensión<iframe src="" vspace="" hspace=""> el espacio del iframe
Obsoleto<br clear=""> detener el ajuste de texto
<a href="" target=""> el marco de destino del enlace
Marcas
ObsoletoElementos o atributos obsoletos

ExtensiónElementos de extensión o atributos

También se permite la posibilidad de añadir nuevas etiquetas, aunque no es muy
utilizado.
<script>
document.createElement("myHero")
</script>
<myHero>My Hero Element</myHero>


barra de progreso /disco duro xejempl meter/
        <meter value="2" min="0" max="10">2 out of 10</meter><br>
        <meter value="0.6">60%</meter></strong>
        <progress value="22" max="100"></progress>

Etiqueta article:
Especifica contenido independiente y autónomo.
Un artículo debería tener sentido por sí mismo, y debería ser posible leerlo
independientemente del resto del sitio web.
Ejemplo: post de un foro, noticia, post de un blog, etc.
Es posible anidar etiquetas section dentro de etiquetas article o vicecersa, o
etiquetas section dentro de etiquetas section y de la misma forma para etiquetas
article. Todo depende del contenido.

<article>
    <h1>What Does WWF Do?</h1>
    <p>WWF's mission is to stop the degradation of our planet's natural environment,
    and build a future in which humans live in harmony with nature.</p>
    </article>
--


Etiqueta nav:
Define un conjunto de enlaces de navegación.
Pueden utilizarse varios a lo largo de un documento.
<nav>
<a href="/html/">HTML</a> |
<a href="/css/">CSS</a> |
<a href="/js/">JavaScript</a> |
<a href="/jquery/">jQuery</a>
</nav>

Etiqueta footer:
Un pie de página generalmente contiene el autor del documento, información de
copyright, enlaces a términos de uso, información de contacto, etc.
Únicamente debería existir un único footer en todo el documento.
<footer>
<p>Posted by: Hege Refsnes</p>
<p>Contact information: <a href="mailto:someone@example.com">
someone@example.com</a>.</p>
<address>JFK, 23</address>
</footer>

Los complementos se pueden agregar a páginas web con la etiqueta object o la etiqueta
embed.
80
LOTE 2
<object width="400" height="50" data="img/bookmark.swf"></object> <!--
Soportado por HTML4 y HTML5 -->
<embed width="400" height="50" src="img/bbookmark.swf"></embed> <!--
Únicamente soportado por HTML5 -->
Aunque también permiten incluir otro código HTML o imágenes:
<object width="100%" height="500px" data="snippet.html"></object>
<embed width="100%" height="500px" src="snippet.html">
<object data="audi.jpeg"></object>
<embed src="audi.jpeg">
En ocasiones, elementos externos también son introducidos mediante la etiqueta iframe.
Youtube
<iframe width="420" height="315"
src="https://www.youtube.com/embed/tgbNymZ7vqY"></iframe>




Elemento vídeo:
El atributo controls agrega controles de video, como reproducir, pausar y volumen.
Desde el elemento source se pueden definir distintas fuentes de vídeos. El
navegador seleccionará la compatible.
Para comenzar automáticamente el vídeo, puede utilizarse el atributo autoplay
(parece funcionar en Firefox, pero no en Chrome).
Para reproducir el vídeo en loop, se puede utilizar el atributo loop.
Es una buena idea incluir siempre atributos de ancho y alto. Si el alto y el ancho no
están configurados, la página puede parpadear mientras se carga el video.
Pueden también añadirse elementos de texto, como los subtítulos, mediante la
etiqueta track.
Desde I can use puede accederse a la actual compatibilidad entre navegadores de
los distintos contenedores de vídeo (mp4, ogg, webm).
<video id="video" width="320" height="240" controls="controls" autoplay="autoplay"
loop="loop">
<source src="img/movie.mp4" type="video/mp4">
<source src="img/movie.ogg" type="video/ogg">
<source src="img/movie.webm" type="video/webm">
<track src="subtitles_en.vtt" kind="subtitles" srclang="es" label="Spanish">
Tu navegador no es compatible con la etiqueta vídeo.
</video>
HTML5 define métodos DOM y propiedades que permiten cargar, reproducir y pausar
videos, así como establecer la duración y el volumen. También hay eventos DOM que
avisan cuando un vídeo comienza a reproducirse, está en pausa, etc.
let x = document.getElementById("video");
x.play();
x.pause();
añadir formatos
<audio controls="controls">
<source src="img/horse.ogg" type="audio/ogg">
<source src="img/horse.mp3" type="audio/mpeg">
<source src="img/horse.wav" type="audio/wav">
Tu navegador no es compatible con la etiqueta audio.
</audio>




articulos
Etiqueta details:
Especifica detalles adicionales que el usuario puede mostrar u ocultar a petición.
<details>
<p> - by Refsnes Data. All Rights Reserved.</p>
<p>All content and graphics on this web site are the property of the company Refsnes
Data.</p>
</details>
Etiqueta summary:
Define un encabezado visible para el elemento details. Se puede hacer clic en el
encabezado para mostrar u ocultar los detalles.
<details>
<summary>Copyright 1999-2014.</summary>
<p> - by Refsnes Data. All Rights Reserved.</p>
<p>All content and graphics on this web site are the property of the company Refsnes
Data.</p>
</details>
Etiqueta figure:
Especifica contenido autónomo como ilustraciones, diagramas, fotos, listas de
códigos, etc.
<figure>
<img src="img_pulpit.jpg" alt="The Pulpit Rock" width="304" height="228">
</figure>

<figure>
<img src="img_pulpit.jpg" alt="The Pulpit Rock" width="304" height="228">
<figcaption>Fig1. - A view of the pulpit rock in Norway.</figcaption>
</figure>
Etiqueta main:
Especifica el contenido principal de un documento.
El contenido dentro del elemento main debe ser exclusivo del documento y no debe
ser un descendiente de un elemento article, aside, footer, header o nav.
<main>
<h1>Web Browsers</h1>
<p>Google Chrome, Firefox, and Internet Explorer are the most used browsers today.
</p>
<article>
<h1>Google Chrome</h1>
<p>Google Chrome is a free, open-source web browser developed by Google,
released in 2008.</p>
</article>
<article>
<h1>Internet Explorer</h1>
<p>Internet Explorer is a free web browser from Microsoft, released in 1995.</p>
</article>
<article>
<h1>Mozilla Firefox</h1>
<p>Firefox is a free, open-source web browser from Mozilla, released in 2004.
</p>
</article>
</main>





FECHA HORA

Etiqueta time:
Define una fecha u hora legible por humanos.
El atributo datetime permite representar fechas/horas legibles por las máquinas, de
modo que los los motores de búsqueda pueden producir resultados de búsqueda
más inteligentes, por ejemplo, con recordatorios para calendarios.
<p>Abrimos a las <time>10:00</time> todos los días</p>
<p>Hoy es <time datetime="2008-02-14 20:00">el día de San Valentín</time>.</p>
78

_____________________________________________________________________________________________________________________________________


Formas de insertar código CSS
El código CSS puede añadirse de tres formas distintas:
En línea: utilizando el atributo style en elementos HTML.
Interno: utilizando un elemento style en la sección head.
Externo: utilizando un archivo CSS externo mediante la etiqueta link.
En línea:
<h1 style="color:blue;">Cabecera azul</h1>
Interno:
<!DOCTYPE html>
<html>
<head>
<style>
body {
background-color: powderblue;
}
h1 {
color: blue;
85
LOTE 2
}p
{
color
: red;
}
</style>
</head>
<body>
<h1>Cabecera</h1>
<p>Párrafo</p>
</body>
</html>
Externo:
<!-- index.html --
>
<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="styles.css"
>
</head>
<body>
<h1>Esto es una cabecera</h1>
<p>Esto es un párrafo</p>
</body>
</html>
/* styles.css */
body
{
background
-color
: powderblue;
}
h1
{
color
: blue;
}p
{
86
LOTE 2
color: red;
}






----


<!-- nombres de colores -->
<h1 style="background-color:red">Rojo</h1>
<!-- rgb(red, green, blue) entre 0 y 255 -->
<h1 style="background-color:rgb(255, 99, 71);">255, 99, 71</h1>
<!-- hexadecimal (#rrggbb) con rr (red), gg (green), bb(blue) entre 00 y FF -->
<h1 style="background-color:#ff6347">#ff6347</h1>
<!--
hsl(hue, saturation, lightness, alpha) con tono, saturación, claridad, opacidad
El tono varía de 0 a 360. 0 es rojo, 120 es verde, 240 es azul y 360 vuelve a ser el
rojo
La saturación (intensidad del color) es un valor porcentual, 0% significa un tono de
gris y 100% es el color completo
La claridad es también un porcentaje: 0% es oscuro y el 100% es claro
La opacidad es un número: 0.0 (totalmente transparente) y 1.0 (totalmente opaco)
-->
<h1 style="background-color:hsla(120, 100%, 64%, 0.5);">120, 100%, 64%,
0.5</h1>























pagina para animaciones https://github.com/FaztWeb/html_login01