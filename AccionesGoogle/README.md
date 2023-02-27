# Descripción del proyecto

En este proyecto realizaremos un análisis sobre los precios históricos de las acciones de Google (Alphabet) en el período mayo del 2021 a octubre del 2022. Comenzamos inicialmente realizando un análisis estadístico de los precios de apertura (Open) en dicho período de tiempo. Para ello:

[Archivo csv](df_goog.csv)

Luego, implementamos un modelo GARCH, probando primero una modelación del tipo ARIMA, a la serie de tiempo anterior.

[Notebook de R](https://luisapaez.github.io/Proyectos_AnalisisDatos/AccionesGoogle/Notebook_pagina.html)

Expandiendo la fecha del primero de enero del 2016 hasta octubre del 2022, lo que haremos ahora será implementar un modelo predictivo de regresión lineal múltiple, y un modelo de red neuronal MLP (Multilayer Perceptron), para predecir el precio de apertura del día siguiente. Comparamos los resultados obtenidos por ambos modelos. 

[Notebook de Python]([df_goog.csv](https://github.com/LuisApaez/Proyectos_AnalisisDatos/blob/main/AccionesGoogle/Prediccion1.ipynb))

Después, implementamos otro modelo de red neuronal pero esta vez del tipo LSTM (Long Short-Term Memory). De nuevo, realizaremos la predicción del precio de apertura del día siguiente y compararemos los resultados con los obtenidos en los dos modelos anteriores.

[Notebook de Python](https://luisapaez.github.io/Proyectos_AnalisisDatos/AccionesGoogle/Prediccion2_LSTM.html)

Finalmente:

1. Comparamos los resultados obtenidos de cada uno de los modelos y nos quedamos con el mejor.
2. Implementamos un modelo predictivo utilizando varias regresiones lineales múltiples para realizar el pronósticos de los precios (ya sea de apertura, más bajo, más alto o de cierre) de un determinado período.

[Notebook de Python](https://github.com/LuisApaez/Proyectos_AnalisisDatos/blob/main/AccionesGoogle/Predicci%C3%B3n3.ipynb)
