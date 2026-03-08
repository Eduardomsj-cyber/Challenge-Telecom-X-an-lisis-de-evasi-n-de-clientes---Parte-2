<p align="left">
  <img src="https://img.shields.io/badge/STATUS-Finalizado-brightgreen" alt="Status: En Finalizado">
  <img src="https://img.shields.io/badge/Python-3.x-blue" alt="Python 3.x">
  <img src="https://img.shields.io/badge/Data%20Science-An%C3%A1lisis%20de%20Ventas-orange" alt="Modelo Predictivo">
</p>

# Predicción de Fuga de Clientes  - TelecomX 2

Este proyecto implementa un flujo completo de Ciencia de Datos para predecir la cancelación de servicios en una empresa de telecomunicaciones, utilizando técnicas avanzadas de preprocesamiento y modelos de Machine Learning.

## Estructura del Proyecto

1.  **Extracción y Limpieza**: Procesamiento de datos anidados en formato JSON y normalización de estructuras complejas.
2.  **Ingeniería de Características**: Transformación de variables categóricas mediante *One-Hot Encoding* y estandarización de escalas numéricas.
3.  **Balanceo de Datos**: Aplicación de la técnica **SMOTE** (Synthetic Minority Over-sampling Technique) para corregir el desbalance de clases (de un 26% a un 50/50).
4.  **Modelado Predictivo**: Implementación y evaluación comparativa de:
    *   **K-Nearest Neighbors (KNN)**
    *   **Árboles de Decisión**
    *   **Random Forest**

## Resultados Clave

*   **Modelo Ganador**: El modelo **Random Forest** obtuvo el mejor desempeño general con una exactitud del **85%**.
*   **Sensibilidad**: El modelo **KNN** demostró ser el más efectivo para detectar fugas reales con un **Recall de 0.84**, ideal para estrategias de retención agresivas.
*   **Factores de Riesgo**: Se identificó que el tipo de contrato (mes a mes) y los cargos mensuales altos son los principales disparadores de la cancelación.

## Tecnologías Utilizadas

*   **Python 3.12**
*   **Pandas & NumPy** (Manipulación de datos)
*   **Scikit-Learn** (Machine Learning & Preprocesamiento)
*   **Imbalanced-learn** (SMOTE para balanceo)
*   **Matplotlib & Seaborn** (Visualización de datos)

