# FAQ Ruido Zaragoza 2017 RDF

### ¿Qué contiene cada observación?
Cada observación contiene información acerca de la estación de medida que la tomó (sosa:madeBySensor), la fecha en la que fue tomada (sosa:resultTime), el intervalo de referencia en el que fue tomada (tipoIntervaloReferencia) y el valor numérico de la misma (hasSimpleResult).

### ¿A qué hace referencia la URI de Observación?
La URI que identifica cada observación se compone de un hash generado a través de un cifrado md5 entre los valores del nombre de la estación que tomó la observación, la fecha de esta y el valor que toma, todo ello sumado a una extensión que indica el intervalo del dia en el que fue realizada la observación (p.e "-NOCHE").

### ¿Qué ocurre si no tengo la hora exacta de la observación?
La hora exacta de la observación no es imprescindible, ya que cada observación contiene información acerca del intervalo en el que fue tomada:
- D: indica que el registro diario corresponde al periodo diurno (07:00h-19:00h)
- E: indica que el registro diario corresponde al periodo vespertino (19:00h-23:00h)
- N: indica que el registro diario corresponde al periodo nocturno (23:00h-07:00h)

### ¿Qué significan las medidas DIA, TARDE, NOCHE?
A continuación se expone una pequeña leyenda aclarativa para los valores de las observaciones:
- DIA: medida de la observacion realizada por la estación correspondiente durante el periodo diurno.
- TARDE: medida de la observacion realizada por la estación correspondiente durante el periodo vespertino.
- NOCHE: medida de la observacion realizada por la estación correspondiente durante el periodo nocturno.
- 
### ¿Dónde puedo encontrar información más detallada acerca de las estaciones de medida que realizan las observaciones?
Todos los datos generados relativos a las estaciones de medida situadas en la ciudad de Zaragoza se encuentran en /data/rdf/ContaminacionAcustica/Zaragoza/EstacionesMedida/EstacionMedida.nt
