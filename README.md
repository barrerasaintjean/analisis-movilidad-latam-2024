# 🚦 Análisis de Movilidad y Economía: Latinoamérica 2024

Este proyecto investiga la correlación entre la congestión vehicular y el Producto Interno Bruto (PIB) per cápita en las principales capitales de América Latina. El objetivo es identificar si existe una relacion entre el ingreso por ciudadano y el trafico de una ciudad

## 🛠️ Stack Tecnológico
* **Python (Pandas & Matplotlib):** Utilizado para la limpieza de datos, manejo de valores nulos y unificación de datasets macroeconómicos y de tráfico.
* **Power BI:** Diseño de dashboard interactivo y creación de métricas DAX personalizadas.
* **Jupyter Notebooks:** Documentación del flujo de ETL (Extracción, Transformación y Carga).

## 📊 Dashboard de Resultados

![Dashboard de Movilidad Urbana](img/Captura de pantalla 2026-01-14 222202)

> Se desarrolló el **Índice de Eficiencia Urbana**, una métrica que pondera la generación de riqueza frente al tiempo perdido en tráfico, permitiendo rankear ciudades más allá de su PIB nominal.

## 📁 Estructura del Proyecto
* `data/`: Contiene los datasets originales de TomTom Traffic y datos económicos.
* `analisis_movilidad_final.ipynb`: Notebook con el proceso de limpieza y merge de datos.
* `graficos.pbix`: Archivo fuente de Power BI para exploración interactiva.
* `img/`: Capturas de pantalla del reporte final.

## 💡 Conclusiones del Análisis

* **Ausencia de correlación PIB-Tráfico:** Tras el análisis cruzado, se determinó que no existe una relación directa entre el tráfico vehicular y el ingreso per cápita por ciudadano. Esto sugiere que la congestión responde a factores estructurales (diseño vial, eficiencia del transporte público) más que al nivel de ingresos.
* **Efecto de Outliers:** Al excluir ciudades con alta densidad demográfica como Sao Paulo, Buenos Aires y Río de Janeiro, se aprecia una relación directa en el gráfico de dispersión, lo que confirma que el volumen de población es un factor determinante en la saturación vial por sobre las variables económicas.

---
**Contacto:** [https://www.linkedin.com/in/bastian-barrera-analistadedatos/]
