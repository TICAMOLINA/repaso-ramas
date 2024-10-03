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

# Para ver si se agrego el repo remoto

```sh
git remote -v
```

# Subo al remoto el repositorio local

```sh
git push -u origin main # La primera vez
git push
```


# Para recuperar mi código
Ira al repositorio de Github, hacer click sobre el botón code y copiar la url a mi repositorio. Si pone ./ se va a clonar en el directorio actual. Si no lo ponen crea una carpeta con el nombre del repositorio y clona el remoto

```sh
git clone <url-al-repositorio>
git clone https://github.com/TICAMOLINA/repaso-ramas.git ./ # clona en el directorio actual
git clone https://github.com/TICAMOLINA/repaso-ramas.git # crea una carpeta (repaso-ramas) y clona el repositorio remoto al actual
```