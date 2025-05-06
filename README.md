# angy_study
Study guide for developer. En markdown (.md)

## Comandos basicos de git

- git add
- git commit
- git push
- git status
- git pull

- git merge
- `git checkout -b <branch_name>` (para crear nuevas ramas)
- `git checkout <branch_name>` (sin el flag `-b` es para cambiarse de ramas)

## Links

- https://www.atlassian.com/git
- https://learngitbranching.js.org/
- https://www.w3schools.com/git/

## Flujo/Flow

1. Agregamos o modificamos archivos localmente en la compu
2. Con `git add <nombre_archivo>` (Eg: `git add README.md `) --> lo que hacemos es ponerlo en `staging` (en tu git local)
3. Con `git commit -m "my mensage">` basicamente creamos un snapshot, captura de estado.
4. Con `git push` enviamos todos los commits a la nube, en este caso gith, tambien conocido como `origin/<branch_name>` (Eg: `origin/main`).
5. Con `git pull` nos bajamos de la nube todos los cambios pusheados o actualizados que otros developers hicieron.
6. Con `git status` vemos el estado de nuestros commits y sync con la nube.
