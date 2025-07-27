# Proyecto: Impacto del Gasto Público en el Crecimiento Económico

Este proyecto analiza la relación entre el gasto público y el crecimiento económico utilizando datos de países con diferentes niveles de desarrollo. Se utilizarán herramientas de análisis de datos, visualización y modelos econométricos para identificar patrones y posibles correlaciones.

---

## 🗂 Estructura del Proyecto

```
gastoPublico_vs_crecimiento/
│
├── data/                      # Archivos de datos crudos y procesados
│   ├── raw/                   # Datos descargados directamente de fuentes externas
│   └── processed/             # Datos ya limpios y listos para el análisis
│
├── notebooks/                # Notebooks del flujo de análisis
│   ├── 01_eda.ipynb           # Análisis exploratorio de los datos
│   ├── 02_limpieza.ipynb      # Limpieza y transformación de los datos
│   ├── 03_modelado.ipynb      # Modelos de regresión y análisis estadístico
│   └── 04_visualizaciones.ipynb  # Visualizaciones finales y storytelling
│
├── visualizaciones/          # Exportaciones de gráficos y dashboards
│   ├── png/                   # Gráficos exportados en formato imagen
│   ├── powerbi/               # Archivos de Power BI (.pbix)
│   └── tableau/               # Archivos de Tableau o exportaciones PDF
│
├── README.md                 # Descripción general del proyecto (este archivo)
└── .gitignore                # Archivos a ignorar por git
```

---

## 🌍 Países seleccionados (muestra no sesgada)

* Estados Unidos (USA)
* Alemania (DEU)
* Japón (JPN)
* Argentina (ARG)
* India (IND)
* Sudáfrica (ZAF)
* Nigeria (NGA)
* México (MEX)
* Indonesia (IDN)
* Suecia (SWE)

---

## 📊 Indicadores a analizar

| Indicador                       | Código WB         |
| ------------------------------- | ----------------- |
| Gasto público (% del PIB)       | GC.XPN.TOTL.GD.ZS |
| PIB per cápita (USD constantes) | NY.GDP.PCAP.KD    |
| Crecimiento del PIB (% anual)   | NY.GDP.MKTP.KD.ZG |
| Población total                 | SP.POP.TOTL       |

---

## 🧰 Herramientas y tecnologías utilizadas

* Python (pandas, numpy, matplotlib, seaborn, scikit-learn)
* Jupyter Notebooks
* wbdata (API del Banco Mundial)
* Git y GitHub
* Visualización avanzada (Power BI, Tableau, Looker Studio)

---

## 🎯 Objetivo

Explorar si existe una correlación relevante entre el nivel de gasto público y el crecimiento económico entre países de diferentes regiones y niveles de desarrollo, durante el período 2000–2023.

---

## 📌 Estado del proyecto

* [x] Estructura inicial
* [x] Configuración del repositorio y .gitignore
* [ ] Descarga y limpieza de datos
* [ ] Modelado y análisis econométrico
* [ ] Visualizaciones finales
* [ ] Conclusiones y recomendaciones

---

## 📁 Fuente de datos

Todos los datos provienen de la API oficial del Banco Mundial: [https://data.worldbank.org/](https://data.worldbank.org/)
