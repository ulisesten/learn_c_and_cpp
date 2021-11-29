# Directivas del preprocesador

En el programa hola mundo, tanto de [c](https://github.com/ulisesten/c_and_cpp/blob/master/Ejemplos/HolaMundo/main.c) como de [c++](https://github.com/ulisesten/c_and_cpp/blob/master/Ejemplos/HolaMundo/main.cpp), vimos como primer línea, algo como esto:

    #include <stdio.h> // para c

    #include <iostream> // para c++

El proceso de construcción, que es donde convertimos nuestro código en un programa que podemos ejecutar, tienes tres etapas:

- Preprocesado
- Compilado
- Enlazado

El preprocesado es donde se elige el contenido a incluir con nuestro código; esto está relacionado con los archivos de cabecera(.h, .hpp, .hxx). También se pueden elegir secciones de código para ser excluidas.

El compilado es donde se convierte nuestro códifo en c o c++ en código máquina; es una versión ejecutable de nuestro programa.

El enlazado es donde se incluyen las librerías ya compiladas que incluímos en nuestro programa: los archivos de cabecera.
Ejemplo: `<stdio.g>`

Todas las directivas del preprocesador empiezan con el símbolo `#`.
Ejemplo: `#include, #define, #ifdef, #ifndef, #endif`
