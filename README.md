# Docker_compose
Primerarment instalem docker, mitjançant els paquets docker-ce i docker-compose.
Creem una carpeta anomenada DOcumentRoot, dins de la carpeta dokerized-lamp(aquesta contindra tots els contiguts de la practica que estem realitzant. 
Dins de la carpeta Document Root creem un arxiu php anomenat index.php que contindra la següent estructura:
<?php
  phpinfo();
  ?>
  A continuació creem un fitxer que li donarem el nom de docker-compose.yml on escriurem unes linees ja donades en la practica.
  Aquest document incloeix linnes sobre php-apache per a que oferixca un servei, linnes sobre mariadb (un servidor de base de dades,.
  En definitiva la carpeta dockerized-lamp te que mostrar la següent estructura:
  dockerized-lamp/
  -docker.compose.yml
  -Document Root
    -- index.php
  -php-apache
    -- dockerfile
