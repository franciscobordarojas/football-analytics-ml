# Football Analytics & Machine Learning

Proyecto de análisis de datos y Machine Learning aplicado a fútbol, utilizando estadísticas de rendimiento (FBRef) e información de mercado (Transfermarkt) para clustering, clasificación y recomendación de jugadores.

El proyecto se presenta como una pieza de portfolio: el análisis completo se encuentra ejecutado y los resultados pueden visualizarse directamente en la notebook incluida.

---

## Alcance del proyecto

El análisis abarca el flujo completo de un proyecto de Data Science:

- Análisis exploratorio de datos (EDA)
- Reducción de dimensionalidad con PCA
- Clustering de jugadores (K-Means y DBSCAN)
- Clasificación de posiciones
- Recomendación de jugadores considerando similitud y costo
- Estimación de valuación mediante modelos de regresión

---

## Datos

- **FBRef**: estadísticas de rendimiento por jugador y temporada.
- **Transfermarkt**: información de valor de mercado por jugador.

Los datasets se integran mediante identificadores o nombres normalizados (según disponibilidad) y se aplican filtros mínimos (por ejemplo, minutos jugados) para evitar observaciones poco representativas.

Por cuestiones de licencia y tamaño, los archivos de datos no se incluyen en el repositorio.

---

## Notebook y resultados

La notebook principal del proyecto se encuentra en:

notebooks/Football_Analytics_Portfolio.ipynb


Incluye:
- el código completo del análisis,
- visualizaciones generadas,
- métricas de evaluación de los modelos,
- y conclusiones finales.

El proyecto está pensado para ser leído y evaluado directamente a partir de la notebook, sin necesidad de ejecutar el código.

---

## Tecnologías utilizadas

- Python
- Pandas, NumPy
- Scikit-learn
- Seaborn
