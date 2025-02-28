# RRHH-analisis-de-personal

# 📊 Capstone Project: Providing Data-Driven Suggestions for HR

📌 **Resumen del Proyecto**
Este proyecto analiza datos de Recursos Humanos mediante técnicas de Machine Learning y análisis exploratorio para mejorar la toma de decisiones en gestión del talento. Utilizamos **Python, Pandas, Seaborn, XGBoost y Scikit-Learn** para la limpieza, exploración y modelización de datos.

📌 **Entendimiento del Negocio**
🎯 **Problema a Resolver**
Las empresas enfrentan desafíos al intentar reducir la rotación de empleados y mejorar la retención del talento. Sin embargo, la interpretación de los datos de RRHH puede ser compleja. El objetivo es:

✔ Identificar factores clave que influyen en la retención de empleados.
✔ Analizar tendencias en desempeño y satisfacción laboral.
✔ Optimizar estrategias de recursos humanos con base en datos.

📌 **Comprensión de los Datos**
El dataset utilizado contiene información sobre empleados, rendimiento, evaluaciones y métricas de satisfacción laboral.

📌 **Estructura de los datos:**
- **Employee_ID** → Identificador único del empleado.
- **Department** → Área de trabajo.
- **Tenure** → Tiempo en la empresa.
- **Satisfaction_Score** → Nivel de satisfacción laboral.
- **Performance_Score** → Evaluación de desempeño.
- **Promotion_Last_5_Years** → Indica si recibió una promoción reciente.

📊 **Exploración de Datos Inicial**
✔ Limpieza de datos y manejo de valores nulos.
✔ Conversión de fechas y categorización de variables.
✔ Visualización inicial de distribuciones y correlaciones.

📌 **Modelización y Evaluación**
Se realizaron distintos análisis exploratorios y modelos predictivos:
✔ Histogramas y diagramas de dispersión para identificar tendencias.
✔ Matrices de correlación entre desempeño, promociones y satisfacción.
✔ Modelos de clasificación (XGBoost, Random Forest, Logistic Regression).
✔ Evaluación con métricas como precisión, recall y AUC-ROC.

📌 **Conclusión**
📌 **Hallazgos clave:**
🔹 La satisfacción laboral tiene una fuerte correlación con la retención de empleados.
🔹 Los empleados con mayor tiempo en la empresa tienden a tener mayor estabilidad.
🔹 La promoción en los últimos 5 años influye positivamente en la permanencia de los empleados.

🎯 **Próximos Pasos:**
✔ Implementar un dashboard interactivo con Streamlit/Tableau para visualizar métricas clave.
✔ Incorporar modelos de predicción de rotación de empleados.
✔ Analizar factores externos como condiciones del mercado laboral.

🚀 **Cómo Ejecutar este Proyecto**
```bash
# Clonar este repositorio
git clone https://github.com/tu-usuario/hr-data-analysis.git

# Instalar dependencias necesarias
pip install -r requirements.txt

# Ejecutar el análisis de datos
python scripts/eda_rrhh.py

# Ejecutar dashboard interactivo
python dashboard_interactivo.py
```

