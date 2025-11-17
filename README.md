# TPE-Fundamentos-de-la-Ciencia-de-Datos-Grupo-03
Trabajo Práctico Especial para la materia Fundamentos de la Ciencia de Datos de la carrera Ingeniería en Sistemas de la UNICEN.

Cursada: 2025
Grupo: 3
Autores:
Manuel Oñatibia
Juan Pablo Padilla
Alexis Nehuen Ramundo

---

Para poder leer El Notebook de jupyter desde visual Studio Code o (o su editor de codigo de confianza). Cargue los archivos:
AmbienteJupyter.ipynb
horse-colic.data
horse-colic.test
requirements.txt
Y ejecutar desde la terminal, el comando : "pip install -r requirements.txt"

Sobre el Proyecto
Este proyecto consiste en un análisis de punta a punta del dataset "Horse Colic" (Cólico Equino) del repositorio de Machine Learning de UC Irvine. El objetivo es aplicar el proceso completo de la ciencia de datos, desde la exploración inicial y la limpieza, hasta el planteo y la validación de hipótesis estadísticas para comprender los factores que influyen en el pronóstico de un caballo con cólico.

El trabajo se estructura siguiendo los 4 enunciados principales del TPE:
Análisis Exploratorio de Datos (EDA)
Limpieza y Pre-procesamiento de Datos
Planteo de 6 Hipótesis (Uni, Bi y Multivariadas)
Validación Estadística de Hipótesis

Contenido del Repositorio
Este repositorio contiene todos los archivos necesarios para replicar el análisis:
horse-colic.data # El dataset original (sin procesar). 
hose-colic.test # El dataset de testeo (sin procesar).
TPE_Informe.pdf # El informe final redactado según el template oficial. README.md # Este archivo.
Requirements.txt # Requisitos para ejecutar el código.
El análisis se centró en 6 hipótesis clave, de las cuales 4 fueron confirmadas, demostrando relaciones significativas entre los signos clínicos y el desenlace del paciente:

H1 (Rechazada).
H2 (Confirmada).
H3 (Confirmada).
H4 (Confirmada).
H5 (Rechazada).
H6 (Confirmada).

Tecnologías Utilizadas
Python 3.x
Pandas: Para la manipulación y limpieza de datos.
NumPy: Para operaciones numéricas.
Matplotlib / Seaborn: Para la visualización de datos (Boxplots, Scatter plots, Histogramas).
SciPy (scipy.stats): Para la ejecución de tests estadísticos (T-test, ANOVA, Chi-Cuadrado).
Scikit-learn (sklearn): Para el pre-procesamiento (OneHotEncoder) y el modelado (LogisticRegression, train_test_split).
