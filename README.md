# 🤖 MachineLearningProjects

## Descripción general

Este repositorio contiene una colección de proyectos de aprendizaje automático diseñados para desarrollar habilidades prácticas en:

- **Análisis de datos y preprocesamiento**: limpieza, imputación, escalado y manejo de desequilibrios.
- **Implementación de algoritmos clave**: desde modelos clásicos (regresión, árboles de decisión) hasta técnicas avanzadas (ensemble, redes neuronales).
- **Optimización de modelos**: búsqueda de hiperparámetros, validación cruzada y evaluación rigurosa de desempeño.
- **Documentación y visualización**: análisis de resultados con gráficos explicativos y reportes que facilitan la interpretación.

Cada proyecto incluye notebooks detallados, código modular en `src/` y documentación que describe el flujo completo del desarrollo del modelo.

---

## 🚀 Objetivos del repositorio

1. **Comprender fundamentos de ML**: aplicar conceptos teóricos a través de ejemplos prácticos con scikit-learn y TensorFlow/PyTorch.
2. **Construir pipelines reproducibles**: integrar preprocesamiento, entrenamiento y evaluación en scripts robustos.
3. **Dominar técnicas de optimización**: utilizar GridSearchCV, RandomizedSearchCV y herramientas de automatización (Optuna/Hyperopt).
4. **Interpretabilidad de modelos**: implementar SHAP, LIME y análisis de importancia de características.
5. **Escalar soluciones**: preparar modelos para producción, incluyendo serialización (Pickle, ONNX) y despliegue básico.

---

## 🗂 Estructura de carpetas

```
MachineLearningProjects/
│
├── project_01_iris_classification/
│   ├── data/                  # Dataset Iris original y procesado
│   ├── notebooks/             # Notebook paso a paso
│   ├── src/                   # Funciones de carga y preprocesamiento
│   ├── models/                # Modelos entrenados serializados
│   ├── reports/               # Resultados, gráficos y métricas
│   └── README.md              # Descripción del proyecto
│
├── project_02_titanic_survival/
│   ├── data/
│   ├── notebooks/
│   ├── src/
│   ├── models/
│   ├── reports/
│   └── README.md
│
├── project_03_customers_segmentation/
│   └── …
│
├── project_04_deep_learning_image_classification/
│   └── …
│
└── README.md                  # Este archivo de presentación
```

---

## 📁 Proyectos incluidos

1. **Clasificación de Iris**
   - **Tecnologías**: scikit-learn, pandas, matplotlib.
   - **Enfoque**: exploración de datos, modelado con KNN, SVM y evaluación comparativa.

2. **Predicción de supervivencia en Titanic**
   - **Tecnologías**: pandas, scikit-learn, XGBoost.
   - **Enfoque**: análisis de características, ingeniería de variables y modelos de ensemble.

3. **Segmentación de clientes**
   - **Tecnologías**: K-Means, DBSCAN, PCA para reducción de dimensionalidad.
   - **Enfoque**: clustering y perfilamiento de segmentos de clientes.

4. **Clasificación de imágenes con redes neuronales**
   - **Tecnologías**: TensorFlow/Keras o PyTorch.
   - **Enfoque**: construcción de CNN, data augmentation y ajuste fino.

5. **Proyecto avanzado (tú decides)**
   - Añade un caso de uso específico: NLP, series de tiempo, recomendadores, etc.

---

## 🤝 Contribuciones

Para colaborar con el repositorio:

1. Abre un **issue** detallando tu idea o error.
2. Realiza un **fork** y crea una rama (`git checkout -b feat/nombre-proyecto`).
3. Implementa y documenta tu proyecto.
4. Envía un **pull request** para revisión.

---

## 📚 Referencias y recursos

- **Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow** – Aurélien Géron.
- **Pattern Recognition and Machine Learning** – Christopher Bishop.
- Documentación oficial de scikit-learn, TensorFlow, PyTorch y XGBoost.
