# Clase 06 - Bootcamp

# Repaso GIT

## Comando para sacar del area intermedia lo que pusimos en add

```sh
git rm --cached <nombre del archivo>
```

# creo el respositorio de GIT
```sh
git init
```

# Listo el estado de los archivos
```sh
git status
```
# Haciendo un commit

1. Agrego al area de SA los archivos que necesito que formen parte del commit

```sh
git add <nombre de archivo>
git add . # agrega todos los archivos
```

2. Hago el commit

```sh
git commit -m "mensaje descriptivo del commit"
```

# Cambiar el editor por nano

```sh
git config --global core.editor nano
git config --global core.editor "code --wait"
```

# Ver listado  de commits que hice en el repo

```sh
git log # version larga
git log --oneline # version corta
```