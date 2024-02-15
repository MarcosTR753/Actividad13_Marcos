# ACTIVIDAD 1.3.1: Instalación de la pila LAMP (Linux, apache, MariaDB y PHP) en una instancia EC2 de AWS con Debian/Ubuntu Server  

## Instalación de PHP 

#### Actualizamos los repositorios
![Imagen-1p](php/1.PNG)
#### Instalamos Apache2
![Imagen-2p](php/2.PNG)
#### Instalamos PHP
![Imagen-3p](php/3.PNG)
#### Editamos el sitio web por defecto en el fichero 000-default.conf
![Imagen-4p](php/4.PNG)
#### Reiniciamos el servicio apache2 porque hemos modificado un fichero de configuracion.
![Imagen-5p](php/5.PNG)
#### Comprobación de LAMP stack.
![Imagen-6p](php/6.PNG)
![Imagen-7p](php/7.PNG)

## Instalación de MariaDB

#### Actualizamos los repositorios
![Imagen-1m](mariadb/1.PNG)

#### Instalamos el servidor de base de datos y cliente
![Imagen-2m](mariadb/2.PNG)
![Imagen-3m](mariadb/3.PNG)
#### Accedemos a MariaDB desde la consola del servidor
![Imagen-4m](mariadb/4.1.PNG)
#### Cambiamos la contraseña del usuario root
![Imagen-5m](mariadb/5.PNG)
![Imagen-6m](mariadb/6.PNG)
![Imagen-7m](mariadb/7.PNG)
#### Instalamos phpmyadmin con el comando "apt install phpmyadmin php-mbstring php-zip php-gd php-json php-curl -y" y cuando nos aparezca la siguiente pantalla seleccionaresmoas apache2 
![Imagen-1pma](phpmyadmin/1.PNG)
#### Comprobamos el acceso a PHPMyAdmin buscando en el navegador http://ip_host/phpmyadmin/
![Imagen-2pma](phpmyadmin/2.PNG)
#### Contenido ficheros index.php e info.php
![Imagen-3pma](phpmyadmin/finalo%201.3.1.PNG)