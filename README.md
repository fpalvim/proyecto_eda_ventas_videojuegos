# Análisis EDA de ventas de videojuegos (1980-2016) 📈📊

Autor: Felipe Alvim

<hr>
<br>

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/04/shutterstock_1290635251.jpg?q=49&fit=crop&w=1100&h=618&dpr=2)

## Descripción

Este conjunto de datos ofrece información sobre las ventas de videojuegos según plataforma, editora y género para los títulos más populares a nivel mundial.
Con más de 16,000 registros de ventas entre 1980 y 2016, este análisis busca descubrir relaciones clave entre estas variables y proporcionar insights sobre las tendencias de una industria que mueve millones de dólares cada año.

## Estructura de Carpetas 📁

```
EDA_Project/
│
├── data/
│   ├── raw/    # Datos en su forma original, sin procesar.
│   └── processed/    # Datos después de la limpieza y transformación.
│
├── my_scripts/
│   └── auto_importer.py    # Funciones auxiliares (helpers) para el proyecto.
│
├── notebooks/
│   ├── 01_proyecto_EDA_data_loading_and_cleaning.ipynb    # Notebook para cargar y explorar 
│   │                                                        los datos.
│   └── 02_analisis_exploratorio_data_visualizations # Notebook para visualización y análisis 
│                                                       exploratorio.
│
├── reports/
│   └── MEMORIA.pdf     # Reporte en formato PDF.
│
├── pyproject.toml         # Archivo con las dependencias del proyecto 
├── README.md                # Descripción del proyecto.
└── .gitignore               # Archivos y carpetas que deben ser ignorados por git. 
```

## Herramientas y librerías utilizadas
**Jupyter**    📓  
**Matplotlib** 🎨  
**Pandas**     🐼  
**Python**     🐍  
**Scipy**      🔬  
**Seaborn**    📊


## Principales hallazgos 🔍
*  Clasificación de los principales juegos más vendidos a lo largo de los años, identificando patrones clave en el comportamiento de la industria.
*  Análisis de los géneros, editoriales y plataformas principales del mercado para determinar las tendencias predominantes.
*  Evaluación de las ventas por región y a nivel global para identificar los mercados con mayor consumo en esta industria.

## Aspectos visuales 📈📉

Se emplearon los siguientes tipos de gráficos para el análisis de datos:

Countplot - Visualización del conteo de ocurrencias en variables categóricas.  
Mapas de calor (Heatmap) - Análisis de correlaciones entre variables numéricas y categóricas.   
Barplots - Representación de clasificaciones para identificar las mayores ventas y analizar series temporales.  

## La evolución de los videojuegos: Descubre los secretos que te esperan

En lugar de terminar con una conclusión, quiero invitarte a que descubras por ti mismo los secretos que te esperan.

En las últimas décadas, la industria de los videojuegos ha experimentado una transformación extraordinaria. Electronic Arts (EA) ha consolidado su legado en el género deportivo con franquicias inolvidables como FIFA y Madden NFL. Por su parte, Activision ha redefinido el panorama de la acción, liderado por el fenómeno global perdurable de Call of Duty. Nintendo, con su encanto atemporal, continúa cautivando a los jugadores a través de los mundos mágicos de Mario y The Legend of Zelda, dominando como pocos los géneros de plataformas y RPG.

En los últimos 15 años, el mundo de los videojuegos ha sido impulsado por los gigantes de la innovación en hardware: PlayStation de Sony, Wii de Nintendo y Xbox de Microsoft. Su rivalidad ha moldeado una industria que prospera gracias a su dinamismo y feroz competitividad.

Pero, ¿qué hace que mercados como Japón sean tan distintos? ¿Cómo varían las preferencias por los géneros de acción, deportes, shooters y RPG en diferentes partes del mundo? ¿Y qué podemos descubrir al explorar los datos detrás de estos fenómenos?

Este repositorio guarda las claves para desentrañar respuestas. No se trata solo de analizar números, sino de revelar las historias ocultas dentro de los datos de una industria que ha cautivado a miles de millones.

¿Estás listo para sumergirte en el mundo de los videojuegos y descubrir qué secretos se esconden bajo la superficie?


