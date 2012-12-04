Phenoscape RDF Knowledgebase
============================

This repository contains the complete Phenoscape Knowledgebase in RDF form. It is divided into two main folders, "kb", and "closure".

kb
--

This is the main Knowledgebase content. It contains downloaded ontologies, Phenoscape-annotated evolutionary data (converted from NeXML to OWL), model organism phenotype and gene expression annotations (converted from various download formats to OWL), and other axioms added by the Phenoscape pre-reasoning pipeline. In the Phenoscape KB triplestore, all of these files are loaded into the graph <http://kb.phenoscape.org/>.

closure
-------

This folder holds files containing some "redundant" RDF data. These are triples representing the fully materialized transitive closure of the OWL class hierarchy and certain transitive properties. This graph can be included in SPARQL queries to avoid requiring transitity at query time.
