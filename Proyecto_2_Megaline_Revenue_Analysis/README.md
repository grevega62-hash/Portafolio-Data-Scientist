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
