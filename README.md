# Portfolio: Calibración de Probabilidades y Threshold

## Descripción
Este portafolio demuestra, con ejemplos reproducibles, cómo calibrar probabilidades de modelos y cómo elegir umbrales (thresholds) considerando costos asimétricos de error.

## Contenido

- notebooks/
  - calibracion_threshold_costly_errors.ipynb: Notebook sobre ajuste de thresholds bajo errores costosos, con ejemplos, métricas y recomendaciones.
  - tecnicas_calibracion_modelos.ipynb: Notebook profesional con teoría, ventajas/desventajas, código y visualizaciones para:
    - Histogram Binning
    - Platt Scaling
    - Isotonic Regression
    - Temperature Scaling
    - Beta Calibration (explicación)
    - Otros enfoques y consejos prácticos

## Calibración: visión general
Un modelo bien calibrado produce probabilidades que coinciden con frecuencias observadas. La calibración mejora decisiones basadas en riesgo, métricas de costo, y comunicación con stakeholders. En este repositorio se muestran técnicas clásicas (binning, Platt, isotonic, temperature) y cuándo usarlas.

## Cómo correr los notebooks
1. Requisitos:
   - Python 3.9+
   - Paquetes: numpy, pandas, scikit-learn, matplotlib, scipy, jupyter
2. Instalar dependencias (opcional con venv):
   - pip install -r requirements.txt (si existe) o:
   - pip install numpy pandas scikit-learn matplotlib scipy jupyter
3. Ejecutar Jupyter:
   - jupyter notebook
4. Abrir en el navegador:
   - notebooks/calibracion_threshold_costly_errors.ipynb
   - notebooks/tecnicas_calibracion_modelos.ipynb

## Propósito del repositorio
Servir como portfolio técnico y guía práctica para calibración de probabilidades y selección de thresholds en clasificación binaria con costos asimétricos.

## Tecnologías
- Python
- Scikit-learn
- Matplotlib/Seaborn
- Jupyter Notebook
