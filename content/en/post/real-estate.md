---
description: "A tool to ease pre and post insvesting analysis"
featured_image: "/images/Real-Estate.jpg"
tags: ["analytics","dashboard","Data Science","Real Estate"]
title: "Real Estate Dashboard"
---

This project is a Streamlit dashboard where investors can analyse their personal protfolios and future aquisitions

This dashboard includes two sections:

**General portfolio**

![General image 1](/images/Real-Estate-General1.jpeg)

![General image 2](/images/Real-Estate-General2.jpeg)

In this section we have general portfolio information: net value, KPIs and a map to analysis geogephical information of properties

**Individual analysis**

![Individual image](/images/Real-Estate-Individual.jpeg)

In this section investors can get specific metrics for aquired and non aquired properties, the property to analyze can be selected in a dropdown menu, the properties shown in this can be filtered using filters located in site's sidebar.

Depending on the type of property to analyze, metrics shown will vary:

*Bought*: Investment quality rating, historical info and profitability metrics

*Oportunity*: Investment quality rating, negaotiation values and KPIs estimated accoirding to geographic location

You can check a demo of this dashboard in this [URL](https://thetecj-realestatedashboard-main-ktz5fv.streamlit.app/)

**About the dataset**

 At the moment this tool uses a manually filled csv file where an interested investor can enter properties and get calculated KPIs and a scraped dataset including 1419 properties pusblished for sale in [Mercado Libre](https://www.mercadolibre.com). In the future I plan to add more realistic data about rent prices near properties to make metric calculations as accurate as possible, possibly this will be done by including another scraped dataset with porperties for rent.