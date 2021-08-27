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

Y tenemos que pushear los cambios a la rama develop [rama creada]

Cualquier cambio hecho en la rama no impactara en master hasta que hagamos un merge,
donde se combina los commits de un branch a otro.

Recordar hacer merge develop (rama de desarrollo) into master, para eso debemos tener seleccionado
la rama master y hacemos click en la rama develop y luego deberemos hacer un push para que se efectuen los cambios
a la rama master.

git checkout permite desplazarnos entre las ramas creadas por git branch

# Clonar un repositorio

1° Asegurarse estar en la carpeta donde queremos clonar el repositorio
2° Copiamos la URL del repositorio
3° git clone https://github.com/DiegoSanchez413/aprendiendo-git

# Pull

Cuando alguien hace cambios y hace un push al repositorio remoto, y necesitamos los archivos actualizados
requerimos de una actualización de repositorio [traer ultimos cambios]

# Tags

Los tags lo utilizamos para etiquetar las versiones del repositorio, crea un zip en el repositorio para descargar.
Y debemos hacer un push to origin, no olvidar.

# Git flow

Es una forma de trabajo, donde generamos features y release
Debemos ir a file > preferences > git flow > initialize git flow
Luego en la ventana del lado izquierdo apareceran opciones.

START

 - Feature : cuando implementamos una funcionalidad nueva y queremos que este separada de la rama develop
 - Release : lo pnemos cuando tenemos una app funcional

FINISH
 - Feature : Cuando terminemos de desarrollar la funcionalidad lo pondremos - puede que tengamos que eliminar el feature manualmente al terminar de remote y local.

 - Release : aqui le añadimos el tag