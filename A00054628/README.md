###EXAMEN 1  
**Nombre:** Miguel Andrés Isaza Barona  
**Código:** A00054628  
###3 validación de la imagen  
Primero descargamos la imagen debian 9 de https://www.debian.org/distrib/netinst#smallcd seleccionamos amd64, luego de
http://cdimage.debian.org/debian-cd/current/amd64/iso-cd/MD5SUMS consultamos el valor del checksum de la imagen, descargamos un software 
que nos permite comprobar que el checksum de la imagen fuera igual al consultado, esta herramienta se descargó de
http://download.cnet.com/MD5-SHA-Checksum-Utility/3001-2092_4-10911445.html  

###4 instalación  
Primero abrimos virtualbox, luego de esto damos nueva para cear una nueva máquina, le damos un nombre (en mi caso es Debian9),
seleccionamos el tipo (Linux) y la versión de la máquina virtual (Debian 64 bits).  
Luego nos vamos a configuración, en almacenamiento montamos la imagen, y en la parte de red habilitamos 2 adaptadores (el nat
y el adaptador puente).  
Luego lo iniciamos, le damos graphical install, seleccionamos el idioma, el idioma del teclado, luego le damos un nombre de usuario
y una contraseña, a partír de ahí se da continuar para la instalación.  

###8 centos7 vs debian9

