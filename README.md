# 🚖 Predicción de Pedidos de Taxis

## 🔍 Introducción
Este proyecto desarrolla un modelo predictivo para anticipar la cantidad de pedidos de taxis en la próxima hora.  

## 🎯 Objetivo
Predecir con precisión la demanda de taxis mediante modelos de Machine Learning,  

## 🛠️ Tecnologías Utilizadas
- **Procesamiento de Datos**: pandas, numpy, statsmodels, IPython  
- **Visualización**: matplotlib, seaborn  
- **Modelado Predictivo**:  
  - Modelos evaluados: RandomForest, XGBoost, LightGBM, MLPClassifier  
  - Modelo seleccionado: Regresión Lineal (LinearRegression)  
  - Métricas de evaluación: RMSE (Root Mean Squared Error), AUC-ROC  
- **Métricas**: mean_squared_error, make_scorer  

## 📈 Pasos Clave (Metodología)
### 1️⃣ Análisis y Preparación de Datos
- Recopilación y limpieza de datos históricos de pedidos.  
- Análisis exploratorio de tendencias y estacionalidad en la demanda de taxis.  

### 2️⃣ Entrenamiento del Modelo
- Prueba de diferentes modelos de Machine Learning.  
- Selección del mejor modelo basado en la métrica RMSE.  

### 3️⃣ Optimización de la Predicción
- Comparación de modelos en términos de precisión y tiempo de cómputo.  
- Implementación del modelo de Regresión Lineal, logrando un RMSE de **8.91**.  

## 📊 Resultados
El modelo permite:
- **Mayor precisión** en la predicción de la demanda de taxis.  
- **Optimización de la asignación de vehículos**, reduciendo tiempos de espera.  
- **Mejora en la eficiencia operativa**, maximizando la rentabilidad del servicio.  

## 🚀 Cómo Ejecutarlo
```bash
Clonar este repositorio.
