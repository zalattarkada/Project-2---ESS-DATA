# Project 3 - Análisis de una muestra de encuestas de la European Social Survey
---
<p align="center">
  <img src="images/ESS.png" />
</p>

En este trabajo se realiza un análisis de una muestra de encuestas de la décima públicación del European Social Survey. La European Social Survey (ESS) es una encuesta de investigación social a gran escala que se realiza en Europa. El objetivo de esta encuesta es medir las actitudes, valores y comportamientos de los ciudadanos europeos en una amplia gama de temas sociales, políticos y económicos. La encuesta se lleva a cabo cada dos años en más de 30 países europeos y ha sido una fuente importante de datos para la investigación social desde su lanzamiento en 2002. Analizaremos una muestra de más de 30000 encuestas con el objetivo de evaluar las hipótesis planteadas a continuación.

---

## Hipótesis

- La raza del inmigrante afecta significativamente a la valoración que hace el encuestado de la inmigración.
- La variable de la raza de un inmigrante tiene más importancia que otra variable cómo la económica.
- No hay una diferencia concluyente entre los encuestados de distintos países con un porcentaje de población inmigrante similar (del 10% al 15%).

## Estructura del repositorio
El repositorio cuenta con los siguientes elementos:

- **code**: carpeta que contiene el archivo analysis.ipynb, en el que se analiza el dataset y se representan visualmente los resultados, cleaness.ipynb y cleanpib.ipynb, en los que se trata los datasets para su gestión, y sql.ipynb, en el que se importa y crea la base de datos.
- **data**: carpeta que contiene el dataset utilizado para el análisis.
- **images**: carpeta que contiene las imágenes y gráficas generadas en el análisis.

--- 

### Tratamiento de los datasets
En los archivos cleaness.ipynb y cleanpib.ipynb se lleva a cabo el tratamiento de los datasets para su gestión. En ambos casos, se realiza una limpieza de los datos y se crean nuevas variables a partir de las existentes.

### Análisis del dataset
En el archivo analysis.ipynb se realiza un análisis del dataset utilizando diferentes técnicas y herramientas. En primer lugar, se realiza una limpieza y tratamiento de los datos, incluyendo la eliminación de valores nulos y la creación de nuevas columnas a partir de las existentes.

A continuación, se lleva a cabo un análisis exploratorio de los datos, que incluye una descripción estadística de las variables y la representación visual de los resultados mediante gráficas.

Por último, se realizan pruebas de hipótesis para evaluar las hipótesis planteadas anteriormente y se representan los resultados visualmente mediante gráficas.

Para analizar las hipótesis, utilizamos tres preguntas de la encuesta:

- imsmetn: ¿Permite que muchos/pocos inmigrantes sean de la misma raza/grupo étnico que la mayoría de las personas de su país?
- imdfetn: ¿Permite que muchos/pocos inmigrantes sean de una raza/grupo étnico diferente a la mayoría de las personas de su país?
- imbgeco: ¿Cree que la inmigración es buena o mala para la economía de su país?

### Importación y creación de la base de datos
En el archivo sql.ipynb se importa y crea la base de datos utilizada en el análisis y se realizan informes.

---

## Conclusiones

Tras el análisis realizado, se puede concluir que:

- Pese a que se puede comprobar que los ciudadanos encuestados tienen por lo general una vision más negativa de la inmigración cuándo el inmigrante es de diferente raza, esta diferencia no es estadísticamente significativa. Por lo tanto, no se puede concluir que haya una diferencia significativa en la actitud hacia la inmigración dependiendo de si el inmigrante es de la misma raza o no en base a los datos proporcionados en el dataset.
  
- La variable de la raza tiene más importancia que la variable económica en la valoración de la inmigración.
  
- Podemos concluir que la percepción de la inmigración es significativamente diferente entre los países incluidos en el análisis.