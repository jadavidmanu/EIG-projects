# Clasificación de Dígitos Manuscritos MNIST
# Integrantes:
# David Maldonado 
# Esteban Caza
# Luis Campaña
# Bolivar Alvarez
# Joffre Quinteros
## Descripción
Este proyecto implementa un modelo de clasificación de dígitos manuscritos utilizando el algoritmo RandomForest. Además, se ha mejorado la precisión del modelo calculando características de simetría vertical y horizontal.

## Métodos
- RandomForest para clasificación.
- Cálculo de simetría para diferenciar dígitos similares como el 6 y el 9.

## Pasos
1. Cargar los datos: Utilizamos los archivos CSV proporcionados para cargar los datos de entrenamiento y prueba.
2. Procesamiento de datos: Calcular la simetría de las imágenes puede ser útil para diferenciar dígitos como el 6 y el 9. Añadiremos características de simetría vertical y horizontal.
3. Entrenar el modelo: Se utilizó RandomForest para aprender de las características de los dígitos, incluyendo las nuevas características de simetría.
4. Evaluación del modelo: Evaluaremos el rendimiento del modelo utilizando la matriz de confusión.

## Resultados
El modelo alcanzó una precisión del  97.02%

## Requisitos
- Python 3.8
- pandas
- numpy
- scikit-learn
- matplotlib