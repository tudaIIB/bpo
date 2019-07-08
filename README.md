# The Ontology for Managing Geometry (OMG)

The Building Product Ontology defines concepts to describe (building) products in a schematic way. It provides methods to describe assembly structures and component interconnections, and attach properties to any component without restricting their types, as is often the case in template-driven product descriptions. To allow the description of complex properties, it also contains terms for unordered, two-dimensional lists.

## HTML documentation
* Namespace (base-URI): http://www.w3id.org/bpo#
* Suggested prefix: bpo

## Introduction to BPO 
The BPO's scope is on the schematic description of product only, not including geometry or material compositions. Therefore, it can be used to describe theoretical product components without geometric representations as well as those with geometric representations, without restrictions. To exploit all benefits from the Semantic Web, especially during online searches, the BPO is closely aligned to well-known upper-level ontologies, as schema.org and SEAS.

For classification purposes, it uses the buildingSMART Data Dictionary (bSDD) by referencing to the terms' bSDD GUID. If geometric descriptions are desired for components, the authors suggest to use the Ontology for Managing Geometry (OMG) resp. the File Ontology for Geometry formats (FOG) to connect the descriptions to any desired geometry description.

## Combining BPO with other ontologies
As an example, the combination of BPO with an (RDF-based) geometry description and a (non-RDF) taxonomy is demonstrated in this section. Before going into detail, it should be understood that the BPO is not complete but aims to serve as a small ontology that can be re-used in various use cases and scenarios. Thus, in accordance with the best practices for publishing Linked Data, instead of large ontologies that are trimmed towards one specific use cases, smaller ontologies should be combined, which is the idea behind the BPO as well. Recommendations for combining the BPO with other ontologies are to create meaningful links between ontologies for other domains, or creating more specific subclasses and subproperties from the generic terms and concepts of BPO.

## SPARQL-visualizer demo
An [online sparql-visualizer demo](https://madsholten.github.io/sparql-visualizer/?file=https:%2F%2Fwww.dropbox.com%2Fs%2F33ah5crs4a0a25c%2Fbpo-demo.json) is available, containing sample Abox triples and example queries. 

## Authors and contributors
Authors:
[Anna Wagner](https://www.researchgate.net/profile/Anna_Wagner13) - [iib, TU Darmstadt](https://www.iib.tu-darmstadt.de/willkommen/index.en.jsp)
[Laura Kristina Möller](https://www.iib.tu-darmstadt.de/mitarbeiter_iib/ehemalige_iib/moeller.en.jsp) - [iib, TU Darmstadt](https://www.iib.tu-darmstadt.de/willkommen/index.en.jsp)
[Christian Leifgen](https://christian.leifgen.eu/) - [iib, TU Darmstadt](https://www.iib.tu-darmstadt.de/willkommen/index.en.jsp)
[Christian Eller](https://www.iib.tu-darmstadt.de/mitarbeiter_iib/eller.en.jsp) - [iib, TU Darmstadt](https://www.iib.tu-darmstadt.de/willkommen/index.en.jsp)

Contributors:
* [Johannes Eisenlohr](https://www.researchgate.net/profile/Johannes_Eisenlohr) - [Fraunhofer ISE](https://www.ise.fraunhofer.de/)
* [Tim Rist](https://www.researchgate.net/profile/Tim_Rist) - [Fraunhofer ISE](https://www.ise.fraunhofer.de/)
* [Gesa Benndorf](https://www.ise.fraunhofer.de/en/about-us/staff-profiles/benndorf-gesa.html) - [Fraunhofer ISE](https://www.ise.fraunhofer.de/)
* Wendelin Sprenger - Ed. Züblin AG
* [Christoph Maurer](https://www.linkedin.com/in/christophmaurercleanenergy) - [Fraunhofer ISE](https://www.ise.fraunhofer.de/)
* Tillmann E. Kuhn - [Fraunhofer ISE](https://www.ise.fraunhofer.de/)

## References
Please cite the following paper when using BPO:
* Wagner, A., & Rüppel, U. (2019). BPO: The Building Product Ontology for Assembled Products. In Proceedings of the 7th Linked Data in Architecture and Construction workshop (LDAC 2019) (Vol. 7, p. 12), CEUR: http://ceur-ws.org/Vol-2389/08paper.pdf.
* Wagner, A., Möller, L. K., Leifgen, C., & Rüppel, U. (2018). SolConPro: Describing multi-functional building products using semantic web technologies. In J. Karlshøj & R. J. Scherer (Eds.), EWork and eBusiness in architecture, engineering and construction: proceedings of the 12th European Conference on Product and Process Modelling (ECPPM 2018) (pp. 447–455). CRC Press.
