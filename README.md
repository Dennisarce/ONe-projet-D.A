# ONe-projet-D.A

Repositorio del informatorio para el grupo commonTec

------------0------------- Para iniciar sesion en la consola de comando

git config --global --unset user.name
git config --global --unset user.email

Para salir de la sesion en la consola

git config --global --unset-all

Realizar Click derecho dentro de la carpeta en la que quieras guardar tu repositorio

Click en Git Bash Here

//Este paso es solo para cuando queres crear un repositorio NUEVO, en este caso no se utilizaria

Para poder iniciar un nuevo repositorio
git init

Para poder comenzar primero realizar un git clone para poder realizar una copia del repositorio

git clone https://github.com/Mariano92m/commonTecInfo2016.git

Para verificar si los archivos estan actualizados realizar

git status

Una ves agregada una nueva carpeta o un nuevo archivo a la carpeta del repositorio realizar

git add nombredearchivo.txt (Se agrega un archivo en especifico)
git add . (Si se quiere agregar todos los archivos nuevos)

Luego colocar un comentario para los archivos agregados

git commit -m "Aqui agregar un mensaje"
git commit -a (Sirve para realizar comentarios automaticos)

Una ves terminado eso realizar un push

git push -u origin master (la palabra master puede variar dado a que se debe ingresar el nombre del branch)

Si desea controlar si el repositorio esta actualizado realizar

git checkout

Para ver los commits que se realizaron hacer

git log
