# git_adsi

- GIT y GITHUB

comando                                         			// descripción de lo que hace

git add .						// guardar los cambios
git commit 						// aceptar los cambios
git status						// el estado de los cambios
git log 							// ver el estado de todos los cambios

git checkout -b NOMBRE DE LA RAMA               // crea una rama y se posiciona  en la rama para trabajar 

git checkout NOMBRE RAMA                      	// cambia a la rama o main
git branch 			               	                // muestra todas las ramas

git push --set-upstream origin NOMBRE RAMA      // esto es para subir la rama a git hub(creo q solo al principio)
git log --oneline --decorate --all --graph      // muestra todas las  ramas local y en github
git log --oneline                               // muestra en cada línea los comits resumidos
git merge RAMA A INTEGRAR                       // se unen las ramas  debe  estar ubicado  en la rama principal
git branch -d  NOMBRE RAMA                      // elimina la rama de forma local 
git add .                                       // agreg a todos los cambios a la stage 
git commit -m MENSAJE Q VA CON EL COMIT         // comando para hacer un comit
git pull origin master                          // Descarga la rama  principal más actualizada



----------------------------------ATENCIÓN-----------------------------------------
estos dos comandos sirven para borrar el HEAD usualmente 
es el último comit  y cuando se ejecuta este comando no se puede restaurar lo eliminado
(lo use para borrar un comit ya subido a github)


git reset HEAD^ --hard                          // tiene que estar sincronizados el local y necesita 
						//del comando git push origin -f   para borrar en remoto

git push origin -f                              // borrar en remoto
