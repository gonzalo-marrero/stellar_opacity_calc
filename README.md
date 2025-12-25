# 🌟 Stellar Opacity Calculator

📌 **Objetivo:**  
Cálculo de la opacidad total en atmósferas estelares para dos modelos:  
- Tipo solar (T = 5000 K)  
- Modelo caliente (T = 8000 K)  

Se emplea Python y se asume LTE (equilibrio local de radiación) para calcular las poblaciones de los distintos estados de ionización y excitación mediante la **ecuación de Saha**, y a partir de ellas se determinan las opacidades. El modelo de atmósfera considera únicamente **hidrógeno**.  

📊 **Resultados:**  
Los cálculos se presentan en tablas y gráficos, mostrando la dependencia de la opacidad con la temperatura y la densidad.

🛠 **Herramientas y librerías:**  
Python 3.x, NumPy, SciPy, Astropy, Matplotlib, Seaborn

📂 **Estructura del proyecto:**  
- `notebooks/` → Notebooks con cálculos y pruebas  
- `src/` → Scripts Python para cálculos de opacidad  
- `data/` → Archivos de datos usados en los cálculos  
- `docs/` → Gráficos, tablas e informes  
- `requirements.txt` → Librerías necesarias  

🚀 **Cómo ejecutar:**  
1. Instala las librerías:  
```bash
pip install -r requirements.txt
👥 Autoría y colaboración
Este proyecto corresponde a un desarrollo de código colaborativo realizado por:

Gonzalo Marrero

Fernando Barnés Sánchez

La implementación del código, el análisis y la interpretación de resultados fueron realizados de manera conjunta como parte de un trabajo académico.
