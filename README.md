COMANDOS git:

git init
- Inicializa un repositorio en la carpeta local donde nos situamos en la consola

git remote add origin https://github.com/magentaFire/leccion-12.git
-Linkea la carpeta donde estamos en la terminal con la dirección URL que le indicamos

git add .
-Prepara todos los archivos dentro de la carpeta donde se inicializó el repositorio local para comentarlos y luego subirlos

git commit -m "first commit"
-Agrega un comentario a las versiones nuevas que queremos subir al repositorio

git push -u origin master
-Sube los archivos que preparamos y comentamos desde "git add" y "git commit" al repositorio en el servidor de github
