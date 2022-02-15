# Introducción a la Ciencia de Datos

## Máster Universitario en Ciencia de Datos e Ingeniería de Computadores 21-22

### Ejercicios de Evaluación Continua

#### Análisis Exploratorio de Datos
En este fichero se incluyen un conjunto de diferentes ejercicios para calcular diversas métricas estadísticas y representar algunos gráficos visuales con los que realizar un análisis exploratorio sobre diferentes conjuntos de datos.

#### Regresión

1. En el primer ejercicio el objetivo consiste en analizar el dataset `California` para experimentar con diferentes modelos de Regresión Lineal Simple y Múltiple, añadiendo interacciones y términos no lineales.

2. En el segundo ejercicio, la primera parte consiste en aplicar validación cruzada para entrenar varios modelos con Regresión Lineal Múltiple y KNN utilizando las mismas particiones almacenadas como ficheros sobre el dataset `California`. Mientras que la segunda parte se trata de realizar comparativas mediante tests estadísticos entre los resultados obtenidos sobre varios datasets para los algoritmos de Regresión Lineal, KNN y M5.

#### Clasificación

1. Reproducir el comportamiento del algoritmo KNN para aplicar diferentes métricas con las que calcular las distancias entre muestras. Para cada métrica, aplicar diferentes valores para K y realizar varios experimentos sobre el dataset `BreastCancer`.

2. Aplicar la validación cruzada sobre Regresión Logística utilizando el dataset `BreastCancer`.

3. Entrenar tres modelos con Regresión Logística, LDA y QDA para compararlos utilizando el dataset `Smarket`.

4. Utilizando el fichero `clasif_train_alumnos.csv` se pide:
    - Comparar el comportamiento de LDA y QDA en función de los resultados de clasificación con diferentes datasets utilizando el test de Wilcoxon.
    - Realizar una comparación múltiple entre los algoritmos disponibles KNN, LDA y QDA utilizando el test de Friedman.
    - Aplicar un Post Hoc para intentar averiguar cuál es el algoritmo ganador (aunque el test de Friedman rechace).

### Trabajos teórico-prácticos

1. **Apartado de regresión**. En mi caso particular he utilizado el dataset `abalone` tanto para el desarrollo de un análisis exploratorio como para la aplicación de diferentes técnicas de regresión como son la **Regresión Lineal Simple, Múltiple y *K Nearest Neighbours* (KNN)** previa adaptación para problemas de regresión.

2. **Apartado de clasificación**. En este segundo problema se ha empleado un conjunto de datos conocido como `vehicle` para el desarrollo de su análisis exploratorio y su resolución con diversas técnicas de clasificación, como la versión para clasificación de ***K Nearest Neighbours* (KNN), *Linear Discriminant Analysis* (LDA) y *Quadratic Discriminant Analysis* (QDA)**.

Finalmente en sendos trabajos se ha realizado una comparativa estadística de los diferentes algoritmos utilizados para cada uno de los problemas contemplados a través del **test de Friedman y su *post-hoc* aplicando la penalización por pasos de Holm**.
