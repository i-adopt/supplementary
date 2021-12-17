# I-ADOPT as enrichment of the OMOP implementation guide

This implementation guide assists ETLs with the task of loading EHR-like data from the WHO COVID-19 Core CRF into the OMOP CDM.
This implementation guide is powered by the I-ADOPT variable initiative.
In the implementation guide, variables from the CRF are annotated in line with I-ADOPT, and the "deep metadata" these variables come to contain is used to guide the construction of OMOP CONDITION_OCCURRENCEs, PROCEDURE_OCCURRENCEs, DRUG_EXPOSUREs, MEASUREMENTs, OBSERVATIONs and the like.

Coincidentally, the guide with this infusion of deep metadata can be used by a computer program to construct a data catalog following either the DCAT or the schema.org standard.
