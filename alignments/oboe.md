# I-ADOPT to Extensible Observation Ontology

The Extensible Observation Ontology (OBOE) [OBOE-docs] is a formal ontology for describing scientific observations and measurements.
Similarly to [SAREF](saref.md), OBOE has two core classes for defining a variable; the first is an Entity, defined as an object or phenomenon on which measurements are made, and the second is a Characteristic, which is the property being measured.
The OBOE Characteristic maps directly to the I-ADOPT Property, while the Entity maps to the I-ADOPT Entity corresponding to the role of Object of Interest.
OBOE does not include any additional components corresponding to I-ADOPT Matrix or I-ADOPT ContextObject.

![OBOE overview](./gfx/oboe.svg)

| OBOE                | I-ADOPT                              |
|---------------------|--------------------------------------|
| oboe:Entity         | iop:Entity + iop:hasObjectOfInterest |
| oboe:Characteristic | iop:Property                         |
| oboe:hasContext        | iop:Entity + iop:hasContextObject    |

## References

* [OBOE-docs] https://github.com/NCEAS/oboe Accessed 3 November 2021
