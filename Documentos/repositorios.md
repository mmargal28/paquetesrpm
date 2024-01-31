# Repositorios
En Rocky Linux, la gestión de paquetes se realiza principalmente a través de DNF (Dandified YUM), pero en versiones antiguas se ha usado el YUM(Yellowdog Updater, Modified) el cual sigue funcionando y comparte con el dnf, los archivos de configuración para los repositorios se encuentran en lugares específicos.

## Repositorios de DNF:
* Archivo Principal de Configuración de DNF:

  * /etc/dnf/dnf.conf: Este archivo contiene configuraciones globales para DNF. Aunque no almacena la información específica de los repositorios, puede contener configuraciones globales relacionadas con la gestión de paquetes.
* Directorio de Repositorios de DNF:

  * /etc/yum.repos.d/: Este directorio contiene archivos individuales de configuración para cada repositorio. Cada archivo representa un repositorio específico y contiene detalles sobre la URL del repositorio, habilitación, opciones de seguridad y más.
 <br>
 
![DNF](../img/dnf.png)

## Repositorios de YUM:
* Archivo Principal de Configuración de YUM:

  * /etc/yum.conf: Este archivo contiene configuraciones globales para YUM. Similar al caso de DNF, no almacena información específica de los repositorios, pero puede contener configuraciones globales para la gestión de paquetes.
* Directorio de Repositorios de YUM:

  * /etc/yum.repos.d/: Al igual que con DNF, este directorio contiene archivos individuales de configuración para cada repositorio. Cada archivo representa un repositorio específico y contiene detalles sobre la URL del repositorio, habilitación, opciones de seguridad y más.
 <br>
 
![YUM](../img/yum.png)
