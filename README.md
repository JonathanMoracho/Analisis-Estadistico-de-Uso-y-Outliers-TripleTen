# 📊 Sprint 7 Final Project — Análisis Estadístico de Uso y Outliers (TripleTen)

Proyecto final del Sprint 7 enfocado en **análisis estadístico para detectar patrones de uso, segmentar clientes e identificar outliers**, utilizando datos de una empresa de telecomunicaciones.

---

## 🎯 Objetivo del proyecto

Una empresa de telecomunicaciones con operaciones en **México y Colombia** necesita comprender cómo sus clientes utilizan los servicios móviles para:

- Analizar el comportamiento real de uso en **llamadas y mensajes**
- Detectar **patrones de consumo** y **comportamientos atípicos**
- Identificar **segmentos de clientes con necesidades diferenciadas**
- Optimizar la **oferta comercial** y mejorar la **experiencia del usuario**

---

## 📁 Datasets utilizados

- **plans.csv** → Información de planes (precio, minutos incluidos, GB incluidos, costos adicionales)
- **users.csv** → Datos de clientes (edad, ciudad, fecha de registro, plan, churn)
- **usage.csv** → Detalle del uso real de servicios (llamadas y mensajes)

---

## 🔎 Etapas del análisis realizadas

### 1️⃣ Exploración inicial de datos
- Carga y revisión de estructura
- Inspección de columnas y tipos de datos

### 2️⃣ Evaluación de calidad de datos
- Identificación de valores nulos
- Detección de valores inválidos y **sentinels**
- Revisión y estandarización de fechas

### 3️⃣ Limpieza y corrección de datos
- Corrección de sentinels
- Manejo de fechas imposibles y registros inconsistentes

### 4️⃣ Análisis de uso por usuario
- Construcción de métricas agregadas por cliente
- Resumen estadístico del comportamiento durante **2024**

### 5️⃣ Visualización y detección de outliers
- Análisis de distribuciones
- Identificación visual y estadística de valores atípicos

### 6️⃣ Segmentación de clientes
- Segmentación por **nivel de uso**
- Segmentación por **edad**
- Visualización comparativa de segmentos

### 7️⃣ Generación de insights ejecutivos
- Conclusiones clave para stakeholders
- Recomendaciones basadas en datos

---

## 📓 Cómo abrir el notebook

El análisis completo se encuentra en el archivo:

📄 **Proyecto 7.ipynb**

### Opciones para visualizarlo:

- 📌 Abrirlo directamente en GitHub (vista previa del notebook)
- 💻 Descargar el repositorio y abrirlo con **Jupyter Notebook** o **VS Code**
- ☁️ Subirlo a **Google Colab** para ejecutarlo en línea

---

## 🧠 Tecnologías utilizadas
- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Jupyter Notebook

