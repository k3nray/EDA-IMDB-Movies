# 🎬 EDA IV – Análisis Exploratorio de Datos: IMDB Movies

Proyecto de Análisis Exploratorio de Datos (EDA) realizado en **The Valley Business & Tech School**  
Diploma de Especialización: Data Analytics con Programación en Python (2025–2026)

---

## 📋 Descripción

Análisis exhaustivo del dataset de películas de IMDB con más de 1.000 registros. El objetivo es explorar, limpiar y visualizar los datos para extraer insights sobre tendencias cinematográficas, géneros, ingresos y ratings.

**Dataset:** [IMDB Movie Data](https://raw.githubusercontent.com/ssillerom/modulo_analisis_exploratorio/refs/heads/main/data/IMDB-Movie-Data.csv)

---

## 🔍 Contenido del análisis

| Sección | Descripción |
|---|---|
| 1. Lectura de datos | Carga del CSV desde URL con Pandas |
| 2. Análisis descriptivo | Shape, tipos, estadísticas básicas |
| 3. Gestión de duplicados | Detección y eliminación |
| 4. Filtrado y transformación | `.loc`, `.iloc`, nuevas columnas, cuartiles |
| 5. Gestión de nulos | Eliminación, imputación con media/mediana |
| 6. Agrupaciones | `groupby`, `agg`, `transform` |
| 7. Visualizaciones | Seaborn, Matplotlib y Plotly |

---

## 📊 Visualizaciones incluidas

- 📈 Cantidad de películas por año (countplot)
- 📉 Distribución de duración (histplot + KDE)
- 🔵 Relación rating vs duración (scatterplot)
- 📦 Rating por género (boxplot)
- 🎻 Distribución de ingresos por género (violinplot)
- 🌡️ Mapa de correlaciones (heatmap)
- 📅 Rating promedio por año (lineplot)
- 🌐 Votos vs Revenue interactivo por año (Plotly)

---

## 🛠️ Tecnologías

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-2.x-150458?logo=pandas)
![Seaborn](https://img.shields.io/badge/Seaborn-0.13-blue)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.8-orange)
![Plotly](https://img.shields.io/badge/Plotly-5.x-3F4F75?logo=plotly)

---

## 🚀 Cómo ejecutarlo

### 1. Clona el repositorio
```bash
git clone https://github.com/k3nray/EDA-IMDB-Movies.git
cd EDA-IMDB-Movies
```

### 2. Instala las dependencias
```bash
pip install -r requirements.txt
```

### 3. Abre el notebook
```bash
jupyter notebook EDA_IV_-_Workshop_.ipynb
```

---

## 📁 Estructura del proyecto

```
EDA-IMDB-Movies/
│
├── EDA_IV_-_Workshop_.ipynb   # Notebook principal
├── requirements.txt            # Dependencias
└── README.md                   # Este archivo
```

---

## 👤 Autor

**Kenyer Villegas** – Analista de Datos  
📧 Kenyer@me.com | 📍 Madrid, España  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?logo=linkedin)](https://www.linkedin.com/in/kenyer-villegas/)

---

## 📜 Licencia

Este proyecto es de uso educativo, desarrollado como parte del programa de formación en The Valley Business & Tech School.
