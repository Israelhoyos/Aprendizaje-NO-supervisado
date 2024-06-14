# Aprendizaje-NO-supervisado

El aprendizaje no supervisado es una técnica de machine learning utilizada para identificar patrones y estructuras ocultas en los datos sin utilizar etiquetas predefinidas. A diferencia del aprendizaje supervisado, donde los modelos se entrenan con pares de entrada-salida conocidos, en el aprendizaje no supervisado, los datos no tienen etiquetas y el algoritmo debe inferir la estructura inherente de los datos.

## Tipos de Aprendizaje No Supervisado

### 1.Clustering (Agrupamiento):

* K-means: Algoritmo que divide los datos en k clusters, donde cada punto pertenece al cluster con la media más cercana.
  
* Jerárquico: Construye una jerarquía de clusters. Puede ser aglomerativo (comienza con puntos individuales y los agrupa) o divisivo (comienza con todos los puntos en un solo cluster y los divide).

* DBSCAN: Agrupa puntos que están densamente conectados, permitiendo descubrir clusters de formas arbitrarias y manejar ruido.

### 2.Reducción de Dimensionalidad:

* PCA (Principal Component Analysis): Transforma los datos en un nuevo conjunto de variables no correlacionadas llamadas componentes principales, ordenadas por la cantidad de varianza explicada.

* t-SNE (t-Distributed Stochastic Neighbor Embedding): Técnica para la reducción de dimensionalidad que es particularmente buena para visualizar datos en 2D o 3D.

### 3.Modelos de Mezcla (Mixture Models):

* Gaussian Mixture Models (GMM): Asume que los datos son una mezcla de varias distribuciones gaussianas y utiliza la estimación de máxima verosimilitud para encontrar los parámetros de las distribuciones.

### 4.Asociación de Reglas:

* Apriori: Encuentra reglas de asociación en bases de datos grandes. Es útil para el análisis de cesta de la compra.

* FP-Growth: Una alternativa al algoritmo Apriori que es más eficiente en ciertos casos.

## Proceso de Aprendizaje No Supervisado

### 1.Preprocesamiento de Datos:

* Limpiar y normalizar los datos.
* Seleccionar y/o crear las características relevantes.

### 2.Selección de Algoritmo:

* Elegir el algoritmo de clustering, reducción de dimensionalidad o modelos de mezcla que sea adecuado para el problema en cuestión.

### 3.Entrenamiento del Modelo:

* Aplicar el algoritmo a los datos para identificar patrones o reducir la dimensionalidad.

### 4.Evaluación y Validación:

* Evaluar la calidad del modelo utilizando métricas como la inercia (para K-means) o la varianza explicada (para PCA).
  
* Validar los resultados con técnicas como la validación cruzada o el análisis visual.

### 5.Interpretación de Resultados:

* Interpretar los clusters o componentes principales y relacionarlos con el dominio del problema.
----
## Conclusión
El aprendizaje no supervisado es fundamental en el análisis de datos, especialmente cuando no se dispone de etiquetas claras o cuando se busca descubrir estructuras ocultas en los datos. Mediante técnicas como el clustering, la reducción de dimensionalidad y los modelos de mezcla, es posible extraer información valiosa que puede guiar decisiones empresariales, descubrimientos científicos y mucho más. Utilizando herramientas y bibliotecas de Python, como scikit-learn, se puede implementar fácilmente estas técnicas para realizar análisis complejos y obtener insights significativos.
