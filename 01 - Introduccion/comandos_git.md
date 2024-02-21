# Comando de git

## Comando para ver la version de git 
-git -v
-git --version

## Comando para configuracion inicial de git
- git config --global user.name "nombre"
- git config --global user.email "email"

## Comando para editar o ver la configuracion de git
para salir del edit ctrl + O y crtl + x y si es vim esc + :wq

- git config --global --edit
- git config --global --list

## Como iniciar git en un directorio
- git init


## Comando para saber el estado de nuestros archivos
-git  status

## Comando para listar las versiones de mi proyecto
- git log
- git log --oneline

## Comando para cambiar de version
- git checkout <nombre de la rama o id del commit>


## Pasos para crear una version de nuestro codigo
1. agregar todos los archivos al commit

- git add .
- git add *.js
- git add index.js

2. Tomar foto del codigo (crear una nueva version)
-git commit -m "nombre del commit" 


