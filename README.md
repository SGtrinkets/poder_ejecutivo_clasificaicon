Clasificación de Poder Ejecutivo en Constituciones
Este proyecto analiza constituciones nacionales para clasificar el nivel de poder ejecutivo utilizando técnicas de procesamiento de lenguaje natural y machine learning. El análisis se basa en el texto de los preámbulos constitucionales para predecir si una constitución otorga alto o bajo nivel de poder ejecutivo.

Descripción del Proyecto
El proyecto utiliza datos del dataset "Constitution Dataset" que incluye información sobre 190+ constituciones nacionales. Se implementan y comparan varios algoritmos de clasificación:

Naive Bayes (MultinomialNB)
Regresión Logística
Árbol de Decisión
LinearSVC (Support Vector Classifier)
Random Forest

El objetivo es clasificar las constituciones en dos categorías:

Nivel 0: Bajo poder ejecutivo (0-4 en escala original)
Nivel 1: Alto poder ejecutivo (5-7 en escala original)

Librerías Requeridas:
Instala las siguientes librerías antes de ejecutar el proyecto:
pip install pandas numpy matplotlib scikit-learn nltk



Cómo Abrir y Ejecutar

Opción 1: Visual Studio Code

1. Abre Visual Studio Code
2. Instala las extensiones:
- Python
- Jupyter
3. Abre la carpeta del proyecto
4. Abre el archivo clasificacion_poder_ejecutivo.ipynb
5. Ejecuta las celdas secuencialmente con Shift + Enter

Opción 2: Jupyter Notebook
1. Abre terminal/comando en la carpeta del proyecto
2. Ejecuta:
- jupyter notebook

3. Abre clasificacion_poder_ejecutivo.ipynb desde el navegador
4. Ejecuta las celdas secuencialmente


Funcionalidades Principales
- Preprocesamiento de texto: Limpieza y normalización de preámbulos constitucionales
- Vectorización TF-IDF: Conversión de texto a features numéricas
- Múltiples algoritmos: Comparación de 5 modelos de clasificación
- Validación cruzada: Evaluación robusta con 10-fold cross-validation
- Métricas de evaluación: Accuracy, precision, recall, F1-score y matrices de confusión
