# 🚀 Employee Promotion Prediction - HR Analytics Challenge

Este repositorio contiene un proyecto de **análisis predictivo** desarrollado para abordar el desafío de identificar empleados aptos para promoción en una empresa multinacional. Utilizando Machine Learning, el objetivo es predecir con precisión qué empleados serán promovidos, optimizando así el proceso de selección y acelerando la transición a roles de mayor responsabilidad.

![HR Analytics Image](https://github.com/user-attachments/assets/d17f8b14-84d5-4696-9e81-29067163e7ec)

## 📋 Descripción del Proyecto

El cliente es una gran multinacional con múltiples áreas de negocio. La promoción de empleados en roles gerenciales e inferiores es crucial, y este proyecto facilita la predicción de empleados aptos para promoción, mejorando el flujo de transiciones a nuevos roles. La solución considera variables como rendimiento, tasa de finalización de KPI y demografía para determinar las promociones de forma anticipada y precisa.

## 📑 Tabla de Contenidos

1. [Contexto](#contexto)
2. [Objetivo](#objetivo)
3. [Pipeline del Proyecto](#pipeline-del-proyecto)
4. [Modelos y Métricas](#modelos-y-métricas)
5. [Resultados](#resultados)
6. [Requisitos](#requisitos)
7. [Referencias](#referencias)

## 🔍 Contexto

La empresa identifica candidatos para promoción basándose en recomendaciones y desempeño histórico, quienes luego pasan por programas de capacitación y evaluación. Solo los empleados que completan al menos el 60% de los KPI son considerados para promoción. Sin embargo, el proceso actual resulta en demoras significativas. Con un modelo predictivo, el cliente podrá seleccionar los mejores candidatos en un punto de control específico, acelerando así el ciclo de promociones.

## 🎯 Objetivo

Desarrollar un modelo de aprendizaje automático que prediga, con base en datos históricos y de desempeño actual, si un empleado es apto para ser promovido. Esto ayudará a la empresa a optimizar su proceso de selección para promociones, reduciendo el tiempo total del ciclo de promoción.

## 🛠 Pipeline del Proyecto

1. **Exploración de Datos**: Análisis de variables clave, detección de valores faltantes y visualización de patrones.
2. **Preparación de Datos**: Limpieza de datos, codificación de variables categóricas y creación de variables.
3. **Selección y Entrenamiento de Modelos**: Entrenamiento de varios algoritmos de clasificación para predecir la promoción.
4. **Evaluación de Modelos**: Evaluación del rendimiento de los modelos usando métricas como precisión y F1-Score.
5. **Optimización y Selección Final**: Ajuste de hiperparámetros y selección del modelo con mejor rendimiento.

## 🧠 Modelos y Métricas

Se entrenaron varios modelos de clasificación, tales como:
- Árboles de Decisión
- Random Forest
- Gradient Boosting

### Métricas de Evaluación
Se usaron métricas como:
- **Precisión**: Para evaluar la exactitud general del modelo.
- **F1-Score**: Para balancear precisión y recall, dada la posible desproporción en los datos.

## 📊 Resultados

El modelo final elegido demostró una alta capacidad predictiva, proporcionando recomendaciones precisas para el equipo de recursos humanos, lo cual facilita una transición de roles más rápida y eficaz en la empresa.

## 💻 Requisitos

- Python 3.7 o superior
- Bibliotecas: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

Para instalar las dependencias:
```bash
pip install -r requirements.txt
```

## 📚 Referencias

- [Documentación de Pandas](https://pandas.pydata.org/pandas-docs/stable/)
- [Scikit-Learn](https://scikit-learn.org/stable/)
- [Analytics Vidhya - HR Analytics Challenge](https://datahack.analyticsvidhya.com/contest/)

Para más detalles sobre el proyecto, consulta el [notebook completo](./CHALLENGE_HR_ANALYTICS.ipynb).
