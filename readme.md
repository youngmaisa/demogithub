
Primera clase 
GIT STATUS
GIT ADD .
GIT COMMIT -M 'Mensaje de commit'
GIT PUSH -U ORIGIN MAIN

Segunda clase - CREAMOS RAMAS 
GIT BRANCH
GIT CHECKOUT -B NOMBRERAMA (FEAT/---) -- crea rama y te mueve
    (trabajamos la rama)
    GIT STATUS
    GIT ADD .
    GIT COMMIT -M 'Mensaje de commit'
        se puede subir la rama a la nube
        GIT PUSH -U ORIGIN NOMBRERAMA
        mas no es necesario

GIT CHECKOUT MAIN -- regresamos a main para traer la rama
GIT MERGE NOMBRERAMA -- importamos rama
GIT PUSH -U ORIGIN MAIN  -- subimos a la nube

NOTA: SI QUEREMOS VOLVER A ACCEDER A UNA RAMA
GIT CHECKOUT NOMBRERAMA