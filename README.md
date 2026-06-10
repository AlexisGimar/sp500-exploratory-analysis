# Exploratory Analysis of the S&P 500

## Descripción

En este proyecto se realizó un análisis exploratorio del índice S&P 500 utilizando Python y diversas herramientas del ecosistema de ciencia de datos.

## Objetivos

* Manipular datos financieros mediante pandas.
* Trabajar con series de tiempo.
* Generar visualizaciones utilizando matplotlib.
* Calcular rendimientos diarios.
* Realizar análisis estadístico descriptivo.
* Interpretar eventos financieros relevantes.
* Utilizar Git y GitHub para control de versiones.

## Herramientas utilizadas

* Python 3.13
* pandas
* matplotlib
* yfinance
* Jupyter Notebook
* Git
* GitHub

## Datos

Los datos fueron obtenidos mediante la biblioteca yfinance a partir de Yahoo Finance.

Ticker utilizado: ^GSPC

Periodo analizado: 2021-06-09 a 2026-06-09

## Resultados principales

* 1256 observaciones analizadas.
* Rendimiento diario promedio: 0.0501%.
* Volatilidad diaria (desviación estándar): 1.07%.
* Mejor día observado: 2025-04-09 (+9.52%).
* Peor día observado: 2025-04-04 (-5.98%).

Se identificó un episodio de volatilidad extrema durante abril de 2025 asociado a anuncios y posteriores modificaciones en políticas arancelarias de Estados Unidos.

## Estructura del proyecto

```text
sp500-exploratory-analysis/
│
├── notebooks/
│   └── analisis_indice.ipynb
│
├── README.md
└── .gitignore
```

## Cómo ejecutar el proyecto
1. Clonar el repositorio.
2. Crear un entorno virtual.
3. Instalar dependencias.
4. Abrir el notebook.

## Autor

Alexis Isidro
