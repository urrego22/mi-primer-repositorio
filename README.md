# mi-primer-repositorio
Sara García urrego
Aprendi que Git se trabaja desde servidores locales y git hub trabaja desde la nube con internet, Git es una herramienta local para control de versiones y Git hub es una plataforma en la nube para almacenar y trabajar con repositorios
git config --global user.name "Tu Nombre": Define tu nombre para que Git lo use en tus commits.

git config --global user.email "tuemail@ejemplo.com": Define tu correo electrónico para que Git lo use en tus commits.

git config --list: Muestra la configuración actual de Git.

2. Iniciar un repositorio
git init: Inicializa un nuevo repositorio Git en la carpeta actual.

git clone <URL>: Clona un repositorio remoto (por ejemplo, desde GitHub) a tu computadora.

3. Trabajar con cambios
git status: Muestra el estado de los archivos en tu repositorio (qué archivos han cambiado, cuáles están listos para commit, etc.).

git add <archivo>: Añade un archivo específico al área de preparación (staging area).

git add .: Añade todos los archivos modificados al área de preparación.

git commit -m "Mensaje descriptivo": Guarda los cambios en el repositorio con un mensaje descriptivo.

git diff: Muestra las diferencias entre los archivos modificados y la última versión guardada.

git restore <archivo>: Descarta los cambios en un archivo y lo restaura a la última versión guardada.

4. Ver el historial
git log: Muestra el historial de commits (con detalles como autor, fecha y mensaje).

git log --oneline: Muestra el historial de commits en una sola línea por commit.

git show <commit_id>: Muestra los detalles de un commit específico.

5. Ramas (branches)
git branch: Muestra la lista de ramas en el repositorio.

git branch <nombre_rama>: Crea una nueva rama.

git checkout <nombre_rama>: Cambia a la rama especificada.

git checkout -b <nombre_rama>: Crea una nueva rama y cambia a ella.

git merge <nombre_rama>: Fusiona la rama especificada con la rama actual.

git branch -d <nombre_rama>: Elimina una rama (si ya está fusionada).

6. Trabajar con repositorios remotos
git remote add origin <URL>: Conecta tu repositorio local con un repositorio remoto (por ejemplo, en GitHub).

git push origin <nombre_rama>: Sube los cambios de la rama local al repositorio remoto.

git pull origin <nombre_rama>: Descarga los cambios del repositorio remoto y los fusiona con tu rama local.

git fetch: Descarga los cambios del repositorio remoto, pero no los fusiona.

7. Deshacer cambios
git reset <commit_id>: Deshace commits y devuelve el repositorio a un estado anterior (sin eliminar los cambios locales).

git reset --hard <commit_id>: Deshace commits y descarta todos los cambios locales.

git revert <commit_id>: Crea un nuevo commit que deshace los cambios de un commit anterior.

8. Etiquetas (tags)
git tag <nombre_tag>: Crea una etiqueta en el commit actual (útil para marcar versiones).

git tag -a <nombre_tag> -m "Mensaje": Crea una etiqueta anotada con un mensaje.

git push origin <nombre_tag>: Sube una etiqueta al repositorio remoto.

9. Limpieza y mantenimiento
git clean -n: Muestra qué archivos no rastreados serán eliminados (simulación).

git clean -f: Elimina archivos no rastreados del directorio de trabajo.

git gc: Realiza una limpieza y optimización del repositorio.

10. Comandos útiles adicionales
git stash: Guarda temporalmente los cambios no commitidos para cambiar de rama.

git stash pop: Recupera los cambios guardados con git stash.

git rebase <nombre_rama>: Reorganiza los commits de una rama sobre otra.

Ejemplo de flujo de trabajo típico
git clone <URL>: Clona un repositorio.

git checkout -b nueva-rama: Crea y cambia a una nueva rama.

git add .: Añade los cambios al área de preparación.


git commit -m "Mensaje": Guarda los cambios.

git push origin nueva-rama: Sube los cambios al repositorio remoto.

git pull origin main: Actualiza tu rama local con los últimos cambios de la rama principal.



[Explorando GIT y GIT (1).docx](https://github.com/user-attachments/files/19096753/Explorando.GIT.y.GIT.1.docx)
diapositivas: https://www.canva.com/design/DAGg4ihaOJw/fvDGYibr_DK8o7_hbWVO0w/view?utm_content=DAGg4ihaOJw&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h0d97633694
