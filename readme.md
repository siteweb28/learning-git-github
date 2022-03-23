# Comandos Utiles

1- git init = Va a iniciar el repository 
2- git add . = Va a tomar todos los archivos desde el ultimo commit o para el presente ejercicio desde el "git init" y prepararlos para una captura o mejor fotografia. (staging Area

3- git reset . = Revierte todo lo que hace el "git add", es decirle al archivo por favor bajate del escenario todavia no estas listo.
4- git commit -m = Es la foto ya tomada del archivo o primera version de mi programa. Podre regresar en el tiempo y mirar todo lo que esta ahi en modo "toma".

5- git checkout -- . = Reconstruye los archivos a como se encontraban en el ultimo "commit" (inclusive si borra el archivo) entre otras tareas que puede realizar este comando.
6- git log = Es para ver el listado de los "commit" haciendo scroll se puden vizualizar todos los demas, para este caso solo tenemos dos.

7- git commit --amend = Este comando se usa para arreglar el texto del ultimo "commit" (oprimir la tecla (i) para insertar nuevo texto) (para salir primero oprimir la tecla (escape), luego (:), seguido (w = write), seguido (q) para salir y por ultimo seguido el signo de admiracion (!) para que lo haga inmediatamente), y si ejecutas el comando de "git log" se podra ver corregido el error.
8- git checkout -b nombre-de-la-rama = la (b) es de branch, este comando sirve para crear nuevas ramas de trabajo y despues unirlas a la rama principal.

9- git checkout nombre de la rama = Este comando sirve para trasladarnos entre ramas.
10- git branch -d rama-localm = (la letra (d) es de delete) Este comando sirve para eliminar una rama que ya no se necesite. 

11- git push 