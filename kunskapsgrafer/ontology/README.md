# 3CIM ontology - short information

The 3CIM ontology is an extension of OntoCityGML, a CityGML 2.0 ontology developed by the University of Geneva (Chadzynski et al., 2021).

The 3CIM ontology is stored in two (Turtle) files
- 3cim.ttl contains an RDFS/OWL-ontology based on the conceptual model available here: https://github.com/3CIM/3CIM2.0/tree/main/schema. 
The ontology imports and extends concepts from OntoCityGML.
- 3cim--geosparql.ttl	contains an alignment ontology (RDFS/OWL) linking 3CIM/OntoCityGML concepts with OGC GeoSPARQL (https://www.ogc.org/standards/geosparql/) according to what is 
outlined in a paper by the University of Lyon (Diego Vinasco-Alvarez et al. 2024). 
- test3CIM.ttl contains a small example with a single individual (belonging to class veg:SolitaryVegetationObject) to illustrate and test the use of 3CIM including GeoSPARQL 
- catalog-v001.xml is a parameter file for the 3CIM ontology to Protege. Have to be updated depending on your settings.  

The 3CIM ontology was developed by Lars Wikström, Triona, Sweden, in the project "Interoperabilitet – Digital samverkan för den byggda miljön", see https://smartbuilt.se/projekt/informationsinfrastruktur/interoperabilitet-digital-samverkan-for-den-byggda-miljon/

References:
Chadzynski, A., Krdzavac, N., Farazi, F., Lim, M. Q., Li, S., Grisiute, A., Herthogs, P., von Richthofen, A., Cairns, S., & Kraft, M. (2021). Semantic 3D City Database — An enabler for a dynamic geospatial knowledge graph. Energy and AI, 6, 100106. https://doi.org/https://doi.org/10.1016/j.egyai.2021.100106 

Diego Vinasco-Alvarez, John Samuel, Sylvie Servigne, Gilles Gesquiere. 2024. Towards an Automated Transformation of an nD Urban Data Model to a Computational
Ontology Network: From UML to OWL, From CityGML 3.0 to “CityOWL”. https://www.researchgate.net/publication/381091948_Towards_an_Automated_Transformation_of_an_nD_Urban_Data_Model_to_a_Computational_Ontology_Network_From_UML_to_OWL_From_CityGML_30_to_CityOWL 
