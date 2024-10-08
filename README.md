# GIT RAMAS (Branches)

## Crear un repositorio

```sh
git init
```

## Ver el status de los archivos

```sh
git status
```

## Git Alias

```sh
git config --global alias.st "status --short"
git config --global alias.a "add"
git config --global alias.c "commit -m"
git config --global alias.l "log --oneline"
```


## Ver las diferencias entre el WD y LR

```sh
git diff
```

## Ver el contenido de cada commit

```sh
git show <numero-hash>
```

## Crear una RAMA

```sh
git branch <nombre-rama> # crea una rama y nos deja en la rama original
git branch feature/ramas # ejemplo
git switch -c <nombre-rama> # crea una rama y nos mueve a la rama que se creo
```

## Me mueve entre ramas

```sh
git switch <nombre-rama>
git switch feature/ramas # ejemplo
```

## Comparar los ultimos commits entre las ramas

```sh
git diff <nombre rama que quiero comparar con la actual> git 
git diff dev  ejemplo. ## comparo feaure/ramas con dev
```

## Ver las ramas locales y remotas

```sh
git branch -a  # me muestra las ramas locales y remotas
```

