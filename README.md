# ```Telecomunicaciones```

![telecomunicaciones](imagenes/technology.jpg)

## ```Introducción```

El acceso a Internet se ha convertido en una necesidad básica en la vida cotidiana de las personas. Hoy en día, la mayoría de las actividades diarias, como el trabajo, el estudio, las compras, el entretenimiento y la comunicación, requieren el uso de Internet. Por lo tanto, tener un acceso confiable y de alta calidad es fundamental para las personas y las empresas.

Para las empresas prestadoras de servicios de telecomunicaciones, brindar un servicio de calidad que satisfaga las necesidades de sus clientes es vital para su éxito. Los clientes esperan un acceso rápido y confiable a Internet, sin interrupciones o problemas de conexión. Además, los clientes también buscan servicios personalizados y adaptados a sus necesidades, lo que significa que las empresas deben estar atentas a las tendencias y necesidades del mercado para poder ofrecer soluciones adecuadas.

En este contexto, como parte de mi formación como Data Analytics en la edtech Henry, se me asignó un proyecto donde la empresa **K-Sistem Tecnology** me designa la realización de un análisis completo del comportamiento del sector de las telecomunicaciones a nivel nacional en Argentina. Este análisis permitirá reconocer las tendencias y patrones en el comportamiento del mercado, identificar oportunidades de crecimiento y mejorar la calidad de los servicios ofrecidos.

## ```Objetivos```

El objetivo principal de este análisis es proporcionar información detallada sobre el comportamiento del sector de las telecomunicaciones en Argentina, con un enfoque particular en el acceso a Internet fijo. Algunos objetivos específicos incluyen:

1. Realizar un análisis completo del comportamiento del sector de las telecomunicaciones a nivel nacional, principalmente orientado el acceso a Internet, para así identificar tendencias y patrones en el comportamiento del mercado.

2. Identificar los KPIs relevantes para medir el éxito de los objetivos de la empresa prestadora de servicios de telecomunicaciones, teniendo en cuenta las tendencias y patrones identificados en el análisis del mercado.

3. Sugerir a la empresa prestadora de servicios de telecomunicaciones tres KPIs específicos que sean relevantes para medir el éxito de sus objetivos.

## ```Desarrollo del Proyecto```

Para lograr estos objetivos, se utilizaron los datasets proporcionados por ![ENACOM](https://datosabiertos.enacom.gob.ar/dashboards/20000/acceso-a-internet/), incluyendo la penetración de Internet fijo por hogares a nivel nacional, el total nacional de accesos a Internet fijo por banda ancha y banda angosta, el acceso a Internet fijo por tecnología y provincia, la velocidad media de bajada de Internet fijo por provincia y los accesos a Internet fijo por velocidad de bajada y provincia.

En primera instancia el análisis se llevó a cabo a través de un notebook utilizando herramientas de análisis estadístico y visualización de datos para realizar un análisis exploratorio de cada uno de los datasets destacando los siguientes puntos:

- Los resultados del análisis muestran que la penetración de Internet fijo varía significativamente entre las diferentes provincias de Argentina. Por ejemplo, algunas provincias tienen una penetración de más del 60%, mientras que otras apenas alcanzan el 40%. Esto indica que hay oportunidades de crecimiento en aquellas provincias donde la penetración es baja. La empresa prestadora de servicios de telecomunicaciones podría enfocar sus esfuerzos en estas provincias para aumentar su participación en el mercado y brindar acceso a Internet a un mayor número de personas.

- Además, la proporción de accesos de banda ancha es un indicador importante de la calidad del servicio de Internet fijo. En Argentina, más del 90% de los accesos a Internet fijo son de banda ancha, lo que indica que la empresa prestadora de servicios de telecomunicaciones debe enfocar su participación en este segmento del mercado.

- La velocidad media de descarga de Internet fijo varía entre las diferentes provincias de Argentina. Mientras que algunas provincias tienen una velocidad media de descarga de más de 20 Mbps, otras apenas alcanzan los 10 Mbps. Esto indica que hay oportunidades para mejorar la calidad del servicio de Internet fijo en algunas áreas. La empresa prestadora de servicios de telecomunicaciones podría enfocar sus esfuerzos en aquellas provincias donde la velocidad media de descarga es más baja para mejorar la calidad de su servicio y satisfacer mejor las necesidades de sus clientes.

Por otra parte a la empresa se le sugieren 3 KPIs: Penetración de Internet fijo, Proporción de accesos a Internet fijo a través de banda ancha y la Velocidad media de descarga del servicio de Internet fijo en Argentina.

Por último se presenta un dashboard en PowerBI con el objetivo de resumir y presentar la información de manera clara y concisa a la empresa así como mencionar los insights obtenidos a partir del análisis, los cuales permitirán a la empresa prestadora de servicios de telecomunicaciones mejorar la calidad del servicio y a impulsar un crecimiento sostenible en el futuro.

## ```Tecnologías utilizadas```

- **Python**: lenguaje de programación principal utilizado en el proyecto.

    ![Python](https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=Python&logoColor=white)

- **Librerías de Python**: se utilizaron diversas librerías de Python para diferentes tareas en el proyecto como pandas, numpy, matplotlib, seaborn y geopandas

- **Google Colab**: plataforma de Jupyter Notebook basada en la nube que se utilizó para el EDA (Análisis Exploratorio de datos)

    ![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00.svg?style=for-the-badge&logo=Google-Colab&logoColor=white)

- **PowerBI**: es una plataforma de análisis de datos y visualización de Microsoft, la cual se utilizó para la realización del dashboard

    ![Power BI](https://img.shields.io/badge/Power%20BI-F2C811.svg?style=for-the-badge&logo=Power-BI&logoColor=white)

## ```Referencias```

- Datasets obtenidos de ![ENACOM](https://datosabiertos.enacom.gob.ar/dashboards/20000/acceso-a-internet/)

- El archivo geojson del mapa de Argentina proviene de [Kaggle](https://www.kaggle.com/datasets/pablomgomez21/geojson-file-provincias-argentinas)