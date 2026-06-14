# 🎮 Proyecto 3: Análisis de Ventas de Videojuegos — Ice

## 📌 Descripción

Ice, una tienda online de videojuegos con ventas a nivel mundial, busca identificar patrones que permitan determinar si un juego puede ser exitoso o no.

El análisis utiliza datos históricos de ventas, plataformas, géneros, reseñas de usuarios y expertos, así como clasificaciones ESRB. El objetivo es detectar proyectos prometedores y apoyar la planificación de campañas publicitarias para el año 2017.

---

## 🎯 Objetivo

Analizar el comportamiento histórico de ventas de videojuegos para identificar plataformas, géneros y características asociadas con mayores ingresos, con el fin de apoyar decisiones estratégicas de marketing.

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

El análisis se realizó con el archivo:

| Archivo | Descripción |
|---|---|
| `games.csv` | Datos históricos de videojuegos, ventas por región, plataformas, géneros, reseñas y clasificación ESRB |

---

## 📊 Variables analizadas

| Variable | Descripción |
|---|---|
| `name` | Nombre del videojuego |
| `platform` | Plataforma de lanzamiento |
| `year_of_release` | Año de lanzamiento |
| `genre` | Género del videojuego |
| `na_sales` | Ventas en Norteamérica |
| `eu_sales` | Ventas en Europa |
| `jp_sales` | Ventas en Japón |
| `other_sales` | Ventas en otras regiones |
| `critic_score` | Calificación de críticos |
| `user_score` | Calificación de usuarios |
| `rating` | Clasificación ESRB |

---

## 📋 Tareas realizadas

✔️ Carga y exploración inicial del dataset.  

✔️ Estandarización de nombres de columnas.  

✔️ Conversión de tipos de datos.  

✔️ Tratamiento de valores ausentes y registros con valor `TBD`.  

✔️ Cálculo de ventas globales por videojuego.  

✔️ Análisis de lanzamientos por año.  

✔️ Evaluación del ciclo de vida de las plataformas.  

✔️ Identificación de plataformas líderes, emergentes y en declive.  

✔️ Análisis de ventas globales mediante diagramas de caja.  

✔️ Evaluación de la relación entre reseñas y ventas.  

✔️ Análisis de ventas por género.  

✔️ Creación de perfiles de usuario por región: Norteamérica, Europa y Japón.  

✔️ Evaluación del impacto de la clasificación ESRB en las ventas regionales.  

✔️ Formulación y prueba de hipótesis estadísticas.  

---

## 📈 Análisis realizado

El proyecto se dividió en cinco bloques principales:

### 1. Preparación de datos

Se limpiaron y transformaron los datos para asegurar consistencia antes del análisis.  
También se calcularon las ventas totales globales por videojuego.

### 2. Análisis temporal y de plataformas

Se revisó la cantidad de juegos lanzados por año y el comportamiento de ventas por plataforma.  
Esto permitió identificar qué plataformas fueron populares, cuáles disminuyeron y cuáles podían considerarse relevantes para planear campañas futuras.

### 3. Análisis de reseñas y géneros

Se analizó la relación entre las calificaciones de usuarios y críticos con las ventas.  
También se comparó el desempeño de distintos géneros para identificar categorías con mayor potencial comercial.

### 4. Perfil regional de usuarios

Se construyeron perfiles de comportamiento para tres regiones principales:

- Norteamérica
- Europa
- Japón

Para cada región se analizaron las plataformas principales, los géneros más populares y el posible efecto de la clasificación ESRB en las ventas.

### 5. Pruebas de hipótesis

Se realizaron pruebas estadísticas para comparar calificaciones promedio entre plataformas y géneros.

---

## 🧪 Pruebas de hipótesis

### Hipótesis 1

**H₀:** Las calificaciones promedio de los usuarios para Xbox One y PC son iguales.  
**H₁:** Las calificaciones promedio de los usuarios para Xbox One y PC son diferentes.

### Hipótesis 2

**H₀:** Las calificaciones promedio de los usuarios para los géneros Acción y Deportes son iguales.  
**H₁:** Las calificaciones promedio de los usuarios para los géneros Acción y Deportes son diferentes.

Para evaluar las hipótesis se utilizó una prueba estadística de comparación de medias con un nivel de significancia definido.

---

## 🚀 Resultados

El análisis permitió identificar patrones relevantes en el mercado de videojuegos, incluyendo diferencias por plataforma, género y región.

Los resultados obtenidos ayudan a detectar videojuegos y plataformas con mayor potencial comercial, así como a orientar campañas publicitarias según el comportamiento de los usuarios en cada mercado.

---

## 🧠 Habilidades desarrolladas

- Limpieza y preparación de datos.
- Análisis exploratorio de datos.
- Tratamiento de valores ausentes.
- Análisis de ventas por región.
- Visualización de distribuciones.
- Diagramas de caja y gráficos de dispersión.
- Análisis de correlación.
- Estadística descriptiva.
- Pruebas de hipótesis.
- Interpretación de resultados para negocio.

---

## 📚 Proyecto desarrollado en

Bootcamp de Ciencia de Datos de TripleTen.

---

## 📁 Estructura del proyecto

```text
📁 Proyecto_4_Ice_Videogame_Sales_Analysis
│
├── README.md
├── notebook.ipynb
├── data
│   └── games.csv
└── images
    ├── ventas_por_plataforma.png
    ├── ventas_por_genero.png
    ├── boxplot_plataformas.png
    └── correlacion_resenas_ventas.png
```

---
