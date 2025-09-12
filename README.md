# Análisis de ventas - Sample Superstore.
Este proyecto realiza un análisis exploratorio de datos (EDA) sobre el dataset Sample Superstore. El objetivo es obtener insights relevantes sobre ventas, ganancias, envios y clientes, utilzando Python con sus librerias de analisis y visualización. 

## Tecnologías utilizadas 
- Python 3.x
- Pandas
- Numpy
- Matplotlib
- Seaborn
- IPython (para visualización en notebooks)

## Dataset
El dataset utilizado es SampleSuperstore.csv, que contiene informacion de ordenes de clientes invluyendo:
- Fechas de orden y envio
- Región, estado y ciudad 
- Categorias y subcategorias de productos
- Ventas, descuentos y ganancias
- Datos generales de clientes

## Análisis realizado
**1. Preparación de datos**
- Conversion de fechas (Order Date, Ship Date)
- Creación de columnas:
  + ingreso_total (Ventas ajustadas de acuerdo al descuento)
  + margen_ganancia (Ventas por cantidad)
  + Variables de temporalidad: YerMonth, OrderY, OrderM

**2. Visualizaciones principales**
- Evolución mensual de ventas 
- Ventas por región, estado y ciudad
- Análisis de ventas y profit por categorías y subcategorías
- Principales clientes por ventas y por profit

**3. KPIs clave**
- Total de ventas
- Total de profit
- Tiempo promedio de envio
- Mejores meses de venta
- Categoria y región con mayores ventas

**4. Análisis RFM (Segmentación de clientes)**
- Días desde la última compra
- Número de órdenes
- Total gastado
- Clasificación por segmentos:
  + Cliente excelente
  + Cliente fiel
  + Cliente prometedor
  + Cliente en riesgo

## Resultados destacados
- Diciembre presenta picos de ventas significativos
- La región Oeste lidera el número de ventas
- La categoría de Tecnología es la más rentable
- El tiempo promedio de envio es de aproximadamente 3 días
- De acuerdo a la segmentación RFM, se obtuvieron los siguientes datos:
  + Cliente excelente: 24%
  + Cliente fiel: 28%
  + Cliente prometedor: 23%
  + Cliente en riesgo:  25%

## Optimización de Análisis
El análsis continua en proceso de optimización para incorporar modelos de predicción de ventas, asi como visualizaciones en Power BI. 