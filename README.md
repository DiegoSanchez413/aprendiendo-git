# Para iniciar un repositorio
git init

# Para ver los cambios
git status

# Para agregar archivos que no están en el tracking
git add index.html

- Para agregar todos los archivos
git add --all
# Commits -> confirmaciones de cambio
git commit -m "Se creo el archivo index"

# Asignar un repositorio remoto , en este caso Github
git remote add origin https://github.com/DiegoSanchez413/aprendiendo-git.git

# Branch 
Cuando creamos un branch debe ser en base al estado de otro branch
Y tenemos que pushear los cambios a la rama develop (rama creada)