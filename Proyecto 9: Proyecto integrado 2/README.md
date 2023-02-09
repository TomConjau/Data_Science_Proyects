En este proyecto queremos preparar un prototipo de un modelo de ML para Zyfra. La empresa desarrolla soluciones de eficiencia para la industria pesada. El modelo debe predecir la cantidad de oro extraído del mineral de oro. Disponemos de los datos de extracción y purificación, aunque estos pueden tener algunos problemas. Es por esto que uno de nuestros primeros pasos será verificar si estos son correctos al comprobar si el cálculo de la recuperación es correcto.

Luego analizaremos los datos y veremos como cambian las concentraciones de los metales (Au, Ag, Pb) en función de la etapa de purificación.

Finalmente, construiremos y entrenaremos nuestros modelos. Se compararán diferentes modelos y se evaluarán utilizando la validación cruzada, para luego testear el mejor de estos con la muestra de prueba.

Librerías de Python utilizadas:
- pandas
- numpy
- matplotlib.pyplot
- math
- sklearn

Modelos predictivos utilizados:
- DecisionTreeRegressor
- RandomForestRegressor
- LinearRegression
- DummyRegressor
