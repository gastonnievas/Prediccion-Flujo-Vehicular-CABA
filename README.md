# Prediccion Flujo Vehicular CABA
 Analisis exploratorio, preparación del dataset y aplicación de modelos de predicción sobre series de tiempo. Modelos de Machine Learning y Deep Learning.

# Series de tiempo - Flujo Vehicular por Unidades de Peaje AUSA

En este trabajo haré un análisis de los datasets para los años 2016, 2017, 2018, 2019 y 2020. En base a los datos y la información obtenida, se realizara una predicción para el último trimestre de 2019 y el primer trimestre de 2020.

El objetivo de este proyecto es probar modelos de Machine Learning y Deep Learning para aplicar en Series de Tiempo, comparar su funcionamiento y predicciones, y finalmente comparar los errores arrojados y sacar conclusiones.

Exploración de datos
En esta oportinidad adherimos los datos de 2016 y 2020 a la exploración de datos, intentado obtenes nueva información que nos permita lograr una mejor predicción. Haremos un estudio del dataset para la autopista Illia y pago en Efectivo, y tambien agregaremos una explotación para todos los medios de pago.

# Componentes de la serie
Calcula las componentes estacionales y tendencia de la serie. Interpreta los resultados, si es necesario con información auxiliar (por fuera del dataset) o elementos del dataset que no estés utilizando (por ejemplo, si la tendencia es negativa, ¿puede ser porque se migre a otras formas de pago?).
¿La serie posee valores atípicos? Si es así, interpreta, si es necesario con información auxiliar.

# Predicción a Futuro
Se implementan modelos que prediga el tráfico en la autopista Illia para el último trimestre del 2019, el primer trimestre de 2020.

# Transformaciones de datos necesarias.
- Evalúación de resultados. Se justifica la métrica elegida.
- Se elige un modelo benchmark y compara los resultados con este modelo.
- Optimiza los hiperparámetros del modelo.
- Intenta responder la pregunta: ¿Qué modelo funciona mejor para este problema?
- Utiliza el modelo creado para predecir el tráfico en el primer trimestre de 2020. ¿Cómo funciona?

# EDA
- Time Series resample
- Missing Values
- Atypical Values / Outliers
- Descomposición

# Modelos
- Benchmark 1: Media Móvil
- ARMA
- ARIMA
- SARIMA
- Random Forest Regressor
- XGBoost Regressor 
- Benchmark 2 : Random Forest Regressor
- Prophet
- Neural Prophet
- Redes Neuronales MLP
- Redes Neuronales Recurrentes LSTM

# Métrica
- RMSE

# Tech stack
- Python
- Pandas
- Numpy
- Matplotlib
- Sklearn
- Keras
