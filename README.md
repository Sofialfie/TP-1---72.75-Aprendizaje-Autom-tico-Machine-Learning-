# Notebooks
Desarrollo TP 1

En este trabajo práctico se implementarán modelos de regresión para predecir una variable
numérica a partir de un conjunto de datos. El objetivo principal es aprender a entrenar y
evaluar modelos utilizando validación cruzada.

0.1. Bike Sharing
Este dataset corresponde a un sistema de alquiler de bicicletas. Contiene variables
relacionadas con el clima y el calendario (temperatura, humedad, estación del año, día laboral,
etc.), y el objetivo es predecir la cantidad de bicicletas alquiladas en un momento determinado.
El dataset, así como más información sobre el mismo, está disponible en el UCI Machine
Learning Repository: https://archive.ics.uci.edu/ml/datasets/bike+sharing+datase


1. ¿Qué modelo obtuvo menor error?

Regresión polinómica de grado 3 sin regularizar: RMSE de validación = 99.35 ( en contraste de 102.39 lineal y 101.26 grado 2).

2. Si tuvieran que implementar uno de los modelos en una aplicación real, ¿cuál
elegirían? Justificar.

También grado 3 sin regularizar. Mejora real (no memoriza el train, gap ~0.77) y Lasso solo agregó sesgo (no había overfitting que corregir).

3. Si tuvieran que vendernos o publicar esa aplicación, ¿que RMSE me dirían que
esperan que tenga cuando se utilice? (i.e., Cómo esperan que el modelo elegido
funcione en datos nuevos)

RMSE final esperado sobre test (bicis/hora) : 97.58


