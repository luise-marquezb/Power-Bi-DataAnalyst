# Power-Bi-DataAnalyst
Ejercicios personales power bi

*SELECCIÓN DE DATASET (KAGGLE)*

Para realizar el análisis de datos, se tomó como fuente de datos la siguiente página: 

https://www.kaggle.com/datasets/fredericksalazar/pib-gdp-global-by-countries-since-1960-to-2021

En el cual se especifica datos interesantes sobre PIB GLOBAL por países y su tasa de crecimiento en ese periodo. El archivo descargado tiene como nombre countries_gdp_hist.csv . 


*ANÁLISIS PRELIMINAR Y LIMPIEZA DE DATOS*

Este tipo de data es muy importante debido a que te permite ver el crecimiento de cada país y poder sacar conclusiones del por qué dependiendo del año y las ocurrencias hubo un aumento o descenso en su PIB. Al abrir esta data y dar una vista previa de su contenido nos encontramos con lo siguiente:

Está conformada por 10 columnas, de las cuales vimos la posibilidad de usar solo 9, descartando la columna llamada country_code, la cual solo tenia una especie de codificación para cada uno de los países, pero que no era necesaria para el análisis que íbamos a realizar.

Revisando el tipo de datos de cada columna, el resto de las 9 columnas poseen los tipo de datos correctos para utilizarlo en el dashboard a realizar.
 

*ANÁLISIS DE DATOS*

Haciendo un análisis previo de las columnas, pudimos notar que las columnas bajo el cual iban a girar las visualizaciones, son : total_gdp y Año, debido que la primera contiene el total de PIB dependiendo del Año, por lo que íbamos a variar las visualizaciones en relación al resto de las columnas buscando saber, las variaciones, los nombres de los países, las regiones a cuales pertenecían y el grupo según ingresos.

Dividimos el dashboard en 4 ventanas en las cuales buscamos poder visualizar los siguientes puntos partiendo de los anterior:

-	*Data por países*: Se utilizaron dos gráficos de líneas comparando el PIB total con cada uno de los años (1960-2021), y la variación del PIB con cada uno de los años. Adicionalmente incluimos dos ventanas de filtros para poder ver el movimiento de estos gráficos por subregiones y por países. Esto nos permite ver visualmente el crecimiento o decrecimiento según el país o la región seleccionada.


-	*Data por años*: Para esta ventana se utilizaron dos filtros (año y país) y una tarjeta y un medidos, además de un mapa coroplético. La razón de esta ventana es poder sectorizar de forma más particular un país dependiendo del año seleccionado y poder evaluarlo de forma más detallada.


-	*Data por regiones*: Luego de ver el crecimiento por países y un determinado año, es importante ver el también lo relacionado a las regiones, ya que nos determina el avance de una zona en específico. A pesar de ver variaciones negativas (por ejemplo para el año 2020), vemos que habían PIB altos en la región, esta ventana de nuestro dashboard nos permitirá evaluar el desempeño de cada región de acuerdo a un año en específico. Se utilizaron dos filtros, una tabla y un gráfico de barras, estos últimos cambian de valor según la selección de la región o el año.

 
-	*Data por tipo de ingresos*: En esta última ventana del dashboard tenemos la ubicación de las regiones y países por el tipo de ingreso que también nos permitiría ver los avances según una ubicación de estratos según los tipos de ingresos (altos, medios, bajos). Se utilizaron 3 filtros y una tabla.
 
*Algunas consideraciones*:

Cuando tenemos datos relacionados a finanzas, ingresos, egresos, crecimiento y decrecimiento, es importante poder mostrar la variabilidad que hay en un periodo de tiempo, por lo que para este dashboard se tomaron en cuenta todos estos factores. La utilización de gráficos de líneas nos permiten ver el movimiento o cambios en el tiempo según la selección de un filtro en específico. Los gráficos de barra nos permiten ver los tops según el monto de los PIB y sus respectivos países o regiones. Los filtros utilizados por otra parte, nos permiten ver o jugar con variaciones en la data a mostrar, dando dinamismo a la información mostrada.

