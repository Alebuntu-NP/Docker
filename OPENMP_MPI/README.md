# CONTENEDOR_MPI_OPENMP


## Descripción y contexto

* Es una imagen de de un contenedor que parte de una imagen de mfisherman que tiene instalado lo minimo para que puedas ejecutar openmp y mpi.


## Guía de instalación

Esta guía es para que instales la aplicación localmente.

##### Comando de instalacion del contenedor: 

docker run -dit --name nombre_de_tu contenedor -v ruta_del_equipo_principal:/project/  aromcab314/mpi_openmp

##### Para entrar dentro del contenedor:

docker exec -it nombre_del_contenedor /bin/bash

### Example:

##### Comando de instalacion del contenedor: 

docker run -dit --name maquina  aromcab314/mpi_openmp


##### Para entrar dentro del contenedor:

docker exec -it maquina  /bin/bash


#### Para cambiarlo al inicio del contenedor:

###### docker run -it --name maquina  -v ruta_del_equipo_principal:/project/ aromcab314/mpi_openmp

Esto nos creara un contenedor con la imagen de mpi_openmp.

