# Practica de Git

## Comandos básicos

Comando para ver los datos de la rama y los archivos

    ``` bash
        git status


Para agregar archivos de forma local usamos>

    ```bash
        git add <nombreArchivo>

Para agregar todos los documentos modificados o agregados
    ```bash
        git add .

Para quitar un documento del commit 
    ```bash
        git reset <nombreArchivo>

Para quitar todos los documentos del commit 
    ```bash
        git reset .

Para realizar un commit en la historia del repositorio
    ```bash
        git commit -m "mensaje del commit"


Para bajar cambios de github a git en local
    ```bash
        git pull

## Ramas en git

Para crear una rama usamos
    ```bash
        git branch <nombreRama>

Para ccambiarnos de rama
    ```bash
        git checkout <nombreRamaALaQueNosPasamos>