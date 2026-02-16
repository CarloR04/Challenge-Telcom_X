📊 Telcom_X – Análisis de Churn de Clientes

## 📌 Descripción del Proyecto

Este proyecto corresponde a un análisis exploratorio de datos (EDA) enfocado en la identificación de factores asociados a la cancelación de clientes (Churn) en una empresa de telecomunicaciones ficticia denominada Telecom X.

El objetivo principal es comprender los patrones y variables que influyen en la pérdida de clientes, generando información valiosa que sirva como base para futuros modelos predictivos y estrategias de retención.

## 🎯 Objetivos

  Extraer y normalizar datos desde un archivo JSON con estructura anidada.
  
  Realizar limpieza y transformación de datos.
  
  Identificar valores nulos, inconsistencias y errores de tipo de dato.
  
  Analizar variables categóricas y numéricas relacionadas con el churn.
  
  Detectar patrones relevantes en la cancelación de clientes.
  
  Generar insights para apoyar decisiones estratégicas.

## 🗂️ Fuente de Datos

  El dataset utilizado contiene información sobre:
  
  Datos demográficos del cliente
  
  Servicios contratados
  
  Información de facturación
  
  Tipo de contrato
  
  Antigüedad del cliente
  
  Estado de cancelación (Churn)
  
  El archivo original se encuentra en formato JSON con estructura anidada, por lo que fue necesario aplicar procesos de normalización para su análisis.

## 🔄 Metodología

  El proyecto se desarrolló siguiendo tres etapas principales:

### 1️⃣ Extracción

    Carga del archivo JSON.
    
    Conversión a DataFrame usando pandas.
    
    Normalización de datos anidados.

### 2️⃣ Transformación

    Revisión de estructura del dataset (info(), shape, dtypes).
    
    Identificación de valores nulos y espacios vacíos.
    
    Corrección de tipos de datos incorrectos.
    
    Limpieza de variables categóricas.
    
    Estandarización de columnas clave.

### 3️⃣ Análisis Exploratorio (EDA)

    Análisis de variables categóricas.
    
    Revisión de valores únicos.
    
    Evaluación de la variable objetivo Churn.
    
    Exploración de variables financieras como cargos totales.
    
    Identificación de posibles relaciones entre variables y cancelación.

## 🛠️ Tecnologías Utilizadas

    Python 3
    
    Pandas
    
    JSON
    
    Google Colab / Jupyter Notebook

## 📁 Estructura del Proyecto

Telcom_X/
│

├── Telcom_X.ipynb      # Notebook principal con el análisis 

└── README.md           # Documentación del proyecto


## 📊 Principales Hallazgos

  Durante el análisis se identificaron:
  
    Presencia de valores vacíos en la variable Churn.
    
    Inconsistencias en el tipo de dato de los cargos totales.
    
    Variables categóricas con múltiples valores únicos que requieren estandarización.
    
  Factores potencialmente relacionados con la cancelación, como:
    
    Tipo de contrato
  
    Antigüedad del cliente
  
    Cargos mensuales y totales
    
    Servicios adicionales contratados

Estos hallazgos permiten sentar las bases para el desarrollo de modelos predictivos de churn. 

## ✒️ Mentores ✒️

Con mucho agradecimiento por el conocimiento impartido a los tutores de Alura Latam: 

- Alvaro Camacho https://github.com/ahcamachod
- Alejandro Gamarra https://github.com/ElProfeAlejo


## 👤 Autor

| [<img src="https://avatars.githubusercontent.com/u/225071618?v=4&size=64" width=115><br><sub>Carlo Robles</sub>](https://github.com/CarloR04) |  
| :---: |


Carlos Robles
Ingeniero Industrial | Data Analytics & Data Engineering Jr

📍 Colombia
