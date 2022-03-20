# GIT

## Instalaciones necesarias
## Markdown
## Uso de consola

## Moverme entre directorios

### Change directory

```sh
cd
cd ..
```

### Saber en el directorio que estoy

```sh
pwd
```

### Crear archivos vacios

```sh
touch <nombre del archivo>
```

### Crear directorios vacios

```sh
mkdir <nombre del archivo>
```

### Limpiar

```sh
clear
```

### Tirar múltiples comando en una linea

```sh
touch index.min.js && mkdir css js
```

## Uso de GIT inicial

### Modificar el editor por defecto
```sh
git config --global core.editor "code --wait" #Para configural el editor  que se va abrir por defecto
git config --global core.editor "nano"
```

### Configuraciòn inicial

```sh
git config --global user.name "Cristian Moreno"
git config --global user.email "cristian.moreno1986@outlook.com" #email con el cual se registraron en GitHub
```

### Crear repositorio GIT

```sh
git init
```

### Ver y editar las configuraciones de GIT con el editor

```sh
git config --global -e #Para abrir con el programa configurado las configuraciones de global
git config --local -e #Para abrir con el programa configurado las configuraciones de local
```

### Agrego archivos al Stage Area o Index

```sh
git add <nombre-archivo>
git add .
git add *.js
```

### Puedo hacer un commit (saco foto/snapshot) 

```sh
git commit #me abre el editor por defecto que tengo configurado
git commit -m "mensaje descriptivo de lo contiene el commit"
```