Receta para hacer un pull request
Previo: Instalación de Git en nuestro equipo, creación de cuenta en github.

1.-Nos movemos a directorio raiz
2.- Hacemos fork(Escaneado) al proyecto que vamos a clonar.
3.-Clonamos el repo a nuestro local desde bash con el siguiente comando:
	git clone (url obtenida después del fork)
4.-Ubicamos en que rama nos encontramos con:
	git branch -a  --> Muestra la rama virtual en la que nos encontramos.
	git checkout -b miRamaNueva-->  Crea la nueva rama en la que estaremos trabajando.
5.-Usamos pwd para revisar la ruta  en la que nos encontramos.
6.-Vamos al archivo  que deseamos modificar en nuestro equipo y lo abrimos en algun editor (ej. sublime o atom) y realizamos las actualizaciones. Guardamos.
7.-Regresamos a bash de git y tecleamos:
	git status --> nos aparecerán los archivos que fueron modificados y están  listos para agregar.
8.-Agregamos los archivos modificados al repositorio local con:
 	git add NOMBREARCHIVO.md
9.-.-Verificamos que el archivo haya sido agregado correctamente.
	git status.
10.-Hacemos el commit (Snapshoot del estado actual de nuestra rama)
	git commit-m "mensaje explicando que hace nuestra aportación"
11.-Verificamos que el status sea "clean". Ya no hay modificaciones que realizar.
	git status
12.-Subimos a nuestro repositorio remoto las modificaciones que hicimos:
	git push origin NombreRama (Origin toma el valor del origen del repositorio original a donde queremos subirlo).
13.-Vamos a nuestro github, buscamos el registro de la modificacíón y presionamos "Pull Request"
14.- Esperamos a que nos hagan comentarios o nos den Merge! :D

