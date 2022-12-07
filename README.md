# Comandos utiles de Git

1. git init
2. git add .  prepara para la fotografia todos los archivos modificados desde el ultimo commit
3. git reset .  revierte lo que hace el git add
4. git commit -m 
5. git checkout -- .  para regresar al ultimo commit
6. git log  muestra un listado de los commits
7. git commit --amend  para arreglar el mensaje de un commit (letra I para cambiar el mensaje) (ESC :wq! para salir)
8. git checkout -b rama-heroes  para crear una nueva rama (git branch para ver en que rama estoy trabajando)
9. git checkout master  para volver a la rama master
10. git merge rama-heroes  para unir esa rama a la master
11. git branch -d rama-heroes  para eliminar la rama rama-heroes
12. git push  para aplicar los cambios al repositorio remoto ( GitHub)
13. git commit -am  para evitar escribir siempre add y commit