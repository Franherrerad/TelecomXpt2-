# TelecomXpt2-
Parte 2 del challenge de Alura Latam

📌 Descripción del Proyecto

Este proyecto tiene como objetivo analizar la base de datos de clientes de TelecomX para identificar los factores que influyen en la cancelación de servicios (churn) y construir modelos predictivos que permitan anticipar clientes con alto riesgo de abandono.

Se incluyen las siguientes etapas:

Extracción y limpieza de datos

Transformación y estandarización

Exploración y visualización de datos

Análisis de correlación y selección de variables

Modelado predictivo y evaluación de modelos

Interpretación de resultados y conclusiones

📂 Contenido del Repositorio

datos_tratados.csv: Datos limpios y transformados listos para análisis y modelado.

TelecomX2.ipynb: Notebook principal con todo el flujo de análisis, visualización y modelado.

README.md: Este archivo, que describe el proyecto y su estructura.

🛠️ Tecnologías y Librerías Utilizadas

Lenguaje: Python 3

Librerías principales:

pandas → Manipulación de datos

numpy → Cálculos numéricos

matplotlib y seaborn → Visualización

scikit-learn → Preprocesamiento, modelado y evaluación

imblearn → Técnicas de balanceo de clases (SMOTE)

🔧 Funcionalidades

Limpieza y transformación de datos: manejo de valores nulos, codificación de variables categóricas, creación de métricas derivadas.

Análisis exploratorio: distribución de cargos diarios, proporción de churn por categoría, correlaciones entre variables.

Modelos predictivos:

Regresión Logística (con normalización y SMOTE)

Random Forest (sin normalización)

Evaluación de modelos: exactitud, precisión, recall, F1-score, matriz de confusión.

Interpretación: identificación de variables más relevantes para la predicción de cancelación de clientes.

📈 Resultados Principales

Las variables más influyentes en la cancelación son: tipo de contrato, gasto total, antigüedad del cliente y uso de servicios adicionales.

Los modelos muestran buen desempeño, destacando Random Forest para capturar interacciones complejas y Regresión Logística para interpretabilidad.

Se identificaron patrones de clientes con mayor riesgo de churn, lo que permite sugerir estrategias de retención específicas.

⚡ Uso del Proyecto

Clonar el repositorio:

git clone https://github.com/Franherrerad/TelecomXpt2-/blob/main/TelecomX2.ipynb


Abrir TelecomX2.ipynb en Google Colab o Jupyter Notebook.

Cargar los datos desde datos_tratados.csv.

Ejecutar las celdas para reproducir el análisis, visualizaciones y modelado.
