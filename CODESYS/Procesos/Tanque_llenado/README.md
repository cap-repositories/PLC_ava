# Ejemplo de un proceso para el llenado de un tanque

### Sensores y actuadores
En este ejemplo se cuentan con los siguientes sensores:

+ Tanque lleno (**S1**, digital)
+ Tanque medio (**S2**, digital)
+ Tanque vacío (**S3**, digital)

y los siguientes actuadores:

+ Válvula líquido 1 (**A1**, digital)
+ Válvula líquido 2 (**A2**, digital)
+ Válvula de salida (**A3**, digital)
+ Motor de mezcla (**M1**, digital)

### Funcionamiento

El proceso cuenta con un tanque, que inicialmente esta vacío y su interacción con los sensores es la siguiente:
+ Cuando el tanque esta vacío el sensor **S3** se encuentra activado.
+ Cuando el tanque se llena hasta la mitad o más el sensor **S2** se activa.
+ Cuando el tanque se llena completamente el sensor **S3** se activa.

Además se cuentan con actuadores para llenar, vaciar o mezclar el liquido del tanque, la interacción de estos es la siguiente:
+ Cuando se activa **A1** el tanque se comienza a llenar con el líquido 1.
+ Cuando se activa **A2** el tanque se comienza a llenar con el líquido 2.
+ Cuando se activa **A3** el tanque se comienza a vaciar.
+ Cuando se activa **M1** los liquidos que hayan en el tanque se mezclan.

### Suposiciones

+ El tanque no se reboza

### Visualización principal

![alt text](https://github.com/cap-repositories/PLC_ava/blob/master/CODESYS/Procesos/Tanque_llenado/tanque_visualizacion_principal.JPG "visualizacion")
