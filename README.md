# 📊 Telecom X — Parte 1  
## Análisis de Evasión de Clientes (Churn | ETL + EDA)

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2.0-150458?style=flat&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualización-4C72B0?style=flat)
![Status](https://img.shields.io/badge/Estado-Completado-brightgreen?style=flat)

---

## 🔗 Proyecto Completo

Este repositorio corresponde a la **Parte 1 (ETL + EDA)** del proyecto Telecom X.

📌 La **Parte 2 (Machine Learning — Modelado Predictivo)** se encuentra disponible aquí:  
👉 https://github.com/ernes2111/Challenge-Telecom-X-part2

Ambas partes conforman un flujo completo **end-to-end**, donde esta etapa prepara y analiza los datos que luego serán utilizados para construir el modelo predictivo en la Parte 2.

---

## 📌 Descripción del Proyecto

Este proyecto tiene como objetivo analizar la evasión de clientes (Churn) en la empresa **Telecom X**, identificando los factores que influyen en la cancelación del servicio.

A través de un proceso completo de **ETL (Extracción, Transformación y Carga)** y un **Análisis Exploratorio de Datos (EDA)**, se identifican patrones relevantes que sirven como base para:

- Estrategias de retención basadas en datos.
- Construcción de modelos predictivos (desarrollados en la Parte 2).

---

## 🎯 Objetivos

- Comprender la magnitud del churn en la empresa.
- Identificar variables asociadas a la cancelación.
- Analizar patrones en variables categóricas y numéricas.
- Generar insights estratégicos basados en datos.
- Preparar el dataset para el modelado predictivo posterior.

---

## 🧱 Estructura del Proyecto

El proyecto está organizado en las siguientes etapas dentro del notebook:

### 1️⃣ Extracción
- Importación de datos desde una fuente estructurada (JSON).
- Normalización de columnas anidadas usando `pd.json_normalize()`.

### 2️⃣ Transformación
- Limpieza y tipado de variables.
- Conversión de variables binarias.
- Creación de nueva variable `Cuentas_Diarias`.
- Estandarización de nombres de columnas.
- Generación del dataset limpio `datos_tratados.csv` (input de la Parte 2).

### 3️⃣ Carga y Análisis (EDA)
- Análisis descriptivo (media, mediana, desviación estándar).
- Distribución general del churn.
- Análisis de churn por variables categóricas.
- Análisis de churn por variables numéricas.
- Matriz de correlación y análisis adicional.

### 4️⃣ Informe Final
- Conclusiones estratégicas.
- Recomendaciones para reducir la evasión.
- Identificación de variables clave para el futuro modelado.

---

## 📊 Principales Hallazgos

- La tasa de churn es aproximadamente del 27%.
- Los contratos mensuales presentan la mayor tasa de cancelación.
- La antigüedad del cliente es el factor más influyente (relación negativa con churn).
- Clientes con mayor cargo mensual presentan mayor tendencia a cancelar.
- La estabilidad contractual reduce significativamente el riesgo de evasión.

Estos hallazgos fueron posteriormente validados cuantitativamente en la **Parte 2 mediante modelos de Machine Learning**.

---

## 🛠️ Tecnologías Utilizadas

- Python 3.x  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## ▶️ Cómo Ejecutar el Proyecto

Clonar el repositorio:

```bash
git clone https://github.com/ernes2111/Challenge-Telecom-X.git
cd Challenge-Telecom-X