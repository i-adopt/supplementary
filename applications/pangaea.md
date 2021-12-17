# Pangaea

One of the most important elements of the PANGAEA data structure are the descriptions of measured values and observations, the so-called parameters.
The data infrastructure curates hundred thousands observation types with their parameter information.
PANGAEA parameters represent from simple to complex concepts and are usually formulated as tuples consisting of the parameter name and a measurement unit.
A parameter name can consist of one or more observed properties and their measurement contexts, such as an observation object, a scientific method or a measurement device.
Examples of parameters are 'Methane, daily formation rate per unit sediment mass' or 'Carbon dioxide, partial pressure'.

To improve the findability of data, PANGAEA has made considerable efforts in recent years to better structure these parameter names and to semantically annotate them using existing ontologies.
As a result, large parts of PANGAEA's metadata are linked to semantic artifacts.
This should enable semi-automated mapping with other vocabularies such as SeaDataNet parameters or CF variables in the future.
A prerequisite for this, however, is a uniform data structure.
To this end, this uptake story will investigate the extent to which the I-ADOPT schema can be integrated into existing metadata formats such as [schema.org/Dataset](https://schema.org/Dataset) or [DCAT-2](https://www.w3.org/TR/vocab-dcat-2/).
The overall goal is an exemplary implementation of I-ADOPT compliant parameter descriptions for PANGAEA with the help of these standards.

*Timescale*: work on this uptake story will have a first demonstrable output in April/May 2022.
