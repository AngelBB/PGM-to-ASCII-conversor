# PGM-to-ASCII-conversor
Conversor de formato PGM a ASCII y viceversa.

## Forma de uso
1 Hacemos make.
2 Ejecutamos desde la carpeta bin el ejecutable que deseemos:
  - Este ejecutable sirve para crear un degradado y un recorte de una determinada imagen:
  ```sh
    ./testimagen  <sin parametros> 
  ```
 - Lee cualquier imagen indicada por el usuario y un fichero con cadenas de caracteres y crea ficheros de imagen transformadas, una por cadena:
 ```sh
 ./arteASCII2 ruta_imagen.pgm ruta_cadenas.txt
 ``` 
- Realiza la concatenación de dos imagenes:
  ```sh
  ./suma ruta_imagen1.pgm> ruta_imagen2.pgm
 ```
  
