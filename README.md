## Sitio Web first-code
https://dannylarrea.github.io/first-code/
- - - -
## 30 de septiembre y 1 de octubre :white_check_mark:
Comandos Git:
```git
    git clone HTTPS
    git pull
    git checkout gh-pages 
    git add -A
    git commit -m "mensaje de subida"
    git push origin gh-pages
```

## 7 y 8 de octubre :mega:
Objetivo:
![picture alt](https://raw.githubusercontent.com/dannylarrea/reread-php/master/BackupRandom/form.png "formulario: autor y país")

Pasos:
1. Generar la estructura de directorios y ficheros del proyecto:
    ```JS
    first-code
        - css/
            styles.css
        - img/
        - view/
        - index.html
    ```
2. Copiar la estructura y los estilos del recurso [CSS Website Layout](https://www.w3schools.com/css/tryit.asp?filename=trycss_website_layout_grid "código fuente") (w3schools.com).
3. Separar los estilos CSS del HTML.
    ```HTML
    <link rel="stylesheet" type="text/css" href="css/styles.css">
    <!--
    Los estilos externos son definidos con la etiqueta <link>,
    dentro de la sección <head> de la página HTML:
    -->
    ```
4. Editamos el proyecto:
    - Añadimos un título a la página
        ```HTML
        <title>First Code</title>
        ```
    - Nos quedamos únicamente con una columna que ocupe el 100% de ancho de la página.
        ```CSS
        width: 100%;
        ```
    - Damos más relleno (en porcentaje) a los laterales izquierdo y derecho de la columna principal. Damos más relleno (en píxeles) al lateral superior y al inferior.
        ```CSS
        padding: top left right bottom;
        ```
    - Eliminamos el menú de navegación (HTML y estilos asociados).
    - Vamos a darle una altura de la mitad de la vertical de la página al encabezado ```class="header"```.
        ```CSS
        height: 50vh;
        ```
    - Cambiamos el estilo ```font-family``` y el tamaño ```font-size``` de fuente al encabezado ```class="header"```.
        - [Google Fonts](https://fonts.google.com/ "fuentes")
    

- - - -
Extensiones interesantes para VSC:
- JS-CSS-HTML Formatter
- IntelliSense for CSS class names in HTML
