# Fashion MNIST Classifier Model Card

## Descripción del modelo:

### Tipo de modelo: 
Red neuronal secuencial
### Arquitectura del modelo: 
Capa de entrada Flatten, 2 capas ocultas con activación sigmoid de 128 neuronas cada una, capa de salida con activación softmax de 10 neuronas
### Algoritmo de optimización: 
Adam
### Precisión objetivo: 
80%

## Datos de entrenamiento:

### Conjunto de datos: 
Fashion MNIST
### Número de imágenes de entrenamiento: 
60,000
### Número de imágenes de prueba: 
10,000
### Preprocesamiento de datos: 
Escalado de píxeles de 0 a 1
### Tamaño de lote (batch size): 
64
### Épocas de entrenamiento: 
10
## Métricas de rendimiento:
### Precisión de entrenamiento: 
86.74%

## Consideraciones éticas:
El clasificador se ha entrenado con datos de prendas de vestir que representan una variedad de culturas y estilos de vida, pero se debe tener cuidado al aplicar el modelo en situaciones que involucren grupos minoritarios o comunidades marginadas.

El modelo puede ser susceptible a sesgos involuntarios si los datos de entrenamiento no son representativos de la población que se desea clasificar.
## Limitaciones del modelo:
El modelo ha sido entrenado para clasificar imágenes en 10 categorías diferentes, pero puede no ser adecuado para clasificar imágenes de prendas de vestir fuera de estas categorías.
El modelo puede no ser lo suficientemente preciso para su uso en aplicaciones críticas como la seguridad pública o la atención médica.
El modelo puede requerir ajustes adicionales para su uso en dispositivos móviles o con recursos limitados de procesamiento.
