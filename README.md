
# Predicción del Abandono de Empleados (Burnout)

El objetivo de este proyecto es construir un modelo de Machine Learning capaz de predecir el abandono de empleados en una empresa, a partir de un conjunto de datos proporcionados por el departamento de recursos humanos.

---

## 📌 Descripción del Proyecto
El proyecto aborda el **ciclo completo de un modelo de aprendizaje automático**:

1. **EDA simplificado**: análisis inicial de los datos para identificar variables, tipos, valores faltantes y balance de clases.  
2. **Preprocesamiento**: escalado, imputación y preparación de variables mediante *pipelines*.  
3. **Evaluación de modelos**: división en conjuntos *train/test* (holdout) y validación interna (*inner*) para optimización de hiperparámetros.  
4. **Modelos básicos**: KNN y Árboles de decisión, con análisis de hiperparámetros y coste computacional.  
5. **Modelos avanzados**: Modelos lineales (con y sin regularización) y SVMs.  
6. **Selección de modelo final**: se guarda como `modelo_final.pkl` y se generan predicciones (`predicciones.csv`).  
7. **Tarea abierta**: ampliación opcional para explorar mejoras o aspectos adicionales del problema.

---

## 🛠️ Tecnologías y Librerías Utilizadas
- **Python 3.x**
- **Jupyter Notebook**
- **Scikit-learn**: modelos, pipelines, preprocesamiento y evaluación
- **Pandas & NumPy**: manipulación y análisis de datos
- **Matplotlib & Seaborn**: visualización de resultados
- **Joblib**: guardado del modelo final

---

