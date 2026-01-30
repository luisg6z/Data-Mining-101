# Minería de Datos: Fundamentos y Aplicaciones

Este repositorio recopila los proyectos, prácticas y evaluaciones desarrolladas durante la asignatura de **Minería de Datos (Data Mining)**. El objetivo principal es la aplicación de técnicas avanzadas para la extracción de conocimiento, el modelado predictivo y el análisis profundo de conjuntos de datos complejos.

## 📁 Áreas de Aplicación

El repositorio está estructurado por módulos temáticos que recorren las principales metodologías de la ciencia de datos:

### 1. Análisis y Preprocesamiento de Datos
*   **Tratamiento de Datos**: Limpieza, imputación de valores nulos y normalización de variables.
*   **Análisis Exploratorio (EDA)**: Identificación de patrones, distribuciones y correlaciones estadísticas significativas.
*   *Módulos:* `data-analisys`, `practica 2`.

### 2. Aprendizaje Supervisado
*   **Modelos de Clasificación y Regresión**: Implementación de algoritmos como Regresión Lineal Múltiple y Árboles de Decisión.
*   **Máquinas de Soporte Vectorial (SVM)**: Aplicación de modelos de clasificación robustos.
*   *Módulos:* `APE_practica_3`, `SVM`, `Decision Trees`.

### 3. Aprendizaje No Supervisado
*   **Clustering**: Segmentación y agrupamiento de datos utilizando K-means.
*   **Reducción de Dimensionalidad**: Aplicación de Análisis de Componentes Principales (PCA) para la optimización de modelos.
*   *Módulos:* `kmeans`, `Dimensionalidad`.

### 4. Redes Neuronales y Procesamiento Especializado
*   **Deep Learning**: Modelado con Redes Neuronales Artificiales y Perceptrón Multicapa (MLP).
*   **Procesamiento de Lenguaje Natural (NLP)**: Extracción de características y análisis de texto.
*   **Automatización**: Creación de Pipelines de Machine Learning eficientes y escalables.
*   *Módulos:* `neural networks`, `MLP`, `NLP`, `pipelines`.

## 🛠️ Stack Tecnológico

El entorno del proyecto está optimizado con herramientas de alto rendimiento:

*   **Lenguaje**: Python 3.13+
*   **Gestión de Entorno**: `uv` (Fast Python package manager)
*   **Librerías Clave**:
    *   **Data Science**: Pandas, NumPy, SciPy.
    *   **Machine Learning**: Scikit-Learn.
    *   **Visualización**: Matplotlib, Seaborn, Plotly.
    *   **NLP**: NLTK.
    *   **Notebooks**: Jupyter (IPyKernel).

## 🚀 Configuración del Proyecto

Este repositorio utiliza `uv` para garantizar la reproducibilidad y rapidez en la gestión de dependencias.

1. **Sincronizar dependencias**:
   ```bash
   uv sync
   ```

2. **Ejecutar experimentos**:
   Si desea ejecutar los notebooks en el entorno gestionado por uv:
   ```bash
   uv run jupyter notebook
   ```

---
**Desarrollado por Luis González**
