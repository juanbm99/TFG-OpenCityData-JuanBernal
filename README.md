# TFG-OpenCityData-JuanBernal
- Autor: Juan Bernal Mencía

Repositorio correspondiente al material generado para la elaboración del Trabajo de Fin de Grado relacionado con datos abiertos sobre ciudades.

- URL Memoria: https://drive.google.com/drive/folders/1DsCRXDE9BCcmsluESwcNHajbfYGV20mn?usp=sharing

## Tareas Realizadas

- Lectura del documento de creación de ontologías https://link.springer.com/article/10.1007%2Fs12652-019-01561-2
- Acceso al portal vocab.ciudadesabiertas.es y visualización del Webinar de Convenios
- Lectura del ejemplo de Deuda Pública
- Datos de Contaminación Acústica:
  - Zaragoza: Mapa de Ruido (Formato WMS)
  - Santiago Compostela: No tiene
  - A Coruña: No tiene
  - Madrid: 
    - Contaminación acústica. Datos diarios (CSV): https://datos.madrid.es/portal/site/egob/menuitem.c05c1f754a33a9fbe4b2e4b284f1a5a0/?  vgnextoid=b8c427a272e4e410VgnVCM2000000c205a0aRCRD&vgnextchannel=374512b9ace9f310VgnVCM100000171f5a0aRCRD&vgnextfmt=default
    - Contaminación acústica. Datos históricos diarios (CSV): https://datos.madrid.es/portal/site/egob/menuitem.c05c1f754a33a9fbe4b2e4b284f1a5a0/?vgnextoid=c035669177294610VgnVCM2000001f4a900aRCRD&vgnextchannel=374512b9ace9f310VgnVCM100000171f5a0aRCRD&vgnextfmt=default
    - Contaminación acústica. Datos históricos mensuales (CSV): https://datos.madrid.es/portal/site/egob/menuitem.c05c1f754a33a9fbe4b2e4b284f1a5a0/?vgnextoid=2ec892874870b410VgnVCM1000000b205a0aRCRD&vgnextchannel=374512b9ace9f310VgnVCM100000171f5a0aRCRD&vgnextfmt=default
    - Contaminación acústica: Estaciones de medida (CSV): https://datos.madrid.es/portal/site/egob/menuitem.c05c1f754a33a9fbe4b2e4b284f1a5a0/?vgnextoid=b05a79ea1770b410VgnVCM1000000b205a0aRCRD&vgnextchannel=374512b9ace9f310VgnVCM100000171f5a0aRCRD&vgnextfmt=default
    
- Estudio de los CSV y transformación de algunas columnas para mejorar la legibilidad de estos (OpenRefine):
   - Renombrado y Eliminación de Columnas innecesarias (p.e Latitud y Longitud en varios formatos)
   - Susititución de COD_VIA por COD_POSTAL
   - Problema con fechas de alta de Estaciones (Formato Desconocido ?)
- Estudio de la ontología de Contaminación Acústica (https://github.com/juanbm99/medio-ambiente-contaminacion-acustica/tree/master/Ontology) y enlazado de conceptos para    preparación de RML
