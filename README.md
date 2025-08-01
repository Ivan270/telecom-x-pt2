# 📊 Desafío Final Data Science: Predicción de Cancelación de Clientes (Churn) - Telecom X

## 1. Descripción del Problema 📝

Una empresa de telecomunicaciones enfrenta una alta tasa de cancelaciones de clientes (churn). El objetivo de este proyecto es analizar los datos de clientes, identificar los factores que influyen en la cancelación y construir modelos predictivos que permitan anticipar el churn, facilitando la toma de decisiones estratégicas para reducir la pérdida de clientes.

## 2. Pasos Realizados en el Proyecto 🛠️

1. **Carga y exploración de datos:** Lectura del dataset tratado y análisis exploratorio inicial.
2. **Limpieza y preprocesamiento:** Eliminación de columnas irrelevantes, codificación de variables categóricas y análisis de desbalance de clases.
3. **Análisis de correlación:** Identificación de variables más correlacionadas con la cancelación.
4. **Selección de variables:** Selección de las variables más relevantes para el modelado.
5. **Separación de datos:** División en conjuntos de entrenamiento, validación y prueba.
6. **Entrenamiento de modelos:** Implementación de modelos de clasificación (Decision Tree y Random Forest), incluyendo un modelo base.
7. **Evaluación de modelos:** Uso de métricas como accuracy, recall, precisión y F1-score, además de validación cruzada y análisis de overfitting/underfitting.
8. **Balanceo de clases:** Aplicación de técnicas de oversampling (SMOTE) para mejorar el desempeño en clases desbalanceadas.
9. **Optimización y selección de variables:** Análisis de importancia de variables y optimización de hiperparámetros.
10. **Conclusiones:** Interpretación de resultados y recomendaciones estratégicas.

## 3. Herramientas Utilizadas 🧰

- **Python 3.x**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **Imbalanced-learn (SMOTE, Pipeline)**
- **Matplotlib**
- **Plotly**
- **Jupyter Notebook**

## 4. Estructura del Proyecto 📁

```
├── README.md
├── telecom-x.ipynb         # Notebook principal con todo el análisis y modelado
├── data/
│   └── datos_tratados.csv  # Dataset preprocesado listo para análisis
```

## 5. Instrucciones para Ejecutar el Jupyter Notebook 🚀

### 🖥️ Opción 1: Ejecución en entorno local

1. Clona este repositorio o descarga los archivos.
2. Instala las dependencias necesarias (se recomienda usar un entorno virtual):
   ```bash
   pip install pandas numpy scikit-learn imbalanced-learn matplotlib plotly jupyter
   ```
3. Abre una terminal en la carpeta del proyecto y ejecuta:
   ```bash
   jupyter notebook
   ```
4. Abre el archivo `telecom-x.ipynb` y ejecuta las celdas secuencialmente.

### ☁️ Opción 2: Ejecución en Google Colab

1. Sube los archivos del proyecto a tu Google Drive (incluyendo la carpeta `data/`).
2. Abre [Google Colab](https://colab.research.google.com/).
3. Sube y abre el archivo `telecom-x.ipynb`.
4. Si es necesario, ejecuta la siguiente celda al inicio del notebook para instalar las dependencias:
   ```python
   !pip install pandas numpy scikit-learn imbalanced-learn matplotlib plotly
   ```
5. Asegúrate de montar tu Google Drive si el archivo de datos está allí:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
   ```
6. Modifica la ruta de acceso al archivo CSV si es necesario (por ejemplo, `/content/drive/MyDrive/tu_carpeta/data/datos_tratados.csv`).

---
