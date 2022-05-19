# Práctica XML UF 2217

Para iniciar la práctica de esta unidad formativa seguimos los siguientes pasos:

1. Descargamos el programa XML Copy Editor
![XML Copy Editor](https://i.ibb.co/W2jxWrX/Captura-de-pantalla-2022-05-12-125734.png)
2. En el gist de formawebiv encontramos los ejercicios escritos en XML en los cuales tenemos que detectar los errores y corregir el código
3. El código a corregir es el siguiente:

##### Práctica 1

```xml
<?xml version="1.0" encoding="UTF-8"?>
<deportistas>
  <deportista>
    <deporte Atletismo />
    <nombre>Jesse Owens</nombre>
  <deportista>
    <deporte Natación />
    <nombre>Mark Spitz</nombre>
  </deportista>
</deportistas>
```

##### Práctica 2

```xml
<?xml version="1.0" encoding="UTF-8"?>
<pelicula>
  <titulo>Con faldas y a lo loco</titulo>
  <director>Billy Wilder</director>
</pelicula>
<pelicula>
  <director>Leo McCarey</director>
  <titulo>Sopa de ganso</titulo>
</pelicula>
<autor />barto</autor>
```

##### Práctica 3 - Texto

```xml
<?xml version="1.0" encoding="UTF-8"?>
<texto>
  <Titulo>XML explicado a os niños</titulo>
  <párrafo>O <abreviatura>XML</abreviatura>define cómo crear
  linguaxes de marcas.</párrafo>
  <párrafo>Las marcas se añaden a un documento de texto
  para añadir información.</párrafo>
  <http://>www.example.org</http://>
</texto>
```

##### Práctica 4 - Información xeográfica

```xml
<?xml version="1.0" encoding="UTF-8"?>
<geografia mundial>
  <pais>
    <pais>España</pais>
    <continente>Europa</continente>
    <capital></capital nombre="Madrid">
  </pais>
</geografia mundial>
```

##### Práctica 5 - Programas

```xml
<?xml version="1.0" encoding="UTF-8"?>
<programas>
  <programa nombre="Firefox" licencia="GPL" licencia="MPL" />
  <programa nombre="LibreOffice" licencia="LGPL" />
  <programa nombre="Inkscape" licencia=GPL />
</programas>
```

##### Práctica 6 - Mundiais de fútbol

```xml
<?xml version="1.0" encoding="UTF-8"?>
<mundiales-de-futbol>
  <mundial>
    <pais="España" />
    <1982 />
  </mundial>
</mundiales-de-futbol>
```

##### Práctica 7 - Medios de transporte

```xml
<?xml version="1.0" encoding="UTF-8"?>
<mediosDeTransporte>
  <bicicleta velocidad="v<100km/h" />
  <patinete velocidad maxima="50 km/h"
</mediosDeTransporte>

```

4. En los archivos de este repositorio se muestra el código en XML bien realizado.
5. El programa que utilizamos nos ayuda a detectar los errores, además nos permite validar el código y nos muestra donde están los errores.
6. En estos casos nos econtramos con errores de sintaxis en los que faltan etiquetas raíz, hay etiquetas sueltas, faltan etiquetas de cierre, hay espacios en los nombres de las etiquetas, atributos repetidos o carácteres mal escritos.
7. En el primer caso nos encontamos que la etiqueta <deportista> no está cerrada y los términos Atletismo y Natación están sueltos.
8. En el segundo caso nos encontramos que no hay una etiqueta raíz y falta una etiqueta de cierre en <autor> hay que añadir la etiqueta de cierre con la barra.
9. En el tercer caso las etiquetas de apertura y cierre están mal y no se permiten los caracteres ://
10. En el cuarto caso, nos encontramos con un espacio en la etiqueta y no está permitido.
11. En el quinto caso, hay atributos repetidos.
12. En el sexto caso las etiquetas necesitan tener un nombre.
13. En el séptimo caso el carácter <  sólo puede utilizarse para la apertura de la etiqueta.
14. Podemos consultar las dudas en la siguiente web: <https://www.mclibre.org/consultar/xml/ejercicios/documentos-bien-formados.html>
