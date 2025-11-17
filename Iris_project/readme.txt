=== MI PROYECTO DE CIENCIA DE DATOS (TAREA 2) ===

Proyecto para la asignatura de Introducción a la Ciencia de Datos.

### 1. Descripción
Este proyecto configura un entorno de ciencia de datos, explora el dataset 'Iris' y entrena un modelo básico de clasificación.

### 2. Entorno y Librerías [cite: 93]
- Entorno: Anaconda (conda)
- Nombre del entorno: datascience_env
- Librerías clave:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - jupyterlab
- (Las versiones exactas están en el archivo environment.yml [cite: 102])

### 3. Dataset [cite: 99]
- Nombre: Iris dataset
- Fuente: Cargado desde la librería Seaborn
- Objetivo: Clasificar 3 especies de flores (setosa, versicolor, virginica) basándose en las medidas de sus pétalos y sépalos.

### 4. Modelo [cite: 99]
- Tipo: Clasificación
- Algoritmo: Árbol de Decisión (DecisionTreeClassifier)
- Rendimiento: 100.0% de precisión en el set de prueba.

### 5. Cómo reproducir [cite: 98]
1. Instalar Anaconda.
2. Crear el entorno desde el archivo: `conda env create -f environment.yml`
3. Activar el entorno: `conda activate datascience_env`
4. Iniciar Jupyter: `jupyter lab`
5. Abrir el notebook y ejecutar las celdas.