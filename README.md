# Proyecto: Impacto del Gasto Público en el Crecimiento Económico

Este proyecto tiene como objetivo analizar la relación entre el gasto público y el crecimiento económico utilizando datos de organismos internacionales. Se aplicarán técnicas de análisis de datos, visualización y modelado estadístico para explorar posibles correlaciones o patrones relevantes.

---

## 📊 Objetivos

* Evaluar si existe una relación significativa entre el gasto público y el crecimiento del PBI en distintos países.
* Comparar resultados por regiones o niveles de ingreso.
* Explorar si hay umbrales donde el gasto público tiene efectos positivos o negativos.

---

## 📂 Estructura del proyecto

```
gastoPublico_vs_crecimiento/
├── data/                   # Datos crudos y procesados
├── notebooks/              # Jupyter Notebooks por etapa
│   ├── 01_eda.ipynb
│   ├── 02_limpieza.ipynb
│   ├── 03_modelado.ipynb
│   ├── 04_visualizaciones.ipynb
│   └── 05_conclusiones.ipynb
├── .venv/                  # Entorno virtual
├── requirements.txt        # Dependencias
└── README.md               # Documentación del proyecto
```

---

## 🔍 Datos utilizados

Se utilizarán datos de fuentes abiertas como:

* [Banco Mundial (WB)](https://data.worldbank.org/)
* [FMI](https://www.imf.org/en/Data)
* [OCDE](https://data.oecd.org/)

Indicadores clave:

* **Gasto público (% del PBI)**
* **PBI per cápita**
* **Crecimiento del PBI anual (%)**
* **Población total**

---

## 📚 Herramientas

* Python 3
* Jupyter Notebooks
* Pandas, Seaborn, Matplotlib, Scikit-learn
* WBData para acceso a datos del Banco Mundial
* Visualizaciones complementarias en Power BI / Tableau (opcional)

---

## 🔄 Reproducibilidad

1. Clonar el repositorio
2. Crear entorno virtual:

   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```
3. Instalar dependencias:

   ```bash
   pip install -r requirements.txt
   ```
4. Ejecutar los notebooks en orden desde la carpeta `notebooks/`

---

## 📈 Resultado esperado

* Análisis visual y cuantitativo del impacto del gasto público
* Conclusiones por país, región o nivel de ingreso
* Modelo predictivo simple del crecimiento económico basado en indicadores fiscales

---

## 📖 Autor

Tomas — 2025
