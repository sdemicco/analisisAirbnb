# analisisAirbnb

Se desarrolló un tablero en PowerBi que permite entender en negocio de airbnb en la ciudad de Buenos Aires.
Se utilizaron tres datasets con la siguiente informacion:

| calendar.csv: (incluye datos de ocupación, precio, etc.)  
| listings.csv: Detalle de cada operación de Listing (incluye datos descriptivos de la vivienda (ambientes, host, noches mínimas y máximas, cantidad de reviews)
| reviews.csv Datos de review de los usuarios.

Para un primer analisis se utilizaron las tablas calendar.csv y listings.csv. Se realizó un analisis exploratorio con python para comprender las variables exlicativas, identificar las variables relevantes para este primer analisis y realizar las transformaciones de datos para obtener un archivo csv que luego se utlizará para construir el dasbord en powerBI.

### Tablero PowerBI 

En la primera página del tablero puede realizarse un analisis dinamico por Barrio de las cantidades y ubicacion de hospedajes, tipo de hospedajes, precios y variación de precios de acuerdo a diferentes caracteristicas de los hospedajes (cantidad de huéspedes, tipo, etc)

<span>![</span><span>Aquí la descripción de la imagen por si no carga</span><span>]</span><span>(</span><span>https://raw.githubusercontent.com/sdemicco/analisisAirbnb/main/airbnb_1.png</span><span>)</span>


airbnb_1.png



En la segunda página del tablero se muestran valores de facturacion (tomando las reservas del periodo estudiado), teniendo en cuenta barrios, ocupación, tipo de propiedad etc.


### Preguntas 

* ¿Qué podemos describir con los datasets acerca del negocio de airbnb?

Con los dataset provistos se puede describir como es el negocio de hospedajes en Buenos Aires.

Se puede determinar por barrio:
- Cantidad de hospedajes y proporcion que representan.
- Tipos de hospedajes predominantes
- Precio promedio
- Cantidad huespedes promedio
- Puntuación promedio

Por otro lado con los datos de ocupación y precios se pueden identificar las caracteristicas que presentan los hospedajes que presentaron mayor facturación.

Se puede definir por barrio, tipo de propiedad, cantidad de huespedes:
- Ocupación
- Facturación
 Tambien si muestra una metrica que  la proporcion de hospedajes con ocupacion mayor a 6 meses para determinar si la combinacion de caracteristicas
  que maximiza la facturacion no se encuentra saturada.


* ¿Cuál es la mejor forma de invertir en AirBnb?. Si presentamos nuestras conclusiones a un grupo inversor: ¿Qué propuestas le haríamos?
  
  Palermo es el barrio que presenta la mayor ocupación y facturación. Aunque no posee los precios mas altos, es el que barrio con mas ocupación.
  Tambien es el barrio que tiene mas alojamientos, por lo tanto es importante analizar un indicador que determine si el mercado se encuentra saturado.
  Para ellos se calculó la proporción de hospedajes con ocupacion mayor a 6 meses para todos los barrios, y Palermo no presento valores inferiores, por lo tanto el mercado no estaría saturado. 
   Las propiedades más rentadas fueron departamentos con capacidad de entre 2 y 3 personas.
  De acuerdo a este analisis, recomendaria invertir en un departamento en la zona de Palermo, para dos o 3 personas. Como segunda opción, recomendaria invertir en el barrio Recoleta que es el segundo con mas ocupación y facturación. 

  



