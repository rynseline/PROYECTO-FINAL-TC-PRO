# 🎭 PopStar Insights  
## 📊 Análisis de Popularidad de Actores Chinos

---

## 📌 Descripción del proyecto

**PopStar Insights** es una aplicación móvil desarrollada con **MIT App Inventor** como proyecto final del curso **Introducción a la Ciencia de Datos**, impartido por **Tecnolochicas**.

La aplicación analiza la **evolución temporal de la popularidad de actores y actrices chinos** a partir de datos anuales (2010–2024). Mediante visualizaciones interactivas, limpieza de datos y análisis asistido por inteligencia artificial, la app permite identificar tendencias y realizar predicciones básicas sobre la trayectoria profesional de los actores.

Este proyecto demuestra cómo las herramientas de ciencia de datos pueden aplicarse al ámbito del **entretenimiento y la cultura popular**, manteniendo rigor metodológico.

---

## 📱 Funcionalidades de la aplicación

La aplicación cuenta con una pantalla principal desde la cual el usuario puede **seleccionar un actor** y acceder a las siguientes secciones:

### 1️⃣ Limpieza de datos
- Visualización de la serie histórica de popularidad del actor seleccionado.
- Detección de anomalías en los datos anuales.
- Eliminación interactiva de valores atípicos para mejorar el análisis.

### 2️⃣ Visualización y línea de mejor ajuste
- Gráfica de la evolución de la popularidad a lo largo del tiempo.
- Cálculo y visualización de la **línea de mejor ajuste**.
- Presentación de métricas de regresión:
  - Pendiente (slope)
  - Coeficiente de correlación
  - Intercepto

### 3️⃣ Análisis con inteligencia artificial
- Interpretación automática de los resultados del modelo de regresión.
- Predicción básica del comportamiento futuro de la popularidad del actor.
- Análisis contextual de la trayectoria profesional mediante IA.

---

## 🧠 Metodología

El proyecto sigue una metodología basada en el análisis de **series temporales**, replicando el flujo de trabajo visto en clase:

1. Carga y visualización de datos
2. Identificación y limpieza de anomalías
3. Aplicación de regresión lineal
4. Interpretación de resultados
5. Análisis asistido por inteligencia artificial

La estructura y lógica del modelo se mantienen constantes, variando únicamente el dominio de aplicación (de fenómenos físicos a datos de entretenimiento).

---

## 📂 Dataset

Los datos utilizados corresponden a indicadores anuales de popularidad de actores chinos, organizados en hojas independientes dentro de un archivo de Google Sheets.

**Variables principales:**
- `Año`
- `Popularidad`
- `Impacto_Proyectos` (variable contextual)

---

## 🛠️ Tecnologías utilizadas

- **MIT App Inventor**
- **Google Sheets**
- **Regresión lineal**
- **Detección de anomalías**
- **Inteligencia artificial (ChatBot component)**

---

## 👩‍💻 Autora

**Sheila Jacqueline Rayón Celis**  
Proyecto final del curso **Introducción a la Ciencia de Datos**  
Programa **Tecnolochicas**

---

## 📝 Nota final

Este proyecto tiene fines educativos y demuestra cómo los conceptos fundamentales de ciencia de datos pueden aplicarse a distintos contextos, incluyendo el análisis cultural y del entretenimiento.
