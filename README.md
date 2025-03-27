# taxi_demand_prediction
Creación de modelos de machine learning para predecir la demanda de taxis dentro de un periodo determinado futuro.
***Proyecto desarrollado como evaluación final del sprint 14 (series temporales) del Bootcamp de Data Scientist de TripleTen.***

## Contexto del proyecto
La compañía Sweet Lift Taxi ha recopilado datos históricos sobre pedidos de taxis en los aeropuertos. Para atraer a más conductores durante las horas pico, se necesitaba predecir la cantidad de pedidos de taxis para la hora siguiente.

## Objetivo del proyecto
Crear un modelo de machine learning para analizar la serie temporal que obtenga un score RMSE menor a 48

## Modelos de machine learning creados
- Linear Regression

## Librerías principales utilizadas
- pandas
- matplotlib
- seaborn
- sklearn
- statsmodels

## Resultados
- Se utilizó la **prueba estadísitca de Dickey-Fuller** para verificar la estacionalidad de la serie temporal.
- El modelo construido obtuvo un score RMSE de 29, un **rendimiento 40% mejor** que el esperado.
- En el archivo *codigo_proyecto* se puede observar el dasarrollo completo del proyecto, desde el análisis exploratorio hasta el entrenamiento de los modelos de machine learning.