# Predicción de Precios de Viviendas con Machine Learning (Ames Housing)
Proyecto end-to-end de Data Science para predecir el precio de venta de propiedades basándose en 79 variables explicativas. Se logró un modelo capaz de explicar el 91.6% de la variabilidad de los precios.

**Tecnologías:** Python, Pandas, Scikit-Learn, XGBoost, Seaborn.

**Metodología:**

1. **EDA**: Análisis de distribución y correlaciones.
2. **Limpieza**: Manejo de nulos y eliminación estratégica de outliers (que mejoró el R2 de 0.84 a 0.89).
3. **Feature Engineering**: Creación de variables sintéticas (Total_SF, Total_Bath) que resultaron ser los mejores predictores.
4. **Modelado**: Comparación entre Regresión Lineal, Random Forest y XGBoost.
5. **Resultados**: El modelo ganador fue XGBoost con los siguientes resultados en el set de prueba:
    * R2 Score: 0.9163
    * RMSE: $21,800

**Grafico Clave:**
  <img width="989" height="702" alt="Feature_importances_XGB" src="https://github.com/user-attachments/assets/a77dab29-534c-42e6-8a51-29fc4a486357" />
