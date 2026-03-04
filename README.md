# 📊 Telecom X - Análisis de Evasión de Clientes (Churn)

## 📌 Descripción del Proyecto

Este proyecto tiene como objetivo analizar la evasión de clientes (Churn) en la empresa **Telecom X**, identificando los factores que influyen en la cancelación del servicio.

A través de un proceso completo de ETL (Extracción, Transformación y Carga) y un Análisis Exploratorio de Datos (EDA), se identifican patrones relevantes que pueden servir como base para estrategias de retención y futuros modelos predictivos.

---

## 🎯 Objetivos

- Comprender la magnitud del churn en la empresa.
- Identificar variables asociadas a la cancelación.
- Analizar patrones en variables categóricas y numéricas.
- Generar insights estratégicos basados en datos.
- Preparar el dataset para posibles modelos predictivos futuros.

---

## 🧱 Estructura del Proyecto

El proyecto está organizado en las siguientes etapas dentro del notebook:

1. **Extracción**
   - Importación de datos desde una fuente estructurada (JSON).
   - Normalización de columnas anidadas usando `pd.json_normalize()`.

2. **Transformación**
   - Limpieza y tipado de variables.
   - Conversión de variables binarias.
   - Creación de nueva variable `Cuentas_Diarias`.
   - Estandarización de nombres de columnas.

3. **Carga y Análisis (EDA)**
   - Análisis descriptivo (media, mediana, desviación estándar).
   - Distribución general del churn.
   - Análisis de churn por variables categóricas.
   - Análisis de churn por variables numéricas.
   - Matriz de correlación y análisis adicional.

4. **Informe Final**
   - Conclusiones estratégicas.
   - Recomendaciones para reducir la evasión.

---

## 📊 Principales Hallazgos

- La tasa de churn es aproximadamente del 27%.
- Los contratos mensuales presentan la mayor tasa de cancelación.
- La antigüedad del cliente es el factor más influyente (relación negativa con churn).
- Clientes con mayor cargo mensual presentan mayor tendencia a cancelar.
- La estabilidad contractual reduce significativamente el riesgo de evasión.

---

## 🛠️ Tecnologías Utilizadas

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📦 Instalación y Dependencias

Clonar el repositorio:

```bash
git clone https://github.com/ernes2111/Challenge-Telecom-X.git
cd Challenge-Telecom-X