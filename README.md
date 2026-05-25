# Análisis de una empresa de telecomunicaciones- Sprint 7

Este repositorio contiene el análisis realizado durante el Sprint y del caso ConnectaTel.

Se utilizaron tres datasets distintos: 
-plans.csv: los planes actuales
-users_latam.csv: información de clientes: edad, ciudad, fecha de registro, plan contratado 
-usage.csv: el detalle de uso real: llamadas (duración) y mensajes (longitud)

Dichos dataset contaban con valores faltantes, sentinels, outliers y problemas de calidad diseñados para simular datos reales de la empresa de telecomunicaciones.

## 📂 Contenido del repositorio

- `notebooks/sprint7-final-project.ipynb`
  → Notebook principal con limpieza, EDA, distribuciones, outliers y conclusiones.
  
## 🛠️ Tecnologias utilizadas.

- El proyecto fue realizado utilizando Python y las librerias de  Pandas, Matplotlib, Seaborn.

## 📘 Cómo reproducir el análisis

1. Abre `notebooks/sprint7-final-proyect.ipynb`
2. Ejecuta las celdas en orden
3. El notebook carga automáticamente el dataset desde `/data/` o desde un enlace público (según corresponda)

## 🧠 Objetivo del análisis

- Identificar problemas de calidad de datos
- Analizar comportamientos, distribuciones y outliers
- Generar insights para entender las necesidades de los clientes.

