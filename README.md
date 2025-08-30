# Caso 8: Clasificación (Ciberseguridad)

## Contexto
Proyecto de detección de **intrusiones en transacciones** mediante modelos de clasificación binaria (Normal vs Ataque). El objetivo es alcanzar un **F1-score ≥ 80%** con una matriz de confusión que refleje un bajo número de falsos negativos. Se utiliza la metodología **ASUM-DM**

## Metodología
- **Exploración**: definición de variable **Y**, revisión de distribución de clases, variables categóricas y numéricas.  
- **Preparación**: manejo de datos nulos, eliminación de variables innecesarias y manejo de desbalance.  
- **Transformación**: construcción de pipeline mediante **MinMaxScaler()** para variables numéricas y **OneHotEncoder()** para variables categóricas.  
- **Modelado**: entrenamiento y comparación de algoritmos (**Regresión Logística, Árboles, Random Forest, SVM, Gradient Boosting**) con validación cruzada.
- **Evaluación**: verificación de los modelos mediante matriz de confusión y reporte de confusión

## Tecnologías
- Python  
- Pandas
- Scikit-learn  
- Matplotlib, Seaborn  
- Jupyter Notebook
