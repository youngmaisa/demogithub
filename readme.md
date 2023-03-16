
Primera clase 
GIT STATUS
GIT ADD .
GIT COMMIT -M 'Mensaje de commit'
GIT PUSH -U ORIGIN MAIN

Segunda clase - CREAMOS RAMAS 
GIT BRANCH
GIT CHEKOUT -B NOMBRERAMA (FEAT/---) -- creamos rama
    trabajar la rama
    GIT STATUS
    GIT ADD .
    GIT COMMIT -M 'Mensaje de commit'
        se puede subir la rama a la nube
        GIT PUSH -U ORIGIN NOMBRERAMA
        mas no es necesario

GIT CHECKOUT MAIN -- regresamos a main para traer la rama
GIT MERGE NOMBRERAMA
GIT PUSH -U ORIGIN MAIN 