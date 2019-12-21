# Mouses: Modular Ontology for Unified Statistical Ecology

 
I currently am developing, as a personal project, an ontology for classifying statistical results of ecological studies.
Ontologies are developed in the computing and biomedial domains, but the subject in still young in the ecology field.
My project aims to provide a toolkit, for ecologists, for classifying their results (field and lab data, statistical analyses).
This new ontology will be tailored to the needs of the field of ecology and will rely heavily on existing ontologies, some developed for other domains.
 
 
# Goals

    Provide a toolkit for classifying ecology results and studies
    Facilitate comparison between studies
    Facilitate queries on existing studies
    Make meta-studies easier
    Facilitate input preparation for future Machine Learning/Artificial Intelligence studies.

 
# Properties

This new ontology should have these desirable properties (non-exhaustive list):

    Relies mostly on imported concepts from existing, established ontologies.
    Interoperates well with these existing ontologies.
    Eliminates or minimizes redundancy of concepts imported from other ontologies.
    Uses BFO, the Basic Formal Ontology, for consistency with many existing scientific ontologies.
    Includes most common concepts used in ecology and in ecological studies and results.
    Statistical methods are hierarchically organized and have properties. This enables comparison between statistical methods.
    When possible relations between statistical methods/results are defined. For example, can we define the "total variance" of two statistical results? 
    Environments, species are also imported or accessible from the ontology.
    Ideally, when the ontology is complete and a good number of ecological studies are defined using the ontology, queries such as the following could be answered by a reasoner: "mean population of diptera in arid climate, years between 1990 and 2005, with number and name of studies, and combined error measure"

Some of these goals may be mutually exclusive so sometimes it will be a matter of balance. If a community develops around this project, feedback will be very valuable to achieve balance between competing desirable properties.

 
# Imported ontologies

STATO (currently in full) https://bioportal.bioontology.org/ontologies/STATO

MAMO (excluding domain specific classes) https://sourceforge.net/projects/mamo-ontology/

OBOE (currently in full) https://github.com/NCEAS/oboe/
 
# Considered ontologies for future import, compliance or interaction

BFO https://github.com/BFO-ontology/BFO

NCBITaxon http://www.obofoundry.org/ontology/ncbitaxon.html

Other ontologies to consider: Ontologies about GIS, containing concepts such as point, coordinates, area, area shape, area size, fragmentation, width, neighboring, distance, etc.
 
# Ontologies of interest, not imported at the moment

ENVO https://bioportal.bioontology.org/ontologies/ENVO

BCO https://bioportal.bioontology.org/ontologies/BCO

PCO https://bioportal.bioontology.org/ontologies/PCO

Agronomy Ontology https://github.com/AgriculturalSemantics/agro

ecocore https://github.com/EcologicalSemantics/ecocore

SWEET https://github.com/ESIPFed/sweet

# Other ontologies

OBCS https://github.com/obcs/obcs

EDAM http://edamontology.org/page

GEOSPECIES https://bioportal.bioontology.org/ontologies/GEOSPECIES
 
 
# Plan

Version 0.1:
-Organize imported concepts of STATO, MAMO and OBOE ontologies within the new ontology, while considering compatibility with BFO ontology.
-Work out licencing and citation mechanisms for both imported and new ontology
-Publish version 0.1 of MOUSE ontology on GitHub

Version 0.2:
-Import needed concepts of ENVO, BCO, PCO, Agronomy Ontology, ecocore, SWEET ontologies, and GIS concepts ontology.

Version 0.3:
-Import/interface with NCBITaxon ontology, or the NCBI Taxon database.

Version 0.4:
-Create missing concepts for our domain. Test basic queries.

Version 0.5:
-Work on the relationships between statistical results.

If you have insights on the subject, know of relevant or similar ontologies, work on a similar project, or wish to share ideas, please contact me :)

# Licences

CC 4.0 BY  https://creativecommons.org/licenses/by/4.0/ 5Creative Commons with attribution)

This ontology imports other ontlogies that require attribution:

--------------------
BFO: code: new BSD  https://opensource.org/licenses/BSD-3-Clause   content: CC 4.0 BY  https://creativecommons.org/licenses/by/4.0/
https://basic-formal-ontology.org/

The theory behind BFO was developed first by Barry Smith and Pierre Grenon and presented in a series of publications.

Since then important contributions to BFO have been made by many people, including:

Mathias Brochhausen
Werner Ceusters
Melanie Courtot
Randall Dipert
Janna Hastings
Chris Mungall
Darren Natale
Fabian Neuhaus
James A. Overton
Bjoern Peters
Ron Rudnicki
Alan Ruttenberg
Stefan Schulz
Selja Seppälä
Holger Stenzhorn
Jie Zheng

---------
STATO: CC 3.0 BY https://creativecommons.org/licenses/by/3.0/
http://stato-ontology.org/

Creators:
Orlaith Burke
Philippe Rocca-Serra (http://orcid.org/0000-0001-9853-5668)
Alejandra Gonzalez-Beltran (http://orcid.org/0000-0003-3499-8262)
Susanna-Assunta Sansone

Contributors:
Chris Mungall (http://orcid.org/0000-0002-6601-2165)
Camille Maumet (http://orcid.org/0000-0002-6290-553X)
Thomas Nichols (http://orcid.org/0000-0002-4516-5103)
Hanna Cwiek (https://orcid.org/0000-0001-9113-567X)
Nolan Nichols (http://orcid.org/0000-0003-1099-3328)

-----------------------
MAMO: artistic license 2.0 https://www.perlfoundation.org/artistic-license-20.html
https://sourceforge.net/p/mamo-ontology/_members/

-----------------------
OBOE: CC BY https://creativecommons.org/licenses/by/3.0/
http://agroportal.lirmm.fr/ontologies/OBOE

Please cite OBOE Ontology as:

Mark Schildhauer, Matthew B. Jones, Shawn Bowers, Joshua Madin, Sergeui Krivov, Deana Pennington, Ferdinando Villa, Benjamin Leinfelder, Christopher Jones, and Margaret O&apos;Brien. 2016. OBOE: the Extensible Observation Ontology, version 1.2. KNB Data Repository. doi:10.5063/F1125R0F

This software was developed with support of multiple projects at the National Center for Ecological Analysis and Synthesis (NCEAS), including grants from the National Science Foundation: SEEK (0225676) Semtools (0743429), SONet (0753144), and DataONE (1430508).

The original publication describing the OBOE concept is:

Madin, J., S. Bowers, M. Schildhauer, S. Krivov, D. Pennington, and F. Villa. 2007. An ontology for describing and synthesizing ecological observation data. Ecological Informatics 2:279–296. doi:10.1016/j.ecoinf.2007.05.004

