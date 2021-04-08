# FAQ Estaciones Medida Valencia RDF

### ¿Qué información contiene cada estación de medida?
Cada estación de medida contiene información acerca de la dirección postal de la misma (schema:address) y el nombre de esta (schema:name).

### ¿Cómo puedo obtener información más detallada acerca de la dirección postal donde se encuentra la estación?
El fichero RDF contiene además información sobre las direcciones donde se encuentran las estaciones de medida como el código postal, el nombre de la calle, la ciudad donde se encuentra y la comunidad autónoma donde se sitúa la ciudad 

### ¿Por qué no se incluye información acerca de las coordenadas geográficas?
Las coordenadas geográficas se incluirán en los datos generados con RDF una vez vayamos actualizando la ontología de Contaminación Acústica.

### ¿Dónde puedo encontrar información más detallada acerca de las observaciones que realizan las estaciones de medida?
Todos los datos generados relativos a las observaciones realizadas por las estaciones de medida situadas en la ciudad de Valencia se encuentran en /data/rdf/ContaminacionAcustica/Valencia/RuidoValencia/

### ¿Por qué hay tan poco información de las estaciones de medida en comparación con otras ciudades?
Hay que tener en cuenta que en el portal de datos abiertos del ayuntamiento de Valencia no se incluye ningún dataset que haga referencia a todas las estaciones instaladas, si no que se incluyen datasets por separado que hacen referencia a las observaciones de cada estación.
Para homogeneizar el proceso, se decidió crear un dataset nuevo que conteniese la información básica acerca de estas estaciones.
