# Reto 3 de CSS –  clonar una página web 😺

Este proyecto fue realizado como parte del Reto 3 de CSS, el cual consistía en clonar una página web usando HTML y CSS.
En este caso, quise copiar mi página de home de Spotify, se me hizo como un reto de que dije yo "estaría chido y tal vez se podría poner en el portafolio".
Ya luego después, cuando quise empezar a hacerlo y que vi el Spotify bien dije yo "en que me metí, me estoy mentiendo la soga al cuello" JAJAJA
Empecé un día haciendo un poco la estructura de lo que veía, a lo que sentí es que se dividía entre 3 y 5 partes, principalemente: el lado izquierdo de biblioteca, el medio de todo el contenido principal y el aside a la derecha, más el nav de buscador y el tipo footer de barra de reproducción.

Entonces, empecé con 3 del apartado de la izquierda, solo para tratar de calar que tan feo se me iba a hacer y, fue un poquito pero fue avance, de hecho, después para tratar de hacer un poquito más parecido posible, traté de visualizar los bordes bien de cada contenedor, coloreandolos de color rojo.
Traté de hacer un poco de cada parte, donde tuve problemas fue en lo siguiente:
Uno de los problemas principales fue las imagenes (y de hecho en los commits se ve, incluso de todo lo que les voy a hablar y más), a veces se sobresalian y se veía feo, no se veía con el border-radius adecuado por ello, esto se arregló con un overflow: hidden (de hecho en uno de los commits hasta me emocioné porque lo pude arreglar) y otro fue que las imagenes se cortaban, esto se arregló ajustando los paddings (me costó mucho q-q)

De ahi en fuera, siento que una vez que pude hacer la parte de en medio (la primera sección , la que está arriba de 'hecho para') siento que todo fluyó, con esa partecita pude entender como casi casi hacer todo lo demás.
Si alguien ve esto, como recomendación, para copiar los colores les recomiendo el uso de PowerToys de Microsoft con su selector de colores :D me fue de demasiada ayuda para tratar de hacer que se pareciera lo más en cuanto a colores y siento que de verdad me ayudó.

No quiero que pierdan tiempo leyendome, estoy feliz de verdad, fueron 31 commits que de verdad, en mi vida hubiera pensado que hubiera sido tan "fácil" entre muchas comillas y dificil a la vez de hacer, mil gracias de verdad.

## Descripción del reto

Reto de la semana: clonar una página web

Reto 3:  
No buscamos ahorita que quede idéntica, solo que se vea similar en cuanto a colores, fondos e imágenes.
- Evita animaciones (vamos paso a paso)
- No pagues por fuentes
- ¿Por dónde iniciar?, ¿Cómo divido el trabajo?, ¿Qué tienen en común estas páginas?
- Puedes usar Flexbox... lo veremos la siguiente clase

## Tecnologías empleadas

Se utilizó:
- HTML5 para la estructura de la tarjeta
- CSS3 para el diseño visual

## Características

- Uso de etiquetas HTML
- En este reto si hice uso de flexbox (y fue de demasiada ayuda x-x)
- Uso de align-items y justify-content para alinear tanto en eje vertical y horizontal los elementos con flexbox
- Uso de vh porque de otra forma en mi pantalla había espacio sobrante y con esto al usarlo en min height se arregla lo del espacio en blanco
- Uso de flex-wrap para que se hicieran multilinea los elementos en la parte de arriba (antes de hecho para ti)
- Uso de margins y paddings (mucho)
- Como aprendizaje, el overflow hidden ayuda mucho al momento de tener imagenes que se sobresalgan
- Estilización de todo con CSS

## Archivos principales

- index.html: Tiene la estructura de la tarjeta
- style.css: Tiene todos los estilos que se aplicarán a la tarjeta del html
- Carpeta img: Contiene imagenes como home, k-indie, logo, etc.
- - img contiene también carpetas: barra-reproducción (tiene imagenes de la barra de reproducción), estaciones (imagenes para el apartado de estaciones), hecho-para (imagenes para el apartado de hecho para),  tarjetita-main (imagenes para el centro, que viene siendo el contenido principal)


## Despliegue
Se desplegó en Github Pages a partir de este repositorio, puedes ver la página a través del siguiente link:

https://mor4n.github.io/Reto3CSS.github.io/

## Instalación

1. Clona este repositorio:

    ```

    git clone https://github.com/Mor4n/Reto3CSS.github.io.git

    ```

2. Navega al directorio del proyecto:

    ```
    
    cd Reto3CSS.github.io

    ```

3. Para ejecutar el proyecto puedes escribir en la terminal:
    ```
     index.html
    ```
    Con esto se abrirá en la página web en tu navegador predeterminado

    
    También, en el explorador de archivos, dentro de la carpeta Reto3CSS.github.io

    ```
     Haz doble clic en el archivo index.html y se abrirá en tu navegador predeterminado
    ```
   
## Autor

Creado por [Brayan Morán](https://github.com/Mor4n) - ¡Si te gusta el proyecto, no dudes en contactarme!
## Agradecimientos

Gracias a la sensei Ana, DEV.F, Bécalos y Fundación Traxión por las enseñanzas y el acompañamiento durante el aprendizaje.

Estoy feliz con lo realizado en este proyecto, antes de esta práctica, no me sentía comodo con flexbox y gracias a que nos hicieron hacerla, pude entenderlo bien :D se los prometo, mil gracias,  sin ustedes, realmente nunca lo hubiera podido haber hecho 💜 se los agradezco eternamente.
