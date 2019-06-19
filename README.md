###TPFinal-EDD-2019

##Guia de instalacion del proyecto
#Para realizar este trabajo utilizamos la aplicacion Jupyter. Esta es una aplicacion web que permite crear y compartir documentos que ejecutan codigo.

#Comando para instalar y ejecutar Jupyter (en linux)
sudo docker run -v ~/JupyterProyects/TPFinal-EDD-2019:/home/jovyan -p 8888:8888 jupyter/pyspark-notebook start-notebook.sh --NotebookApp.password='sha1:7d88ba3166c0:580fc1523e0e53c4d6411b0734c61e026f2ac90b'
#El directorio puede verse sujeto a cambios dependiendo del sistema operativo (Posiblemente haya que cambiar de directorio del ~/JupyterProyects al de Windows).

#La carpeta ~/JupyterProyects/TPFinal-EDD-2019 estara bajo control de versiones para subir y modificar el codigo. Recomiendo usar GitHub (herramienta de control de versiones de git) y GitKracken (herramienta grafica para utilizar Github) para mayor facilidad.

