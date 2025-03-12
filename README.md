# Equipo_Manitas
# Team Challenge: ASL Image Classification

## Descripción del Proyecto
Este proyecto tiene como objetivo construir un pipeline de clasificación de imágenes de la Lengua de Señas Americana (ASL) utilizando el conjunto de datos disponible en Kaggle. El desafío consiste en aplicar técnicas de preprocesamiento, entrenamiento y optimización de modelos usando `Scikit-learn` en un entorno de trabajo colaborativo.

## Estructura del Repositorio
- `/src/data`: Contiene los archivos de datos de entrenamiento y test en formato `.npy`.
- `/src/result_notebooks`: Notebooks con el desarrollo de los pipelines.
- `/src/utils`: Funciones auxiliares, como el preprocesamiento de datos (si se usa).
- `requirements.txt`: Librerías necesarias para ejecutar el código.
- `.gitignore`: Archivos que no deben ser incluidos en el control de versiones.

## Cómo correr el código
1. Clona este repositorio.
2. Crea un entorno virtual:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # Para Linux/Mac
   venv\Scripts\activate     # Para Windows
