# graficacion-CamCap

Descargar OpenCV 2.4.9 o 3.0.0  (el proyecto está hecho con la version 2.4.9)

Descomprimir el archivo en una carpeta cualquiera, ejemplo c:\java\opencv-2.4.9

En NetBeans, agregar una libreria con el nombre "opencv" y referenciar el archivo:  

  opencv-249.jar 

que lo localizan dentro de los archivos descomprimidos.

Agregar a la variable PATH la ruta donde se encuentran los DLL para que enlace el opencv-249.jar 

Tambien se puede modificar en "Project Properties-> Run -> VM Options y modificar:
    -Djava.library.path="<ubicacion de los DLLs>"

