# OpenBSD 6.2 (amd64)
Vamos a estudiar el código fuente del sistema operativo **OpenBSD** en su versión 6.2, basándonos en la arquitectura *amd64*.


## Bootstrap
El objetivo del sistema de arranque es el de cargar el kernel en memoria y empezar a ejecutarlo.
El proceso de arranque del sistema lo podemos dividir en tres fases.
 - **mbr** (master boot record): 
 - **biosboot**: 
 - **boot**: 


### mbr
En la arquitectura intel, este código es lo primero que se ejecuta. La BIOS se encarga de copiar el primer sector del disco de arranque en memoria y lo empieza a ejecutar, a este primer sector se le conoce como *mbr*. En general, este código se encarga de buscar la partición activa y cargar en memoria su primer sector. Realmente este código no se le considera propiamente del sistema operativo, debido a que podría ser otro bootloader el que se encargara de este proceso.


### biosboot



### boot





