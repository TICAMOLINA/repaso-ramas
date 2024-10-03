# Clase 06 - Bootcamp

## Repaso GIT

# Creo el repositorio de GIT

```sh
git init
```

# Listo el estado de los archivos


```sh
git status
```

# Haciendo un commit

1. Agrego al área de Staging los archivos que necesito que formen parte del Commit

```sh
git add <nombre archivo>
git add <nombre archivo> <nombre archivo>
git add . Como insertar comentario aca
```

2. Hago el commit

```sh
git commit -m "Mesaje descriptivo"
```

# Cambiar el editor por nano

```sh
git config --global core.editor nano
git config --global core.editor "code --wait"
```

```sh
git log # versión larga
git log --online # versión corta
```

# Agregar un remoto a mi repositorio local

```sh
git remote add origin <url-al-repo-remoto>
git remote add origin https://...
```

```sh
git remote -v
```
