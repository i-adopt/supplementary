# NERC Vocabulary Server implementation

The I-ADOPT framework is being implemented on the [NERC Vocabulary Server](https://www.bodc.ac.uk/resources/products/web_services/vocab/) in order to align two major earth sciences parameter labelling schemes: the Climate and Forecast (CF) Standard Names and the British Oceanographic Data Centre Parameter Usage Vocabulary (BODC PUV). 
Both are well governed operational vocabularies that are used to label data streams and data fields in the atmosphere and climate modeling community, and in the oceanographic community respectively. 
The CF Standard Names are used in the CF-netCDF data format while the BODC PUV is used in the SeaDataNet, EMODnet, and OBIS data formats and systems.
The two schemes have experienced growth in recent years and have some overlap in their thematic coverage. 
The following steps are being taken:
* Identify shared concepts and design patterns based on unit dimensions and variable types;
* Align CF Standard Names and BODC PUV concepts to a set of common terminologies using the I-ADOPT ontology properties;
* Implement properties and mappings on the NVS;
* Publish outcome as an I-ADOPT profile on the NVS;
* Develop mapping rules as sparql queries to enable dynamic “smart” mappings between these growing 2 resources.

This uptake story relates to the following I-ADOPT use cases:

* [Semantic alignment](https://github.com/i-adopt/requirements/issues/4)
* [Data integration](https://github.com/i-adopt/requirements/issues/15)

*Timescale*: work on this uptake story will have a first demonstrable output in February 2022.
