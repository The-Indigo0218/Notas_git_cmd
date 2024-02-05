#Comandos en git

1. git branch -m <Name branch> // cambiar el nombre de una rama
2. git branch <nombre-de-la-rama> // para crear una rama
3. git status // ver el estado del proyecto de git
4. git add <Nombre fichero> // para agregar un fichero a git
5. git add -A // para agregar los ficheros pendientes a git
6. git commit -m "Contenido commit" // para agg un commit
7. git log // para ver los commit, id, autor y fecha
8. git log --graph --decorate --all --online //comando para ver mas estetico el log
9. git checkout <name fichero> // volver al ultimo cambio (agregaste algo pero quieres regresar al ultimo guardado)
10. git checkout -b <name branch> //crea una rama y cambia a ella
10. git checkout <id del commit> //Regresa los cambios hasta el commit elegido
11. git reset // para deshacer los cambios que no se guardaron
12. git reset <Name file> // para los cambios de ese archivo en especifico
13. git reset --hard <referente> // deshace el último commit y descarta todos los cambios realizados en el último commit.
14. git diff // muestra los cambios entre el ultimo commit y ahora
15. git reflog // el historia completo de las acciones en git, incluso despues del git reset --hard
16. git reset --hard <referente> // Mueve la rama a la referencia elegida, si el main esta en la id 1 pero quieres llevarla al id 2, usas git reset --hard 2
17. git checkout <id del commit> //tambien se usa para mover la cabeza, por ejemplo si luego de usar el reser hard quieres volver a un commit eliminado lo usas
