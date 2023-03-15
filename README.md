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

### git commit
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

## .gitignore
Es un archivo que sirve para que git ignore ciertos archivos al hacer un add
Ejemplo, dentro del archivo .gitignore:
```
passwords.txt
build/
*.jpg
```