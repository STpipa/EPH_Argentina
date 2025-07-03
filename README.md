Análisis Socioeconómico de Argentina y Modelo Predictivo de Pobreza (EPH T1 2024)
📜 Descripción del Proyecto
Este repositorio contiene un análisis de datos exhaustivo sobre la situación socioeconómica de Argentina, utilizando datos de la Encuesta Permanente de Hogares (EPH) publicada por el INDEC para el primer trimestre de 2024.

El objetivo principal del proyecto es doble:

Análisis Exploratorio (EDA): Realizar una limpieza de datos, analizar y visualizar las variables clave para extraer insights sobre la distribución de ingresos, la brecha de género y el impacto de la educación en el mercado laboral.

Modelo de Machine Learning: Construir y evaluar un modelo de clasificación supervisada para predecir si un individuo se encuentra por debajo de la línea de pobreza, basándose en sus características demográficas y laborales.

📊 Dataset
Fuente: Instituto Nacional de Estadística y Censos (INDEC) de Argentina.

Encuesta: Encuesta Permanente de Hogares (EPH).

Período: Primer Trimestre de 2024.

Archivo: usu_individual_T124.xlsx

El notebook EPH_ARGENTINA.ipynb contiene todo el proceso, desde la carga y limpieza de los datos hasta la evaluación final del modelo.

🚀 Hallazgos Principales
Análisis Descriptivo
Desigualdad de Ingresos: Se observa una fuerte asimetría en la distribución de ingresos, con una alta concentración de la población en los rangos salariales más bajos.

Brecha Salarial de Género: El análisis reveló una brecha de ingresos significativa. La mediana de ingresos de los hombres es un 28.57% superior a la de las mujeres.

Impacto de la Educación: Existe una correlación positiva y clara entre un mayor nivel educativo y el acceso a empleos formales con mejores remuneraciones.

Modelo Predictivo
Se desarrolló un modelo de clasificación Random Forest para predecir la condición de pobreza.

Performance General: El modelo alcanzó una exactitud (accuracy) del 82%.

Métrica Clave (Recall): El modelo es particularmente efectivo para identificar a las personas en situación de pobreza, logrando un recall del 89% para esta clase. Esto lo convierte en una herramienta potencialmente útil para la focalización de políticas públicas.

🛠️ Tecnologías Utilizadas
Lenguaje: Python 3

Librerías Principales:

pandas para la manipulación y limpieza de datos.

numpy para operaciones numéricas.

matplotlib y seaborn para la visualización de datos.

scikit-learn para la construcción y evaluación del modelo de Machine Learning.

Entorno: Jupyter Notebook (desarrollado en Google Colab).
