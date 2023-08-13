# COMANDOS-SO
Bitácora de comandos para la clase de sistemas operativos
| Comando | Descripción | Ejemplo de uso |
|--|--|--|
| `clear` | Limpia la pantalla de la sesión de consola actual. | `clear` muestra toda la información (gracias al flag `-a`) sobre 
| `cd <ruta de directorio>` | Cambia el directorio actual | `cd ~/Ulacit` para ir a una carpeta llamada Ulacit en el home (~) del usuario actual. |
| `ls <directorio>` | Lista los archivos y directorios que están dentro de un directorio. Si no se pasa ningún directorio cómo parámetro se listan los del directorio actual. | `ls ~/Ulacit` para mostrar todas las carpetas y archivos dentro de la carpeta Ulacit. |
| `cp <origen> <destino>` | Copia un archivo (o directorio si se usa el flag `-r`) de un origen a un destino. | `cp -r ~/Ulacit/* ~/` para copiar todo el contenido de la carpeta llamada Ulacit al home del usuario actual. |
|`echo`| Imprime en pantalla una cadena de texto. | `echo "Hola"` imprimiría Hola en la salida de la terminal. |
|`man`| Abre el manual. | `man` se visualiza un manual con los comandos de Linux que se deben de conocer para manejar el sistema. |
|`sudo passwd`| Es para cambiar la contraseña a un usuario. | `sudo passwd francel` me solicitaría digitar la nueva contraseña del usuario. |
|`history`| Imprime los comandos que han sido utilizados. | `history` imprimiría una lista en orden de uso de los comandos que han sido utilizados. |
|`nano <nombre de archivo>`| Crea un archivo nuevo. | `nano archivo.txt` crea un nuevo archivo con el nombre de archivo.txt. |
|`cat <nombre de archivo>`| Muestra un archivo. | `cat archivo.txt` abre un archivo y se imprime en la terminal. |
|`mkdir <nombre de carpeta>`| Crea una carpeta nueva. | `mkdir carpeta1` crea na nueva carpeta con el nombre de carpeta1. |
|`rm <nombre de archivo>`| Borra un archivo. | `rm archivo.txt` elimina el archivo con el nombre archivo.txt. |
|`top`| Muestra lista de procesos del sistema. | `top` muestra las tareas del sistema que se estan ejecutando en tiempo real. |
|`tree`| Muestra el contenido de las carpetas. | `tree` muestra todas las rutas de directorios contenidos. |
|`cat /etc/passwd`| Muestra lista de usuarios. | `cat /etc/passwd` muestra la lista de los usuario que existen en el sistema y los datos ingresados sobre cada usuario. |
|`sudo adduser <nombre de usuario nuevo>`| Crea un usuario nuevo. | `sudo adduser francel_m` crea un nuevo usuario con el nombre de francel_m, además, solicita información sobre el usuario. |
|`sudo apt update`| Actualiza el sistema. | `sudo apt update` actualiza toda la lista de paquetes del sistema operativo a la última versión. |
|`sudo apt-get install webmin`| Inicia la instación de Webmin. | `sudo apt-get install webmin` inicializa la descarga del programa Webmin, herramienta de configuración de sistemas accesible vía web para sistemas Unix. |
|`ifconfig`| Visualiza direcciones ip. | `ifconfig` muestra dirección ip del sistema, esto para asignar direcciones IP a interfaces. |
|`sudo apt-get install proftpd -y`| Inicializa la descarga de Proftpd. | `sudo apt-get install proftpd -y` se inicia la descarga de Proftpd, un servidor FTP para transportar archivos entre equipos conectados. |
|`systemctl status proftpd`| Visualiza el estado de Proftpd. | `systemctl status proftpd` muestra el estados de Proftpd, esto para reconocer si el programa ya está activo en el sistema. |
|`nano /etc/proftpd/proftpd.conf`| Abre el archivo principal de configuración del Proftpd. | `nano /etc/proftpd/proftpd.conf` se abre el archivo en donde se realiza la configuración de Proftpd según las necesidades del usuario. |
|`sudo chown <usuario> <nombre de carpeta>`| Asigna un usuario a carpeta. | `sudo chown francel_m carpeta1` asigna a francel_m como el usuario de la carpeta llamada carpeta1. |
|`sudo chmod <permisos> <nombre de carpeta>`| Asigna permisos a usuario de carpeta. | `sudo chmod 700 carpeta1` con este comando se da los permisos de escritura, lectura y ejecución solo al usuario dueño de la carpeta1. |
|`yay -S google-chrome`| Instalar Google Chrome en Manjaro. | `yay -S google-chrome` inicializa la descarga de Google Chrome en el sistema de Manjaro. |
|`uname -a`| Muestra información del sistema operativo. | `uname -a` logra visualizar información del sistema operativo como la versión del mismo y kernel. |
|`sudo useradd -m <usuario> -G wheel -p <contraseña>`| Crea un nuevo usuario en Manjaro. | `sudo useradd -m <usuario> -G wheel -p <contraseña>` crea un nuevo usuario en el sistema y se le asigna una contraseña al mismo. |
|`sudo docker images`| Visualiza las imagenes de Docker. | `sudo docker images` muestra las imagenes de Docker con las que cuenta el sistema, para así seleccionar la que necesitamos para el contenedor. |
|`docker run -it ubuntu`| Inicializa ubuntu en Docker. | `docker run -it ubuntu` inicializa ubuntu como el sistema a utilizar en Docker. |
|`rmdir <nombre de directorio>`| Eliminar directorios. | `rmdir directorio1` se elimina un directorio guardado con el nombre de directorio1. |
|`sudo`| Se da permisos de administrador. | `sudo` se permite realizar acciones específicas de administrador, de las que no pueden realizar cualquier usuario. |
|`zip <nombre de archivo>`| Comprimir archivos. | `zip archivo.pdf` se inicia el proceso de comprimir el archivo.pdf. |
|`unzip <nombre de archivo>`| Descomprimir archivos. | `unzip archivo.zip` se inicia el proceso de descomprimir el archivo.zip. |
|`locate <nombre de archivo>`| Encontrar archivos. | `locate archivo12` se visualizan los archivos que contienen el texto archivo12. |
|`mv <directorio actual><archivo><directorio nuevo>`| Mover archivo de un directorio a otro directorio. | `mv /directorio1/archivo.txt/directorio2/` se pasará de ubicación el archivo.txt del directorio1 al directorio2. |
|`kill <numero de PID>`| Para deterner un proceso. | `kill  5548` se detiene el proceso que tiene el número PID 5548. |
|`Ping`| Conectividad de redes. | `Ping` se visualiza el estado de conectividad de red entre una fuente y un dispositivo. |
|`apt-get install wget`| Instala wget. | `apt-get install wget` se inicializa la descarga de wget, programar para acceder material del internet. |
|`pwd`| Ruta de directorio. | `pwd` se imprime la ruta del directorio en el que se está trabajando. |
|`hostname`| Muestra nombre del host. | `hostname` se imprime el nombre del host del sistema. |
|`userdel <nombre de usuario>`| Elimina usuario del sistema. | `userdel francel_m` se elimina del sistema el usuario llamado francel_m. |
|`cd ..`| Volver a directorio principal. | `cd ..` se abre al directorio principal. |
|`cd -`| Volver al directorio anterior. | `cd -` devuelve al usuario al directorio en el que estaba trabajando anteriormente. |
|`uname -a`| Muestra información del sistema operativo. | `uname -a` logra visualizar información del sistema operativo como la versión del mismo y kernel. |
|`neofetch`| Muestra información sobre el sistema. | `neofetch` imprime información sobre el sistema, cómo el la versión del kernel. |
|`group <nombre de usuario>`| Muestra el grupo del usuario. | `group francel_m` muestra el grupo al que pertenece el usuario francel_m. |

