Para empezar descargamos la libreria de "https://github.com/mishoo/UglifyJS".

Con el comando npm install uglify-js nos instalara las dependencias necesarias para poder usar uglify y con el comando npm install uglify-js -g nos dejara usar uflify en la linea de comandos.

Creamos un archivo que queramos "Poner feo" como el que tengo creado. Y le pasamos esta linea de comando uglifyjs ArchivoBonito.js -c -o ArchivoConUglify.js La opcion -c lo que hace es comprimirnos el archivo y la -o nos da un archivo de salida, en nuestro caso: ArchivoConUglify.js

Tambien podemos conbinar dos archivos en un solo archivo y que nos lo muestre en una sola linea con el comando uglifyjs ArchivoBonito.js ArchivoBonito2.js -c -o ArchivoConbinado.js