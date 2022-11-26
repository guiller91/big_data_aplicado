## **Actividad 1**

A partir del fichero [cars.csv](https://campus.edix.com/courses/1566/files/97485/download)  y usando tanto **Spark RDDs, como Spark SQL como el API de Dataframes de Spark** obtener lo siguiente:

1. Mostrar las primeras 5 filas.
2. Muestra las columnas ‘Cars’ y ‘Cylinders’ de todos los vehículos que sean de ‘Europa’.
3. Obtener la media de ‘Horsepower’, ‘Weight’ y ‘Acceleration’ por ‘Origen’.
4. Calcular el ratio entre potencia y peso y, a continuación, sacar la media por cantidad de cilindros .

## **Actividad 2**

Tenemos la necesidad de realizar el tratamiento de los datos de calidad del aire que generan las estaciones de medida de la Comunidad de Madrid.

Debemos descargar los datos de 2020 de su [página web Links to an external site ](https://datos.madrid.es/portal/site/egob/menuitem.c05c1f754a33a9fbe4b2e4b284f1a5a0/?vgnextoid=f3c0f7d512273410VgnVCM2000000c205a0aRCRD&vgnextchannel=374512b9ace9f310VgnVCM100000171f5a0aRCRD&vgnextfmt=default), en este caso, nos interesan los datos por hora recogidos durante 2020, en la propia página encontraréis información sobre su contenido.

1. Descomprime el fichero y pásalo a la máquina virtual.
2. Vamos a utilizar Spark para realizar el tratamiento batch de los datos.
3. Carga los datos de calidad de aire de todos los meses del 2020 a un dataframe de Spark.
4. Indica el número de estaciones distintas que hay en los ficheros.
5. Indica el número de los distintas MAGNITUDES que se miden.
6. Indica el número de filas que hay para el día 18-01-2020.
7. Averigua la media de dióxido de azufre a las 12h de cada día. A modo de ejemplo el resultado debería mostrar:
