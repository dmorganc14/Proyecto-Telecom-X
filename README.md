# 📊 Telecom X – Análisis de Evasión de Clientes (Churn)

## 📌 Descripción del proyecto

Este proyecto realiza un **Análisis Exploratorio de Datos (EDA)** sobre la evasión de clientes (*Churn*) en la empresa Telecom X.

La compañía enfrenta una alta tasa de cancelación de servicios, por lo que necesita identificar los factores que influyen en la decisión de los clientes de abandonar la empresa.

El objetivo del análisis es **extraer información relevante de los datos** para apoyar futuras estrategias de retención y el desarrollo de modelos predictivos de churn por parte del equipo de Data Science.

---

# 🎯 Objetivos del análisis

* Importar datos desde una **API en formato JSON**
* Aplicar procesos de **ETL (Extracción, Transformación y Carga)**
* Realizar **limpieza y preparación de datos**
* Desarrollar un **Análisis Exploratorio de Datos (EDA)**
* Crear **visualizaciones para identificar patrones**
* Generar **insights estratégicos sobre la cancelación de clientes**

---

# 🧰 Tecnologías utilizadas

Este proyecto fue desarrollado en **Python** utilizando las siguientes librerías:

* **Python 3**
* **Pandas** → manipulación y análisis de datos
* **NumPy** → operaciones numéricas
* **Matplotlib** → visualización de datos
* **Seaborn** → gráficos estadísticos
* **Requests** → extracción de datos desde API

El análisis fue realizado en **Google Colab**.

---

# 📂 Estructura del proyecto

El proyecto se encuentra organizado de la siguiente manera:

```
TelecomX-Churn-Analysis
│
├── TelecomX_Churn_Analysis.ipynb
│
├── README.md
│
└── dataset
```

El cuaderno de análisis contiene las siguientes etapas:

1. Introducción al problema
2. Extracción de datos desde la API
3. Transformación y limpieza de datos
4. Análisis exploratorio de datos
5. Visualización de variables clave
6. Conclusiones e insights estratégicos

---

# 🔄 Proceso de análisis

## 1️⃣ Extracción de datos

Los datos fueron obtenidos desde un archivo JSON alojado en GitHub mediante una solicitud HTTP utilizando la librería `requests`.

Posteriormente se transformaron en un **DataFrame de Pandas** para facilitar su análisis.

---

## 2️⃣ Transformación y limpieza de datos

Durante esta etapa se realizaron las siguientes tareas:

* Conversión de variables a tipos de datos adecuados
* Eliminación de valores nulos
* Eliminación de registros duplicados
* Transformación de variables categóricas a formato analizable

Este proceso garantiza la **calidad y consistencia de los datos** antes de realizar el análisis.

---

## 3️⃣ Análisis exploratorio de datos (EDA)

Se analizaron distintas variables relacionadas con el churn, entre ellas:

* Tipo de contrato
* Tiempo de permanencia del cliente
* Cargos mensuales
* Cargos totales
* Método de pago
* Tipo de servicio de internet

Para identificar patrones se utilizaron visualizaciones como:

* Gráficos de barras
* Diagramas de caja (Boxplots)
* Matriz de correlación
* Distribución de churn

---

# 📊 Principales hallazgos

A partir del análisis se identificaron varios factores asociados a la cancelación del servicio:

### 📉 Tipo de contrato

Los clientes con **contratos mensuales** presentan una mayor tasa de cancelación en comparación con contratos de largo plazo.

---

### ⏳ Tiempo de permanencia

Los clientes que cancelan suelen tener **menor tiempo de permanencia en la empresa**, lo que sugiere que los primeros meses son críticos para la retención.

---

### 💰 Cargos mensuales

Se observa una tendencia de mayor cancelación en clientes con **cargos mensuales más elevados**.

---

### 💳 Método de pago

Algunos métodos de pago presentan mayor proporción de cancelaciones, lo cual podría indicar diferencias en el comportamiento de los clientes.

---

# 📈 Recomendaciones

A partir de los hallazgos se proponen las siguientes estrategias:

* Incentivar contratos de largo plazo mediante promociones o descuentos
* Implementar programas de fidelización durante los primeros meses
* Revisar los planes con cargos mensuales más elevados
* Diseñar estrategias de retención enfocadas en clientes con mayor riesgo de churn

---

# 🚀 Próximos pasos

Este análisis exploratorio puede ser utilizado como base para desarrollar:

* **Modelos de Machine Learning para predicción de churn**
* **Segmentación de clientes**
* **Sistemas de alerta temprana para cancelaciones**

Estas herramientas permitirían anticipar la pérdida de clientes y mejorar las estrategias de retención.

---

# 👨‍💻 Autor

Daniel Morgan

Estudiante de tecnología y análisis de datos interesado en **Data Science, análisis estadístico y aprendizaje automático**.

---

# 📎 Fuente de datos

Dataset utilizado en el challenge de análisis de datos de **Telecom X**.

Los datos fueron obtenidos desde un repositorio público de GitHub utilizado con fines educativos.
