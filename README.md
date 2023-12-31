# Analisis de datos de alojamientos Airbnb realizado en el marco de proyecto integrador Henry

Se desarrolló un tablero preliminar en PowerBi que permite entender en negocio de airbnb en la ciudad de Buenos Aires.
Se utilizaron tres datasets con la siguiente informacion:

* calendar.csv: (incluye datos de ocupación, precio, etc.)  
* listings.csv: Detalle de cada operación de Listing (incluye datos descriptivos de la vivienda (ambientes, host, noches mínimas y máximas, cantidad de reviews.)
* reviews.csv Datos de review de los usuarios.

Para un primer análisis se utilizaron las tablas calendar.csv y listings.csv. Se realizó un análisis exploratorio con python para comprender las variables, identificar las variables relevantes para este primer analisis y realizar las transformaciones de datos para obtener un archivo csv que luego se utlizará para construir el tablero en powerBI.

### Tablero PowerBI 

En la primera página del tablero puede realizarse un análisis dinámico por barrio de las cantidades y ubicación de hospedajes, tipo de hospedajes, precios y variación de precios de acuerdo a diferentes características de los hospedajes (cantidad de huéspedes, tipo, etc)

![página1](airbnb_1.png)


airbnb_1.png



En la segunda página del tablero se muestran valores de facturación (tomando las reservas del periodo estudiado), teniendo en cuenta barrios, ocupación, tipo de propiedad etc.

![página2](airbnb2.png)


### Preguntas 

* ¿Qué podemos describir con los datasets acerca del negocio de airbnb?

Con los dataset provistos se puede describir como es el negocio de hospedajes en Buenos Aires.

Se puede determinar por barrio:
- Cantidad de hospedajes y proporción que representan.
- Tipos de hospedajes predominantes
- Precio promedio
- Cantidad huespedes promedio
- Puntuación promedio

Por otro lado con los datos de ocupación y precios se pueden identificar las caracteristicas que presentan los hospedajes que presentaron mayor facturación.

Se puede definir por barrio, tipo de propiedad, cantidad de huespedes:
- Ocupación
- Facturación
  

* ¿Cuál es la mejor forma de invertir en AirBnb?. Si presentamos nuestras conclusiones a un grupo inversor: ¿Qué propuestas le haríamos?
  
  Palermo es el barrio que presenta la mayor ocupación y facturación. Aunque no posee los precios mas altos, es el que barrio con mas ocupación.
  Tambien es el barrio que tiene mas alojamientos, por lo tanto es importante analizar un indicador que determine si el mercado se encuentra saturado.
  Para ellos se calculó la proporción de hospedajes con ocupacion mayor a 6 meses para todos los barrios, y Palermo no presento valores inferiores, por lo tanto el mercado no estaría saturado. 
   Las propiedades más rentadas fueron departamentos con capacidad de entre 2 y 3 personas.
  De acuerdo a este analisis, recomendaria invertir en un departamento en la zona de Palermo, para dos o 3 personas. Como segunda opción, recomendaria invertir en el barrio Recoleta que es el segundo barrio con mas 
  ocupación y facturación.

  Se puede acceder al tablero en el siguiente link:

  [Enlace al tablero](https://app.powerbi.com/view?r=eyJrIjoiY2ZlMjI1M2QtNDE1Zi00MGFiLTg5ZTktMzQyYzdlOTg3M2QxIiwidCI6IjM0ODg3YWYzLTI0NzUtNDE5MS1iOTMwLTAzMWZhMTNkM2FjMSIsImMiOjR9&pageName=ReportSection68b41557572c939c440d)

  



