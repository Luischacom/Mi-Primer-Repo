# Análisis de los factores que influyen en el tiempo de entrega de pedidos de delivery

## Descripción
Este proyecto analiza los tiempos de entrega de pedidos con el objetivo de identificar los factores que generan retrasos y proponer mejoras operativas basadas en datos.

---

## Objetivo
Analizar los tiempos de entrega y detectar cómo influyen variables como el tráfico, el clima, el tipo de vehículo y la ciudad en la eficiencia del servicio.

---

## Preguntas de negocio
- ¿Qué factores impactan más el tiempo de entrega?
- ¿Cómo varía el tiempo de entrega según el tráfico y el clima?
- ¿Existen diferencias significativas por ciudad o tipo de vehículo?
- ¿En qué franjas horarias se presentan más retrasos?

---

## Dataset
- Dataset de pedidos de delivery con más de 40.000 registros.
- Incluye variables temporales, geográficas y operativas.
- Dataset dividido en `train` y `test`.

---

## Proceso de análisis
1. Limpieza de datos (valores nulos, formatos incorrectos, outliers).
2. Ingeniería de variables (fechas, tiempos y categorías).
3. Análisis exploratorio de datos (EDA).
4. Definición y análisis de KPIs.
5. Visualización de resultados.
6. Conclusiones y recomendaciones.

---

## KPIs Analizados

### KPIs operativos
- Tiempo promedio de preparación
- Tiempo promedio de entrega
- Tiempo total promedio por pedido
- Calificación promedio de los pedidos

### KPIs por condiciones externas
- Tiempo por clima
- Tiempo por tráfico
- Tiempo por ciudad
- Tiempo por tipo de vehículo

### KPIs de actividad y demanda
- Actividad por día de la semana
- Pedidos por hora punta
---

## Herramientas utilizadas
- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Jupyter Notebook

---

## Resultados y conclusiones
- El tráfico alto incrementa significativamente el tiempo promedio de entrega.
- Las entregas en moto presentan mejores tiempos en horas pico.
- La distancia recorrida muestra una influencia relativa baja frente a factores operativos y contextuales.

---

## Próximos pasos
- Implementar un modelo predictivo de tiempo de entrega.
- Incorporar más variables externas (clima real, eventos).

---

## 👤 Autor
Luis Chacón


