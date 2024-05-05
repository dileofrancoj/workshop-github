# Readme del proyecto

## Comandos básicos

```bash
ls (lista los elementos de un dir)
cd (cambia a otro directorio) cd Ejemplo
cd .. (vuelvo hacia atrás)
```

## Comandos de GIT
> Especial importancia a estos

```
 git init (le dice a git que empiece a controlar los cambios sobre la carpeta)
 
 git status : Estado actual del proyecto
 git add . : agregamos todos los archivos al staging

 git commit -m "un mensaje descriptivo"
 git log (muestra el historial completo de todos los commits)

 git log --oneline (muestra los commits con menos información)

 git reset [idDelCommit] --hard (vuelve al commit especificado y elimina los cambios hechos)

```

## Remotos
Un remoto es un repo online

## ¿Como agrego un remoto a mi repositorio local?

```
git remote add origin git@github.com:dileofrancoj/workshop-github.git

git remote -v (nos da info de los remotos)
git branch -M main
git add .
git commit -m "el mensaje que quieran"
git push -u origin main
```

## Clonar un repositorio
```
 git clone git@github.com:Chulevenom/calculadora-inversion.git
```

# Branches / Ramas

Una rama es una bifurcación de nuestro código
Nos sirve para ensayar o generar versiones alternativas de nuestro código principal

```
git checkout -b chore/modify-readme
```