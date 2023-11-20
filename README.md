# Trending-Youtube-FR-G02 - TRABAJO FINAL

#####  Carrera: Ciencias de la Computación


|AUTORES    |
| ----------|
| Quispe Ayala Diego Juan Pablo  |
| Roque Ponce, Christian Alonso     |
| Retuerto Diaz, Pedro Alejandro   |
| Luis Lázaro, Daniel Orlando    |


------------



[INDICE](#título-principal)
1. INTRODUCCIÓN 
2. COMPRENSIÓN DEL NEGOCIO 
3. Objetivos del proyecto 
4. Por Categoría de Videos
5. Por el tiempo transcurrido
6. Por Canales de YouTube
7. Por la geografía del país
8. Adicionalmente, al cliente le gustaría conocer si
9. Objetivos de Data Science 


------------
#### 1.  INTRODUCCIÓN
Debido al aumento significativo de lo que hoy se conoce como “Big Data” las empresas buscan la forma de tener una visión más detallada de esta información, para de esta forma sacarle provecho a dichos datos, es por este mismo motivo que en este proyecto nos enfocaremos en lograr utilizar dicha información para de esta forma lograr un análisis completo brindando un análisis detallado de las preferencias de las personas de Francia que utilizan la plataforma Youtube.

Objetivo:

El objetivo principal del proyecto de analítica es analizar las tendencias de los videos de YouTube del país de Francia, mediante el conjunto de datos "Trending YouTube Video Statistics". Así mismo, se busca extraer conocimientos significativos y patrones que ayuden a comprender el comportamiento de los usuarios, las preferencias de contenido y otros aspectos relevantes en el ámbito de los videos en YouTube.

Alcance del Problema:

El alcance de este proyecto abarca un análisis exhaustivo de las tendencias de videos en YouTube en Francia, utilizando el conjunto de datos "Trending YouTube Video Statistics". Se delimita a las siguientes áreas de interés:

Categorías y Preferencias de Contenido:
 Explorar las categorías de vídeos más populares y evaluar las preferencias del público francés.

Evolución Temporal de Tendencias:
Investigar cómo ha cambiado el volumen y la popularidad de los videos a lo largo del tiempo, identificando patrones y tendencias temporales.

Identificación de Canales Relevantes:
Destacar los canales de YouTube que son tendencia con mayor frecuencia y aquellos que tienen una presencia menos destacada.


Conocimiento a Extraer:

El análisis del conjunto de datos para el proyecto de analitica de tendencia de youtube para el país de Francia nos permitirá aprender y aplicar varios conceptos aprendidos y aplicados en a lo largo de curso de ciencia de datos como lo son: 

Análisis Exploratorio de Datos (EDA):
Comprender la estructura y características del conjunto de datos, el cual en este caso sería el dataset de francia.
   - Identificar patrones y outliers del dataset de francia, así mismo identificar datos faltantes y posibles cambio de filas o columnas del dataset.

Manipulación y Limpieza de Datos:
   - Se debe realizar la limpieza de datos arreglando cualquier fallo detectado con anterioridad, así mismo realizar los cambios de filas o columnas respectivas en este caso dentro de un dataset nuevo el cual llamaremos clean FR

Visualización de Datos:
- Responder a las preguntas planteadas anteriormente y representar los resultados de manera gráfica.

Análisis Geoespacial:
- Emplear las columnas de latitud, longitud, estado, etc., para visualizar los estados a través de la biblioteca Folium.

Modelado Predictivo:
   - Hacer uso de regresión logística para responder las dos últimas preguntas dadas con anterioridad, lo cual nos permitirá conocer y aprender más sobre los modelos predictivos.
   
#### 2. METODOLOGÍA CRISP-DM 

##### 1. COMPRENSIÓN DEL NEGOCIO . 

El análisis se centra en varios aspectos clave para mejorar la estrategia de marketing del cliente o empresa. La identificación de tendencias, basada en las categorías de vídeos más populares, sugiere la alineación estratégica con temas de alta demanda. Esto se traduce en la creación de contenido relevante para mejorar la visibilidad y el compromiso.

El entendimiento de las preferencias del público a través del análisis de categorías de vídeos más y menos populares proporciona información crucial para adaptar el contenido según las demandas del mercado objetivo. La optimización del contenido, evaluando las proporciones de "Me gusta" / "No me gusta" y "Vistas" / "Comentarios" en diferentes categorías, guía la creación de contenido más efectivo, maximizando la interacción positiva.

La identificación de canales de YouTube en tendencia y la frecuencia de su presencia permiten a la empresa asociarse estratégicamente con creadores de contenido populares, generando colaboraciones exitosas y aumentando la visibilidad de la marca. Además, el conocimiento de la segmentación geográfica, incluyendo los estados con mayor participación, proporciona una base sólida para personalizar estrategias de marketing según las preferencias regionales.

La capacidad de prever el rendimiento futuro, ya sea en términos de vistas, "Me gusta" o "No me gusta", brinda a la empresa una ventaja estratégica para planificar campañas de manera más efectiva, asignar recursos de manera óptima y anticiparse a las tendencias emergentes. En resumen, este enfoque analítico dinámico no solo facilita la adaptación a las preferencias del público, sino que también permite una mejora continua en la efectividad de las campañas de marketing a lo largo del tiempo.

Objetivos del proyecto 


El proyecto tiene como objetivo principal explorar y comprender las dinámicas de los videos de tendencia en YouTube específicamente en Francia. Se busca analizar el conjunto de datos proporcionado, responder preguntas clave sobre preferencias de contenido, cambios temporales en las tendencias, destacar canales de YouTube frecuentemente tendenciales y examinar la distribución geográfica de las interacciones.

El alcance incluye el uso de herramientas de ciencia de datos para realizar un análisis exploratorio detallado, manipulación y limpieza efectiva de datos, visualización gráfica de resultados, análisis geoespacial utilizando la biblioteca Folium, y la aplicación de modelos predictivos, como la regresión logística, para evaluar la posibilidad de predecir métricas clave como "Vistas", "Me gusta" o "No me gusta".

Por lo que, el proyecto busca proporcionar una visión completa de las preferencias y comportamientos de los usuarios de YouTube en Francia, aprovechando la riqueza de datos disponibles para obtener información valiosa y aplicar técnicas avanzadas de análisis de datos.

Por Categoría de Videos
1. ¿Qué categorías de videos son las de mayor tendencia?
2. ¿Qué categorías de videos son los que más gustan? ¿Y las que menos gustan?
3. ¿Qué categorías de videos tienen la mejor proporción (ratio) de “Me gusta” / “No me gusta”?
4. ¿Qué categorías de videos tienen la mejor proporción (ratio) de “Vistas” /“Comentarios”?
Por el tiempo transcurrido
5. ¿Cómo ha cambiado el volumen de los videos en tendencia a lo largo del tiempo?
Por Canales de YouTube
6. ¿Qué Canales de YouTube son tendencia más frecuentemente? ¿Y cuáles con menos frecuencia?
Por la geografía del país
7. ¿En qué Estados se presenta el mayor número de “Vistas”, “Me gusta” y “No me gusta”?
Adicionalmente, al cliente le gustaría conocer si
8. ¿Es factible predecir el número de “Vistas” o “Me gusta” o “No me gusta”?
9. ¿Los videos en tendencia son los que mayor cantidad de comentarios positivos reciben?


Objetivos de Data Science 


Lograr identificar patrones de tendencia en las visualizaciones de los videos de Youtube Francia
Los objetivos de Data Science que posee el proyecto son el de recolectar los suficientes datos de las estadísticas de los videos para poder darles un valor
Realizar modelos predictivos para de esta forma lograr informar a la empresa de marketing sobre las categorías más influyentes

##### 2.COMPRENSIÓN DE LOS DATOS 
Los datos recolectados a través de las estadísticas proporcionadas van a proceder a ser limpiados y analizados, para posteriormente conseguir la versión más ideal de estos mismos, que logren generar una mejor información sobre las tendencias en la red social Youtube Francia.


Recolectar los datos iniciales 
Para recolectar los datos iniciales se descargaron del aula virtual los cuales son un dataset de kaggle el cual fue modificado con nuevos apartados los cuales son: 
state: nombre del Estado perteneciente al país 
 Lat:  latitud geográfica de ubicación del Estado.
lon: longitud geográfica de ubicación del Estado.
Geometry: (opcional) registra las coordenadas de las geometrías donde se ubica.

Este dataset se llama “FRvideos_cc50_202101.csv “  el cual es un CSV con la información de los distintos campos.
Después contamos con  “FR_category_id.json” el cual es un archivo tipo JSON el cual nos es útil cuando estás trabajando con datos de YouTube para comprender las preferencias de los usuarios por medio de categorías.


Luego de la descarga se importaron al proyecto por medio de visual studio code en la carpeta code.



