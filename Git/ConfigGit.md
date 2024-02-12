#Pasos pasa configurar git

1. git config --global user.name "your name here" // para configurar git y el nombre de usuario
2. git config --global user.email "your email here" // para configurar git y el correo del usuario
3. git init // Crea un repositorio vacio de git
4. git config --global init.defaultBranch <name branch> // Estable como se llamara la rama principal por defecto
5. git config --global alias.<Alias> "Comando" //Para crear un alias a un comando
6. crea un .gitignore para los archivos que no quieras guardar en git


<----------   En caso de que haya un conflicto entre los repo, usa  --------------->
git remote set-url origin git@github.com-"Nombre usuario":"Nombre Usuario"/"Nombre Repo".git
