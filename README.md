# 👋 Hola, soy Grecia Vega Hernández 

## Sobre mí
Soy Ingeniero Financiero con interés en Data Analytics y Business Intelligence. Me apasiona transformar datos en información útil para la toma de decisiones.

## 📂 Proyectos
# 🛒 Proyecto 1: Customer_Data_Cleaning

## 📌 Descripción

Store 1, una empresa de comercio electrónico, se encontraba preparando el lanzamiento de un Programa de Fidelización de Clientes. Para ello, era necesario asegurar que la información de los clientes fuera consistente, completa y estuviera lista para futuros análisis y campañas de marketing personalizadas.

---

## 🎯 Objetivo

Preparar y transformar una muestra de datos de clientes para garantizar su calidad y facilitar la generación de indicadores de negocio (KPIs).

---

## 🛠️ Herramientas utilizadas

- Python
- Listas y estructuras de datos
- Funciones
- Bucles (`for`)
- Validación y limpieza de datos

---

## 📋 Tareas realizadas

✔️ Limpieza de perfiles de clientes.

✔️ Estandarización de nombres y edades.

✔️ Cálculo del gasto total por cliente.

✔️ Validación y corrección de inconsistencias en los datos.

✔️ Preparación de la información para análisis posteriores y generación de KPIs.

---

## 📊 Variables analizadas

| Variable | Descripción |
|------------|-------------|
| `usuario_id` | Identificador único del cliente |
| `usuario_nombre` | Nombre del cliente |
| `usuario_edad` | Edad del cliente |
| `categorias_fav_low` | Categorías favoritas de compra |
| `gasto_por_categoria` | Gasto total realizado en cada categoría |

---

## 🚀 Resultados

Se obtuvo un conjunto de datos más limpio y estructurado, listo para ser utilizado en procesos de segmentación de clientes y estrategias de marketing orientadas a mejorar la fidelización.

---

## 🧠 Habilidades desarrolladas

- Limpieza de datos (Data Cleaning)
- Transformación de datos
- Validación de información
- Manipulación de estructuras de datos en Python
- Pensamiento analítico
- Preparación de datos para análisis de negocio

---

## 📚 Proyecto desarrollado en

Bootcamp de Ciencia de Datos de TripleTen.

---

## 📂 Estructura del proyecto

```
📁 Proyecto 1: Customer_Data_Cleaning
│
├── notebook.ipynb
├── README.md
└── dataset
```

---

# 📱 Proyecto 2: Análisis de Ingresos de Planes de Prepago — Megaline

## 📌 Descripción

Megaline, una empresa de telecomunicaciones, ofrece dos planes de prepago a sus clientes: **Surf** y **Ultimate**.  
El departamento comercial necesita identificar cuál de los dos planes genera mayores ingresos para tomar mejores decisiones sobre la asignación del presupuesto de publicidad.

Este proyecto analiza el comportamiento de 500 clientes durante el año 2018, considerando llamadas, mensajes, uso de internet y plan contratado.

---

## 🎯 Objetivo

Analizar el comportamiento mensual de los clientes y determinar qué plan de prepago genera mayores ingresos promedio para la empresa.

---

## 🛠️ Herramientas utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- SciPy
- Jupyter Notebook

---

## 📂 Datos utilizados

El análisis se realizó con cinco tablas:

| Tabla | Descripción |
|---|---|
| `users` | Información de clientes, ciudad, edad y plan contratado |
| `calls` | Registro de llamadas realizadas |
| `messages` | Registro de mensajes SMS enviados |
| `internet` | Registro de sesiones web y consumo de datos |
| `plans` | Información de tarifas, límites incluidos y costos adicionales |

---

## 📋 Tareas realizadas

✔️ Carga y revisión inicial de los datos.  

✔️ Conversión de tipos de datos y tratamiento de fechas.  

✔️ Limpieza y corrección de errores en los datos.  

✔️ Cálculo mensual por usuario de:
- Número de llamadas.
- Minutos utilizados.
- SMS enviados.
- Datos consumidos.
- Ingreso mensual generado.

✔️ Comparación del comportamiento de clientes por plan.

✔️ Cálculo de métricas estadísticas:
- Media.
- Varianza.
- Desviación estándar.

✔️ Visualización de distribuciones mediante histogramas.

✔️ Pruebas de hipótesis estadísticas para comparar ingresos promedio.

---

## 📊 Análisis realizado

Se evaluó el comportamiento de los usuarios de los planes **Surf** y **Ultimate** en función de:

- Consumo mensual de minutos.
- Cantidad de mensajes enviados.
- Uso mensual de datos móviles.
- Ingresos mensuales generados por cliente.
- Diferencias entre regiones, incluyendo el área Nueva York-Nueva Jersey.

---

## 🧪 Pruebas de hipótesis

Se plantearon y evaluaron dos hipótesis principales:

### Hipótesis 1

**H₀:** El ingreso promedio de los usuarios de los planes Surf y Ultimate es igual.  
**H₁:** El ingreso promedio de los usuarios de los planes Surf y Ultimate es diferente.

### Hipótesis 2

**H₀:** El ingreso promedio de los usuarios del área Nueva York-Nueva Jersey es igual al de usuarios de otras regiones.  
**H₁:** El ingreso promedio de los usuarios del área Nueva York-Nueva Jersey es diferente al de usuarios de otras regiones.

Para evaluar estas hipótesis se utilizaron pruebas estadísticas con un nivel de significancia definido.

---

## 🚀 Resultados

El análisis permitió comparar los ingresos generados por cada plan y entender el comportamiento de consumo de los clientes.  
A partir de los resultados obtenidos, se identificó qué plan presenta mayor rentabilidad promedio y se generaron conclusiones útiles para apoyar decisiones comerciales y de marketing.

---

## 🧠 Habilidades desarrolladas

- Limpieza y preparación de datos.
- Análisis exploratorio de datos.
- Agrupación y agregación de datos con Pandas.
- Cálculo de ingresos mensuales por usuario.
- Visualización de datos.
- Estadística descriptiva.
- Pruebas de hipótesis.
- Interpretación de resultados para negocio.

---

## 📚 Proyecto desarrollado en

Bootcamp de Ciencia de Datos de TripleTen.

---

## 📁 Estructura del proyecto

```text
📁 Proyecto_2_Analisis_Ingresos_Megaline
│
├── notebook.ipynb
├── README.md
├── data
│   ├── megaline_calls.csv
│   ├── megaline_internet.csv
│   ├── megaline_messages.csv
│   ├── megaline_plans.csv
│   └── megaline_users.csv
└── images
    └── histogramas.png
```

---

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
