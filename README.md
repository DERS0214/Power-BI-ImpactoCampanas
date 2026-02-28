# 📊 Marketing Campaign Impact Dashboard

## 📌 Descripción del Proyecto

Este proyecto consiste en el desarrollo de un dashboard interactivo en Power BI para analizar el impacto de campañas de marketing sobre el comportamiento de compra de los clientes.

El análisis integra procesos de limpieza, transformación y modelado de datos para generar indicadores clave de desempeño (KPIs) y visualizaciones que permitan identificar segmentos de clientes con mayor probabilidad de respuesta a campañas promocionales.

El objetivo principal es proporcionar información estratégica que facilite la toma de decisiones en marketing y segmentación de clientes.

---

## 🎯 Objetivos

- Analizar la efectividad de campañas de marketing.
- Identificar perfiles de clientes con mayor tasa de aceptación.
- Evaluar el impacto de variables demográficas en el comportamiento de compra.
- Medir el incremento de gasto asociado a campañas.
- Desarrollar un dashboard interactivo para exploración de datos.

---

## 📊 Dataset

El dataset contiene información de clientes, incluyendo:

- Datos demográficos (edad, educación, estado civil).
- Ingresos (Income).
- Historial de compras por categorías.
- Antigüedad del cliente.
- Respuesta a campañas de marketing.

Durante el preprocesamiento se realizaron mejoras de calidad como conversión de variables financieras, imputación de valores faltantes y eliminación de registros inconsistentes.

---

## 🧹 Procesamiento de Datos

Las principales transformaciones aplicadas fueron:

- Conversión de variables financieras de texto a formato numérico.
- Imputación de valores faltantes en Income mediante mediana.
- Eliminación de registros con gastos negativos.
- Corrección de edades inválidas mediante imputación robusta.
- Reconstrucción de variables categóricas (educación y estado civil).
- Aplicación de técnicas de capping para controlar outliers.

Estas mejoras permitieron obtener un dataset limpio de aproximadamente 2,205 registros para el análisis.

---

## 📈 KPIs Principales

- **Total Clientes:** 2202  
- **Clientes Impactados:** 458  
- **% Clientes Impactados:** 20.80%  
- **Gasto Promedio Extra por Impacto:** $582.28  
- **Multiplicador de Gasto por Impacto:** 2.32x  

Estos indicadores permiten medir la efectividad de las campañas y el retorno potencial de inversión en marketing.

---

## 📊 Dashboard

El dashboard está compuesto por dos vistas principales:

### 1️⃣ Análisis de Valor y Consumo por Categoría

Permite:

- Comparar gasto promedio entre clientes impactados y no impactados.
- Identificar categorías de productos con mayor incremento de consumo.
- Evaluar el impacto económico de las campañas.

### 2️⃣ Análisis de Penetración Demográfica

Permite:

- Identificar segmentos demográficos con mayor tasa de aceptación.
- Analizar comportamiento por edad, educación y estado civil.
- Detectar perfiles de clientes ideales para futuras campañas.

El dashboard incluye filtros interactivos para facilitar la exploración de datos.

---

## 🔍 Insights Principales

Entre los hallazgos más relevantes:

- Clientes con mayor nivel educativo presentan mayor tasa de aceptación.
- Segmentos de ingresos altos muestran mayor gasto tras campañas.
- Clientes menores de 25 años presentan mayor tasa de respuesta.
- La antigüedad del cliente influye positivamente en la conversión.
- Productos premium como vinos y carnes generan mayor incremento de gasto.

---

## 🛠️ Tecnologías Utilizadas

- Power BI
- Python (preprocesamiento)
- Pandas
- NumPy

---

## 📁 Estructura del Proyecto

```
Power-BI-ImpactoCampanas/
│
├── Dashboard G9.pbix
├── Informe G9.pdf
└── README.md
```

---

## 🚀 Cómo Usar

1. Descargar el archivo:

```
Dashboard G9.pbix
```

2. Abrir en Power BI Desktop.

3. Explorar las visualizaciones utilizando filtros interactivos.

---

## 📚 Aprendizajes Clave

- Preparación y limpieza de datos para análisis.
- Creación de KPIs para marketing.
- Segmentación de clientes basada en datos.
- Diseño de dashboards interactivos.
- Storytelling con visualizaciones.

---

## 👥 Autores

Grupo 9

- David Ramírez  
- Darwin Peralta  
- Romina Intriago  
- Ivonne Rubira  
- Angel Vera  
