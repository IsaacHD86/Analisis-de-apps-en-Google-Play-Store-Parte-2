# Aprendizaje Supervisado.
## Analisis-de-apps-en-Google-Play-Store-Parte-2

## 1. Exploratory Data Analysis (EDA)
Dataset: Heart Attack.csv                                                                                                                                                     
El objetivo es predecir bajo qué escenario es más probable que un paciente tenga un ataque al corazón.                                                                                    
Variables clave: Edad, tipo de dolor de pecho, colesterol, frecuencia cardíaca máxima, angina inducida por ejercicio, entre otras.                                                      
EDA realizado para identificar patrones que incrementan o disminuyen la probabilidad de un ataque al corazón.                                                                          

## 2. Clasificador k-Nearest Neighbors (k-NN)
Creación del modelo:                                                                                                                                                 
Datos preprocesados para cumplir con los requisitos de scikit-learn.                                                                                                                     
Entrenamiento del modelo para clasificar pacientes según la probabilidad de un ataque al corazón.                                                                                         
Predicción:                                                                                                                                                                        
Simulación de una nueva observación para probar el modelo utilizando el método .predict().                                                                                                     
## 3. Reconocimiento de Dígitos (MNIST Dataset)                                                                                                                                            
Descripción:                                                                                                                                                         
Conjunto de datos reducido de MNIST con 10 clases (dígitos del 0 al 9).                                                                                                     
Cada muestra es una imagen de 28x28 píxeles, con valores que representan niveles de negro.                                                                                               
Visualización:                                                                      
Las imágenes se procesaron y visualizaron utilizando herramientas de matplotlib.                                          
Entrenamiento/Test:                                                                              
División del dataset en conjuntos de entrenamiento y prueba con train_test_split.                                                                     
Entrenamiento del modelo k-NN y evaluación de su precisión con accuracy_score.                                                                      

## 4. Reconocimiento de Imagen Personal                                                  
Creación y procesamiento de una imagen personalizada (fondo negro y trazos blancos) para probar el modelo entrenado.                                 

## 5. Overfit y Underfit.                                                
Selección de parámetros k:                                     
Cálculo de precisión en los conjuntos de entrenamiento y prueba para varios valores de k.                                                  
Identificación del mejor valor para evitar overfitting o underfitting.                                     

## 6. Regresión Logística.                                                                                             
Implementación de un modelo de Regresión Logística con el algoritmo LBFGS.

## Conclusión.
Este proyecto exploró múltiples métodos de aprendizaje supervisado, desde la clasificación binaria en problemas médicos hasta el reconocimiento de patrones en datos más complejos.
Se compararon distintos modelos (k-NN y Regresión Logística), destacando las fortalezas y debilidades de cada uno.                                                                 
El proyecto proporcionó una base sólida para el análisis y predicción de datos en múltiples escenarios, incluyendo la clasificación personalizada.                                          
## Autor
Isaac Heredia Diaz
[GitHub](https://github.com/IsaacHD86)
