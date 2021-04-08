# Mapa Descriptivo Ruido Valencia RDF
![Vocabulario Estaciones Medida](https://user-images.githubusercontent.com/43373725/113989153-73a60d80-9850-11eb-899d-afb1d4541bca.png)


# FAQ Ruido Valencia RDF

### ¿Qué contiene cada observación?
Cada observación contiene información acerca de la estación de medida que la tomó (sosa:madeBySensor), la fecha en la que fue tomada (sosa:resultTime), el intervalo de referencia en el que fue tomada (tipoIntervaloReferencia) así como el tipo de medición que es (tipoMedicion) y el valor numérico de la misma (hasSimpleResult).

### ¿A qué hace referencia la URI de Observación?
La URI que identifica cada observación se compone de un hash generado a través de un cifrado md5 entre los valores del nombre de la estación que tomó la observación y la fecha de esta, todo ello sumado a una extensión que indica el tipo de medición de la observación (p.e "-LAEQ-D").

### ¿Qué ocurre si no tengo la hora exacta de la observación?
La hora exacta de la observación no es imprescindible, ya que cada observación contiene información acerca del intervalo en el que fue tomada:
- T: indica que el registro diario corresponde al periodo que abarca las 24 horas del día
- D: indica que el registro diario corresponde al periodo diurno (07:00h-19:00h)
- E: indica que el registro diario corresponde al periodo vespertino (19:00h-23:00h)
- N: indica que el registro diario corresponde al periodo nocturno (23:00h-07:00h)

### ¿Qué significan las medidas LAEQ, LAEQ-D, LAEQ-E, LAEQ-N y LAEQ-T?
A continuación se expone una pequeña leyenda aclarativa para los valores de las observaciones:
- LAEQ: nivel de presión acústica ponderada A continuo equivalente del periodo de medida (expresado en decibelios con ponderación A).
- LAEQ-#: indicador sonoro asociado a un intervalo o periodo del día.

### ¿Dónde puedo encontrar información más detallada acerca de las estaciones de medida que realizan las observaciones?
Todos los datos generados relativos a las estaciones de medida situadas en la ciudad de Madrid se encuentran en /data/rdf/ContaminacionAcustica/Valencia/EstacionesMedida/estacionMedidaValencia.nt
