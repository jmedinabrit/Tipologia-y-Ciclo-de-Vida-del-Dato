
# Práctica II

Práctica II de la asignatura de Tipólogía y ciclo de vida de los datos, segundo semestre de 2022. 

# Correlación del precio del Gas y la Electricidad en Europa


## Componentes de la práctica

 - Jonás Medina Brito (jmedinabrit@uoc.edu)
 
## Guía  de la práctica

La guía de la práctica se encuentra en la siguiente ruta:

### 1. Descripción del dataset. ¿Por qué es importante y qué pregunta/problema pretende responder?
El Dataset, escogido en la práctica 1 de la asignatura, describe los precios del KWh para la electricidad y el gas, para todo los países de la Zona Euro y de la Comunidad Europea. Siendo de especial interés por el momento efervescente en debido al impacto en la inflación de los precios de los países debido a la incertidumbre en los países proveedores por su inestabilidad social y económica.
### 2. Integración y selección de los datos de interés a analizar. Puede ser el resultado de adicionar diferentes datasets o una subselección útil de los datos originales, en base al objetivo que se quiera conseguir.
El resultado son dos datsetes de trabajos individuales y uno general, auqnue para las pruebas de calidad de esta práctica nos centraremos en los dos datasets de precios de gas y electricidad Familiares:
-[`Notebook/JonasMedina_Pract2.ipynb`](Notebook/JonasMedina_Pract2.ipynb)
### 3. Limpieza de los datos.
### *3.1. ¿Los datos contienen ceros o elementos vacíos? Gestiona cada uno de estos casos.*
Si, se limpian datos corruptos, carácteres no válidos, y los valores NaN se sustituyen por la media de ese año en la muestra.
### *3.2. Identifica y gestiona los valores extremos.*
Se identifican dentro del Notebook en el Apartado 2.
En este caso para el Gas, en el año 2018 un valor muy cercano a 0 y para 2021 un valor superior a 0.08 que supone un posible outlier de la muestra.
Para la electricidad, en el año 2018 un por encima de 0.14, posible outlier de la muestra, y para 2020 un valor muy cercano a 0.

## Conlusión

Se concluye de forma general, que la muestra, presenta dificultades para poder demostrar de forma Hipotética fiable, que los precios de la electricidad están directa o inversamente relacionados con los del Gas.
Para más detalle, ver el apartado 6 del guión de la práctica o del notebook.

## Descripción de los ficheros fuentes

La extración como para el proceso y curación de los datos, así como su representación se ha realizado gracias a un notebook de [jupyter](https://jupyter.org/)

El notebook con el código se encuentra en el directorio

 - [`subdataset/data_electricity_prices_household_consumers.csv`](subdataset/data_electricity_prices_household_consumers.csv)
 - [`subdataset/data_gas_prices_household_consumers.csv`](subdataset/data_gas_prices_household_consumers.csv)
 
  
 ### Dataset 
 
 La exportación del dataset principal se localiza en la ruta  [`dataset/energy_price_dataset.csv`](./dataset/energy_price_dataset.csv)

 
## DOI del dataset en Zenodo

DOI: **`10.5281/zenodo.6424152`**

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6424152.svg)](https://doi.org/10.5281/zenodo.6424152)






