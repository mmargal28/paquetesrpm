# ¿Que son los paquetes rpm?
Los paquetes RPM (Red Hat Package Manager) son un formato de archivo utilizado para la distribución de software en sistemas basados en Red Hat, como Fedora y CentOS. Estos paquetes contienen archivos binarios, scripts de instalación y metadatos necesarios para la instalación y gestión de software en sistemas Linux.
## Caracteristicas
* Los paquetes pueden ser cifrados y verificados con GPG y MD5.
* Los archivos de código fuente (por ejemplo .tar.gz, .tar.bz2) están incluidos en SRPMs, posibilitando una verificación posterior.
* PatchRPMs y DeltaRPMs, que son equivalentes a ficheros parche, pueden actualizar incrementalmente los paquetes RPM instalados.
* Las dependencias pueden ser resueltas automáticamente por el gestor de paquetes.
### Ventajas
* Control de Versiones:
  * El formato RPM incluye información detallada sobre la versión del software, permitiendo un mejor control de versiones y actualizaciones.
* Gestión de Dependencias:
  * RPM es capaz de gestionar las dependencias de los paquetes de software, facilitando la instalación de software complejo con sus bibliotecas y componentes asociados.
* Verificación de Integridad:
  * RPM incluye mecanismos de verificación de integridad que permiten comprobar la integridad de los archivos en un paquete.
* Soporte de Firmas Digitales:
  * RPM puede verificar firmas digitales para garantizar la autenticidad de los paquetes, lo que mejora la seguridad y previene la instalación de paquetes comprometidos.
<br>
![rpm](../img/rpm.webp)
