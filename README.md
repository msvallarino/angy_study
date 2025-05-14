# angy_study
Study guide for developer. En markdown (.md)

## Comandos basicos de git

- git init
- git add: tried
- git commit: tried
- git push: tried
- git status
- git pull
- git init

- git merge
- `git checkout -b <branch_name>` (para crear nuevas ramas)
- `git checkout <branch_name>` (sin el flag `-b` es para cambiarse de ramas)
## Cambio

## Flujo/Flow

1. Agregamos o modificamos archivos localmente en la compu
2. Con `git add <nombre_archivo>` (Eg: `git add README.md `) --> lo que hacemos es ponerlo en `staging` (en tu git local)
3. Con `git commit -m "my mensage">` basicamente creamos un snapshot, captura de estado.
4. Con `git push` enviamos todos los commits a la nube, en este caso gith, tambien conocido como `origin/<branch_name>` (Eg: `origin/main`).
5. Con `git pull` nos bajamos de la nube todos los cambios pusheados o actualizados que otros developers hicieron.
6. Con `git status` vemos el estado de nuestros commits y sync con la nube.


## Links

- https://www.atlassian.com/git 
- https://learngitbranching.js.org/
- https://www.w3schools.com/git/


 (1) git add: -> git add file name <br>
 (2) git commit: -> git commit -m "commit name" -> any name <br>
 (3) git push: -> git push 

## git branches

- `main` (old `master`): son de production
- `qa` que son para los de QA o tester
- `dev` o `develop` que son de los desarrolladores para romper y subir lo que quieran

- nueva rama en git `new_feature` --> `git merge dev` --> `git merge qa` --> `git merge main`