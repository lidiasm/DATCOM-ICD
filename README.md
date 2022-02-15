# Introducción a la Ciencia de Datos

## Máster Universitario en Ciencia de Datos e Ingeniería de Computadores 21-22

### Ejercicios de Evaluación Continua

#### Análisis Exploratorio de Datos

En este fichero se incluyen un conjunto de diferentes ejercicios para calcular diversas métricas estadísticas y representar algunos gráficos visuales con los que realizar varios análisis exploratorios sobre diferentes conjuntos de datos.

#### Regresión

1. En el primer ejercicio el objetivo consiste en analizar el dataset `California` para experimentar con diferentes modelos de Regresión Lineal Simple y Múltiple, añadiendo interacciones y términos no lineales.

2. En el segundo ejercicio, la primera parte consiste en aplicar validación cruzada para entrenar varios modelos con Regresión Lineal Múltiple y *K Nearest Neighbors* (KNN) utilizando las mismas particiones almacenadas como ficheros sobre el dataset `California`. Mientras que la segunda parte trata de realizar comparativas entre diversos algoritmos, como son Regresión Lineal Simple, *K Nearest Neighbors* (KNN) y M5 utilizando el test de Friedman y su *post-hoc* aplicando la penalización por pasos de Holm.

#### Clasificación

1. En el primer ejercicio se ha implementado uan versión del algoritmo *K Nearest Neighbours* (KNN) con el que es posible aplicar diferentes métricas con las que calcular las distancias entre las muestras de entrenamiento y las de validación. Para realizar los diferentes experimentos se ha utilizado el dataset `BreastCancer` con diferentes valores de *K*.

2. El segundo ejercicio trata de aplicar validación cruzada sobre Regresión Logística utilizando, de nuevo, el dataset `BreastCancer`.

3. En el tercer ejercicio se han entrenado tres modelos con Regresión Logística, *Linear Discriminant Analysis* (LDA) y *Quadratic Discriminant Analysis* (QDA) para realizar una comparativa estadística entre sus comportamientos sobre el dataset `Smarket`.

4. Finalmente, utilizando el fichero `clasif_train_alumnos.csv` se pide:
    - Comparar el comportamiento de *Linear Discriminant Analysis* (LDA) y *Quadratic Discriminant Analysis* (QDA) en función de los resultados de clasificación obtenidos mediante diferentes utilizando el test de Wilcoxon.
    - Realizar una comparación múltiple entre los algoritmos disponibles *K Nearest Neighbours* (KNN), *Linear Discriminant Analysis* (LDA) y *Quadratic Discriminant Analysis* (QDA) utilizando el test de Friedman.
    - Aplicar su correspondiente *post-hoc* con una penalización de libre elección para intentar obtener el algoritmo ganador de la comparativa anterior.

### Trabajos teórico-prácticos

1. **Apartado de regresión**. En mi caso particular he utilizado el dataset `abalone` tanto para el desarrollo de un análisis exploratorio como para la aplicación de diferentes técnicas de regresión como son la Regresión Lineal Simple, Múltiple y *K Nearest Neighbours* (KNN) previa adaptación para problemas de regresión.

2. **Apartado de clasificación**. En este segundo problema se ha empleado un conjunto de datos conocido como `vehicle` para el desarrollo de su análisis exploratorio y su resolución con diversas técnicas de clasificación, como la versión para clasificación de *K Nearest Neighbours* (KNN), *Linear Discriminant Analysis* (LDA) y *Quadratic Discriminant Analysis* (QDA).

Finalmente en sendos trabajos se ha realizado una comparativa estadística de los diferentes algoritmos utilizados para cada uno de los problemas contemplados a través del test de Friedman y su *post-hoc* aplicando la penalización por pasos de Holm.
