# Demonstration-Environments-Ontology-Version1.0

Demonstration Environments (DE) refer to all facilities and environments for technology development including testing, prototyping and confronting technology with different usage situations (e.g. testbed, pilot plant, living lab, sandbox, etc.). This DE Ontology is proposed to define, conceptualise and characterise DEs from various perspectives including their application domains, characteristics, network components and measurable values like lifespan. It enables different types of DEs to be situated on the same level for comparison and benchmarking. It also provides a standardisation of terminologies related to DEs which solves heterogeneity in the description of various names of DEs across domains, and provides a common understanding of DEs through a systematic framework which is the ontology.

This ontology can be visualised in WebVOWL via https://service.tib.eu/webvowl/#opts=doc=4;#iri=http://purl.org/deo


## Project Introduction
This thesis aims to develop an ontology for Demonstration Environments by using a semi-automatic approach: Word Embeddings. The ontology development process is available at https://github.com/bbkk0502/Word2vec-model-for-ontology-construction. Besides, we have documented the entire research data in OSF, it can be accessed via https://osf.io/y9nem/.

## System Requirement

Protégé 5.5.0 

HermiT Reasoner 1.4.3.456

## Use Case
An use case of quering DEs that support tasks of assessment and diagnosis is defined in this DE ontology. This is enabled by SPARQL Query. Malware analysis is an defined individual for Class 'Assessment_and_diagnosis', a set of DE individuals including 'cyber_security_testbed' is defined to support malware analysis. Figure below shows how this information can be queried in SPARQL Query Tab in Protégé.

![alt text](https://github.com/bbkk0502/Demonstration-Environments-Ontology-Version1.0/blob/master/use%20case.png)

This ontology can be further instantiated to support more query through SPARQL.

#Contribute to this Ontology
If you would like to suggest any changes to this ontology, please submit a pull request via the test branch. 

