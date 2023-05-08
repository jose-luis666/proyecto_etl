# Proyecto ETL

En este proyecto se realizará una extracción, transformación y carga de los datos de las canciones más virales de Spotify durante el 2022 a una base de datos de SQL.

## Metodología:

    -Extracción de datos de tres fuentes distintas utilizando dos métodos de extracción diferentes.
    -Transformación y limpieza de los datos.
    -Carga en base de datos.

## Primer paso:

En primer lugar hemos descargado un archivo csv de Kaggle, con toda la información acerca de estas canciones virales y sus artistas.

Seguidamente hemos procedido a su limpieza, para evitar confusiones e imprecisiones. También hemos decidido prescindir de gran cantidad de filas y quedarnos sólo con las 50 canciones más virales, para facilitar el proceso de extracción de datos posterior.


## Segundo paso:

Una vez limpios y ordenados los datos, hemos pasado a enriquecer la tabla. 

Para esto hemos decidido acudir a las redes sociales de los artistas, y observar su actividad. Seguidamente, hemos recopilado el número de tweets de cada uno de ellos y su número de seguidores en TikTok, y los hemos incorporado a nuestra tabla.

Nos hemos valido de la automatización para extraer los datos, y gracias al scrapping con Selenium, en sólo unos minutos hemos obtenido toda la información.


## Resultado:

El resultado nos ofrece una tabla con información completa y ordenada acerca del artista y de las canciones más virales del año 2022.