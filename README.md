# ChallONE-DSci-Telecom-X-p2

TelecomX - Predicción de Churn (Parte 2)
Este proyecto analiza datos de clientes de una empresa de telecomunicaciones y entrena modelos de Machine Learning para predecir la fuga de clientes (Churn).

📌 Objetivo
El propósito es identificar patrones que indiquen si un cliente dejará la compañía, utilizando técnicas de preprocesamiento, análisis exploratorio y modelos supervisados de clasificación.

📂 Contenido
El notebook TelecomX_parte_2.ipynb incluye:

Carga y preparación de datos

Lectura del archivo out.csv desde Google Drive

Eliminación de columnas irrelevantes (customerID, Unnamed: 0)

Imputación de valores faltantes con la mediana

Análisis exploratorio de datos (EDA)

Distribución de variables

Histogramas de las características

Matriz de correlación con énfasis en la variable Churn

Preprocesamiento

Escalado de variables con MinMaxScaler

Modelado

Entrenamiento con Regresión Logística y Random Forest

Evaluación con métricas como Accuracy, Precision, Recall, F1-score, ROC-AUC

Búsqueda de hiperparámetros con GridSearchCV

Evaluación de resultados

Matriz de confusión

Reporte de clasificación

🛠️ Requisitos
Instalar las siguientes librerías de Python:

bash
Copiar
Editar
pip install numpy pandas matplotlib seaborn scikit-learn
🚀 Ejecución
Subir el archivo out.csv a Google Drive en la ruta:

bash
Copiar
Editar
/MyDrive/Colab Notebooks/Challenges/challenge2-data-science-LATAM/out.csv
Abrir el notebook en Google Colab.

Ejecutar todas las celdas en orden.

📊 Salidas principales
Visualización de correlaciones entre variables y Churn

Métricas de rendimiento para cada modelo

Comparación de resultados de distintos algoritmos

📄 Licencia
Uso educativo y de investigación.

