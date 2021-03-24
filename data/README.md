# Data Directory

## Mappings Directory
This directory includes the RML mappings to generate the RDF data by using the datasets contained in the *preprocessed* directory and the *contaminacion-acústica* ontology.

The data is generated with two different tools (RMLMapper and SFM-RDFizer (https://github.com/SDM-TIB/SDM-RDFizer):
- RMLMapper: `java -jar rmlmapper.jar -m estacionesMedidaRML.rml -o estacionMedida.nt -d`
- SFM-RDFizer (using the "RDFizerConfig file contained in the directory): `python3 rdfizer/run_rdfizer.py RDFizerConfig`

## Original Directory
This directory includes the original datasets in CSV format used to generate the RDF data.

## Preprocessed Directory
This directory includes the transformed CSVs made by Google OpenRefine in order to prepare the data to be generated.

## RDF Directory
This directory includes RDF data generated.
