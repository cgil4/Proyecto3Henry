![HenryLogo](https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png)

# **Proyecto 3**

# <h1 align="center">**`Presentacion ultimo proyecto individual Data Analytics`**</h1>

<p align="center">
<img src="https://img.freepik.com/free-vector/linear-flat-visitor-analytics-website-hero-image-illustration-seo-smm-online-marketing-concept-laptop-tablet-with-report-data-screen_126523-2649.jpg?w=2000"  height=300>
</p>

Ultimo proyecto individual de la etapa de labs! Trabajo realizado situándose en el rol de un ***Data Analyst***.


## **Contexto**

La **Organización de Aviación Civil Internacional (OACI)**, organismo de la Organización de las Naciones Unidas, quiere investigar en profundidad los accidentes producidos desde inicios del siglo XX. Para ello, les solicita la elaboración de un informe y un dashboard interactivo que recopile tal información. 

La OACI únicamente cuenta con un dataset sobre datos de accidentes de aviones, pero insta a la consultora de datos -de la que forman parte- que intente cruzar esta información con otras fuentes de su interés. Esto con el objetivo de obtener mayor claridad y consistencia en los fundamentos del estudio.

## **Realización de trabajo**


+ Se realiza un EDA con el dataset provisto, junto con un reporte de calidad y diccionario de datos
+ Se Busca y relaciona información relevante con los eventos
+ Se crea una base de datos en MySQL e ingesta el csv procesado
+ Se elaborar un dashboard que sera presentado
+ Adjuntamos todo el trabajo en un repositorio de GitHub


Stack tecnológico:

+ `Python`: EDA + transformaciones 
+ `MySQL`: base de datos
+ `Power BI` se crea el Dashboard
+ `GitHub`: se sube toda información

Diccionario de datos


+ `fecha`: Fecha del siniestro
+ `HORA declarada`: Hora del siniestro
+ `OperadOR` Operador de la aeronave
+ `flight_no`: Numero de vuelo
+ `Ruta`: Lugar del accidente
+ `route`: Ruta que cubria
+ `ac_type` Tipo de Avion
+ `registration`: Registro
+ `cn_ln`: Fuselaje
+ `All_aboard`: Personas a bordo
+ `PASAJEROS A BORDO` Pasajeros a bordo
+ `crew_aboard`: Tripulacion a bordo
+ `cantidad de fallecidos`: Cantidad total de fallecidos
+ `passenger_fatalities`: Pasajeros fallecidos
+ `crew_fatalities` Tripulantes fallecidos
+ `ground`: salvados
+ `summary`: Informe del siniestro


                            
                          

Se realiza un primer acercamiento al dataset con Python. creando un análisis exploratorio transformaciones y preprocesamiento pertinentes. Documentamos con los comentarios necesarios. 

Se ingesta el dataset en MySQL para finalmente conectar a la herramienta de visualización en este caso Power BI
- - -
