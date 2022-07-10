# tarea-Qgis-banfi-lima

Tarea perteneciente a la clase numero dos del Curso Herramientas computacionales.

En este caso, el objetivo es demostrar mediante mapas y graficos la informacion que consideremos relevante de la base de datos sobre lugares de Airbnb, indicadores socioeconómicos y delincuencia por barrio en Chicago.

Ademas, graficar variables obtenidas del INDEC para Buenos Aires.


En la carpeta "files" de este repositorio se encuentran los archivos con los que trabajamos. 
-Para Chicago: el archivo "airbnb_Chicago 2015.dbf" contiene una base de datos armada por Rodrigo Valdes para la ciudad estadounidense de Chicago con elementos de Airbnb y datos socioeconómicos y de crímenes, todo por áreas comunitarias. La descripción de esta base se encuentra en el archivo "Airbnb.pdf". En "Boundaries_Chicago.zip" es posible encontrar los archivos necesarios para delimitar geográficamente los barrios de Chicago en QGIS. 
-Para Buenos Aires: los archivos "act_bsas.csv" y "nbi_bsas.csv" contienen los datos de desempleo y NBI para la Provincia de Buenos Aires (PBA) y la Ciudad Autónoma de Buenos Aires (CABA). En "partidos_caba_bsas.zip" se pueden ver los archivos para trabajar con el área geográfica en QGIS, siendo estos datos provenientes de INDEC. 

Finalmente, en el archivo "Tarea 2 QGIS (Banfi, Lima).pdf" se encuentran los mapas y gráficos correspondientes al análisis para ambas bases de datos. Los mapas para Chicago son un mapa coroplético para la distribución de precios de Airbnb por barrio, un cartograma para crímenes y disponibilidad de habitaciones y un mapa coreoplético con los desvíos estándar del índice Hardship, por barrio. Los gráficos, por su parte, muestran un scatter plot entre el ingreso per cápita y el índice Hardship, un histograma 2D para el precio de los Airbnb y los robos y un box plot para los quintiles de ingreso y el precio de los Airbnb. Por su parte, para Buenos Aires y la Ciudad Autónoma de Buenos Aires es posible encontrar un mapa coreoplético por departamentos para NBI y un mapa 3D para el desemlpeo, también por departamentos.
