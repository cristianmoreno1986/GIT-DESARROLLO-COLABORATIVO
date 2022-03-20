# Vinculación con nuestra cuenta de GITHUB

# Cuando quiero guardar una carpeta vacia necesito crear un archivo de tipo **.gitkeep**

# .gitignore sirve para descartar archivos no deseados

# Log

## Para mostrar las dos ultimas líneas de los commit

```sh
git log --oneline 2 
```

# GIT BRANCH

## Creo rama

```sh
git branch <nombre de la rama>
```

## Listo ramas

```sh
git branch
```

## Cambio de rama

```sh
git switch <nombre de la rama>
```

## Eliminar una rama

```sh
git branch -d <nombre de la rama>
```

## Forzar eliminar una rama

```sh
git branch -D <nombre de la rama>
```

## Para modificar el ultimo commit

```sh
git commit --amend
```
## Lista commit por fecha

```sh
git log --since="2022-03-20"
git log --after="2022-03-20"
git log --before="2022-03-20"
git log --after="2022-03-20" --before="2022-03-20" --oneline
```

# GIT STASH
Es una pila almacena el working directory
Permite almacenar el working directory para seguir trabajando
Los stash que creo solo estan en la copia local

## Creo un stash

```sh
git stash
```

## Ver los stash

```sh
git stash list
```

## Recuperar un stash

```sh
git stash pop
```