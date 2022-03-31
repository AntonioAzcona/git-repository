# Comandos útiles de Git

1. git init                - Inicializa un repositorio
2. git add .               - Agrega y prepara todos los archivos nuevos (en el stage) para un 
                          commit
3. git reset .             - Deshace lo que se agregó con el git add . 
4. git commit -m           - Agrega al repositorio los archivos
5. git checkout -- .       - Todos los archivos que se encuentran en el repositorio se 
                             reconstruyen a como se encontraban en el último commit 
6. git log                 - Muestra el historial de commits
7. git commit --amend      - Para arreglar el nombre de un commit
                          (Presionar i para poder modificar y para guardar presionar esc + :wq!)
8. git checkout -b rama    - Crea y se cambia a una rama
9. git checkout master     - Se pasa a la rama principal
10. git merge               - Fusiona los cambios entre ramas
11. git branch -d rama      - Borra la rama

12. git remote add origin url   -   Agrega la rama a remoto
13. git branch -M main      - Renombra la rama master a main
14. git push -u origin main - Sube cambios al main

15. git push                - Sube los cambios

