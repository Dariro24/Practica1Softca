# Practica1Softca
## 1. Crear un repositorio en vuestro GitHub llamado Practica1Softca
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
* `git push origin main` 
# 5. Crear una carpeta llamada `privada` y un archivo llamado `privado.txt`
## 6. Realizar cambios para que el documento y la carpeta sean ignorados.
```markdown
echo "privado.txt" > .gitignore
echo "/privada" > .gitignore
git add .
git commit -m "añadido fichero .gitignore"
```
## 7. Crear un fichero `1.txt`
```markdown
git add .
git commit -m "añadido 1.txt"
```