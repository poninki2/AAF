
# Proyecto de Sistemas Operativos II
# Ingenieria de Sistemas

Grupo # 4
Integrantes:
Acosta Algarañaz Fernando
Yhon Yefferson Torrico Claros
Gutierrez Rivero Javier

Docente:Ing. Jaime Zambrana Chacon










##INTRODUCCION

En el entorno dinámico y expansivo del desarrollo web, la elección y configuración adecuada de software son elementos cruciales para asegurar un rendimiento óptimo y un despliegue eficiente de aplicaciones. Este proyecto se centra en la instalación de paquetes fundamentales para el desarrollo web en un entorno Ubuntu, abordando específicamente la implementación de MySQL como base de datos, Apache como servidor web y PHP como lenguaje de programación del lado del servidor, junto con la integración del sistema de gestión de aprendizaje E-front.

##OBJETIVOS
-instalación de un sistema operativo de la distribucion linux.
-instalación de un servidor web(apache2).
-instalación de MySQL.server
-instalación de PHP.
-instalación de paquetes de administración de base de datos E-front

##MARCO TEORICO
linux-Ubuntu
Ubuntu, una distribución de Linux, fue creada por Mark Shuttleworth y su empresa Canonical Ltd. La primera versión estable de Ubuntu, la 4.10 "Warty Warthog", fue lanzada el 20 de octubre de 2004. Desde entonces, se han lanzado numerosas versiones con mejoras y actualizaciones
Linux: Linux es un sistema operativo de código abierto basado en el kernel Linux. Creado por Linus Torvalds, su flexibilidad y estabilidad lo han convertido en una opción popular para servidores y estaciones de trabajo.

Ubuntu: Ubuntu es una distribución de Linux que se enfoca en la facilidad de uso y la accesibilidad. Desarrollada por Canonical Ltd., Ubuntu ha ganado reconocimiento por su comunidad activa, actualizaciones regulares y soporte a largo plazo (LTS).

Características Clave de Ubuntu:

Entorno de Escritorio: Ubuntu utiliza varios entornos de escritorio, como GNOME, KDE o XFCE, ofreciendo una experiencia visual y de usuario personalizable.

Sistema de Paquetes: Ubuntu utiliza el sistema de gestión de paquetes APT (Advanced Package Tool) para instalar, actualizar y gestionar software de manera eficiente.

Seguridad: Ubuntu implementa medidas robustas de seguridad, incluyendo el sistema de permisos basado en usuarios y grupos, así como actualizaciones automáticas para mantener el sistema seguro.

Actualizaciones Regulares: Las versiones LTS de Ubuntu reciben actualizaciones de seguridad y soporte a largo plazo, brindando estabilidad y confiabilidad a los usuarios empresariales y de servidores.

Kernel de Linux:

El kernel de Linux es el núcleo del sistema operativo, gestionando recursos y proporcionando servicios esenciales. Ubuntu utiliza el kernel Linux, que se actualiza regularmente para ofrecer mejoras de rendimiento y soporte de hardware.

MySQL:

Introducción a MySQL:
MySQL es un sistema de gestión de bases de datos relacional (RDBMS=sistemas de gestión de base de datos relacionable.) de código abierto. Desarrollado por Oracle Corporation, es ampliamente utilizado para almacenar y gestionar datos en aplicaciones web.

Características Clave:
MySQL es conocido por su rendimiento, confiabilidad y facilidad de uso. Ofrece soporte para transacciones, replicación, funciones almacenadas y desencadenadores, convirtiéndolo en una opción robusta para el manejo de datos.

Lenguaje SQL:
MySQL utiliza el lenguaje de consulta estructurado (SQL) para definir y manipular datos. Esto incluye operaciones como SELECT, INSERT, UPDATE y DELETE para interactuar con las bases de datos.

PHP:

Introducción a PHP:
PHP (Hypertext Preprocessor) es un lenguaje de programación del lado del servidor diseñado para el desarrollo web. Se incrusta fácilmente en HTML y se ejecuta en el servidor, generando contenido dinámico.

Características Clave:
PHP es conocido por su simplicidad y versatilidad. Permite la creación de páginas web dinámicas, la manipulación de archivos, la conexión a bases de datos y la interacción con servicios web, siendo un componente esencial en el desarrollo web.

