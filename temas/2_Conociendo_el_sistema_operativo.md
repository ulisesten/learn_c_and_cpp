# Conociendo el sistema operativo

## Conociendo cómo se distribuyen las herramientas de desarrollo de software en el sistema operativo.

Un programa en c o en c++, depende de archivos llamados cabeceras, con extensión .h, .hpp, .hxx, y de librerías con extensión .a, .so ó .dll.

Estos archivos se distribuyen en el sistema operativo para poderlos usar en diferentes programas. Si las rutas a estos archivos no están bien especificadas en nuestro proyecto, obtendremos errores como:

    function was not declared in this scope
    undefined reference to function

Estos errores, seremos capaces de corregirlos si conocemos bien cómo se distribuyen las dependencias en el sistema operativo y configuramos nuestro proyecto para que busque en las rutas correctas.
