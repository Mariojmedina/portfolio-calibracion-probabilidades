# Portfolio: Calibración de Probabilidades y Threshold

## Descripción

Este portafolio ejemplifica la importancia de calibrar las probabilidades y ajustar el threshold en problemas de clasificación, especialmente cuando equivocarse es muy costoso.

## Contenido

- **notebooks/**: Contiene el Jupyter Notebook principal con ejemplos y análisis
  - `calibracion_threshold_costly_errors.ipynb`: Notebook completo con:
    1. Introducción al problema
    2. Ejemplos de problemas donde equivocarse cuesta mucho
    3. Técnicas de calibración de probabilidades (Platt scaling, isotonic regression)
    4. Experimentación con diferentes thresholds y análisis de métricas de costo
    5. Conclusiones sobre la importancia de calibrar y elegir el threshold correcto

## Objetivo

Demostrar cómo la calibración de probabilidades y la selección adecuada del threshold pueden mejorar significativamente el desempeño de modelos de clasificación en escenarios donde los errores tienen costos asimétricos.

## Tecnologías

- Python
- Scikit-learn
- Matplotlib/Seaborn
- Jupyter Notebook