Integración con Bases de Datos:
PHP facilita la integración con sistemas de gestión de bases de datos, como MySQL, permitiendo la creación de aplicaciones web interactivas y dinámicas.

Apache:
Historia y Año de Creación:

Apache HTTP Server fue creado en 1995 por un grupo de desarrolladores que formaron la Apache Group. Desde entonces, ha evolucionado y se ha convertido en el servidor web más utilizado del mundo.

Características Principales:
Código Abierto: Apache es un software de código abierto, lo que significa que su código fuente está disponible para el público y puede ser modificado y distribuido libremente.

Multiplataforma: Es compatible con varios sistemas operativos, incluyendo Unix, Linux, Windows, y otros.
Módulos: La arquitectura modular permite la extensibilidad mediante módulos, lo que facilita la adición de nuevas funciones y la personalización del servidor.
Configuración Flexible: Apache es altamente configurable a través de archivos de configuración que permiten adaptarse a una variedad de situaciones y requisitos.

Ventajas:
Robustez y Estabilidad: Es conocido por su estabilidad y robustez, y ha demostrado ser capaz de manejar un gran número de solicitudes simultáneas.
Gran Comunidad y Soporte: Al ser de código abierto, cuenta con una gran comunidad de desarrolladores y usuarios que proporcionan soporte a través de foros, documentación y otros recursos en línea.
Seguridad: Apache tiene un historial sólido en cuanto a seguridad, y su comunidad responde rápidamente a las vulnerabilidades mediante actualizaciones y parches.

Desventajas:
Consumo de Recursos: En comparación con algunos servidores web más ligeros, Apache puede consumir más recursos, especialmente en configuraciones predeterminadas.
Configuración Inicial Compleja: La configuración inicial puede parecer complicada para usuarios principiantes, ya que requiere la edición de archivos de configuración. Sin embargo, existen herramientas y interfaces gráficas que facilitan este proceso.

Introducción a Apache:
Apache HTTP Server, comúnmente conocido como Apache, es un servidor web de código abierto ampliamente utilizado. Proporciona un entorno robusto para alojar sitios web y aplicaciones web.

Características Clave:
Apache es conocido por su estabilidad, rendimiento y flexibilidad. Es extensible mediante módulos, lo que permite a los usuarios personalizar su configuración según sus necesidades específicas.

Configuración mediante Archivos .htaccess:
Apache utiliza archivos de configuración .htaccess que permiten a los desarrolladores ajustar la configuración del servidor en el nivel del directorio, brindando control sobre la seguridad, redirecciones y otras configuraciones específicas del sitio.

Integración de MySQL, PHP y Apache:

LAMP Stack:
MySQL, PHP y Apache son componentes esenciales de la pila LAMP (Linux, Apache, MySQL, PHP/Python/Perl), una combinación comúnmente utilizada para el desarrollo y alojamiento de aplicaciones web.

Conexión entre Componentes:
PHP se conecta a MySQL para realizar operaciones de lectura y escritura en la base de datos. Apache actúa como servidor web, manejando las solicitudes HTTP y sirviendo páginas web dinámicas generadas por PHP.

Seguridad y Optimización:

Prácticas de Seguridad:
Implementar prácticas de seguridad, como la validación de datos y el uso de consultas parametrizadas, es esencial para prevenir vulnerabilidades en aplicaciones web.

Optimización del Rendimiento:
Ajustar la configuración de Apache, optimizar consultas de MySQL y mejorar el código PHP son estrategias clave para garantizar un rendimiento eficiente de la aplicación.

##DESARROLLO
###1.INSTALACION DE LINUX.Ubuntu
Paso 1: Preparación:
Descarga la imagen ISO de Ubuntu desde el sitio web oficial: Ubuntu Download.

Paso 2: Crear un Medio de Instalación:
Graba la imagen ISO en un USB o DVD. Puedes usar herramientas como Rufus (para Windows) o dd (para Linux) para crear un USB de arranque.

Paso 3: Arrancar desde el Medio de Instalación:
Inserta el USB o DVD en la computadora y reinicia.
Accede al menú de arranque o configura la BIOS/UEFI para arrancar desde el dispositivo USB/DVD.

Paso 4: Iniciar la Instalación:
Selecciona "Instalar Ubuntu" en el menú de inicio.
Elige el idioma y haz clic en "Instalar Ubuntu".

