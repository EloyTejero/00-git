# Apunte sobre GIT

## Comandos Básicos

### git init
Inicializa la carpeta para git
```bash
    git init 
```

### git add
Agrega el archivo al commit
```bash
    git add miArchivo.txt 
```

### git commit / commit --amend
Confirmar un conjunto de cambios provisionales de forma permanente
```bash
    git commit -m "texto" 
    git commit --amend  # modificar el ultimo commit
```

### git status
Muestra el estado de los archivos de la carpeta
```bash
    git status  
```

### git log
Muestra el registro de commits
```bash
    git log 
```

### git clone
clona el repositorio en el servidor a tu carpeta
```bash
    git clone [url del repositorio].git #si no se agrega el .git se agrega automaticamente
```

### git pull
Se emplea para extraer y descargar contenido desde un repositorio remoto y actualizar al instante el repositorio local para reflejar ese contenido.
```bash
    git pull [url del repositorio]
```

## .gitignore
Es un archivo que sirve para que git ignore ciertos archivos al hacer un add
Ejemplo, dentro del archivo .gitignore:
```
passwords.txt
build/
*.jpg
```

## git branchs
```bash
    git branch [branch name] #Crea una nueva rama
    git checkout [branch name] #Cambia el HEAD a una rama
    git checkout -b [branch name] #Crea una nueva rama y cambia el HEAD a la misma. Version corta de los dos comandos anteriores
    git merge [branch name] #Fusiona una rama con la actual del HEAD
    git branch -d [branch name] #Elimina una rama

```