



# Best practices

## Pull Request CookBook
Receta para realizar tu primer pull request paso a paso.

*Previo: Instalación de Git en nuestro equipo, creación de cuenta en github.


##Pasos:
1. Nos movemos a directorio raiz
1. Hacemos fork(Escaneado) al proyecto que vamos a clonar.
1. Clonamos el repo a nuestro local desde bash con el siguiente comando:
```
git clone (url obtenida después del fork)
```
1. Ubicamos en que rama nos encontramos con:
```
git branch -a  --> Muestra la rama virtual en la que nos encontramos.
git checkout -b miRamaNueva-->  Crea la nueva rama en la que estaremos trabajando.
```
1. Usamos pwd para revisar la ruta  en la que nos encontramos.
1. Vamos al archivo  que deseamos modificar en nuestro equipo y lo abrimos en algun editor (ej. sublime o atom) y realizamos las actualizaciones. Guardamos.
1. Regresamos a bash de git y tecleamos:
```
git status --> nos aparecerán los archivos que fueron modificados y están  listos para agregar.
```
1. Agregamos los archivos modificados al repositorio local con:
```
git add NOMBREARCHIVO.md
```
 	
1. Verificamos que el archivo haya sido agregado correctamente.
```
git status

```
	
1. Hacemos el commit (Snapshoot del estado actual de nuestra rama)
```
git commit-m "mensaje explicando que hace nuestra aportación"
```
	
1. Verificamos que el status sea "clean". Ya no hay modificaciones que realizar.
```
git status
```
	
1. Subimos a nuestro repositorio remoto las modificaciones que hicimos:
```
git push origin NombreRama (Origin toma el valor del origen del repositorio original a donde queremos subirlo).
```
	
1. Vamos a nuestro github, buscamos el registro de la modificacíón y presionamos "Pull Request"
1. Esperamos a que nos hagan comentarios o nos den Merge! :D

* Nota: 
Es importante hacer  "git pull origen ramaorigen" para jalar los cambios realizados hasta el momento antes de realizar el pull request.