Paso 5: Configuración de Idioma y Teclado:
Selecciona tu idioma y haz clic en "Continuar".
Configura tu disposición de teclado.

Paso 6: Configuración de Red y Actualizaciones:
Conéctate a una red Wi-Fi si es necesario.
Selecciona "Descargar actualizaciones durante la instalación" para obtener las últimas actualizaciones durante la instalación.

Paso 7: Tipo de Instalación:
Elige el tipo de instalación según tus necesidades: "Borrar disco e instalar Ubuntu" o "Instalar Ubuntu junto a [otro sistema operativo]".

Paso 8: Zona Horaria:
Selecciona tu zona horaria y haz clic en "Continuar".

Paso 9: Crear Usuario:
Completa la información del usuario, incluyendo el nombre de usuario y la contraseña.
Puedes optar por cifrar tu directorio personal para mayor seguridad.

Paso 10: Instalación:
Revisa la configuración y haz clic en "Instalar" para comenzar el proceso de instalación.
Espera a que se complete la instalación.

Paso 11: Reiniciar:
Una vez que se completa la instalación, se te pedirá que reinicies el sistema.

Paso 12: Iniciar Sesión en Ubuntu:
Después del reinicio, inicia sesión con la cuenta de usuario que creaste durante la instalación.

###2.INSTALACION DE MySQL
Paso 1: Actualizar el Índice de Paquetes:
sudo apt update

Paso 2: Instalar el Servidor MySQL:
sudo apt install mysql-server

Durante la instalación, se te pedirá establecer una contraseña para el usuario root de MySQL. Asegúrate de elegir una contraseña segura y recuérdala, ya que la necesitarás para acceder a MySQL más adelante.

Paso 3: Configurar MySQL:
sudo mysql_secure_installation

Este script te guiará a través de varias configuraciones de seguridad, incluida la configuración de la contraseña para el usuario root, la eliminación de usuarios anónimos, la desactivación del inicio de sesión remoto para el usuario root, y la eliminación de la base de datos de prueba.

Paso 4: Iniciar y Habilitar el Servicio MySQL:

sudo systemctl start mysql
sudo systemctl enable mysql

Paso 5: Verificar el Estado del Servicio:

sudo systemctl status mysql

Asegúrate de que el servicio MySQL se esté ejecutando sin problemas.

Paso 6: Acceder a MySQL:

mysql -u root -p

Ingresa la contraseña que estableciste para el usuario root durante la instalación.

###3.INSTALACIÓN DE apache2

Paso 1: Actualizar el Índice de Paquetes:
sudo apt update

Paso 2: Instalar Apache:
sudo apt install apache2

Paso 3: Verificar el Estado del Servicio:
sudo systemctl status apache2

Asegúrate de que Apache se esté ejecutando sin problemas. Deberías ver un mensaje indicando que el servicio está activo y en ejecución.

Paso 4: Configuración de Cortafuegos (si es necesario):

Si estás utilizando un cortafuegos, debes permitir el tráfico HTTP. Por ejemplo, si estás utilizando UFW, puedes hacerlo con estos comandos:

sudo ufw allow 'Apache'
sudo ufw reload

Paso 5: Acceder a la Página de Prueba:
Abre tu navegador web y visita http://localhost. Deberías ver la página de inicio de Apache, indicando que la instalación ha sido exitosa.

##4.INSTALACION DE PHP
Paso 1: Actualizar el Índice de Paquetes:
sudo apt update

Paso 2: Instalar PHP y Módulos Adicionales:
sudo apt install php libapache2-mod-php

Si estás utilizando Nginx en lugar de Apache, puedes instalar el módulo de PHP de Nginx en su lugar:

sudo apt install php-fpm

Paso 3: Verificar la Instalación de PHP:
php -v
Esto debería mostrar la versión de PHP instalada y otra información relevante.

Paso 4: Configurar PHP (opcional):

Dependiendo de tus necesidades, es posible que desees ajustar la configuración de PHP. El archivo principal de configuración se encuentra en /etc/php/{version}/apache2/php.ini para Apache o /etc/php/{version}/fpm/php.ini para Nginx.

Paso 5: Reiniciar el Servidor Web:
Si estás utilizando Apache, reinicia el servicio para que los cambios surtan efecto:

sudo systemctl restart apache2

