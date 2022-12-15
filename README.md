# Octavo_experimento_datos_aleatorios_con_tres_ficheros_filtrados

Se analizan las medidas de  10 dispositivos conectados a tres ozm's . 

No se tienen en cuenta los transitorios de tension corriente o potencia  dado que esta circunstancia se considerara en el quinto experimento

Las medidas se realizaron el dia 11/7/2022 entre las 10:25 y las 12:37 en el laboratorio de Electrotecnia de la Escuela Politécnica Superior de la Universidad de Almeria.

Los dispositivos analizados,  asi como su orden es el siguiente:

 - 1 mains
 - 2 electric_furnace
 - 3 microwave
 - 4 television
 - 5 kettle
 - 6 vacuum_cleaner
 - 7 electric_space_heater
 - 8 electric_shower_heater
 - 9 fan
 - 10 fridge
 - 11 freezer

En este repositorio se adjunta el dataset generado (DSUAL) en formato HDFS5

NOTA:  Los ficheros  4,5 y 11 se han filtrado con objeto de eliminar los picos de potencia activa con valores negativos, es decir en caso de obtener valores de potencia negativa   hacemos las potencia reactivas y aparente cero , ademas la intensidad tambien la hacemos cero  y el coseno de fi o factor de potencia loshacemos uno. Por cierto como el dispositivo 4  tenia las medidas invertidas tambien se invierten los valores . Todos estas acciones se realizan en la fase 1 de preparacion de los datos. 
