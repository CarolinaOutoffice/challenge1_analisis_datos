
# 🛍️ Análisis Comparativo de Tiendas - Proyecto de Ciencia de Datos

Este proyecto realiza un análisis exploratorio de datos sobre el desempeño de cuatro tiendas del sr. Juan. Fue desarrollado como parte de un reto de Data Science propuesto por Alura Latam.

---

## 📦 Datos Utilizados

Los datos fueron importados directamente desde GitHub, y contienen información de ventas, productos, precios, categorías, calificaciones y costos de envío de 4 tiendas distintas.

### Fuentes:
- [`tienda_1.csv`](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_1%20.csv)
- [`tienda_2.csv`](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_2.csv)
- [`tienda_3.csv`](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_3.csv)
- [`tienda_4.csv`](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_4.csv)

---

## 📊 Objetivos del Análisis

- Evaluar la facturación total por tienda.
- Analizar las categorías de productos más vendidos.
- Comparar calificaciones promedio por tienda.
- Identificar productos más y menos vendidos.
- Analizar el costo de envío promedio por tienda.
- Recomendar una tienda para cerrar basada en desempeño general.

---

## 🧪 Proceso Analítico

1. **Importación y limpieza de datos**
   - Carga de datasets individuales y consolidación en un único DataFrame.
   - Identificación de valores nulos o atípicos.

2. **Análisis de facturación**
   - Suma total y por tienda.
   - Gráficos de barras con formateo en millones.

3. **Ventas por categoría**
   - Agrupación por tienda y categoría.
   - Visualización con gráficos de barras y mapa de calor.

4. **Calificación promedio**
   - Comparación de la satisfacción del cliente por tienda.

5. **Productos más y menos vendidos**
   - Agrupación y conteo.
   - Visualización comparativa por tienda.

6. **Evaluación de costos de envío**
   - Promedio por tienda.
   - Análisis de facturación neta (`Precio - Costo de envío`).
   - Visualización en gráfico de torta.

---

## 📈 Herramientas Usadas

- `Python` + `Pandas` para manipulación de datos
- `Matplotlib` y `Seaborn` para visualización
- `Jupyter Notebook` como entorno interactivo

---

## ✅ Recomendación Final

> 💡 Se recomienda el cierre de la **Tienda 4**, dado que:
> - Tiene la menor facturación neta
> - Menor volumen de ventas
> - Calificación de cliente más baja

---

## 📁 Estructura del Proyecto

```
.
├── tienda_analisis.ipynb       # Notebook con el análisis completo
├── README.md                   # Este archivo

```

---

## 🚀 Cómo Ejecutar

1. Clona este repositorio o descarga el notebook.
2. Asegúrate de tener `pandas`, `matplotlib` y `seaborn` instalados.
3. Ejecuta el notebook `tienda_analisis.ipynb` paso a paso.


## 📬 Autor

Carolina Núñez  
---
