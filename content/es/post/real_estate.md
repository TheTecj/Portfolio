---
description: "Una herramienta para facilitar el analisis pre y post inversion"
featured_image: "/images/Real-Estate.jpg"
tags: ["analitica","dashboard","ciencia de datos","bienes raices"]
title: "Dashboard de Bienes Raices"
---

Este proyecto consiste en un dashboard de Streamlit mediante el cual lo inversionistas pueden analizar tanto su portafolio como perfilar futuras adquisiciones

Este dashboard se divide en 2 apartados:

**Portafolio general**

![Imagen general 1](/images/Real-Estate-General1.jpeg)

![Imagen general 2](/images/Real-Estate-General2.jpeg)

En este apartado se brinda la informacion general del portafolio: valuacion, KPIs de rendimiento y se muestra un mapa en el que se puede visualizar la informacion geografica de los inmuebles

**Analisis individualizado**

![Imagen individual](/images/Real-Estate-Individual.jpeg)

En este apartado, los inversionistas tienen la posibilidad de consultar metricas especificas tanto de los inmuebles adquiridos como de las oportunidades de inversion, la seleccion de inmuebles se hace a traves de un menu dropdown en el que se debe escoger la propiedad a analizar, las opciones mostradas en el dropdown se pueden filtrar usando filtros ubicados en la barra de opciones lateral de la pagina

Segun el tipo de inmueble a analizar, se muestran metricas diferentes:

*Comprado*: Se muestra su calificacion de calidad como inversion, informacion historica y metricas de rentabilidad

*Oportunidad*: Se muestran su calificacion de calidad como inversion, posibles valores implicados en la negociacion y metricas de desempeño estimadas mediante informacion geografica

Puede revisar una demo del dashboard en esta [URL](https://thetecj-realestatedashboard-main-ktz5fv.streamlit.app/)

**Sobre el dataset**

De momento esta herramienta usa un archivo csv llenado de forma manual, de manera que cualquier inversionista interesado en conocer los KPI de sus  inmuebles solo tendria que ponerlas en el archivo y revisar las metricas generadas, ademas se hace uso de un dataset de 1419 propiedades obtenido de publicaciones de venta en [Mercado Libre](https://www.mercadolibre.com) con Web Scraping. En el futuro, tengo planeado añadir informacion mas realista de sobre los precios de los arriendos cerca a cada inmueble, de manera que los caluclos de las metricas sean tan precisos como sea posible, probablemente esto se haga construyendo otro dataset mediante Web Sraping en el que se registren propiedades en arriendo.
