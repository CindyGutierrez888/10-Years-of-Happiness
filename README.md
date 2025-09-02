# 10-Years-of-Happiness
Explore Gobal report of happiness from 2015 to 2024 with Power BI dashboards

## Resumen

### Tema: 
Felicidad mundial 2015–2024 

### Objetivo: 
Ademas de cuestionarse cómo evoluciona nuestra satisfacción a nivel global, puedes explorar diferentes sentimientos al rededor del mundo, como por ejemplo el sentimiento de libertad para tomar decisiones, o que tan apoyados por parte de amigos y familiares, se sienten en diferentes paises. 
Este dashboard nos invita a valorar qué tan agradecidos o no deberiamos estar por nuestra vida y qué mejoras podemos hacer para sentirnos más felices.

### Resultados clave:
##### Al ser un Data set tan grande, incluye 10 data sets diferentes uno por año, con informacion de mas de 150 paises cada uno, se han logrado diferentes hallazgos:
- Varios paises han tenido que ser eliminados en la limpieza de datos al no estar registrados cada año.
- Los 5 primeros lugares siempre han sido los mismos paises alternando lugar en el ranking
- En el caso de los Territorios palestinos: cambiaron el nombre en el 2023 a Estado de Palestina, Borrandolo completamente del reporte en el 2024.
- Todos los paises eliminados de este dashboard se encuentran en los archivos originales y tambien como tabla invisible disponible en Transform Data en el archivo .pbix
- Más insighs pueden ser descubiertos por ti mismo.

## Datos

### Fuente(s): 
kaggle

### Periodo:
2015 - 2024

### Diccionario de datos:
entra a https://www.worldhappiness.report/ si necesitas ayuda para comprender cada una de las variables. 
ó directamente en el archivo da clic en el icono de información. 

## 👉 Live report: 
Si no quieres descargar el archivo, entra en https://app.powerbi.com/links/sGV_4BEHFL?ctid=53e0f663-6802-4124-8200-fd801cb6141c&pbi_source=linkShare para visualizar, jugar con los slicers y obtener insights

## Cómo está construido
### Limpieza de datos:
Revision de nombres de paises inconsistentes cada año. Revision de pertenencia verdadera a la region correspondiente
### Normalizacion de datos:
Normalizar todos los scores y paramentros, ya que algunas medidas venian con mas de 5 digitos, cuando el score que nos intereza tendria que ser del 1 al 10
### Añadir nueva info:
Se ha añadido la columna "Continente" para obtener información y vistazos sobre ello.
### Modelado de datos:
Conectar adecuadamente sobre todo datos como "year" para el correcto dinamismo
### Vizualizaciones:
Usando la herramienta Power BI

* Todas las transformaciones estan visibles en el archivo .pbix (Power Query)

## Roadmap / Futuro
Tal vez sea interezante predecir la felicidad por pais para el año 2025 o 2030, con algun modelo predictivo.

## Gracias!
de ante mano gracias por leer este read me, por visualizar mi proyecto y por toda la data recabada en un tema tan interezante como lo es la felicidad en el mundo.
Espero que nuestro promedio actual global (5.6) mejore y no estemos "reprovados" en felicidad a nivel planeta.
