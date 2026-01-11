# 🛢️ Análisis Predictivo y Business Intelligence: Vaca Muerta (2010-2025)

## 📌 Descripción del Proyecto
Este proyecto integral de Data Science analiza la evolución de la Cuenca Neuquina, procesando más de **3 millones de registros** de la Secretaría de Energía de Argentina. El objetivo es doble: visualizar la transición hacia los recursos no convencionales y predecir la producción diaria de petróleo.

## 🚀 Características Técnicas
* **Pipeline de Datos:** Integración con la **Kaggle API** para la descarga y procesamiento automatizado de grandes volúmenes de datos.
* **Machine Learning:** Entrenamiento de un modelo **Random Forest Regressor** logrando un **$R^2$ de 0.80** tras una transformación logarítmica de la variable objetivo.
* **Feature Engineering:** Creación de variables críticas para la industria como *Water Cut*, *GOR (Gas Oil Ratio)* y *Antigüedad del Pozo*.
* **Business Intelligence:** Dashboard interactivo en Power BI para el seguimiento de KPIs operativos.

## 📂 Repositorios de Datos
El dataset sin procesar se encuentra disponible en Kaggle para la comunidad(se utiliza y limpia en el notebook):
🔗 [Dataset en Kaggle](https://www.kaggle.com/datasets/mauriciochocholacek/produccion-vaca-muerta-2010-2025)

## 🛠️ Requisitos para Ejecución
1. Clonar el repositorio.
2. Configurar tus credenciales de Kaggle en los **Secrets** de Colab/Entorno (`KAGGLE_USER` y `KAGGLE_KEY`).
3. Ejecutar `analisis_vaca_muerta.ipynb`.

---
**Contacto:** https://www.linkedin.com/in/mauricio-chocholacek/ | mauri.chocholacek@gmail.com
