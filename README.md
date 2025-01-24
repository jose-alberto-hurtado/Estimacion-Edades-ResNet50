# Estimacion-Edades-ResNet50

Este proyecto implementa un modelo basado en ResNet50 para estimar edades a partir de imágenes. Se utilizan técnicas de preprocesamiento y modelado avanzadas para entrenar y evaluar el modelo en un conjunto de datos de imágenes etiquetadas con edades.

Contenido del Proyecto
Análisis Exploratorio de Datos (EDA): Visualización y análisis de la distribución de edades en el conjunto de datos.
Preprocesamiento de Datos: Uso de ImageDataGenerator para la generación y normalización de datos de entrenamiento y validación.
Arquitectura del Modelo: Modelo de red neuronal convolucional basado en ResNet50 preentrenado con pesos de ImageNet.
Entrenamiento del Modelo: Configuración del modelo para predecir valores continuos (edad) con técnicas como Dropout para evitar sobreajuste.
Evaluación de Resultados: Gráficas de métricas de rendimiento (MAE) y observaciones clave sobre el modelo.
Estructura del Notebook

Inicialización:
Configuración del entorno de trabajo y bibliotecas necesarias.

Carga de Datos:
Carga de imágenes y etiquetas desde un directorio y un archivo CSV.
División en datos de entrenamiento y validación.

Exploración de Datos:
Distribución de edades y visualización de imágenes representativas.

Construcción del Modelo:
Arquitectura basada en ResNet50 con capas adicionales para regresión.

Entrenamiento y Evaluación:
Entrenamiento del modelo y evaluación del rendimiento en datos de validación.

Conclusiones:
Observaciones sobre el rendimiento del modelo y recomendaciones para futuras iteraciones.

Requisitos
Para ejecutar este proyecto necesitas:

Python 3.7 o superior.
Bibliotecas: tensorflow, pandas, numpy, matplotlib, keras.

Puedes instalar los requisitos ejecutando:
pip install -r requirements.txt
Cómo Ejecutar

Descarga el repositorio:
git clone https://github.com/jose-alberto-hurtado/Estimacion-Edades-ResNet50.git
Coloca el conjunto de datos en el directorio indicado en el notebook (/datasets/faces/).
Ejecuta el notebook estimacion_edades_resnet50.ipynb en Google Colab o en tu entorno local con soporte para GPU.

Resultados del Modelo
Pérdida Final (Loss): ~26.33
MAE (Error Absoluto Medio): ~3.75
Épocas: 20

Licencia
Este proyecto está bajo la licencia MIT.

