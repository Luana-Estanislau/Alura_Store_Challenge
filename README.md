# 📊 Análisis de Tiendas – Alura Store

Este proyecto analiza el rendimiento de las cuatro tiendas de la cadena **Alura Store** con el objetivo de apoyar la decisión de cuál vender para financiar un nuevo emprendimiento.  

El análisis se realizó en **Python** utilizando **Google Colab** y diversas librerías de análisis y visualización de datos.

---

## 🎯 Objetivo

Determinar, en base a datos históricos de ventas, logística y satisfacción del cliente, cuál de las cuatro tiendas presenta el menor rendimiento global y es candidata a ser vendida.

---

## 📂 Contenido del repositorio

- `AluraStoreLatam_Final.ipynb` → Notebook principal con todo el análisis y las visualizaciones.
- `README.md` → Documento actual con descripción del proyecto.

---

## 🛠️ Tecnologías y librerías usadas

- **Python 3**
- [pandas](https://pandas.pydata.org/) – Manipulación y análisis de datos.
- [matplotlib](https://matplotlib.org/) – Visualización de gráficos.
- [numpy](https://numpy.org/) – Operaciones numéricas.

---

## 📊 Metodología

1. **Importación y unificación de datos** de las 4 tiendas.
2. **Análisis de ingresos totales** por tienda.
3. **Estudio de categorías más y menos vendidas**, tanto por cantidad como por ingresos.
4. **Evaluación de calificaciones promedio** de los clientes.
5. **Identificación de productos más y menos vendidos** por tienda.
6. **Cálculo de costos de envío promedio** por tienda.
7. **Análisis geográfico** de ventas (latitud y longitud).
8. **Cálculo de un Índice de Eficiencia (IE)** que pondera ingresos, margen, ticket promedio, calificación y logística.
9. **Conclusión y recomendación** de la tienda a vender.

---

## 📈 Resultados

- Tienda con **mayores ingresos**: Tienda 1.
- Tienda con **menores ingresos**: Tienda 4.
- **Índice de Eficiencia** más bajo: Tienda 4 (bajo margen y ticket promedio).
- **Recomendación**: Vender Tienda 4.

> El notebook incluye el informe final completo en formato Markdown y todas las visualizaciones utilizadas para llegar a la recomendación.

---

## 🚀 Ejecución del proyecto

1. Clonar este repositorio:
   ```bash
   git clone https://github.com/Luana-Estanislau/Alura_Store_Challenge.git
