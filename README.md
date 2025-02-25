# BetaBank_Churn_Sprint10

## Objetivo del Proyecto
Este proyecto tiene como objetivo predecir qué clientes de Beta Bank están en riesgo de abandonar el banco. Se optimizan las métricas F1 y AUC-ROC para mejorar la precisión del modelo y permitir estrategias efectivas de retención.

## Tecnologías Utilizadas
- Python
- Pandas
- Scikit-learn
- NumPy
- Técnicas de balanceo de datos (submuestreo y sobremuestreo)

## Principales Desafíos y Soluciones
1. **Desequilibrio de Clases:** Se aplicaron técnicas como submuestreo y sobremuestreo para equilibrar la distribución de datos.
2. **Optimización de Modelos:** Se entrenaron múltiples modelos, seleccionando el que mejor optimizara la métrica F1.
3. **Evaluación de Modelos:** Se compararon los resultados utilizando la métrica AUC-ROC para validar la calidad del modelo.
4. **Generalización del Modelo:** Se realizaron pruebas en un conjunto de datos de prueba para garantizar su desempeño en nuevos datos.

## Instrucciones para Ejecutar el Proyecto
1. Clonar el repositorio y navegar al directorio del proyecto.
2. Instalar las dependencias necesarias:
   ```bash
   pip install pandas numpy scikit-learn
   ```
3. Ejecutar el notebook Jupyter para realizar el análisis y entrenar los modelos.
   ```bash
   jupyter notebook
   ```
4. Seguir los pasos detallados en el notebook para la exploración, modelado y validación de los resultados.

Este proyecto permite a Beta Bank tomar decisiones informadas para reducir la fuga de clientes y mejorar su retención.

