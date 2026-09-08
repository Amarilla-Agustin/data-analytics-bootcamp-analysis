# 📊 TalentHub - Análisis de Vacantes para un Bootcamp de Data Analytics
![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter)
![Seaborn](https://img.shields.io/badge/Seaborn-violet?logo=Seaborn)
## 📖 Descripción del proyecto

Este proyecto tiene como objetivo analizar un conjunto de vacantes laborales relacionadas con perfiles de análisis de datos para identificar las habilidades, tecnologías y perfiles más demandados por el mercado.

A partir del análisis exploratorio de datos (EDA), se obtuvieron insights que permiten responder a una necesidad de negocio planteada por TalentHub: diseñar un bootcamp alineado con las competencias que actualmente solicitan las empresas.

---

# 🎯 Objetivo del cliente

TalentHub busca desarrollar un nuevo bootcamp de Data Analytics que prepare a sus estudiantes para ingresar al mercado laboral.

Para ello, necesita conocer:

- Las habilidades técnicas más demandadas.
- Los puestos con mayor cantidad de ofertas.
- Los niveles de experiencia más solicitados.
- Las tecnologías que suelen aparecer en conjunto dentro de una misma vacante.

El análisis permitirá elaborar recomendaciones para estructurar el contenido del bootcamp de acuerdo con las necesidades reales del mercado.

---

# 📂 Fuente de datos

Se utilizaron tres conjuntos de datos proporcionados para la actividad:

- **Vacantes:** información general de las ofertas laborales.
- **Habilidades:** catálogo de habilidades identificadas.
- **Vacantes-Habilidades:** tabla relacional que vincula cada vacante con las habilidades requeridas.

Los datos fueron integrados mediante operaciones de `merge` utilizando la librería **Pandas**.

---

# 🛠️ Metodología utilizada

El proyecto se desarrolló siguiendo las etapas de un proceso de análisis de datos:

1. Carga de datos.
2. Exploración inicial.
3. Evaluación de la calidad de los datos.
4. Tratamiento de valores nulos.
5. Conversión de tipos de datos.
6. Integración de tablas mediante `merge`.
7. Análisis exploratorio (EDA).
8. Visualización de resultados.
9. Obtención de insights.
10. Elaboración de recomendaciones para el cliente.

Las principales herramientas utilizadas fueron:

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

---

# 📈 Principales hallazgos

Del análisis realizado se identificó que:

- SQL y Python se encuentran entre las habilidades más demandadas.
- El puesto **Data Analyst** concentra la mayor cantidad de ofertas laborales.
- Muchas vacantes buscan combinaciones de habilidades, especialmente SQL junto con Python y herramientas de visualización.
- Los niveles de experiencia más frecuentes corresponden a perfiles Junior, Entry Level y Middle, aunque una parte importante de las ofertas no especifica este requisito.
- Herramientas como Power BI y Tableau aparecen de forma recurrente como competencias complementarias.

---

# 💡 Recomendaciones

A partir de los resultados obtenidos, se recomienda que TalentHub:

- Priorice la enseñanza de SQL como competencia fundamental.
- Incorpore Python como lenguaje principal para análisis de datos.
- Incluya herramientas de visualización como Power BI y Tableau.
- Diseñe el bootcamp mediante módulos progresivos que integren las tecnologías más utilizadas por el mercado.
- Desarrolle proyectos prácticos que combinen varias habilidades, simulando situaciones reales de trabajo.

---

# ▶️ Instrucciones para reproducir el análisis

1. Clonar este repositorio.

```bash
git clone https://github.com/tu_usuario/talenthub-analisis.git
```

2. Instalar las dependencias.

```bash
pip install -r requirements.txt
```

3. Abrir el notebook.

```text
notebooks/TalentHub_Analisis.ipynb
```

4. Ejecutar todas las celdas en orden para reproducir el análisis y las visualizaciones.

---

# 📁 Estructura del proyecto

```
talenthub-analisis/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   └── TalentHub_Analisis.ipynb
│── presentation/
├── README.md
├── requirements.txt
└── .gitignore
```

---

# 👨‍💻 Amarilla Agustin

Proyecto desarrollado como parte del curso de **Análisis de Datos**, aplicando técnicas de limpieza, integración y análisis exploratorio de datos para resolver un caso de negocio.
