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
<<<<<<< HEAD
Y tenemos que pushear los cambios a la rama develop (rama creada
Cualquier cambio hecho en la rama no impactara en master hasta que hagamos un merge,
donde se combina los commits de un branch a otro.

Hacer git checkout es cuando cambiamos de rama.

Recordar hacer merge develop (rama de desarrollo) into master, para eso debemos tener seleccionado
la rama develop y hacemos click en la rama master.
=======
>>>>>>> master
