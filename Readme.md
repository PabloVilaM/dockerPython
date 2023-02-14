# Docker + Python

---

# Creamos un contenedor sencillo de python

`$ docker run -it --rm --namemy-running-script -v "$PWD":/usr/src/myapp -w /usr/src/myapp python:3 python your-daemon-or-script.py`

`docker` el comando base, es el daemon

`run` crea el contenedor

`-it` dos opciones que me valen para interactuar con la terminal del contenedor

`--rm` borra el contenedor cuando finaliza la acción

`-v` define el mapeo del volumen a continuacion

- `"$PWD"` el directorio donde estamos
- `/usr/src/myapp` el directorio dentro del contenedor

`-w` el directorio de trabajo(_workdir_)

`python:3` la imagen de la que se creará el contenedor

`python script.py` es el comando para ejecutar dentro del contenedor
 


