# Ejercicio_fstab_y_crontab

Primero comprobamos la etiqueta de nuestros discos nuevos

    fdisk -l | less

Una vez sepamos cuales son, los particionamos 

    fdisk /dev/sdb

Y les damos formato y tamaño

    mkfs.fat /deb/sdb2

    mkfs.ntfs /deb/sdc2
  
    mkfs.fat /deb/sdc3

Modificamos el fichero /etc/fstab para permitirnos montar los discos

![fstab](URL fstab.PNG)

*Pedro Herrera López*
