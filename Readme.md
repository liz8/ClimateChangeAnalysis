# Objetivo del Análisis
El objetivo de este análisis es entender cómo ha cambiado la temperatura global a lo largo del tiempo. Vamos a explorar los datos para identificar tendencias y patrones que nos permitan comprender mejor el calentamiento global.

# Explicación de las Variables
El archivo GLB.Ts+dSST.csv contiene varias columnas de datos. A continuación, te explicaré cada una de ellas:
•  Year (Año): Representa el año en que se registraron las temperaturas.

•  Jan (Enero), Feb (Febrero), ..., Dec (Diciembre): Estas columnas representan la anomalía de temperatura para cada mes del año. Una anomalía de temperatura es la diferencia entre la temperatura observada y una temperatura promedio de referencia.

•  J-D: La anomalía de temperatura promedio de enero a diciembre.

•  D-N: La anomalía de temperatura promedio de diciembre del año anterior a noviembre del año actual.

•  DJF: La anomalía de temperatura promedio para los meses de diciembre, enero y febrero (invierno en el hemisferio norte).

•  MAM: La anomalía de temperatura promedio para los meses de marzo, abril y mayo (primavera en el hemisferio norte).

•  JJA: La anomalía de temperatura promedio para los meses de junio, julio y agosto (verano en el hemisferio norte).

•  SON: La anomalía de temperatura promedio para los meses de septiembre, octubre y noviembre (otoño en el hemisferio norte).

# Análisis de Datos de Cambio Climático

Este proyecto analiza las anomalías de temperatura global usando datos reales proporcionados por la NASA.

## Datos

Los datos utilizados en este proyecto son del GISS Surface Temperature Analysis (GISTEMP) y pueden ser encontrados en: [NASA GISS Surface Temperature Analysis](https://data.giss.nasa.gov/gistemp/).

## Estructura del Proyecto

- `GLB.Ts+dSST.csv`: Contiene el archivo de datos.
- `https://github.com/liz8/ClimateChangeAnalysis/blob/main/ClimateChangeAnalysis_Scripts.ipynb`: Contiene el cuaderno de Jupyter (o script de Python) con el análisis.
- `README.md`: Este archivo, que describe el proyecto.

## Requisitos

- Python 3.x
- Pandas
- Matplotlib

