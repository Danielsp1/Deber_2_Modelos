# Deber_2_Modelos
# Descripción del dataset personalizado:
Se eliminaron los vacios, se cambio el nombre de la columna "Lable" por "Malicioso?" y se cambio los valores "non-malicius" por 0 y "malicious" por 1
# Descripcion del codigo

-Ajustamos el modelo PCA a los datos de entrada y transformamos el conjunto de datos original en el nuevo espacio de características de dos dimensiones.

-Luego entrenamos un modelo de Máquinas de Soporte Vectorial (SVM) con un kernel lineal en un conjunto de datos después de dividirlo en conjuntos de entrenamiento y prueba utilizando train_test_split

-Luego se realizo la optimización de hiperparámetros para un modelo de SVM utilizando Grid Search Cross Validation (GridSearchCV).

-Luego evalúamos el rendimiento del modelo SVM optimizado en los conjuntos de validación y prueba y visualiza las curvas ROC para ambos conjuntos.

-Por ultimo calculamos los coeficientes del modelo SVM optimizado y creamos un DataFrame para visualizar las características más importantes para la clasificación de malware.

-Luego lo graficamos.
