# 🚕 Proyecto 3: Análisis de Viajes Compartidos en Chicago — Zuber

## 📌 Descripción

Zuber, una nueva empresa de viajes compartidos en Chicago, busca comprender las preferencias de los pasajeros y el impacto de factores externos en la frecuencia y duración de los viajes.

En este proyecto se analizan datos de viajes en taxi, empresas competidoras, barrios de Chicago y condiciones climáticas. Además, se prueba una hipótesis relacionada con el efecto del clima lluvioso en la duración de los viajes desde el Loop hasta el Aeropuerto Internacional O'Hare.

---

## 🎯 Objetivo

Identificar patrones en los viajes urbanos de Chicago, analizar el comportamiento de las empresas competidoras y evaluar si las condiciones climáticas influyen en la duración promedio de los viajes.

---

## 🛠️ Herramientas utilizadas

- SQL
- Python
- Pandas
- Matplotlib
- SciPy
- Web scraping
- Jupyter Notebook

---

## 📂 Datos utilizados

El proyecto utiliza información proveniente de una base de datos y archivos CSV derivados de consultas SQL.

### Tablas de la base de datos

| Tabla | Descripción |
|---|---|
| `neighborhoods` | Información de los barrios de Chicago |
| `cabs` | Información de taxis y empresas propietarias |
| `trips` | Registro de viajes realizados |
| `weather_records` | Registro de condiciones climáticas por hora |

### Archivos CSV utilizados

| Archivo | Descripción |
|---|---|
| `project_sql_result_01.csv` | Número de viajes por empresa de taxis |
| `project_sql_result_04.csv` | Promedio de viajes por barrio de destino |
| `project_sql_result_07.csv` | Viajes desde Loop hasta O'Hare con condiciones climáticas |

---

## 📋 Tareas realizadas

✔️ Extracción de datos climáticos desde una página web.  

✔️ Consultas SQL para recuperar y agrupar información de viajes.  

✔️ Uso de `JOIN` para relacionar viajes con condiciones climáticas.  

✔️ Agrupación de empresas de taxis por volumen de viajes.  

✔️ Identificación de las empresas con mayor número de viajes.  

✔️ Identificación de los 10 principales barrios por finalización de viajes.  

✔️ Limpieza y validación de tipos de datos en Python.  

✔️ Visualización de datos mediante gráficos.  

✔️ Formulación y prueba de hipótesis estadística.  

---

## 📊 Análisis realizado

El análisis se enfocó en tres áreas principales:

1. **Competencia en el mercado de taxis**
   - Se analizaron las empresas con mayor cantidad de viajes.
   - Se comparó el desempeño de compañías populares como Flash Cab y Taxi Affiliation Services.

2. **Preferencias de destino**
   - Se identificaron los barrios con mayor promedio de finalización de viajes.
   - Se analizaron los principales puntos de llegada en Chicago.

3. **Impacto del clima**
   - Se clasificaron las condiciones climáticas como buenas o malas.
   - Se evaluó si los sábados lluviosos afectan la duración de los viajes desde el Loop hasta el Aeropuerto Internacional O'Hare.

---

## 🧪 Prueba de hipótesis

Se evaluó la siguiente hipótesis:

> La duración promedio de los viajes desde el Loop hasta el Aeropuerto Internacional O'Hare cambia los sábados lluviosos.

### Hipótesis planteadas

**H₀:** La duración promedio de los viajes en sábados lluviosos es igual a la duración promedio en sábados con buen clima.  

**H₁:** La duración promedio de los viajes en sábados lluviosos es diferente a la duración promedio en sábados con buen clima.

Para evaluar la hipótesis se utilizó una prueba estadística de comparación de medias con un nivel de significancia definido.

---

## 🚀 Resultados

El proyecto permitió identificar las empresas de taxis con mayor actividad, los barrios más frecuentes como destino y evaluar el posible impacto del clima en la duración de los viajes.

Los resultados obtenidos aportan información útil para comprender el mercado de viajes compartidos en Chicago y apoyar decisiones estratégicas para Zuber.

---

## 🧠 Habilidades desarrolladas

- Extracción de datos desde la web.
- Consultas SQL.
- Unión de tablas con `JOIN`.
- Agrupación y filtrado de datos.
- Limpieza y validación de datos con Python.
- Análisis exploratorio de datos.
- Visualización de información.
- Pruebas de hipótesis.
- Interpretación de resultados para negocio.

---

## 📚 Proyecto desarrollado en

Bootcamp de Ciencia de Datos de TripleTen.

---

## 📁 Estructura del proyecto

```text
📁 Proyecto_3_Analisis_Viajes_Zuber
│
├── notebook.ipynb
├── README.md
├── data
│   ├── project_sql_result_01.csv
│   ├── project_sql_result_04.csv
│   └── project_sql_result_07.csv
└── images
    ├── viajes_por_empresa.png
    └── top_10_barrios.png
```

---
