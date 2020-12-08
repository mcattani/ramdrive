# ramdrive
v2.0.4

Pequeña aplicación para crear unidades con memoria RAM.
GUI creado en Gambas!

1. La unidad solo puede almacenar información durante la sesión en curso. Si se apaga o reinicia el sistema, toda la información de la misma se borrará.
2. La velocidad de lecto/escritura de la RAM es muchísimo mas alta que la del disco (incluidas unidades USB y discos SSD).

Normalmente estas unidades se crean mas o menos así:

>mkdir /RUTA/CARPETA ( ej. /mnt/ramdisk)
>mount -t [TYPE] -o size=[SIZE] [FSTYPE] [MOUNTPOINT]

Existen dos tipos de unidades. 
* ramfs
* tmps

El programa usa por defecto **tmps**.

Esta APP permite crear este tipo de unidades; asignándoles tamaño y montándolas.

Si te gustó/interesa esta app visitá mi blog!.
https://thenerdyapprentice.blogspot.com/
