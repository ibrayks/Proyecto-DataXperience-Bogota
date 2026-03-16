# Proyecto Final DataXperience: Análisis del Mercado Inmobiliario en Bogotá

Análisis completo de datos inmobiliarios en Bogotá usando Python, pandas, seaborn y scikit-learn. Incluye limpieza, EDA, estadísticas descriptivas, visualizaciones y un modelo de regresión lineal para predecir precios.

## Objetivo
Demostrar habilidades en ciencia de datos aplicadas a un problema real: entender y predecir precios de inmuebles en Bogotá.

## Dataset
- Fuente: Kaggle - [Real Estate Bogotá](https://www.kaggle.com/datasets/pablobravo73/real-estate-bogota)
- Columnas clave: Tipo, Barrio, Área, Habitaciones, Baños, Valor

## Etapas del Proyecto
1. **Preparación de Datos**  
   - Limpieza de 9520 → 5945 filas (duplicados, formatos, nulos).  
   - Evidencias: [Notebook](Proyecto_DataXperience.ipynb)

2. **Análisis Estadístico**  
   - Media precio: ~917M COP | Mediana: 450M COP  
   - Outliers detectados y relación Área-Precio positiva.

3. **Visualizaciones y Modelado**  
   - Gráficos: precio por tipo, distribución, boxplot por barrio.  
   - Regresión Lineal: R² ≈ 0.35 (explica 35% con Área, Habitaciones, Baños).  
   - Coeficientes: Área (+6.65M por m²), Baños (+352M por unidad).

## Cómo ejecutar
1. Abre el notebook en Colab: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/TU-USUARIO/Proyecto-DataXperience-Bogota/blob/main/Proyecto_DataXperience.ipynb)
2. Sube el CSV limpio o usa el link de Kaggle.

## Aprendizaje y Aplicación Profesional
Aprendí manejo de datos reales, interpretación estadística y modelado simple. En mi carrera [tu carrera], lo usaría para dashboards de precios inmobiliarios, predicciones para inversionistas o análisis de riesgo en finanzas.

## Video de Presentación
[Enlace al video en YouTube o Google Drive] (duración: ~4 min)

¡Gracias por ver! Feedback bienvenido. 🚀

#datascience #python #bogota #inmobiliario