Si estás utilizando Nginx, reinicia el servicio PHP-FPM:
sudo systemctl restart php7.4-fpm   # Reemplaza "7.4" con tu versión de PHP

Paso 6: Prueba de PHP:
Crea un archivo de prueba PHP para asegurarte de que todo esté configurado correctamente. Puedes hacerlo creando un archivo llamado info.php en el directorio de documentos del servidor web:

sudo nano /var/www/html/info.php
Añade el siguiente contenido:

php
Copy code
<?php
phpinfo();
?>

###5.INSTALACION DE E-front

Paso 1: Descargar el Paquete de Instalación de E-Front:

Ve al sitio web oficial de E-Front o ponte en contacto con el proveedor para obtener el paquete de instalación.
Descarga el paquete en tu sistema Ubuntu.

Paso 2: Descomprimir el Paquete:
tar -zxvf nombre_del_paquete.tar.gz

Paso 3: Mover los Archivos a la Carpeta del Servidor Web:
sudo mv carpeta_descomprimida /var/www/html/e-front

Paso 4: Otorgar Permisos:
sudo chown -R www-data:www-data /var/www/html/e-front
sudo chmod -R 755 /var/www/html/e-front

Paso 5: Crear una Base de Datos MySQL:
Accede a MySQL:
mysql -u root -p

Crea la base de datos:
CREATE DATABASE nombre_de_la_base_de_datos;

Crea un usuario y asigna privilegios:
CREATE USER 'nombre_de_usuario'@'localhost' IDENTIFIED BY 'tu_contraseña';
GRANT ALL PRIVILEGES ON nombre_de_la_base_de_datos.* TO 'nombre_de_usuario'@'localhost';
FLUSH PRIVILEGES;
EXIT;

Paso 6: Configurar E-Front:
Abre tu navegador y accede a http://localhost/e-front o la ruta donde hayas instalado E-Front.
Sigue el asistente de instalación. Introduce la información de la base de datos que creaste, el nombre de usuario y la contraseña.

Paso 7: Configurar el Cron:
Configura el cron job para E-Front. Editar el crontab:
sudo crontab -e

Agrega la siguiente línea y guarda:
* * * * * php /var/www/html/e-front/cron.php

Esto asegurará que las tareas programadas se ejecuten regularmente.

Paso 8: Finalizar la Instalación:

Sigue cualquier instrucción adicional proporcionada por el asistente de instalación de E-Front.


##CONCLUSIÓN 
Lo que pudimos aprendere en el desarrollo de este proyecto fue; hemos logrado implementar con éxito un entorno de desarrollo web robusto utilizando tecnologías clave como Linux Ubuntu, MySQL, PHP, Apache y el sistema de gestión de aprendizaje E-Front. Cada componente desempeña un papel crucial en la creación, gestión y despliegue de aplicaciones web dinámicas y educativas.

##RECOMENDACIONES
1. Seguridad:

Mantener el equipo actualizado para poder trabajar con las nuevas actualizaciones.

Firewall: configurar un firewall para restringir el tráfico no deseado. UFW (Uncomplicated Firewall) es una opción fácil de configurar en Ubuntu.

Seguridad de PHP: ajustar la configuración de PHP para limitar posibles vulnerabilidades. Desactiva las funciones innecesarias y utiliza configuraciones seguras.

2. Copias de Seguridad:

Programación de Copias de Seguridad: establecer un sistema de copias de seguridad automatizado para los datos críticos, incluidas las bases de datos y el contenido del servidor web.

Almacenamiento Externo: Guardar las copias de seguridad en un almacenamiento externo o en la nube para garantizar la recuperación en caso de fallo del sistema.

3. Rendimiento y Optimización:

Caché: implementar soluciones de caché para mejorar el rendimiento. Puedes utilizar herramientas como Redis o Memcached para la caché de datos y el rendimiento de PHP.

Optimización de Consultas SQL: Asegúrarse de optimizar las consultas SQL para mejorar la eficiencia de las operaciones de la base de datos.


##ANEXOS.
- https://help.ubuntu.com/kubuntu/desktopguide/es/manual-install.html

- https://www.digitalocean.com/community/tutorials/how-to-install-the-apache-web-server-on-ubuntu-20-04-es

- https://geekrd57.blogspot.com/2010/10/guia-de-instalacion-de-efront-e.html

- https://ubuntu.com/
