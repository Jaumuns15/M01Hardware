# Diferencias entre 32 y 64 bits  
## Diferencias en la CPU  
* En una CPU de 32 bits solo puedes tener un sistema operativo de 32 bits y máximo 4GB de memoria RAM.    
* En una CPU de 64 bits puedes tener ambos sistemas operativos de 32 o 64 bits pero no es recomendable tener uno de 32 bits por que por mucho que la CPU sea de 64 solo podrás tener 4 GB de memoria RAM.  
* En windows para poder saber si tu CPU es de 32 o 64 bits puedes descargarte un programa(Gratuito) que se llama CPU-Z que te dice la información de tu CPU
* En linux puedes utilizas el comando lscpu para poder ver si es de 32 o 64 bits.  
## FAT32
* FAT32 es un sistema de archivos que su tamaño máximo solo puede ser de 4GB, no podrás pasar nada de mas de 4GB a FAT32  
* Siempre que hables de bits que ser con una "b" minúscula y cuando hables de bytes con "B" mayúscula
## BIOS-MBR-DOS  
* BIOS-MBR-DOS como máximo tiene 2T de memoria por partición.  
* Reglas:  
-Como máximo 4 particiones primarias.    
-Dentro de una partición extendida puede haber n lógicas.  
-Una primaria debe ser Activa.  
-EL sistema operativo(windows) necesita estar en una partición primaria y tiene que ser activa.  
