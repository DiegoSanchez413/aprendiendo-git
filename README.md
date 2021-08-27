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
 - HotFixes : cuando requerimos urgentemente arreglar unos bugs

FINISH
 - Feature : Cuando terminemos de desarrollar la funcionalidad lo pondremos - puede que tengamos que eliminar el feature manualmente al terminar de remote y local.

 - Release : aqui le añadimos el tag [no olvidar hacer push en el tag tambien]
 - HotFixes :

 Markdown
 
# Cabeceras
## Cabecera H2
### Cabecera H3
##### Cabecera H4

###### Cabecera H5

# Underlines
Underline1
----------

Underline2
==========

# Formatos de enfasis
- *formato italica 1*
- _formato italica 2_
- **formtato bold o strong 1**
- __formtato bold o strong 2__
- ~~formato tachado con alt 126.~~

# Listas
1. Esto es un item ordenado 
2. Esto es un item ordenado
3. Esto es un item ordenado
4. Esto es un item ordenado
5. Esto es un item ordenado

- item de lista desordenada
- item de lista desordenada
- item de lista desordenada

# Links
- [Google](https://www.google.com/)
- [Index](index.html)

# Imagenes
![Logo de fb](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAHcAAAApCAMAAAA4Y0Y/AAAAbFBMVEVIZ6r///9FZan5+vw1WqQ6XaZBYqg9X6cyWKMtVaLw8ffq7fTl6PLK0eNnfrYpU6FddrK/x95XcrCYpsuHmMORoMjX3OrQ1ubFzOG3wNrd4e2os9JRba2hrc+Bk8Gxu9d2irwcTJ4ORpxuhLlApouHAAADVklEQVRYhe2V2bKjOAyGwXsMwSwBwpKQdN7/HVu/WPp0T5LD1HTV3EQXgLGsz5IlOYo+8pGPfOQ/ivg3unuVv1fUZhx3GnPK7FNUpPgeLKKjjOP4tMegSb1M1R5s76W3b1Wcj+O9XEuKqduheCBXvH6nYer4f+HagmxV97Dr3P4iVx/JVr4zSf8e1x7ALbUlslFIV2Mt+y6sck7z5/Y1c0lPr+Exm9KyRMHSxiVj9plPZTelZKubuky4uk2bOlymabCRcI+uSfszHbuNhpa+rk7M3B9Vkx5P7LUxF0zVjm27jJY0XeY2rj1NU3f9J1hk8SqZ7vld0Mu7yDTrf7UkXtxb5vYtj1ryxp6WKZ+Ty+q8jI5q4YoRwycN5AvXFMsHrUicWrE+XPmFYjsrG/+SyZrbNpAiUsU2OquZ65pXhZIXXQInu05gwZBdAUgODKuyrKoOOIdHCAO9Ruamt0fHO3WYKrIbAjXpHP/qrEYTygK4Dlaap2kobEB0RuUQsnMQ9gHuHXuvlRDGlgjc3dqArSuOmxEBsb4hin0QxnBcsLFKCT6W6Q4u4PH4olSWOrJYVlNIHHPhAieiwD6aYRguZGTgyQPlUwUI3KEUjBxrH2eIwEbbH6SdIirVq2b5lXv6jXvggPw6w4WL+uUmVyFEF7LLyWAQAraIjYILb5PwAvuG6zaunCW+bNzqK5fTx4KLa21cuSksX1/1wYXLHgyabifm4mdGS4RBuhROkBjDdRSTCwohvKIYzrSLQLkoHX7dqO1gowWfL7SleX++XFGyDJwxSYA/iTgEk2lEzCitDzYTzO3ugctvVJJT/Y5QtVwCqQ4aSX7ifGYrxYtrc+3PCvrxfCcmzkh++7i/T/hqi2MaN0v9Stai0cBLWJXaXcJL+LHUb+AafB7plbu2EJ8y97HmUrS1EModcOd2RbGhvR7XmYpOqJTxNrX0KxyS1E8jbQvvJe4jkwPQR633vYrMWMAr2ZZCVRwKmU7CeO+nDMO2hBuqxrdsHrh6jOiwxBfUGF1CVmykBzI+PC8lq/V8YQkV5aMSNIai0HbMS4PToUeel8LRbUG6xqgxF2p2gqbKch2QqTEfZ2t6tgrj39/sf3Zwsf0Q4re5r4M/Zr6FfOQjH/nIfvkJaaIsEa/B1HwAAAAASUVORK5CYII=)

# Code Snippets
##### En el JSON debemos colocar el lenguaje que querramos presentar
### Ejemplo de un JSON
```JSON
[
  {
    "name": "Molecule Man",
    "age": 29,
    "secretIdentity": "Dan Jukes",
    "powers": [
      "Radiation resistance",
      "Turning tiny",
      "Radiation blast"
    ]
  },
  {
    "name": "Madame Uppercut",
    "age": 39,
    "secretIdentity": "Jane Wilson",
    "powers": [
      "Million tonne punch",
      "Damage resistance",
      "Superhuman reflexes"
    ]
  }
]
```

# Tablas
| Nombre | Apellido | Documento|
|--------|----------|--------- |
|Diego   | Smith    |1258941   |


# Citas
Esto es un texto referente a una cita que pondremos debaj:
> Esto es una cita.

Texto que no se relaciona.
> Esto tabmien es una cita.

# Lineas Horizontales
Esto es un texto que sera dividido.

---

Esto es otro texto dividido.
***

Otro texto
___

# Saltos de línea
Primer parrafo.

Segundo parrafo.

Tercer parrafo.