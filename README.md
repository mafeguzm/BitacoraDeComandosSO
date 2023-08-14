
Bitácora de comandos para la clase de sistemas operativos

| Comando | Descripción |
|--|--|
| `sudo su` | Entrar en modo super usuario |
| `clear` | Limpia la pantalla o lo que este escrito |
| `pwd` | Imprime el directorio de trabajo |
| `ip a` | Para saber el IP Address del equipo | 
| `ls -l` | Lista los archivos y directorios y sus propiedades | 
| `ls-la` | Lista los archivos y directorios incluyendo los ocultos | 
| `su` [user] | Cambiar de usuario  | 
| `sudo passwd` [user] | Cambiar la contraseña del usuario | 
| `man` [command] | Ver el manual de un comando en especifico | 
| `sudo apt install` [app] | Instalar una aplicacion en especifico  | 
| `cd` [nombre de carpeta] | Navegar entre directorios | 
| `mkdir` [nombre de carpeta] | Crear una nueva carpeta | 
| `cat` [nombre de archivo y extension] | Visualizar que contiene un archivo | 
| `nano` [nombre de archivo y extension] | Crear un archivo con un nombre y extension especifica | 
| `rm` [nombre de carpeta] | Eliminar archivos | 
| `cp` [nombre de archivo, extension y directorio] | Copiar un archivo | 
| `history` | Visualizar el historial de lo que se ha ingresado | 
| `sudo apt install htop` | Instalar la aplicacion para ver el moitor de progreso del sistema operativo | 
| `sudo chmod 777 -R *` | Da todos los permisos a los usuarios para una carperta especifica | 
| `sudo apt update` | Actualizar la lista de paquetes disponibles en los repositorios de software | 
| `sudo apt upgrade` | Actualizar los paquetes instalados en tu sistema a sus versiones más recientes disponibles en los repositorios | 
| `docker search ubuntu` | Se utiliza en Docker para buscar imágenes relacionadas con "ubuntu" en el Docker Hub | 
| `docker pull ubuntu` | Descargar una imagen del sistema operativo Ubuntu desde el Docker Hub al sistema local | 
| `docker images` | Se utiliza en Docker para listar las imágenes de contenedores que se encuentran en el sistema local | 
| `docker run ubuntu` | Se utiliza en Docker para crear y ejecutar un nuevo contenedor basado en la imagen del sistema operativo Ubuntu | 
| `sudo docker ps -a` | Listar todos los contenedores en tu sistema Docker, ya sean contenedores en ejecución o detenidos | 
| `sudo apt install cockpit` | Instalar la aplicación Cockpit | 
| `sudo systemctl start cockpit` | Iniciar el servicio de Cockpit en sistemas Linux que utilizan el sistema de inicio de systemd  | 
| `sudo apt install vsftpd` | Instalar el servidor FTP (Protocolo de Transferencia de Archivos) llamado "vsftpd" | 
| `sudo ufw status` | Verificar el estado del Firewall Uncomplicated (UFW) | 
| `sudo service vsftpd restart` | Reiniciar el servidor FTP vsftpd en sistemas que utilizan el sistema de inicio tradicional "init" para administrar servicios en Linux | 
| `sudo service vsftpd status` | Obtener el estado actual del servicio del servidor FTP vsftpd en sistemas Linux que utilizan el sistema de inicio tradicional "init" para administrar servicios | 
| `sudo systemctl restart vsftpd` | Reiniciar el servicio del servidor FTP vsftpd en sistemas Linux que utilizan el sistema de gestión de servicios "systemd" | 
| `ifconfig` |  | 
| `sudo apt openssh-server` | Mostrar información sobre las interfaces de red de tu sistema. Proporciona detalles sobre las interfaces de red disponibles, como direcciones IP, máscaras de subred, direcciones MAC, estadísticas de tráfico, etc | 
| `sudo systemctl status ssh` | Obtener el estado actual del servicio SSH en sistemas Linux que utilizan el sistema de gestión de servicios "systemd" | 
| `sudo systemctl enable ssh` | Habilitar el servicio SSH en sistemas Linux que utilizan el sistema de gestión de servicios "systemd" | 
| `sudo systemctl start ssh` | Iniciar el servicio SSH en sistemas Linux que utilizan el sistema de gestión de servicios "systemd" | 
| `sudo ufw allow ssh` | Permite el tráfico SSH a través del Firewall Uncomplicated (UFW) | 
| `sudo adduser anonimo` | Crea un nuevo usuario llamado "anonimo". El comando "adduser" se utiliza para agregar nuevos usuarios al sistema | 
| `sudo pacman -Sy` | Actualiza la base de datos de paquetes y luego sincroniza los paquetes disponibles | 
| `sudo pacman -S unrar zip unzip gzip bzip2` |  Instala varios programas y utilidades de compresión/descompresión, incluyendo unrar, zip, unzip, gzip y bzip2, en sistemas Arch Linux. | 
| `sudo pacman -S yay` | Instala el gestor de paquetes "yay" en sistemas Arch Linux. "yay" es una herramienta que facilita la instalación de paquetes de los repositorios y de AUR (Arch User Repository) | 
| `sudo yay -S --needed base-devel` | Utiliza "yay" para instalar el grupo de paquetes "base-devel" que incluye herramientas esenciales para compilar y desarrollar software en sistemas Arch Linux. | 
| `yay -S google-chrome` | Utiliza "yay" para instalar el navegador web Google Chrome desde el repositorio AUR en sistemas Arch Linux | 
| `chmod` | Cambia los permisos de acceso de archivos o directorios en sistemas Unix-like. "chmod" se utiliza para modificar los permisos de lectura, escritura y ejecución | 
| `chown` | Cambia el propietario y/o el grupo de un archivo o directorio en sistemas Unix-like. "chown" se utiliza para cambiar la propiedad de los archivos | 
| `rmdir` | Elimina un directorio vacío en sistemas Unix-like | 
| `grep -rs “papirus” $HOME` | Busca el texto "papirus" en todos los archivos dentro del directorio de inicio del usuario ($HOME) y sus subdirectorios. "grep" es una herramienta de búsqueda de patrones en texto | 




