# 🛍️ Análisis de Datos de Centros Comerciales en India

Proyecto final de la materia **Analítica de Datos** de la Tecnicatura en Innovación con Tecnologías 4.0. En este trabajo se realiza un análisis completo del comportamiento de los clientes en centros comerciales de distintas regiones de la India.

---

## 👩‍💻 Autora

** Priscila Kwiatkowski**  
| Tecnicatura en Innovación con Tecnologías 4.0

---

## 📌 Objetivo del Proyecto

Analizar los datos de ventas y clientes de centros comerciales en la India para identificar patrones de comportamiento, distribución por género, rango etario, métodos de pago preferidos y ofrecer recomendaciones a partir de los hallazgos obtenidos.

---

## 📊 Conjunto de Datos

- **Origen:** Kaggle  
- **Descripción:** El dataset contiene información detallada sobre ventas realizadas en distintos centros comerciales de la India, con datos asociados a clientes como edad, género, y método de pago.

---

## 🧪 Proceso de Trabajo

### 1. Extracción de Datos (Extract)
- Se utilizaron archivos CSV para cargar dos DataFrames: `df_clientes` y `df_ventas`.
- Se inspeccionaron los datos utilizando `info()`, `describe()` y `shape`.

### 2. Transformación de Datos (Transform)
- Se realizó la unión de los DataFrames con `merge()`.
- Se detectaron y gestionaron valores nulos (por ejemplo, reemplazando edades faltantes con la media).
- Se estandarizaron formatos de fecha y se limpiaron datos duplicados o inconsistentes.

### 3. Análisis Exploratorio (EDA)
- Distribución por género y edad.
- Métodos de pago utilizados.
- Segmentación de clientes por rangos etarios.
- Ventas por tipo de cliente.
- Visualizaciones con **Matplotlib** y **Seaborn** para facilitar la interpretación de resultados.

### 4. Presentación
- Los resultados y hallazgos fueron resumidos en una presentación de PowerPoint para una comunicación más visual y amigable.

---

## 🔍 Herramientas Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- PowerPoint

---

## 📈 Principales Hallazgos

- Las mujeres realizaron aproximadamente el **79.71%** de las ventas.
- El método de pago más utilizado fue el **efectivo** (44.69%).
- Los **adultos mayores (50-69 años)** representaron la mayor parte de las compras, con un **38.13% del total**.
- Se detectaron diferencias en la preferencia de métodos de pago según el género.
- Se recomendaron estrategias basadas en estos datos para optimizar las ventas y campañas de marketing.

---


---

## 🚀 Cómo Ejecutar el Proyecto

1. Clonar el repositorio
2. Instalar dependencias (recomendado: entorno virtual)
3. Ejecutar el notebook `analisis_centros_comerciales.ipynb` en Jupyter
4. Explorar los resultados y gráficos

---

## 📬 Contacto

Podés ver más de mi trabajo en [https://github.com/Priska-87].

---



