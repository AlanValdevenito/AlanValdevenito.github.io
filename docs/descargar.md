---
title: Descargar
description: Requerimientos, descarga, instalación y ejecucion del juego
---

<!-- ##################################################################### -->

# Requerimientos

Es necesario un sistema operativo basado en Ubuntu.

<!-- ##################################################################### -->

# Descarga

Elegir un formato de descarga:
* <a href="https://github.com/AlanValdevenito/Worms/archive/refs/tags/4.zip">Descargar en formato .zip</a>
* <a href="https://github.com/AlanValdevenito/Worms/archive/refs/tags/4.tar.gz">Descargar en formato .tar.gz</a>

<!-- ##################################################################### -->

# Instalación

Es necesario instalar las dependencias del juego. Esto se encuentra automatizado mediante un script el cual debe ejecutarse desde una terminal de la siguiente forma:

```
$ ./install.sh
```

Si fallan los permisos, se le deberán conceder los mismos ejecutando:

```
$ chmod +x ./install.sh
```

# Ejecucion 

En una terminal, dentro del directorio build, ingresar el siguiente comando: 

```
$ ./server 8080
```

En otra terminal, dentro del directorio build y luego de la ejecucion del servidor, ingresar el siguiente comando: 

```
$ ./client 127.0.0.1 8080
```

<!-- ##################################################################### -->

# Documentacion 

Para más informacion acerca de la ejecucion del juego y de la jugabilidad del mismo, se recomienda leer el [Manual de Usuario](https://github.com/AlanValdevenito/Worms/blob/main/documentacion/PDF/manual_de_usuario.pdf) el cual se encuentra en el repositorio del proyecto. 

Este provee una explicación mucho más detallada y con imágenes.

<!-- ##################################################################### -->
