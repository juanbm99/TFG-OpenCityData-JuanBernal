# Mapa Descriptivo Estaciones Medida Madrid RDF
![Vocabulario Estaciones Medida](https://user-images.githubusercontent.com/43373725/111786367-01c84d00-88be-11eb-8610-f79bd441217c.png)

# FAQ Estaciones Medida Madrid RDF

### ¿Qué información contiene cada estación de medida?
Cada estación de medida contiene información acerca de la dirección postal de la misma (schema:address), el identificador de esta (dct:identifier), la fecha de alta de la estación (fechaAlta) y el nombre de esta (schema:name).

### ¿Cómo puedo obtener información más detallada acerca de la dirección postal donde se encuentra la estación?
El fichero RDF contiene además información sobre las direcciones donde se encuentran las estaciones de medida como el código postal, el nombre de la calle, la ciudad donde se encuentra y la comunidad autónoma donde se sitúa la ciudad 

### ¿Por qué no se incluye información acerca de las coordenadas geográficas?
La información acerca de las coordenadas geográficas se encuentra disponible en el CSV de Estaciones de Medida disponible en /data/preprocessed/ContaminacionAcustica/Madrid/EstacionesMedida/EstacionesMedidaChanged.csv
Las coordenadas geográficas se incluirán en los datos generados con RDF una vez vayamos actualizando la ontología de Contaminación Acústica.

### ¿Dónde puedo encontrar información más detallada acerca de las observaciones que realizan las estaciones de medida?
Todos los datos generados relativos a las observaciones realizadas por las estaciones de medida situadas en la ciudad de Madrid se encuentran en /data/rdf/ContaminacionAcustica/Madrid/RuidoDiario/

