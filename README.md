# 📌 Challenge Telecom X – Análisis de Evasión de Clientes

## 📖 Descripción
Este proyecto tiene como objetivo analizar la tasa de cancelación de clientes (**churn**) de la empresa ficticia **Telecom X**, identificar los factores más relevantes que influyen en la pérdida de clientes y proponer estrategias para mejorar la retención.

Se realizó un proceso completo de **ETL (Extracción, Transformación y Carga)**, análisis exploratorio de datos (**EDA**), creación y evaluación de modelos de Machine Learning, análisis de importancia de variables y conclusiones basadas en los resultados obtenidos.

---

## 📂 Estructura del Proyecto

├── data/ # Archivos de datos originales y procesados
├── figures/ # Gráficos generados durante el análisis
├── notebooks/ # Jupyter Notebooks con el desarrollo del análisis
├── README.md # Descripción del proyecto
└── requirements.txt # Librerías necesarias


---

## 🛠 Tecnologías Utilizadas
- **Python 3**
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📊 Flujo de Trabajo
1. **Limpieza de datos**
   - Eliminación de columnas irrelevantes
   - Tratamiento de valores nulos
   - Codificación de variables categóricas

2. **Análisis Exploratorio de Datos (EDA)**
   - Análisis descriptivo
   - Visualizaciones para identificar patrones y relaciones
   - Análisis de correlaciones

3. **Entrenamiento de Modelos**
   - Regresión Logística
   - Random Forest

4. **Evaluación de Modelos**
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - Matriz de confusión
   - Detección de overfitting / underfitting

5. **Análisis de Importancia de Variables**
   - Identificación de las variables más influyentes en la cancelación

6. **Conclusiones y Recomendaciones**
   - Factores que más influyen en la cancelación
   - Estrategias propuestas para retención de clientes

---

## 📈 Resultados Principales
- **Mejor modelo:** Random Forest (Accuracy: 78%)  
- **Variables más influyentes:**  
  - Tipo de contrato  
  - Cargos mensuales  
  - Tenencia de línea telefónica  

- **Estrategia recomendada:**  
  - Incentivar contratos a largo plazo  
  - Ajustar planes con cargos altos  
  - Mejorar beneficios para clientes con alto riesgo de cancelación  

---

## 🚀 Cómo Ejecutar el Proyecto
1. Clonar el repositorio:
   ```bash
   git clone https://github.com/YizGallego/telecomx-churn-analysis-parte2.git

📌 Autor
Proyecto desarrollado por Yizney Gallego Valencia como parte del Challenge Telecom X – Análisis de Evasión de Clientes.

