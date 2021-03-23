# Mapa Descriptivo Ruido Diario RDF
![Vocabulario Observacion](https://user-images.githubusercontent.com/43373725/111815771-57abed80-88dc-11eb-984b-33489159dd48.png)

# FAQ Ruido Diario RDF

### ¿Qué contiene cada observación?
Cada observación contiene información acerca de la estación de medida que la tomó (sosa:madeBySensor), la fecha en la que fue tomada (sosa:resultTime), el intervalo de referencia en el que fue tomada (tipoIntervaloReferencia) así como el tipo de medición que es (tipoMedicion) y el valor numérico de la misma (hasSimpleResult).

### ¿A qué hace referencia la URI de Observación?
La URI que identifica cada observación se compone de un hash generado a través de un cifrado md5 entre los valores del nombre de la estación que tomó la observación, la fecha de esta y el intervalo de referencia en el que fue tomada, todo ello sumado a una extensión que indica el tipo de medición de la observación (p.e "-LAS90").

### ¿Qué ocurre si no tengo la hora exacta de la observación?
La hora exacta de la observación no es imprescindible, ya que cada observación contiene información acerca del intervalo en el que fue tomada:
- T: indica que el registro diario corresponde al periodo que abarca las 24 horas del día
- D: indica que el registro diario corresponde al periodo diurno (07:00h-19:00h)
- E: indica que el registro diario corresponde al periodo vespertino (19:00h-23:00h)
- N: indica que el registro diario corresponde al periodo nocturno (23:00h-07:00h)

### ¿Qué significan las medidas LAEQ, LAS01, LAS10, LAS50, LAS90 y LAS99?
A continuación se expone una pequeña leyenda aclarativa para los valores de las observaciones:
- LAEQ: nivel de presión acústica ponderada A continuo equivalente del periodo de medida (expresado en decibelios con ponderación A).
- LAS_N: percentil enésimo (p.e Nivel de presión acústica con ponderación frecuencial A y ponderación temporal slow por encima del cual se encuentra el n % de los niveles registrados durante el periodo correspondiente).

### ¿Dónde puedo encontrar información más detallada acerca de las estaciones de medida que realizan las observaciones?
Todos los datos generados relativos a las estaciones de medida situadas en la ciudad de Madrid se encuentran en /data/rdf/EstacionesMedida/estacionMedida.nt

