## Sitio Web first-code
https://dannylarrea.github.io/first-code/
- - - -
## 30 de septiembre y 1 de octubre :white_check_mark:
Comandos de Git
```git
    git clone HTTPS
    git pull
    git checkout gh-pages 
    git add -A
    git commit -m "mensaje de subida"
    git push origin gh-pages
```

## 7 y 8 de octubre :mega:
Evolucionamos la página estática asociada al proyecto [reread](https://dannylarrea.github.io/reread "Proyecto HTML reread") a una página dinámica utilizando ```PHP``` y una [BBDD](https://github.com/dannylarrea/reread-php/blob/dev/db/reread.sql)
- Cambiamos la extensión de los ficheros .html a .php :bangbang: las rutas que se utilizan dentro de los ficheros también se han de cambiar!!
- Asociamos la base de datos con el proyecto, para ello creamos el **connection.php**
- Editamos el fichero **ebooks.php**: pintamos (con la ayuda del ```echo```) las [imágenes de los libros](https://github.com/dannylarrea/reread-php/tree/dev/img) recuperadas mediante una consulta en la base de datos

## Semana del 28 de septiembre - 2 de octubre del 2020 (evolutivo a desarrollar) :mega:
**PHP**
1. Una vez realizado correctamente los cambios de la primera semana de clases, se ha de crear un **pull request** de ```dev → master``` para actualizar la rama master con el código final de dev
2. Hacer dinámico el apartado **Top ventas** (columna de la derecha):
    - Crear una nueva rama en GitHub para el desarrollo: **topventas** (recordad en local hacer ```git pull``` para bajar la rama)
    - Se ha de implementar este evolutivo en los tres ficheros .php:
        - index.php
        - libros.php
        - ebooks.php