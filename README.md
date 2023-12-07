# ProyectoDataAnalytic

## Descripción

El siguiente proyecto consta en realizar un análisis completo que permita determinar el comportamiento de los sinietros viales, esto con el fin de establecer nuevas medidas que ayuden a disminuir la cantidad de victimas en la Ciudad Autonoma de Buenos Aires, además de mejorar la movilidad.

Los siniestros viales, también conocidos como accidentes de tráfico o accidentes de tránsito, son eventos que involucran vehículos en las vías públicas y que pueden tener diversas causas, como colisiones entre automóviles, motocicletas, bicicletas o peatones, atropellos, choques con objetos fijos o caídas de vehículos. Estos incidentes pueden tener consecuencias que van desde daños materiales hasta lesiones graves o fatales para los involucrados.

En el contexto de una ciudad como Buenos Aires, los siniestros viales pueden ser una preocupación importante debido al alto volumen de tráfico y la densidad poblacional. Estos incidentes pueden tener un impacto significativo en la seguridad de los residentes y visitantes de la ciudad, así como en la infraestructura vial y los servicios de emergencia.

Las tasas de mortalidad relacionadas con siniestros viales suelen ser un indicador crítico de la seguridad vial en una región. Estas tasas se calculan, generalmente, como el número de muertes por cada cierto número de habitantes o por cada cierta cantidad de vehículos registrados. Reducir estas tasas es un objetivo clave para mejorar la seguridad vial y proteger la vida de las personas en la ciudad.

En Argentina, cada año mueren cerca de 4.000 personas en siniestros viales. Aunque muchas jurisdicciones han logrado disminuir la cantidad de accidentes de tránsito, esta sigue siendo la principal causa de muertes violentas en el país. Los informes del Sistema Nacional de Información Criminal (SNIC), del Ministerio de Seguridad de la Nación, revelan que entre 2018 y 2022 se registraron 19.630 muertes en siniestros viales en todo el país. Estas cifras equivalen a 11 personas por día que resultaron víctimas fatales por accidentes de tránsito.

Solo en 2022, se contabilizaron 3.828 muertes fatales en este tipo de hechos. Los expertos en la materia indican que en Argentina es dos o tres veces más alta la probabilidad de que una persona muera en un siniestro vial que en un hecho de inseguridad delictiva.

## Archivos

### Limpieza_Datos.ipynb

En este archivo se realiza un proceso de ETL en el cual se eliminan columnas innecesarias y se reemplazan valores nulos de un archivo .xlsx denominado "homicidios". Este archivo tiene dos hojas de cálculo llamadas HECHOS y VICTIMAS. Los archivos limpios resultantes se guardan para su posterior análisis.

### PoblacionCABA.ipynb

Este archivo realiza un ETL de un archivo .csv denominado "poblacionCABA". En este proceso se realiza la inversión de columnas a filas, eliminación de columnas y reemplazo de valores nulos.

### EDA.ipynb

En este archivo se realizan procesos de ETL y luego se realizan gráficos entre variables para explorar los datos y obtener insights. Para mas detalles revisar dicho archivo, el cual contiene las diferentes graficas y análisis respectivos entre las diferentes variables de los datasets.

### KPIs.ipynb

Este archivo se encarga de realizar cálculos para crear columnas y desarrollar KPIs. Posteriormente, estos KPIs son graficados para su visualización y análisis.

## Proceso

El proceso general que se sigue utilizando estos archivos comienza con la limpieza y preparación de los datos en los archivos 'Limpieza_Datos.ipynb' y 'PoblacionCABA.ipynb'. Luego, se realiza un análisis exploratorio de los datos en 'EDA.ipynb' y finalmente se calculan y visualizan los KPIs en 'KPIs.ipynb'.

## Resultados

En los diferentes procesos se obtienen diferentes datasets limpios que son utilizados de manera cronologica en los archivos descritos anteriormente.
