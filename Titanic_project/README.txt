Proyecto de ciencia de datos . 


# Descripción del poyecto --------------------------------------------------------------

 Basado en el famoso dataset del titanic . Para estudiar quien tubo "más o menos suerte" , a la hora de sobrevivir .  Un dataset el cual da mucho juego para aprender viendo y probando varios aspectos , ya que se compone de muchas variables diferentes .

# Entorno y librerías -------------------------------------------------------------------

Entorno : Anaconda (conda) 

Nombre del entorno: datascience_env_titanic

Librerías clave : 

-Python: 3.11.14 (main, Oct 21 2025, 18:31:21) [GCC 11.2.0]
-NumPy: 2.3.4
-Pandas: 2.3.3
-Matplotlib: 3.10.6
-Seaborn: 0.13.2
-Scikit-learn: 1.7.2



# Dataset ---------------------------------------------------------------------------------

 Nombre : Titanic data set  

 Fuente: seaborn.load_dataset('titanic')   

 Objetivo : Estudiar y intentar crear patrones con el modelo , para ver quienes tubieron más o menos probabilidad de sobrevivir . 


 # Modelo -------------------------------------------------------------------------------

 Tipo : Hemos implementado un modelo de Clasificación , para ver quienes sobrevivieron y quienes no ( 0 = no sobrevivio , 1 = sobrevivio ) . 

 Algoritmo : Árbol de decisión de la librería Scikit-learn ( DecisionTreeClassifier) 

 Rendimiento : 75,42% de precisión . 

# Pasos para reproducir el modelo -------------------------------------------------------

1. Instalar Anaconda.
2. Crear el entorno desde el archivo: `conda env create -f environment.yml`
3. Activar el entorno: `conda activate datascience_env_titanic`
4. Iniciar Jupyter: `jupyter lab`
5. Abrir el notebook y ejecutar las celdas.

