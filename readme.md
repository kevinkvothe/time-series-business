# Tarea 2 - Instrucciones

En el archivo adjunto series.xlsx bajo tu nombre hay una serie medida mensualmente o trimestralmente para un determinado periodo temporal (la columna junto a los valores representa, en un formato no homogéneo, las fechas a las que corresponde cada uno de los valores). La mayoría de las series corresponden a la Comunidad Valenciana, hay unas pocas de España.

Además del archivo de series.xlsx puedes encontrar otros archivos xlsx, que contienen algunos regresores potenciales para las series, útiles si especificas un modelo regARIMA. En el nombre de cada uno de estos archivos se indica: 
* el año de inicio de la serie para los cuales los regresores del correspondiente archivo son de utilidad.
* la frecuencia (mensual o trimestral) asociada a los regresores.
* si deberían emplearse para series de España (ES) o de la Comunidad Valenciana.

Tu objetivo en esta tarea consiste en predecir (sobre la serie original y para la serie desestacionalizada) los valores de tu serie para 2018 (con un horizonte de 1 mes/trimestre, 2 meses/trimestres, …..., 12 meses/4 trimestres) entre un conjunto de alternativas. Selecciona al menos un modelo de la clase ETS (librería forecast), un modelo de la clase regARIMA (librería seasonal) y un modelo de los considerados sencillos. 

Para seleccionar modelos adecuados dentro de cada clase, utiliza los valores de la serie hasta 2017 (prediciendo secuencialmente, y para los diferentes horizontes, los valores de 2016 y 2017, utilizando exclusivamente los valores previos de la serie) y genera las predicciones para 2018 con todos ellos. Valora la calidad predictiva de las diferentes especificaciones en el conjunto de comprobación para selección y en el conjunto de test para cada uno de los horizontes. En las especificaciones regARIMA es necesario considerar, además de los regresores incluidos en los archivos suministrados, los regresores incluidos en el propio programa como la pascua móvil (Easter) o el ciclo semanal (Trading day).
Refleja todos los resultados alcanzados, con una justificación adecuada de los mismos, en un informe.
 
