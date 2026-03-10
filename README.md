# Challenge_TelecomX_Alura
# 📊 Análisis de Evasión de Clientes

## 📌 Descripción del Proyecto

Este proyecto presenta un **análisis exploratorio de datos (EDA)** enfocado en la evasión de clientes (*churn*) en una empresa de servicios.

El objetivo es identificar **patrones y factores asociados con la cancelación del servicio**, utilizando técnicas de análisis de datos y visualización para comprender mejor el comportamiento de los clientes.

---

## 🎯 Objetivos

* Analizar la distribución de clientes que **evaden y no evaden**.
* Identificar variables que influyen en la **evasión de clientes**.
* Explorar la relación entre la evasión y variables como:

  * tipo de contrato
  * método de pago
  * gasto total del cliente
  * Genero
  * Servicios adicionales
* Generar visualizaciones que permitan interpretar los resultados de manera clara.

---

## 📂 Dataset

El dataset contiene información sobre clientes de una empresa de telecomunicaciones, incluyendo características del cliente y de consumo.

Algunas de las variables utilizadas en el análisis son:

* **Gender** – género del cliente
* **Contract** – tipo de contrato
* **Payment Method** – método de pago
* **Tenure** – antigüedad del cliente
* **Total Charges** – total gastado
* **Churn** – estado de evasión del cliente

Variable objetivo:

| Valor | Significado        |
| ----- | ------------------ |
| 0     | Cliente no evadido |
| 1     | Cliente evadido    |

---

## ⚙️ Herramientas y Tecnologías

El análisis fue desarrollado en **Python** utilizando las siguientes librerías:

* **Pandas** → manipulación y análisis de datos
* **Matplotlib** → visualización de datos
* **NumPy** → operaciones numéricas

El proyecto fue desarrollado en un **cuaderno de Python (Jupyter / Google Colab)**.

---

## 📈 Análisis Realizado

Durante el análisis se realizaron diferentes visualizaciones y comparaciones para identificar patrones de evasión, incluyendo:

* Distribución de clientes que evaden y no evaden
* Evasión según **tipo de contrato**
* Evasión según **método de pago**
* Relación entre **total gastado y evasión**
* Análisis de clientes evadidos por categorías

Estas visualizaciones permiten identificar **grupos de clientes con mayor probabilidad de abandono**.

---

## 🔎 Resultados y Conclusiones

El análisis muestra que ciertas características del cliente pueden estar relacionadas con mayores niveles de evasión.

En particular, variables como **tipo de contrato, método de pago y gasto total** presentan diferencias relevantes entre clientes que permanecen en el servicio y aquellos que lo abandonan.

Estos hallazgos pueden servir como base para desarrollar **estrategias de retención de clientes** y mejorar la toma de decisiones en la empresa.

---

## 📁 Estructura del Proyecto

```
📂 churn-analysis
│
├── data/
│   └── dataset.csv
│
├── notebooks/
│   └── analisis_churn.ipynb
│
├── README.md
```

---

## 👤 Autor

Proyecto desarrollado como parte de un ejercicio de **análisis exploratorio de datos y ciencia de datos**.
