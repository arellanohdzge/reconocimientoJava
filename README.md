# graficacion-CamCap

Descargar OpenCV 4.3.0  (el proyecto está hecho con la version 4.3.0)

Descomprimir el archivo en una carpeta cualquiera, ejemplo c:\opencv

En NetBeans, agregar una libreria con el nombre "opencv" y referenciar el archivo:  

  opencv-430.jar 

que lo localizan dentro de los archivos descomprimidos.

Agregar a la variable PATH la ruta donde se encuentran los DLL para que enlace el opencv-430.jar 

Tambien se puede modificar en "Project Properties-> Run -> VM Options y modificar:
    -Djava.library.path="<ubicacion de los DLLs>"

