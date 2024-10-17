# Predicción de Reservas de Petróleo
![GitHub](https://img.shields.io/badge/GitHub-Repository-lightgrey)
![Estado](https://img.shields.io/badge/Estado-Terminado-brightgreen)

## 📖 Descripción del Proyecto
El proyecto tiene como objetivo desarrollar un modelo de machine learning para predecir el volumen de reservas de petróleo y optimizar la selección de ubicaciones para abrir 200 nuevos pozos petrolíferos. Este análisis ayudará a elegir las mejores regiones basándose en los riesgos y el beneficio potencial. Este proyecto se realizo con Tripleten.

## 💻 Funcionalidades
- `Limpieza y Preparación de Datos`: Preprocesamiento de los datos de exploración geológica de tres regiones para su uso en el modelo.
- `Modelos de Predicción`: Implementación de un modelo de regresión lineal para predecir el volumen de reservas en cada región.
- `Evaluación de Riesgos y Beneficios`: Uso de la técnica de *bootstrapping* para calcular el beneficio promedio y evaluar los riesgos de pérdidas.

## 🛠 Tecnologías Utilizadas
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## ✨ Conclusiones
- `Mejor Región`: La región 1 fue identificada como la mejor opción debido a su menor riesgo y mayor ingreso promedio. Además, sus ingresos fueron más estables dentro de un rango positivo.
- `Riesgos en Otras Regiones`: Las regiones 0 y 2 presentaron mayores riesgos, con la posibilidad de obtener pérdidas según el cuantil del 5% en negativo.
- `Precisión del Modelo`: El modelo para la región 1 mostró la mejor precisión en términos de predicción del volumen de reservas, lo que refuerza la selección de esta región como la más adecuada para el desarrollo de nuevos pozos.
