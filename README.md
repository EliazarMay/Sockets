# Sockets
Cliente y Servidor en C

La función de este codigo es enviar un archivo desde un cliente hacia un servidor y que finalmente este responda.

Referencia: Redes de computadoras tanenbaum Capitulo: 6.1.4 Un ejemplo de programación de sockets: un servidor de archivos de Internet432

Los siguientes códigos funcionan unicamente para Linux/Unix

Para compilar primero debes instalar gcc y g++

Comando para compilar: gcc -o [nombredelejecutable] [archivoacompilar]

  *Ejemplo: gcc -o cliente cliente.c
  
El comando anterior generará un archivo ejecutable

Para ejecutar se usa ./nombredelejecutable

  *Ejemplo ./cliente
  
Se realizan los mismo procedimientos para ambos archivos (cliente.c y servidor.c)

El procedimiento es el siguiente:

* Ejecutar el sevidor (este quedará en modo espera)
* Ejecutar el cliente con los siguientes argumentos 
* ./cliente localhost [archivo] > [cualquiernombre] 
