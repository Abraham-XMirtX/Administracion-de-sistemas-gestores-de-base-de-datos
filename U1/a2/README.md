### Instalación de MySQL en Ubuntu

* Configuración de l a maquina

  Ponemos la Ip del Servidor fija:

  ![image](img/img0.png)

* MySQL

  Abrimos un terminal e instalamos el programa.

  > sudo apt-get install mysql-server

  ![image](img/img1.png)

  En mitad da la instalación nos pedira intraducir una contraseña para "**root**"

  ![image](img/img2.png)

  Volvemos a introducir la contraseña.

  ![image](img/img3.png)

  Ahora instalamos el "**mysql-client**" y "**mysql-workbench**"

  > sudo apt-get install mysql-client

  ![image](img/img4.png)

  > sudo apt-get install mysql-workbench

  ![image](img/img5.png)

  ![image](img/img22.png)

### Instalación Phpmyadmin

  Una vez terminado estoy siguimos en el terminal e instalamos "**phpmyadmin**"

  > sudo apt-get install phpmyadmin

  ![image](img/img6.png)

  En medio de la instalación elegimos nuestro "**servidor web apache2**"

  ![image](img/img7.png)

  En la siguiente pantalla le damos al **YES**

  ![image](img/img8.png)

  Y tenemos que instroduccir una contraseña para el usuario phpmyadmin.

  ![image](img/img9.png)

  Comprobamos en un navegador este funcionando correctamente el **phpmyadmin**

  > localhost

  ![image](img/img10.png)

  > localhost/phpmyadmin

  ![image](img/img12.png)

### Creación de un usuario

  Iniciamos el programa Workbench, vamos al apartado Usuarios y privilegios, y lo creamos.

  ![image](img/img14.png)

  Tambien le damos privilegios de administrador.

  ![image](img/img15.png)

### Comprobación desde una maquina cliente.

  Instalamos el mysql-client, mysql-workbench

  ![image](img/img17.png)

  ![image](img/img19.png)

  Ejecutamos el Workbench y iniciamos una conexion con nuestro Servidor

  ![image](img/img21.png)

  Y vamos al nevegador para comprobar si podemos acceder al phpmyadmin con la ip del nuestro servidor.

  ![image](img/img20.png)
