Comandos practicados en orden para poder hacer la prueba:

1.-pwd para saber en donde me encuentro
2.-cd /c/Users/Nombre de usuario/Desktop si quiero ir al escritorio
3.-ls para listar el contenido
4.-mkdir y el nombre de la carpeta para crearla
5.-estando en ella escribir touch y el nombre del archivo para crear el index.html
   o se pueden crear varios archivos al mismo tiempo añadiendo más nombres con espacios entre medio
6.-estando en la carpeta principal del proyecto crear la carpeta Assets con mkdir 
7.-ir a Assets con cd Assets y con mkdir hacer las carpetas css, img y js
8.-ir a css escribiendo cd css y allí usar touch y el nombre del archivo para hacer el styles.css
9.-retroceder a Assets con cd .. e ir a js utilizando cd js y hacer el archivo index.js con touch
10.-en todos los casos comprobar los cambios con ls para verificar el contenido y si quiero eliminar un archivo escribo
   rm y el nombre del archivo para eliminar uno y para borrar una carpeta tengo que escribir rm -r y el nombre


Registro de lo hecho en Git Bash para el primer punto de la rúbrica:

Bruno@LAPTOP-PN8FNTNJ MINGW64 ~/Desktop/git_landing
$ mkdir Assets

Bruno@LAPTOP-PN8FNTNJ MINGW64 ~/Desktop/git_landing
$ ls
Assets/  index.html  style.css

Bruno@LAPTOP-PN8FNTNJ MINGW64 ~/Desktop/git_landing
$ cd Assets

Bruno@LAPTOP-PN8FNTNJ MINGW64 ~/Desktop/git_landing/Assets
$ mkdir css

Bruno@LAPTOP-PN8FNTNJ MINGW64 ~/Desktop/git_landing/Assets
$ ls
css/

Bruno@LAPTOP-PN8FNTNJ MINGW64 ~/Desktop/git_landing/Assets
$ mkdir img

Bruno@LAPTOP-PN8FNTNJ MINGW64 ~/Desktop/git_landing/Assets
$ ls
css/  img/

Bruno@LAPTOP-PN8FNTNJ MINGW64 ~/Desktop/git_landing/Assets
$ mkdir js

Bruno@LAPTOP-PN8FNTNJ MINGW64 ~/Desktop/git_landing/Assets
$ ls
css/  img/  js/

Bruno@LAPTOP-PN8FNTNJ MINGW64 ~/Desktop/git_landing/Assets
$ cd..
bash: cd..: command not found

Bruno@LAPTOP-PN8FNTNJ MINGW64 ~/Desktop/git_landing/Assets
$ cd ..

Bruno@LAPTOP-PN8FNTNJ MINGW64 ~/Desktop/git_landing
$ mv style.css Assets

Bruno@LAPTOP-PN8FNTNJ MINGW64 ~/Desktop/git_landing
$ cd Assets

Bruno@LAPTOP-PN8FNTNJ MINGW64 ~/Desktop/git_landing/Assets
$ ls
css/  img/  js/  style.css

Bruno@LAPTOP-PN8FNTNJ MINGW64 ~/Desktop/git_landing/Assets
$ mv style.css css

Bruno@LAPTOP-PN8FNTNJ MINGW64 ~/Desktop/git_landing/Assets
$ cd css

Bruno@LAPTOP-PN8FNTNJ MINGW64 ~/Desktop/git_landing/Assets/css
$ ls
style.css

Bruno@LAPTOP-PN8FNTNJ MINGW64 ~/Desktop/git_landing/Assets/css
$ cd ..

Bruno@LAPTOP-PN8FNTNJ MINGW64 ~/Desktop/git_landing/Assets
$ cd js

Bruno@LAPTOP-PN8FNTNJ MINGW64 ~/Desktop/git_landing/Assets/js
$ touch index.js

Bruno@LAPTOP-PN8FNTNJ MINGW64 ~/Desktop/git_landing/Assets/js
$ ls
index.js

Bruno@LAPTOP-PN8FNTNJ MINGW64 ~/Desktop/git_landing/Assets/js
$




Creación de archivo README.md:

Bruno@LAPTOP-PN8FNTNJ MINGW64 ~/Desktop/git_landing
$ touch README.md

Bruno@LAPTOP-PN8FNTNJ MINGW64 ~/Desktop/git_landing
$ ls
Assets/  README.md  index.html

Bruno@LAPTOP-PN8FNTNJ MINGW64 ~/Desktop/git_landing
$

Anotación: El nombre de usuario no es el mío porque ocupo una laptop que no es mía