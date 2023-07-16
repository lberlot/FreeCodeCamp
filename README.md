# GIT

git add . => Agrega todos los archivos a area de staging.

git add <file-name> => Agrega ese archivo al area de staging.

git status => Te dice los cambios en tu rama actual.

git commit -m 'Mensaje de commit relacionado a que cambio se hizo.' => Los cambios ya en area de staging, los etiqueto con un mensaje de que se cambió.

git push origin <branch-name> => Subis de tu local "origin", a la rama remota que especifiques. Vease azure, github, etc.

git pull origin <branch-name> => Trae de esa rama remota, los cambios a tu local.

git branch -D <branch-name> => Borra la rama especificada.

git log --oneline => Muestra historial de commits resumido.

git commit --amend => Corrige el ultimo commit, y al hacerlo cambia el hash del mismo.

git reset --hard => Deshace todos los cambios, borrandolos.

git reset --soft => Deshace todos los cambios, dejandolos sin trackear.