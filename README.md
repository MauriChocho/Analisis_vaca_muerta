# Análisis de Producción Vaca Muerta (2010-2025)

Este proyecto combina **Data Engineering, Analytics y Machine Learning** para analizar la producción de hidrocarburos en la Cuenca Neuquina, Argentina.

## 🚀 Resumen del Proyecto
Se procesaron más de 3 millones de filas de datos públicos de la Secretaría de Energía para identificar patrones de productividad y entrenar un modelo predictivo de caudal operativo.

## 🛠️ Herramientas utilizadas
* **Python (Pandas, Scikit-Learn):** Limpieza de datos (ETL) y Modelado Predictivo.
* **Power BI:** Dashboard interactivo para análisis de KPIs (TEF, Caudal, GOR).
* **Random Forest Regressor:** Modelo con un **R² de 0.80** y **MAE de 1.94 bbl/día**.

## 📊 Hallazgos clave
* El modelo identificó la **Profundidad** como el factor de mayor peso (45%) en la producción.
* La ingeniería de variables (*Water Cut* y *Antigüedad*) mejoró la precisión del modelo en un 60%.

## 📂 Contenido del Repositorio
* `analisis_vaca_muerta.ipynb`: Notebook con todo el proceso de limpieza y ML.
* `data/`: (Opcional) Dataset procesado.
* `dashboard/`: Capturas del reporte de Power BI.

---
Mantenido por Mauricio Chocholacek - https://www.linkedin.com/in/mauricio-chocholacek/
