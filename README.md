# Proyecto Final: Pronóstico de Temperatura Diaria en Melbourne (Series de Tiempo)

Repositorio del proyecto de **Modelos de Pronóstico / Series de Tiempo** de la  
**Universidad Autónoma de Querétaro – Facultad de Informática**  
**Ingeniería en Ciencia y Analítica de Datos (CAD22)**  
Por: 
- Jesus Gabriel Gudiño Lara
- Ana Rosa Ramírez López
- 
> Pronóstico de la temperatura mínima diaria en Melbourne (Australia) usando modelos estadísticos, Machine Learning y Deep Learning.

---

## 1. Descripción del proyecto

Este proyecto implementa un sistema de pronóstico para la **temperatura mínima diaria** de la ciudad de **Melbourne, Australia**, a partir de la serie histórica 1981–1990 (dataset *Daily Minimum Temperatures*).

El objetivo principal es:

- Construir y comparar distintos modelos de series de tiempo para **predecir los próximos 7 días** de temperatura mínima.
- Evaluar el desempeño mediante métricas estándar (MAE, RMSE, MAPE).
- Analizar visualmente la calidad de los pronósticos y su plausibilidad física (en particular para la primera semana de 1991).

El proyecto forma parte de la práctica/proyecto parcial de la materia:

- **Curso:** Modelos de Pronóstico / Series de Tiempo  
- **Profesor:** Dr. Martín Muñoz Mandujano  
- **Semestre:** 5º

---

## 2. Estructura del repositorio

La estructura sugerida del repositorio es la siguiente (puedes ajustarla a tu organización real):

```bash
.
├── data/
│   └── 1_Daily_minimum_temps.xlsx   # Dataset original (Daily Minimum Temperatures)
├── notebooks/
│   └── ProyectoFinal.ipynb          # Notebook principal con todo el análisis
├── reports/
│   ├── ProyectoFinal_SeriesTemporales.pdf   # Reporte en PDF (entregable)
│   └── Notebook-ProyectoFinal.pdf          # Versión exportada del notebook
└── README.md
```
## 3. Requisitos e instalación

3.1. Requisitos
	•	Python 3.9+ (idealmente 3.9–3.11)
	•	Entorno virtual (recomendado): venv, conda, mamba, etc.

3.2. Librerías principales

Instalación rápida con pip:
pip install numpy pandas matplotlib seaborn scikit-learn statsmodels xgboost tensorflow

Librerías usadas:
	•	pandas, numpy – manejo de datos y series de tiempo.
	•	matplotlib, seaborn – visualización.
	•	scikit-learn – escalado, métricas, regresión lineal.
	•	statsmodels – descomposición estacional, ACF/PACF.
	•	xgboost – modelo de gradient boosting para regresión.
	•	tensorflow / keras – red LSTM para pronóstico multistep.

