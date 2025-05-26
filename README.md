# Python-para-Data-Science-Challenge-Alura-Store
# Análisis de Ventas - Alura Store

## Introducción

Este proyecto se enfoca en el análisis de los datos de ventas de cuatro tiendas "Alura Store" con el objetivo de proporcionar información valiosa para la toma de decisiones administrativas. El análisis cubre métricas clave como los ingresos totales, las ventas por categoría, la calificación promedio de los clientes, los productos más y menos vendidos, y los costos de envío promedio.

## Datos

Los datos utilizados en este análisis provienen de los siguientes archivos CSV, alojados en un repositorio de GitHub:

- Tienda 1: `https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_1%20.csv`
- Tienda 2: `https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_2.csv`
- Tienda 3: `https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_3.csv`
- Tienda 4: `https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_4.csv`

## Análisis Realizado

El análisis se llevó a cabo utilizando Python con las bibliotecas pandas y matplotlib. Los puntos clave analizados son:

1.  **Análisis de Facturación:** Cálculo del ingreso total para cada tienda.
2.  **Ventas por Categoría:** Identificación de las categorías de productos con mayor y menor volumen de ventas en cada tienda.
3.  **Calificación Promedio de la Tienda:** Determinación de la calificación promedio obtenida por cada tienda según la opinión de los clientes.
4.  **Productos Más y Menos Vendidos:** Identificación de los productos individuales con mayor y menor número de ventas.
5.  **Envío Promedio por Tienda:** Cálculo del costo de envío promedio por tienda.
6.  **Visualizaciones:** Creación de gráficos para ilustrar las relaciones entre el precio y la calificación, y la distribución de productos por categoría.

## Resultados Clave

Los resultados obtenidos del análisis son los siguientes:

*   **Ingreso Total:**
    *   Tienda 1: 1,150,880,400.00
    *   Tienda 2: 1,116,343,500.00
    *   Tienda 3: 1,098,019,600.00
    *   Tienda 4: 1,038,375,700.00

*   **Ventas por Categoría:**
    *   En general, la categoría "Muebles" es la más popular en las cuatro tiendas.
    *   Las categorías menos populares varían entre las tiendas, siendo "Artículos para el hogar" e "Instrumentos musicales" las menos vendidas en diferentes tiendas.

*   **Calificación Promedio:**
    *   Tienda 1: 3.977
    *   Tienda 2: 4.037
    *   Tienda 3: 4.048
    *   Tienda 4: 3.996

*   **Envío Promedio:**
    *   Tienda 1: 26,018.61
    *   Tienda 2: 25,216.236
    *   Tienda 3: 24,805.68
    *   Tienda 4: 23,449.513

## Conclusiones y Recomendaciones

Basado en el análisis de los datos:

*   La tienda con menor volumen de ventas es la **Tienda 4**. Podría considerarse como una opción para un posible cierre si es necesario optimizar recursos.
*   A pesar de que la Tienda 1 tiene el mayor ingreso total, la **Tienda 3** presenta la calificación promedio más alta, lo que podría estar relacionado con su costo de envío promedio más bajo, influyendo positivamente en la satisfacción del cliente.
*   Se recomienda evaluar la estrategia para la categoría de "Artículos para el hogar" e "Instrumentos musicales", ya que consistentemente muestran las menores ventas en las tiendas. Los recursos podrían ser mejor invertidos en la promoción y venta de "Muebles", la categoría más popular.

## Uso

Para replicar este análisis, puedes ejecutar el código proporcionado en un entorno como Google Colab o Jupyter Notebooks. Asegúrate de tener instaladas las bibliotecas pandas y matplotlib.
