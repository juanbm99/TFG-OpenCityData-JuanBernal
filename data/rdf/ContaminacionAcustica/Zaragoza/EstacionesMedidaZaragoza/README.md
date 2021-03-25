# Mapa Descriptivo Estaciones Medida Zaragoza RDF
![Vocabulario Estaciones Medida (1)](https://user-images.githubusercontent.com/43373725/112457611-3758b480-8d5c-11eb-9e00-5047f41204e5.png)

# FAQ Estaciones Medida Zaragoza RDF

### ¿Qué información contiene cada estación de medida?
Cada estación de medida contiene información acerca de la dirección postal de la misma (schema:address) y el nombre de esta (schema:name).

### ¿Cómo puedo obtener información más detallada acerca de la dirección postal donde se encuentra la estación?
El fichero RDF contiene además información sobre las direcciones donde se encuentran las estaciones de medida como el nombre de la calle, la ciudad donde se encuentra y la comunidad autónoma donde se sitúa la ciudad. 

### ¿Por qué no se incluye información acerca de las coordenadas geográficas?
La información acerca de las coordenadas geográficas se encuentra disponible en el CSV de Contaminacion Acustica Zaragoza disponible en /data/preprocessed/ContaminacionAcustica/Zaragoza/EstacionesZaragozaChanged.csv en la columna "gis".
Las coordenadas geográficas se incluirán en los datos generados con RDF una vez vayamos actualizando la ontología de Contaminación Acústica.

### ¿Dónde puedo encontrar información más detallada acerca de las observaciones que realizan las estaciones de medida?
Todos los datos generados relativos a las observaciones realizadas por las estaciones de medida situadas en la ciudad de Zaragoza se encuentran en /data/rdf/ContaminacionAcustica/Zaragoza/Ruido
