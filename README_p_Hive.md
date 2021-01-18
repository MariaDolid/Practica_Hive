#Practica Hive README
Para empezar, en esta práctica se resuelve lo siguiente:

##Guión
(copiar guión terminado)

##Creación de ficheros

###Para el txt desde CSV como viene usar
Crear_tabla_padron_txt.txt

Si vienen cosas indefinidas al guardarse como txt, se puede usar padron_txt2 que viene también.


###Para crear en formato parquet como base la anterior:
Crear_tabla_parquet_basada_table.txt

###Para las búsquedas de los totales por distritos:
En Hive:
Hive_query_cribado1.txt

En Impala:
Impala_query_cribado1.txt

Ahora bien, hay que tener en cuenta que para txt, usamos los cribados en hive metidos en una tabla. No se puede directamente cogerlos

##Particiones
Hive_particiones.txt

Mención especial a la creación de una tabla más de txt, habiendo cambiado el formato del csv a txt.
Se ha de cambiar el formato porque csv no lee ñ etc.
Para ello hay que abrir en bloc de notas el csv y guardarlo como txt, y codificado UTF8

###Luego se hace la query en Hive de con la partición:
Hive_query_cribado2_part.txt

###Luego en Impala es importante el INVALIDATE METADATA de database.tabladfgf y refrescar con INVALIDATE METADATA en HUE 
para txt usar el propio de hive como antes en txt al menos

Impala_query_cribado2_particiones.txt

##Para otras búsquedas:
###En Hive
Hive_query_cribado3.txt

###En Impala con lo de INVALIDATE etc
Impala_query_cribado3.txt