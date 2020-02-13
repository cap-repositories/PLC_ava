# TEST DE ENTRADAS
Este test se utiliza para probar las entradas y salidas integradas en el micro850:

+ Descargue y descomprima el archivo *prueba_entrada.zip*
+ Abra el archivo *prueba_plc_micro850_1.ccwsln* en **Connected Components Workbench**
+ Descargue el programa en el micro850
+ Connecte **COM0** y **COM1** (de las entradas digitales) a GND
+ Conecte uno a uno los puertos (a 24V) y verifique que las salidas correspondientes se encienden:

| Puerto de entrada | Salida Correspondiente |
|-------------------|------------------------|
|         0         |            0           |
|         1         |            1           |
|         2         |            2           |
|         3         |            3           |
|         4         |            4           |
|         5         |            5           |
|         6         |            6           |
|         7         |            7           |
|         8         |            8           |
|         9         |            9           |
|         10        |          0 y 1         |
|         11        |          2 y 3         |
|         12        |          4 y 5         |
|         13        |          6 y 7         |
