# ¿Que son los paquetes rpm?
Los paquetes RPM (Red Hat Package Manager) son un formato de archivo utilizado para la distribución de software en sistemas basados en Red Hat, como Fedora y CentOS. Estos paquetes contienen archivos binarios, scripts de instalación y metadatos necesarios para la instalación y gestión de software en sistemas Linux.
##
Características
Para el administrador de sistemas que realice mantenimiento y actualización de software, el uso de gestor de paquetes en vez de construirlos manualmente tiene ventajas como simplicidad, consistencia y la capacidad de que aquellos procesos se automaticen.

Entre las características de RPM están:

1.Los paquetes pueden ser cifrados y verificados con GPG y MD5.
2.Los archivos de código fuente (por ejemplo .tar.gz, .tar.bz2) están incluidos en SRPMs, posibilitando una verificación posterior.
3.PatchRPMs y DeltaRPMs, que son equivalentes a ficheros parche, pueden actualizar incrementalmente los paquetes RPM instalados.
4.Las dependencias pueden ser resueltas automáticamente por el gestor de paquetes.
