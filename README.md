# Sitio principal de Drupal 7 de DATA  
La presente documentación es para los sitios principales de DATA que se hayan instalado con Drupal 7. Atualmente hemos tomado otro rumbo en tecnologías de RoR y Ionic5 por lo que ya no estamos dando soporte a los sitios en Drupal 7, salvo casos puntuales.  
## Instalación de subsitios  
- git clone https://github.com/datauy/d7main.git
- cd d7main/sites/
- git clone \<subsitio>
- cp default/default.settings.php \<subsitio>
- cd \<subsitio>
- mv default.settings.php settings.php
- configurar sitio de drupal:
  - Base de datos: $databases['default']['default'] = array (  
      'database' => '\<base>',  
      'username' => '\<usuario>',  
      'password' => '\<passwd>',  
      'host' => 'localhost',  
      'port' => '',  
      'driver' => 'mysql',  
      'prefix' => '',  
    );
  
