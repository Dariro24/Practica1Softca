# Practica1Softca
## 1. Crear un repositorio en vuestro GitHub llamado Practica1Softca.
## 2. Clonar vuestro repositorio en local.
* Primero se clona el repositorio en local.`git@github.com:Dariro24/Practica1Softca.git`
* Luego nos ubicamos en la carpeta del proyecto: `cd Practica1Softca/`
* Agregamos los comandos usados al Readme.md

## 3.Agregar un commit.
```markdown
git add .
git commit -m "commit inicial"
```
## 4. Push al repositorio remoto
* git push origin main.
# 5. Crear una carpeta llamada `privada` y un archivo llamado `privado.txt`.
## 6. Realizar cambios para que el documento y la carpeta sean ignorados.
```markdown
git add .
git commit -m "añadido fichero .gitignore"
```
## 7. Crear un fichero `1.txt`.
```markdown
git add .
git commit -m "añadido 1.txt"
```
## 7. Crear un fichero `1.txt`.
```markdown
git add .
git commit -m "añadido 1.txt"
```
## 8. Crear el tag `v0.1`.
git tag v0.1
## 9. Subir el tag al repositorio remoto
git push --tag origin master
## 10. Crear una rama `v0.2` y posiciona tu carpeta de trabajo en esta rama.
```markdown
git branch v0.2
git checkout v0.2
```
## 11. añadir fichero `2.txt` en la rama `v0.2`.
```markdown
git add .
git commit -m "añadido 2.txt"
```
## 12. Subir los cambios al repositorio.
git push origin v0.2
## 13. Posicionarse en la rama `main`.
git checkout main
## 14. Hacer un merge de la rama `v0.2` en la rama `main`.
git merge v0.2 -m "merge v0.2 sin conflictos"
## 15.En la rama main poner Hola en el fichero `1.txt` y hacer commit.
```markdown
git checkout main
git add .
git commit -m "hola en 1.txt"
```
## 16. Posicionarse en la rama `v0.2` y poner Adios en el fichero `1.txt` y hacer commit.
```markdown
git checkout v0.2
git add .
git commit -m "adios en 1.txt"
```
## 17. Posicionarse de nuevo en la rama `main` y hacer un merge con la rama `v0.2`.
```markdown
git checkout main
git merge v0.2
git add .
git commit -m "arreglado merge en 1.txt"
```
## 18. Listar las ramas con merge y las ramas sin merge.
```markdown
git branch --merged
git branch --no-merged
```
## 19. Arreglar el conflicto anterior y hacer un commit.
```markdown
git branch --merged
git branch --no-merged
```
## 20. Crear un tag `v0.2`.
git tag v0.2
## 21. Borrar rama `v0.2`
git branch -d v0.2
## 22. Listar los distintos commits con sus ramas y sus tags.
```markdown
git config --global alias.list 'log --oneline --decorate --graph --all'
git list
```