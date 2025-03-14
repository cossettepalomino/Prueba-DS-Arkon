# Prueba-DS-Arkon
Analisis de Datos + Modelo de Prediccion.
En Los Ángeles existe un sistema compartido de bicicletas que brinda datos anónimos acerca del uso del servicio. Se cuenta con el histórico de viajes que se han realizado desde 2016  buscará analizar a profundidad para entender el comportamiento de la demanda de los usuarios y crear un modelo de predicción del tipo de pase que se consume.

# Preparación de conjunto de datos para Modelos
Modelo de Clasificación
Diagrama de flujo de un modelo de clasificación multiclase desde el entrenamiento hasta la puesta en producción Recopilación de Datos

1. Fuente de datos: Bases de datos, archivos CSV, APIs, etc.
* Extracción/Recopilación: Se recopilan los datos relevantes para el modelo, que incluyen las características necesarias para la clasificación

2. Preprocesamiento de Datos
* Limpiar Datos: Manejo de valores faltantes, corrección de datos inconsistentes.
* Transformaciones: Escalado de características, conversión de variables categóricas a variables numéricas, normalización, etc.
* División de Datos: Separar los datos en conjuntos de entrenamiento, validación y prueba.

3. Entrenamiento del Modelo
* Selección del Algoritmo: Selección del modelo de clasificación
* Entrenamiento: Ajustar el modelo con los hiperparametros adecuados
* Evaluación del Modelo: Evaluar el rendimiento utilizando métricas adecuadas (precisión, recall, F1, matriz de confusión, etc.) en el conjunto de validación.

4. Evaluación Final
* Prueba: Evaluar el modelo final en el conjunto de prueba para obtener una estimación de su rendimiento real.
* Análisis de Resultados: Revisar métricas de rendimiento y determinar si el modelo está listo para producción.
* Puesta en Producción

5. Despliegue del Modelo: Contenedorización: Empacar el modelo en un contenedor para facilitar el despliegue
* Despliegue en Servidor: El modelo se coloca en un servidor para que pueda hacer predicciones en tiempo real o por lotes.

6. Uso en Producción:
* APIs de Predicción: Se puede exponer el modelo a través de una API RESTful para interactuar con aplicaciones externas para su consumo

7. Monitorización: Implementar monitoreo del rendimiento del modelo en producción, para detectar posibles caídas de rendimiento con el tiempo.
* Retraining: Programar un ciclo de retraining como parte de mantenimiento preventivo para evitar decrecimiento en el rendimiento debido a cambios en los datos de entrada.

![Texto alternativo](/diagrama_de_flujo.JPG)


