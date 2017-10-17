## Preparación de  Maquinas

* Instalación de Workbench Server

  Le damos a siguiente

  ![image](img/img1.png)

  Elegimos la opcion Developer Default

  ![image](img/img2.png)

  Ejecutamos

  ![image](img/img3.png)

  Tenemos que instalar los paquetes de Microsoft Visual C++ 2013 y 2015

  > Si ya los tenemos actualizados no lo pedira.

  ![image](img/img4.png)

  ![image](img/img5.png)

  Una vez terminada la ejecucion le damos a siguiente

  ![image](img/img6.png)

  Ahora le damos a ejecuta y empezara la instalación

  ![image](img/img7.png)

  Una vez finalizado le damos a siguiente

  ![image](img/img8.png)

  Ahoara vamos a la configuración.

  ![image](img/img9.png)

  Elegimos Standalone MySQL y le damos siguiente

  ![image](img/img10.png)

  Dejamolos los valores por defecto

  ![image](img/img11.png)

  Introducimos la contraseña que vamos a usar como root

  ![image](img/img12.png)

  Valores por defecto

  ![image](img/img13.png)

  ![image](img/img14.png)

  Le damos a finalizar y siguimos con las configuración

  ![image](img/img15.png)

  ![image](img/img16.png)

  Dejamos los valores por defecto, vamos a la siguiente configuración

  ![image](img/img17.png)

  Probamos la conexion del root con la contraseña creada anteriormente y le damos a siguiente

  ![image](img/img19.png)

  Le damos a finalizar y terminamos la instalación

  ![image](img/img20.png)

  ![image](img/img22.png)

  ![image](img/img23.png)

  * Creación del usuario


  Entramos en nuestra base de datos , vamos a usuarios y privilegisos y creamos nuestro usuario para entrar con la maquina del cliente.

  ![image](img/img29.png)

  * Instalación de Workbench cliente

  Hacemos los mismo pasos anteriores solo que desactivamos el servidor, abrimos la herramienta de Workbench.

  > Tenemos que instalar tambien los paquetes 2013 y 2015 de Microsoft Visual C++

  ![image](img/bd1.png)

  Vamos al boton mas y colocamos la IP del servidor y el usuario con que vamos a acceder y establecemos conexion.

  ![image](img/img28.png)

  ### Instalación de XAMPP

  Instalamos XAMPP  para utilizar la herramienta phpmyadmin.

  ![image](img/img30.png)

  Le damos a siguiente

  ![image](img/img31.png)

  Utilizaremos el servidor apache y phpmyadmin

  ![image](img/img32.png)

  Una vez terminada la Instalación le damos a finalizar y vamos a modificar unos archivos.

  ![image](img/img33.png)

  ### Configuración

  Vamos a la carpeta de XAMPP/phpmyadmin/sql y buscamos el create_tables.sql y lo ejecutamos

  ![image](img/img34.png)

  Una vez terminado esto vamos otra vez a la carpeta de XAMPP/phpmyadmin y modificamos el archivo config.inc.php y añadimos estas lineas.

  ![image](img/img41.png)

  Ahora creamos un nuevo usuario con privilegios.

  ![image](img/img40.png)

  ![image](img/img39.png)

  Levantamos nuestro servidor apache

  ![image](img/img35.png)

  Hacemos click en Admin y vamos al apartado de phpmyadmin

  ![image](img/img36.png)

  Y si todo esta correcto tiene que salir el administrador de phpmyadmin

  ![image](img/img37.png)
