 # Football Analytics & Machine Learning

### Descripción
- Proyecto de análisis de datos y machine learning aplicado al fútbol profesional.
- El objetivo es analizar el rendimiento de jugadores, identificar perfiles similares, clasificar posiciones y recomendar jugadores combinando métricas deportivas y valuación de mercado.
- El proyecto fue desarrollado en el marco de la materia Laboratorio de Datos (Lic. en Ciencias de Datos, UBA).

### Problemas abordados
- Agrupamiento de jugadores con características similares.
- Clasificación de la posición de juego a partir de estadísticas.
- Reducción de dimensionalidad para análisis y visualización.
- Recomendación de jugadores similares con menor costo.
- Detección de jugadores sobrevalorados e infravalorados.

### Datos
- FBRef 2020–21: estadísticas de rendimiento de jugadores profesionales.
- Transfermarkt 2019–20: valuación de mercado de jugadores.

Criterios de limpieza:
- Eliminación de jugadores con pocos minutos jugados.
- Tratamiento de valores faltantes.
- Selección de variables numéricas relevantes para modelado.

### Metodología
1️⃣ Preprocesamiento
- Limpieza de datos y manejo de valores faltantes
- Filtrado por minutos jugados
- Selección de features numéricas
- Escalado de variables

2️⃣ Análisis Exploratorio
- Visualización de distribuciones y relaciones entre variables
- Comparación de perfiles de jugadores

3️⃣ Clustering
- Reducción de dimensionalidad con PCA
- Agrupamiento con K-Means
- Agrupamiento no supervisado con DBSCAN
- Análisis e interpretación de clusters obtenidos

4️⃣ Clasificación
- Clasificación de posición de juego mediante KNN
- Selección del hiperparámetro K usando validación
- Evaluación en conjunto de test
- Comparación de modelos con y sin PCA

5️⃣ Recomendación y valuación
- Modelo predictivo para estimar el valor de mercado de jugadores
- Identificación de jugadores sobrevalorados e infravalorados
- Sistema de recomendación basado en similitud de características
- Análisis de reemplazos potenciales para jugadores de alto costo

### Resultados principales
- Identificación de clusters coherentes con roles de juego
- Buen desempeño en la clasificación de posiciones
- Detección de jugadores con alta similitud a estrellas pero menor valuación
- Ejemplos de recomendaciones justificadas mediante métricas y modelo

(Los detalles completos pueden encontrarse en el notebook del proyecto)

### Tecnologías utilizadas
- Python
- Pandas, Numpy
- Seaborn
- Scikit-learn (PCA, KMeans, DBSCAN, KNN; preprocessing, model_selection, metrics)
- Jupyter Notebook
- Keras

#### Autor
Francisco Bordaro Rojas
Estudiante de Licenciatura en Ciencias de Datos – UBA
