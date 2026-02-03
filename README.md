#  Análisis de Ventas y Desempeño de Tiendas

##  Descripción del proyecto

Este proyecto analiza el desempeño de cuatro tiendas a partir de datos de ventas, utilizando Python y bibliotecas de análisis de datos. El objetivo es identificar patrones relevantes en ingresos, categorías de productos, calificaciones de clientes, productos vendidos y costos de envío, con el fin de tomar una decisión basada en datos.

---

## Objetivos

- Calcular los ingresos totales por tienda.
- Analizar las ventas por categoría de producto.
- Obtener la calificación promedio de cada tienda.
- Identificar los productos más y menos vendidos.
- Calcular el costo promedio de envío por tienda.
- Generar visualizaciones para facilitar la interpretación de los datos.
- Emitir una recomendación final basada en el análisis.

---

## Tecnologías utilizadas

- Python 3
- Pandas
- Matplotlib
- Google Colab / Jupyter Notebook
- GitHub

---

##  Estructura del proyecto

├── data/
│ ├── tienda_1.csv
│ ├── tienda_2.csv
│ ├── tienda_3.csv
│ └── tienda_4.csv
│
├── notebooks/
│ └── analisis_tiendas.ipynb
│
├── README.md
└── .gitignore



---

## Análisis realizados

### 1. Análisis de facturación
Se calcularon los ingresos totales por tienda sumando los valores de la columna `Precio`.

### 2. Ventas por categoría
Se agruparon las ventas por tienda y categoría para identificar las más y menos populares.

### 3. Calificación promedio de la tienda
Se calculó la calificación promedio de los clientes para evaluar la experiencia de compra.

### 4. Productos más y menos vendidos
Se analizó el volumen de ventas por producto en cada tienda.

### 5. Envío promedio por tienda
Se calculó el costo promedio de envío para evaluar su impacto en el rendimiento.

---

## Visualizaciones

Se generaron gráficos utilizando Matplotlib, incluyendo:
- Gráficos de barras para ingresos por tienda.
- Gráficos de ventas por categoría.
- Gráficos comparativos de costos de envío y calificaciones.

---

##  Conclusión

Tras analizar los datos, se identificó que la Tienda 4 presenta el menor ingreso total y no destaca en ventas por producto o categoría. Aunque cuenta con el costo promedio de envío más bajo, este beneficio no compensa su bajo rendimiento general.

Por lo anterior, se recomienda que el Sr. Juan venda la Tienda 4, ya que es la tienda con el desempeño más débil en comparación con las demás.

---

##  Ejecución del proyecto

1. Clonar el repositorio:

2. Abrir el notebook en Google Colab o Jupyter Notebook.

3. Ejecutar las celdas en orden para reproducir el análisis.

---

##  Nota

Proyecto desarrollado con fines académi
