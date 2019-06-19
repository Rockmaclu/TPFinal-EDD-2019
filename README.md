# TPFinal-EDD-2019

## Tecnologias utilizadas.

Para realizar este trabajo utilizamos: 
* Jupyter. Esta es una aplicacion web que permite crear y compartir documentos que ejecutan codigo.
* Github. Repositorio Git online de codigo para control de versiones.
* GitKraken. Cliente Git con GUI.

## Comando para instalar y ejecutar Jupyter (en linux)

```
sudo docker run -v ~/JupyterProyects/TPFinal-EDD-2019:/home/jovyan -p 8888:8888 jupyter/pyspark-notebook start-notebook.sh --NotebookApp.password='sha1:7d88ba3166c0:580fc1523e0e53c4d6411b0734c61e026f2ac90b'
```

### Explicacion del comando:

* docker run (corrermos en el motor docker).
* -v ~/JupyterProyects/TPFinal-EDD-2019:/home/jovyan (montamos nuestra carpeta del proyecto en el contenedor debido a que estos son efimeros).
* -p 8888:8888 (mapeamos el puerto 8888 del contenedor en el puerto 8888 de nuestra PC).
* jupyter/pyspark-notebook (imagen que utilizaremos que ya instala las librerias necesarias).
* start-notebook.sh --NotebookApp.password='sha1:7d88ba3166c0:580fc1523e0e53c4d6411b0734c61e026f2ac90b' (cambiamos la contraseña).

El directorio puede verse sujeto a cambios dependiendo del sistema operativo (posiblemente haya que cambiar de directorio del ~/JupyterProyects/ al de Windows).

La carpeta ~/JupyterProyects/TPFinal-EDD-2019 estara bajo control de versiones para subir y modificar el codigo. En este caso los notebooks que se utilizaran y los conjuntos de datos.

