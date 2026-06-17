# Sprint 7 Final Project Telecom Analysis
Entrega de Notebook y README del proyecto final del sprint 7 del bootcamp de TripleTen.

El notebook `S7_Version_Estudiante_Project_ConnectaTel` incluye 3 dataframes con 4000 registros de clientes de los servicios de telefonía, su uso y el registro de usuarios, con valores faltantes, sentinels, outliers y problemas de calidad diseñados para simular datos reales de servicios de telefonia.

Datasets utilizados:

plans.csv → información de los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra)
users.csv → información de los clientes (edad, ciudad, fecha de registro, plan, churn)
usage.csv → detalle del uso real de los servicios (llamadas y mensajes)

Etapas del análisis realizado:

- Carga, exploración y limpieza de datos.
- Análisis de indicadores estadísticos.
- Visualizaciones para explorar distribuciones.
- Segmentaciones.
- Generación de insights para stakeholders.


## 📂 Contenido del repositorio

- `S7_Version_Estudiante_Project_ConnectaTel.ipynb`
  → Notebook principal con limpieza, EDA, distribuciones, outliers y conclusiones.

## ▶ Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/1Nj6IzUiiK_VxPlJRmY8pasSZNtntDqGc/view?usp=sharing)

O:

1. Abre el archivo `S7_Version_Estudiante_Project_ConnectaTel.ipynb` en GitHub
2. Haz clic en **Open in Colab**

## 📘 Cómo reproducir el análisis

1. Abre `S7_Version_Estudiante_Project_ConnectaTel.ipynb`
2. Ejecuta las celdas en orden.
3. El notebook carga automáticamente el dataset desde `/data/` o desde un enlace público (según corresponda).

## 🧠 Objetivo del análisis

El objetivo del proyecto es evaluar el comportamiento de los clientes de una empresa de telecomunicaciones en Latinoamérica, ConnectaTel.

Trabajamos con información registrada hasta elaño 2024, lo cual nos permitió analizar el comportamiento del negocio dentro de ese periodo.
