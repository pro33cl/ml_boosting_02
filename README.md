# 🧠 Modelos Boosting para Predicción de Enfermedades

Notebook: ml_boosting_02.ipynb

📄 Descripción General

Este notebook implementa un flujo completo de Machine Learning basado en Boosting para predecir enfermedades a partir de datos clínicos. Se combinan varias técnicas de ensamble —AdaBoost, Gradient Boosting y XGBoost— con análisis exploratorio, preprocesamiento y tuning de hiperparámetros para maximizar el rendimiento predictivo.

📂 Contenidos del Notebook

1️⃣ Integración y exploración de datos

- Carga de tres archivos independientes y unión en un solo dataset.
- Análisis de variables categóricas y numéricas.
- Visualización de distribuciones y correlaciones.
- Observaciones sobre la variable objetivo (0 = sano, 1 = enfermedad).

2️⃣ División de datos y modelo base

- Split train/test con proporción adecuada.
- Entrenamiento de un modelo inicial de referencia.
- Evaluación mediante accuracy, precision, recall, F1, ROC y AUC.

3️⃣ Modelos Boosting

- AdaBoostClassifier
- GradientBoostingClassifier
- XGBClassifier
- Comparación de arquitectura y desempeño.

4️⃣ Optimización de hiperparámetros

- Búsqueda con GridSearchCV.
- Validación robusta.
- Entrenamiento del mejor modelo final.
- Comentarios sobre resultados y mejoras.

5️⃣ Exportación del modelo

- Guardado del modelo final con joblib.dump().

🛠️ Tecnologías Utilizadas

- Python 3
- NumPy
- Pandas
- Matplotlib / Seaborn
- SciPy
- Scikit-Learn
- XGBoost
- Joblib

▶️ Cómo Ejecutar el Notebook
1. Clonar el repositorio:

- git clone <URL>
- cd <repo>

2. Instalar dependencias:

- pip install -r requirements.txt

3. Ejecutar:

- jupyter notebook ml_boosting_02.ipynb

🎯 Objetivo del Proyecto

Construir, comparar y optimizar modelos Boosting para predecir enfermedades con alta precisión, identificando el modelo y los hiperparámetros más eficaces.

📬 Contacto

Proyecto desarrollado por Héctor Rubilar Valenzuela.
