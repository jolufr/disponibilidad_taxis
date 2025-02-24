# Predicción de Pedidos de Taxis

En este proyecto se desarrolló un modelo predictivo con el propósito de predecir la cantidad de pedidos de taxis para la próxima hora y así optimizar la disponibilidad de conductores durante las horas pico. Se busca maximizar la eficiencia operativa y mejorar la satisfacción del cliente al anticipar la demanda de taxis en los aeropuertos.

El proceso incluyó la recopilación y análisis de datos históricos de pedidos, asegurando la integridad de la información. Se exploraron tendencias, estacionalidad y ruido en los datos, lo que permitió identificar patrones clave en la demanda. Se implementaron varios modelos de Machine Learning, incluyendo **RandomForestClassifier, XGBClassifier, LGBMClassifier y MLPClassifier**, evaluados con la métrica **AUC-ROC** para medir su rendimiento.

Los resultados indicaron que el modelo basado en **LinearRegression** ofreció el mejor desempeño, logrando un **RMSE de 8.91**, el más bajo entre todas las pruebas realizadas. Además, su tiempo de entrenamiento y predicción fue significativamente menor en comparación con los modelos no lineales. Con este modelo, se podrá prever con mayor precisión la demanda de taxis y tomar decisiones estratégicas para optimizar la asignación de vehículos, maximizando así la eficiencia operativa y la rentabilidad del servicio.

## Librerías Usadas

### Procesamiento de Datos
- `pandas`
- `numpy`
- `statsmodels`
- `IPython`

### Visualización
- `matplotlib`
- `seaborn`

### Modelado Predictivo
- `catboost`
- `lightgbm`
- `xgboost`
- `sklearn`

### Métricas
- `mean_squared_error`
- `make_scorer`

---

## Cómo Ejecutar el Proyecto

1. **Clona el repositorio**:
   ```bash
   git clone https://github.com/usuario/sweet-lift-taxi-prediction.git
   cd sweet-lift-taxi-prediction
