# Bit-cora-Comandos
Comandos de ubuntu, Docker y manjaro
|Comandos|Descripción| ¿Cómo usarlo? Ejemplos|
|--------|-----------|-----------------------|
|`sudo`| | para instalar algún paquete, sudo apt install paq|
|`clear`|Limpia la pantalla de la terminal| Cuando la pantalla está muy cargada y ya no ocupamos ver esos datos digitamos clear|
|`cd`| Cambia el directorio en el que estamos en ese momento digitando el nuevo|Cd / (nombre del directorio) para ir a ese directorio, cd /home|
|`cp`|Copia un archivo de un origen a un destino | Cp (nombre archivo que quiero copiar) (nombre del destino donde lo quiero pegar) cp video1 dir001|
|`pwd`| nos dice el directorio actual en el que me encuentro| Si se pone pwd dentro de directorio “universidad” se imprimiría ese directorio|
|`ip a`|Muestra dirección ip de la máquina | ip a y se imprime la dirección 192… (linet)|
|`history`| Muestra el historial de todos los comandos que hemos usado|digitar history: imprime todos los comandos digitados desde el inicio por medio de un historial|
|`grep`|Busca patrones de acuerdo a la info digitada |grep 'clas1' student.txt|
|`sudo apt upadate`| Actauliza la lista de paqutes disponibles y las versiones más recientes|Se digita el comando y se imprime los archivos que necesitan actaulizarse|
|`sudo apt upgrade`|Actauliza el sistema|Se imprime en pantalla la realización de las actualizaciones y ejecuta las actualizaciones |
|`man`|Para conocer el manual y función de algún comando u acción |Sirve para no recurrir a internet, man ls|
|`whoami`|Indica que usuario estoy utilizando | Whoami, “jrojass131”|
|`sudo su`|Cambiar al super usuario root|Con este usuario no se necesita el comando “sudo”, sudo su, @root
|`exit`|Nos regresa al usuario principal |@root: exit, devuelve a= jrojass131 |
|`cd..`|Devolver la carpeta |Estamos en la carpeta “clase” pero antes estabamos en "universidad" cd.. nos devuelve a “universidad”|
|`sudo adduser`|Agrega un usuario |Puedo crear otro usuario de nombre “Katniss Everdeen” y con su propia contraseña |
|`nano`|Crea un archivo |nano script01.sh |
|`cat`|Concatena y abre archivos con su contenido | Cat script01.sh: abre su contenido|
|`more`|Misma función de cat, pero para archivos más grandes, ya que permite verlo línea por línea |more Biblia |
|`mv`|Para mover un archivo de un lugar a otro |mv<nombre de archivo><donde queremos moverlo>, mv clase universidad |
|`head`| Imprime al inicio las primeras líneas que se especifiquen en un archivo |Head-10 Biblia: imprime las primeras 10 líneas de ese archivo |
|`tail`|Imprime las últimas líneas que se especifiquen en un archivo |tail-3 Biblia: imprime las últimas 3 líneas del archivo |
|`chmod`|gestiona los permisos de archivos o bien directorios |chmod 777 |
|`mkdir`|crear carpetas o subdirectorios | mkdir dir001|
|`ls`| Muestra el contenido de una archivo, carpeta o directorio|/home, ls-l |
|`rm`|Se encarga de eliminar archivos |rm students.txt |
|`rm -r`|Eliminación recursiva |rm -r /home |
|`ps`|Estado actual de los procesos del sistema |ps -aux |
|`echo`|Puede ser usado dentro de un script bash para imprimir en la terminal |echo "Hello world"|
|`chown`|cambiar al usario dueño |chown jrojass131 students.txt |
|`tar`|comprimir archivos dentro de tar |tar script01.sh |
|--------|-----------|-----------------------|
#Manjaro
|`sudo pacman -Syy`|Actualizar el sistema |sudo pacman -Syy: empieza a actualizar en manajro|
|`sudo pacman -S`| Instalación de un programa en manjaro|sudo pacman -S paquete|
|`sudo pacman -Scc`| Limpiar el sitema en manjaro|sudo pacman -Scc: emepieza a limpira cache y demás basura|
|`pacman -R`|Elimina el paquete que se indique en manjaro |pacman -R (paquete)|
|`pacman -Q`|Muestra los paquetes instalados|pacman -Q: ...lista de paquetes|
|`yay -S google-chrome`|ibstala google chrome |ingresar en la terminal de manjaro yay -S google-chrome: se instalará chrome|
|`sudo pacman -S apache`|instala apache |una vez instaldo se puede digitar `nano /svr/html/index.html` para crear el contenido de la página|
|`neofetch`| muestra infromación del SO| neofetc: imagen del SO con la info incluida |
|`sudo pacman -S unrar zip unzip p7zip gzip bzip2 `| instala zip| zip students.txt |
|`sudo yay -S --needed base-devel`|Muestra el repositorio core |36,0 k |
|--------|-----------|-----------------------|
#Docker
|``| | |
|``| | |
|``| | |
|``| | |
|``| | |
|``| | |
|``| | |
|``| | |
|``| | |
|``| | |
|``| | |
|``| | |
