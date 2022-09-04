# Comandos básicos de GIT - Kevin

## Configuración de git

Específica de usuario

```
git config --global user.name "nombre"
git config --global user.email "email"
```

Habilitar la colorización

```
git config --global color.ui auto
```

Ver la configuracion

```
git config --list
```

Establecer un alias

```
git config --global alias.ci 'commit'
```

Autocorreción en git

```
git config --global help.autocorrect 1
```



## Repositorios

Iniciar un nuevo repositorio en tu directorio actual

```
git init
```

Clonar un repositorio remoto

```
git clone <https://repositorio>
```

Agregar archivos a la área de preparación (staging)

```
git add <nombre-del-archivo>
git add . #agrega todos los archivos
```

Agregar todo lo nuevo, cambios y ficheros eliminados a staging

```
git add -A
```

Hacer commit de los cambios con un mensaje

```
git commit -m "Mensaje de Kevin"
```

Subir los cambios al repositorio remoto que tengas en origin

```
git push
```

Subir los archivos a un repositorio remoto

```
git push origin main	
```

Subir los cambios a la rama indicada del repositorio remoto

```
git push origin <BRANCH>
```

Mostrar el estado del repositorio

```
git status -s
```

Mostrar el listado de commits

```
git log --graph --oneline --decorate
```

Traer cambios del repositorio remoto y hacer merge

```
git pull
```

Almacenar temporalmente el trabajo sin comentar

```
git stash
```

Verificar cambios en el repositorio remoto con el local

```
git fetch
```

Ver todos los repositorios remotos

```
git remote -v
```

Crear repositorio remoto y enlazarlo con repositorio local

```
git remote add <Nombre/Origin> <REPO_URL>
```

Eliminar el enlace al repositorio remoto

```
git remote rm <Nombre/Origin>
```

Cambiar URL del repositorio remoto

```
git remote set-url origin <REPO_URL>
```



## Ramas / Branches

Crear una nueva rama en local

```
git branch <nombre-de-la-rama>
```

Crear una nueva rama y posicionarse en ella

```
git checkout <nombre-de-la-rama>
```

Cambiar de rama

```
git checkout <nombre-de-la-rama>
```

Listar ramas

```
git branch
```

Eliminar una rama existente

```
git branch -d <nombre-de-la-rama>
```

Fusionar una rama dentro de otra rama

```
git merge
```



