#Comandos de Git

Para clonar un repositorio usamos:
'''
git clone
'''

Para subir un archivo o archivos a nuestro repoitorio remoto, seguimos el método ACP:
'''
A -> git add (seleccionas que archivos vas a enviar del repositorio local al remoto)

C -> git commit (nombre o comentario que vas a escribir cuando lo vas a enviar ---ser 
descriptivo con lo que estamos haciendo)

P -> git push (empujar al repositorio remoto)
'''

Para verficar que archivos son nuevos o tienen cambios, ejecutamos un:
'''
git status
'''
## 🚀Paso 01 flujo ACP (add)
Selecciono que voy a subir
'''
git add <nombre_archivo>

git add . (<selecciona todos los archivos que sufrieron cambios>)
'''

## 🚀Paso 02 flujo ACP (commit)
Escribimos el comentario con que se subirá este archivo a git. Debe sintetizar todo lo que hemos hecho en pocas palabras.
'''
git commit -m "Comentario"
'''

## 🚀Paso 03 flujo ACP (push)
Enviamos los cambios de nuestro repositorio local al repositorio remoto.
'''
git push origin <nombre_rama>
'''

Gracias porvisitar nuestra documentación 💚