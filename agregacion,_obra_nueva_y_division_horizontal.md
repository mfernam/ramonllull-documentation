# Agregación, Obra Nueva y División Horizontal

*SUPUESTO DE HECHO:*

Juan García adquiere cuatro parcelas para empezar a contruir en ellos un bloque de cinco plantas con un total de veintiseis viviendas y dos plantas en subsuelo para plazas de garaje y trasteros, para su posterior promoción y venta.
Las referencias catastrales involucradas son:

**5625902BD4052N**

**5625903BD4052N**

**5625906BD4052N**

**5625904BD4052N** 

**1. Agregación**

*Procedimiento a seguir:*

El Notario crea una nueva operación correspondiente a la agrupación y descarga, uno a uno, los inmuebles correspondientes a dichas referencias catastrales, archivando el expediente una vez terminada la descarga.
1. Nos aseguramos que estamos en la pestaña de **nuevo expediente**.
2. El programa asigna un numero de expediente automáticamente.
3. Le indicamos el tipo de operación que se va a realizar.
4. Le indicamos el solicitante.
5. Insertamos una breve descripción del proyecto.
6. Con el botón derecho sobre **Operaciones** le indicamos la operación que vamos a realizar.
7. Se añaden, una a una, todas las fincas implicadas.
8. Ventana donde se cargan las referencias catastrales de las fincas implicadas en la operación de agregación.
9. Podemos visualizar las cuatro parcelas que hemos añadido en la ventana gráfica.
10. Una vez descargados todos los inmuebles, el Notario genera el fichero respondiente al inmueble resultante de la agrupación, mediante Generación de parcela resultante.![](images/ag+on+dh/ag+on+dh1.jpg)![](images/ag+on+dh/ag+on+dh2.jpg)
11. A continuación se procede a la operación de **Obra Nueva**. Sobre la parcela resultante, seleccionamos la opción **Generar expediente de obra nueva**.<br>![](images/ag+on+dh/ag+on+dh4.jpg)
12. Se abre un nuevo expediente de Obra Nueva cuya referencia catastral asignada a la parcela nueva es un código temporal asignado por la aplicación.


2. Obra Nueva

*Procedimiento a seguir*

**1.** Como ya se ha expuesto en el caso anterior (ver declaración de Obra Nueva), la planta general es la representación, dentro de la línea perimetral de la parcela, de los recintos de las distintas subparcelas o áreas de diferente grado o tipo de edificación que la componen.  Coincide con representación de la parcela en la cartografía catastral. Es lo que el RD/1997 define como superficie de ocupación en planta.<br>
A continuación sobre la planta general el técnico va a definir cada una de las plantas, en este caso cinco, que componen la edificación distinguiendo en cada una de ellas, cada una de las unidades susceptibles de aprovechamiento independiente, y a su vez, dentro de cada una de éstas, las zonas dedicadas a sus diferentes usos (vivienda, terraza, etc...). Así mismo, dentro de cada planta, la zona que no quede asignada a formar parte de una unidad independiente, se considera siempre, zona o elementos comunes. De acuerdo con la terminología catastral, todas las plantas iguales en superficie y uso dentro de una construcción reciben la denominación de planta significativa. Pero en todo caso, la aplicación distingue el nivel en que se halla cada planta.<br>
> Así por ejemplo, en la siguiente figura se puede apreciar el aspecto y distribución que tendría una planta significativa de una obra nueva con creación dentro de cada planta de unidades independientes (a su vez con sus usos respectivos). 
         
<br>![](images/ag+on+dh/ag+on+dh8.jpg)<br>Cada **planta significativa** tendrá incluidas todas las construcciones de esa planta en todos los edificios. Por ejemplo, si una parcela tiene dos edificios, uno de dos plantas y otro de una, en la planta baja estarán los dos edificios y en la primera solo el que tiene dos plantas.<br> ![](images/ag+on+dh/ag+on+dh9.jpg)<br>El proyecto consta de un edificio con dos sótanos destinados a aparcamientos y trasteros. La planta baja correspondería a la entrada /portería del edificio, cada una de las plantas altas tiene el mismo número de unidades independientes (seis por planta) excepto el ático, que sólo tiene dos unidades con sus respectivas terrazas.
	En este caso, las plantas significativas serían: 
1. La planta significativa de sótano (dos plantas en subsuelo con la misma distribución).
2. La planta significativa correspondiente a la planta baja.
3. La planta significativa correspondiente a las cuatro plantas altas (de la primera a la cuarta).
4. La planta significativa correspondiente a la planta ático. <br> En el caso que haya más de una altura para cada planta significativa se hará siguiendo la siguiente estructura: <br> ![](images/ag+on+dh/ag+on+dh10.jpg) ![](images/ag+on+dh/ag+on+dh11.jpg)


**2.** Una vez creado el esqueleto sobre el que crear el proyecto o adecuar el existente a éste, se crea el fichero dxf pulsando **Generar fichero para técnico competente**.<br> ![](images/ag+on+dh/ag+on+dh12.jpg)<br>
**3.** El técnico, desde un programa CAD, debe editarlo e ir insertando las plantas según correspondan (planta general o planta significativas).  En primer lugar, define los perímetros correspondiente a cada unidad independiente que va a formar una inmueble con referencia catastral propia e independiente. Una vez delimitadas las unidades independientes define, dentro de cada una, las zonas dedicadas a cada uso respectivo. Ej: vivienda = v; terraza=tza...
	La misma operación se realiza en las dos plantas de subsuelo para delimitar e identificar las plazas de garaje y los trasteros. 
	Sin embargo, esta operación no será necesario efectuarla en la planta baja, ya que está enteramente dedicada a usos comunes y por tanto, sólo es necesario delimitar las zonas correspondientes a los citados usos, si los hubiera.
	De esta forma, la aplicación deja identificadas las zonas correspondientes a las unidades independientes para que les pueda ser asignada una referencia catastral propia e independiente. ![Planta general](images/ag+on+dh/ag+on+dh13.jpg)![Sótano](images/ag+on+dh/ag+on+dh14.jpg) ![Planta baja](images/ag+on+dh/ag+on+dh15.jpg) ![Ático](images/ag+on+dh/ag+on+dh16.jpg)<br>
**4.** Guarda el fichero en la versión más antigua de dxf que permita el programa, y siempre le añadiremos delante de la extensión ".rx1", para que lo cargue el programa. <br> ![](images/ag+on+dh/ag+on+dh17.jpg)<br> 
**5.** Carga el fichero en la aplicación y archiva el expediente con las modificaciones introducidas. <br> ![](images/ag+on+dh/ag+on+dh18.jpg)
<br>
**6.** La aplicación debe mostrar ahora cada una de las plantas con sus divisiones correspondientes.
    
![](images/ag+on+dh/ag+on+dh19.jpg)![](images/ag+on+dh/ag+on+dh20.jpg)
<br>
![](images/ag+on+dh/ag+on+dh21.jpg)
<br> **7.** Una vez cargado el dxf del técnico, guardar el expediente.