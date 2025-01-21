---

# Predicción de Reservas de Petróleo en OilyGiant

---

## 🔖 Descripción del Proyecto
En este proyecto se desarrolló un modelo predictivo para identificar las ubicaciones más rentables donde OilyGiant puede abrir 200 nuevos pozos petrolíferos. Usando datos históricos de exploración y producción, se evaluaron tres regiones diferentes para determinar las reservas potenciales, riesgos y beneficios asociados a cada una. Este proyecto se realizo con TripleTen.

---

## 💻 Funcionalidades
- **Análisis Exploratorio de Datos (EDA):** Exploración visual y estadística de datos geológicos y de producción.
- **Modelado Predictivo:**
  - Entrenamiento de modelos de regresión lineal para predecir el volumen de reservas.
  - Evaluación de errores mediante RMSE (Root Mean Squared Error).
- **Cálculo de Ganancias:** Estimación de ingresos considerando costos operativos por pozo y el precio por barril.
- **Análisis de Riesgos:** Uso de bootstrapping para calcular el riesgo de pérdidas y analizar ingresos promedio y percentiles (5% y 95%).

---

## 🛠️ Tecnologías Utilizadas
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Bootstrapping

---

## 🔢 Resultados
- **Mejor Región:** Región 1
  - **Riesgo:** Solo un 1.5% de probabilidades de pérdida.
  - **Ingresos Promedio:** $45.60 millones.
  - **Estabilidad:** Ambos percentiles (5% y 95%) en rangos positivos.
- Las regiones 0 y 2 mostraron mayores riesgos y posibilidad de pérdidas, con riesgos del 6.9% y 7.6%, respectivamente.

---

## ✨ Conclusiones
- **Impacto del Proyecto:**
  Este modelo ayuda a OilyGiant a tomar decisiones estratégicas sobre dónde abrir nuevos pozos petrolíferos, optimizando las ganancias y minimizando los riesgos.
- **Elección de la Región 1:**
  La Región 1 es la mejor opción gracias a sus ingresos promedio más altos, menor riesgo y mayor estabilidad en los ingresos esperados.
- **Estabilidad en el Modelo:**
  La evaluación mediante bootstrapping garantiza que las predicciones sean confiables, reduciendo incertidumbres en la planificación de inversiones.

---
