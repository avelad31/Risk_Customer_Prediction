# User_Default_Prediction
Este proyecto tiene como objetivo desarrollar un modelo de predicción de riesgo crediticio para identificar la probabilidad de que un cliente se convierta en un usuario default (moroso, problemas de pago de un crédito). A lo largo del proceso, se implementan diversas técnicas de análisis de datos y machine learning, que incluyen análisis exploratorio de datos (EDA), visualización mediante gráficos, y la construcción de un modelo de árbol de decisión.

El análisis se realiza utilizando un conjunto de datos crediticios que contiene información demográfica y financiera de los clientes. Los métodos aplicados permiten identificar las variables más influyentes en la morosidad crediticia y mejorar la capacidad de predecir el comportamiento de pago de los usuarios.

![image](https://github.com/user-attachments/assets/b3eb0b59-3d3f-467b-8204-0fd68b2e7be2)

Para evaluar la relación entre las variables clave (Age, Account Balance, y Tiempo de Antigüedad Laboral), generamos un mapa de calor que visualiza la matriz de correlación entre las variables. Este análisis nos permite identificar posibles correlaciones lineales entre las características que podrían impactar el riesgo crediticio del usuario.
Utilizamos la correlación de Pearson para medir la relación entre variables numéricas.

![image](https://github.com/user-attachments/assets/21ccde83-5701-48f7-ae01-aa52e72d9b6d)

El gráfico obtenido en el eje X, los bins de 'Account Balance' y en el eje Y, los valores de Weight of Evidence (WoE) para cada bin. El WoE indica si un grupo específico de la variable tiene una mayor o menor propensión al default en comparación con el grupo de referencia.

# Para mas informacion ver el archivo Credit_Analyst.ipynb
