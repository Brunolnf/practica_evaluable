git init: Inicializa un nuevo repositorio Git en el directorio actual.
git clone <URL>: Clona un repositorio Git existente desde una URL remota.
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
git fetch: Descarga los objetos y las referencias desde otro repositorio.
git config: Configura opciones de Git, como el nombre de usuario y el correo electrónico.
git rm <archivo>: Elimina un archivo del directorio de trabajo y del índice.
git mv <archivo_actual> <nuevo_nombre>: Cambia el nombre de un archivo y lo prepara para el commit.
git reset HEAD <archivo>: Elimina un archivo del área de preparación, pero lo mantiene en el directorio de trabajo.
git revert <commit>: Crea un nuevo commit que revierte los cambios realizados en un commit anterior.
git stash: Guarda temporalmente los cambios locales para poder trabajar en otra cosa.
git cherry-pick <commit>: Aplica los cambios de un commit específico a la rama actual.
git show: Muestra información detallada sobre un objeto Git, como un commit o un tag.
git tag: Crea, lista o verifica tags.
git blame <archivo>: Muestra quién modificó cada línea de un archivo y en qué commit se realizó el cambio.
git remote add <nombre> <URL>: Añade un nuevo repositorio remoto.
git remote remove <nombre>: Elimina un repositorio remoto.
git remote rename <nombre_actual> <nuevo_nombre>: Renombra un repositorio remoto.
git config --global alias.<nombre_alias> "<comando_original>": Crea un alias para un comando Git.
git log --oneline: Muestra el historial de commits en una sola línea por commit.
git log --graph: Muestra el historial de commits como un gráfico ASCII.
git log --author="<nombre>": Filtra el historial de commits por autor.
git log --since=<fecha>: Filtra el historial de commits por fecha.
git log --grep="<patrón>": Filtra el historial de commits por un patrón de búsqueda en los mensajes de commit.
git rebase <rama>: Reorganiza los commits de la rama actual sobre la rama especificada.
git rebase -i <commit>: Permite la edición interactiva de commits durante un rebase.
git bisect: Ayuda a encontrar el commit que introdujo un bug utilizando una búsqueda binaria.
git clean: Elimina archivos no rastreados del directorio de trabajo.
git log --stat: Muestra estadísticas resumidas de cambios en los archivos modificados en cada commit.
git log --decorate: Muestra los refs (ramas, tags, etc.) asociados a cada commit.
git log --pretty=format:"%h - %an, %ar : %s": Muestra el historial de commits con un formato personalizado.
git checkout -b <nueva_rama>: Crea una nueva rama y cambia a ella.
git branch -d <nombre_rama>: Elimina una rama localmente.
git push origin --delete <nombre_rama>: Elimina una rama en el repositorio remoto.
git remote -v: Muestra las URLs de los repositorios remotos configurados.
git remote show <nombre_remoto>: Muestra información detallada sobre un repositorio remoto.
git fetch <remoto>: Descarga objetos y referencias de otro repositorio.
git fetch --all: Descarga todos los objetos y referencias de todos los repositorios remotos.
git remote prune origin: Elimina las referencias locales a branches eliminados en el repositorio remoto.
git clean -n: Muestra qué archivos serían eliminados del directorio de trabajo.
git clean -f: Elimina los archivos no rastreados del directorio de trabajo de forma forzada.
git revert --no-commit <commit>: Deshace los cambios de un commit sin crear un nuevo commit.
git blame -L <inicio>,<fin> <archivo>: Muestra quién modificó las líneas específicas de un archivo.
git config --list: Muestra todas las configuraciones de Git.
git show <commit>: Muestra los cambios introducidos en un commit específico.
git show HEAD: Muestra los cambios introducidos en el commit más reciente.
git log --author="<nombre>" --oneline: Filtra el historial de commits por autor y muestra solo el hash y el mensaje.
git log --grep="<patrón>" --oneline: Filtra el historial de commits por un patrón en el mensaje y muestra solo el hash y el mensaje.
git log --since=<fecha> --until=<fecha>: Filtra el historial de commits por un rango de fechas.
git log --graph --all: Muestra un gráfico ASCII de todas las ramas.
git reset --hard <commit>: Revierte el estado del repositorio a un commit específico, eliminando todos los cambios posteriores.
git cherry-pick --continue: Continúa con el proceso de cherry-pick después de resolver conflictos.
git bisect start: Inicia una sesión de búsqueda binaria para encontrar el commit que introdujo un bug.
git bisect bad: Marca el commit actual como malo durante una búsqueda binaria.
git bisect good <commit>: Marca un commit como bueno durante una búsqueda binaria.
git bisect reset: Finaliza la sesión de búsqueda binaria y vuelve al estado original.
git stash list: Lista todas las entradas en el stash.
git stash apply: Aplica el último conjunto de cambios guardados en el stash.
git stash apply stash@{n}: Aplica un conjunto específico de cambios guardados en el stash.
git stash drop: Elimina el último conjunto de cambios guardados en el stash.
git stash clear: Elimina todos los conjuntos de cambios guardados en el stash.
git checkout -- <archivo>: Descarta los cambios locales en un archivo y lo restaura a la versión del último commit.
git clean -df: Elimina archivos y directorios no rastreados de forma forzada.
git tag -a <nombre_tag> -m "Mensaje": Crea un nuevo tag anotado con un mensaje.
git tag -d <nombre_tag>: Elimina un tag localmente.
git push origin --tags: Sube todos los tags locales al repositorio remoto.
git push origin <nombre_tag>: Sube un tag específico al repositorio remoto.
git describe --tags: Muestra el tag más reciente que contiene el commit actual.
git archive --format=zip --output=<nombre_archivo.zip> <rama>: Crea un archivo zip de una rama específica.
git log --follow <archivo>: Muestra el historial de cambios de un archivo incluso si ha sido renombrado.
git bisect visualize: Abre una interfaz gráfica para ayudar en la búsqueda binaria de commits.