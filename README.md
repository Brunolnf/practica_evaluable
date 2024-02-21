- git init: Inicializa un nuevo repositorio Git en el directorio actual.
-
- git clone <URL>: Clona un repositorio Git existente desde una URL remota.
git add <archivo>: Agrega un archivo al área de preparación para ser incluido en el próximo commit.
git commit -m "Mensaje": Guarda los cambios confirmados en el repositorio con un mensaje descriptivo.
git status: Muestra el estado actual del repositorio, incluyendo archivos modificados, agregados y eliminados.
git diff: Muestra las diferencias entre los archivos en el directorio de trabajo y el área de preparación.
git log: Muestra el historial de commits del repositorio.
git branch: Lista todas las ramas en el repositorio.
git checkout <rama>: Cambia a la rama especificada.
git merge <rama>: Fusiona los cambios de una rama a la rama actual.
git pull: Obtiene y fusiona los cambios del repositorio remoto en la rama actual.
git push: Sube los commits locales al repositorio remoto.
git remote: Muestra los repositorios remotos configurados.
git reset HEAD <archivo>: Elimina un archivo del área de preparación, pero lo mantiene en el directorio de trabajo.
git revert <commit>: Crea un nuevo commit que revierte los cambios realizados en un commit anterior.
git stash: Guarda temporalmente los cambios locales para poder trabajar en otra cosa.
git cherry-pick <commit>: Aplica los cambios de un commit específico a la rama actual.
git show: Muestra información detallada sobre un objeto Git, como un commit o un tag.
git tag: Crea, lista o verifica tags.
git remote add <nombre> <URL>: Añade un nuevo repositorio remoto.
git remote remove <nombre>: Elimina un repositorio remoto.
git remote rename <nombre_actual> <nuevo_nombre>: Renombra un repositorio remoto.
git log --oneline: Muestra el historial de commits en una sola línea por commit.
git log --graph: Muestra el historial de commits como un gráfico ASCII.
git log --author="<nombre>": Filtra el historial de commits por autor.
git log --since=<fecha>: Filtra el historial de commits por fecha.
git log --grep="<patrón>": Filtra el historial de commits por un patrón de búsqueda en los mensajes de commit.
git clean: Elimina archivos no rastreados del directorio de trabajo.
git log --stat: Muestra estadísticas resumidas de cambios en los archivos modificados en cada commit.
git log --decorate: Muestra los refs (ramas, tags, etc.) asociados a cada commit.
git log --pretty=format:"%h - %an, %ar : %s": Muestra el historial de commits con un formato personalizado.
git checkout -b <nueva_rama>: Crea una nueva rama y cambia a ella.
git branch -d <nombre_rama>: Elimina una rama localmente.
git push origin --delete <nombre_rama>: Elimina una rama en el repositorio remoto.
git remote -v: Muestra las URLs de los repositorios remotos configurados.
git remote show <nombre_remoto>: Muestra información detallada sobre un repositorio remoto.
git remote prune origin: Elimina las referencias locales a branches eliminados en el repositorio remoto.
git clean -n: Muestra qué archivos serían eliminados del directorio de trabajo.
git clean -f: Elimina los archivos no rastreados del directorio de trabajo de forma forzada.
git revert --no-commit <commit>: Deshace los cambios de un commit sin crear un nuevo commit.
git show <commit>: Muestra los cambios introducidos en un commit específico.
git show HEAD: Muestra los cambios introducidos en el commit más reciente.
git log --author="<nombre>" --oneline: Filtra el historial de commits por autor y muestra solo el hash y el mensaje.
git log --grep="<patrón>" --oneline: Filtra el historial de commits por un patrón en el mensaje y muestra solo el hash y el mensaje.
git log --since=<fecha> --until=<fecha>: Filtra el historial de commits por un rango de fechas.
git log --graph --all: Muestra un gráfico ASCII de todas las ramas.
git reset --hard <commit>: Revierte el estado del repositorio a un commit específico, eliminando todos los cambios posteriores.
git checkout -- <archivo>: Descarta los cambios locales en un archivo y lo restaura a la versión del último commit.
git push origin --tags: Sube todos los tags locales al repositorio remoto.
git push origin <nombre_tag>: Sube un tag específico al repositorio remoto.
git log --follow <archivo>: Muestra el historial de cambios de un archivo incluso si ha sido renombrado.
git clone <URL_del_repositorio> practica_evaluable_2: Clona un repositorio remoto en un directorio local.
git checkout -b mirama: Crea una nueva rama y cambia a ella.
git add documento1.txt: Agrega un archivo al área de preparación.
git commit -m "Mensaje": Guarda los cambios confirmados en el repositorio con un mensaje descriptivo.
git push origin mirama: Sube los commits locales al repositorio remoto en una rama específica.
git checkout main: Cambia a la rama principal del repositorio.
git merge mirama: Fusiona los cambios de una rama en la rama actual.
git branch -d mirama: Elimina una rama localmente.
git push origin main: Sube los commits de la rama principal al repositorio remoto.
git merge main: Fusiona los cambios de la rama principal en la rama actual.
git push origin main: Sube los commits fusionados al repositorio remoto.
git checkout -b mirama: Crea una nueva rama y cambia a ella.
git add documento2.txt: Agrega un archivo al área de preparación.
git commit -m "Mensaje": Guarda los cambios confirmados en el repositorio con un mensaje descriptivo.
git merge main: Fusiona los cambios de una rama en la rama actual.
git push origin mirama: Sube los commits de la rama actual al repositorio remoto en una rama específica.
git pull origin main: Obtiene y fusiona los cambios del repositorio remoto en la rama actual.
git add README.md: Agrega un archivo al área de preparación.
git commit -m "Mensaje": Guarda los cambios confirmados en el repositorio con un mensaje descriptivo.
git pull origin main: Obtiene y fusiona los cambios del repositorio remoto en la rama actual.
git push origin main: Sube los commits de la rama actual al repositorio remoto.
PRACTICA
mkdir practica_evaluable: Crea un directorio llamado "practica_evaluable".
cd practica_evaluable: Cambia al directorio "practica_evaluable".
git init: Inicializa un nuevo repositorio Git en el directorio actual.
touch documento1.txt documento2.txt: Crea dos archivos llamados "documento1.txt" y "documento2.txt".
echo "Texto para documento 1" >> documento1.txt y echo "Texto para documento 2" >> documento2.txt: Añade texto a los archivos "documento1.txt" y "documento2.txt", respectivamente.
git add documento1.txt documento2.txt: Añade los archivos "documento1.txt" y "documento2.txt" al área de preparación de Git.
git commit -m "Mensaje de commit": Crea un nuevo commit con los cambios preparados y les asigna un mensaje descriptivo.
git reset --hard HEAD~1: Regresa al estado anterior al último commit realizado, eliminando los cambios.
git remote add origin <URL_del_repositorio_remoto>: Conecta el repositorio local con un repositorio remoto en GitHub.
git push -u origin main: Sube los cambios del repositorio local al repositorio remoto en la rama principal (main).
git checkout -b nombre_rama: Crea una nueva rama y cambia a ella.
git tag nombre_etiqueta: Crea una nueva etiqueta en el commit actual.
git clone <URL_del_repositorio_remoto> directorio_local: Clona un repositorio remoto en un directorio local.
git branch -d nombre_rama: Borra una rama local.
git merge nombre_rama: Fusiona los cambios de una rama en otra.
git push origin nombre_rama: Sube los cambios de una rama local al repositorio remoto.
echo "Texto" >> archivo.txt: Añade texto al final de un archivo.
git push origin main: Sube los cambios de la rama principal al repositorio remoto.
git merge nombre_rama: Fusiona los cambios de una rama en otra.
git push origin main: Sube los cambios de la rama principal al repositorio remoto.
git add nombre_archivo: Añade un archivo al área de preparación.
git commit -m "Mensaje de commit": Crea un nuevo commit con los cambios preparados y les asigna un mensaje descriptivo.
git push origin main: Sube los cambios de la rama principal al repositorio remoto.
git push --tags: Sube las etiquetas al repositorio remoto.
