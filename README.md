> *“An ontology defines the basic terms and relations comprising the vocabulary of a topic area, as well as the rules for combining terms and relations to define extensions to the vocabulary. ” (Neches R, Fikes R, Finin T, Gruber T, Patil R, Senator T, Swartout WR (1991) “Enabling Technology for Knowledge Sharing” AI Magazine. Winter 1991. 36-56.)*

> *“An ontology is a formal, explicit specification of a shared conceptualization. ” (Studer, Benjamins, Fensel. Knowledge Engineering: Principles and Methods. Data and Knowledge Engineering. 25 (1998) 161-197)*

# Unified Cyber Ontology (UCO)

Unified Cyber Ontology (UCO) is a community-developed ontology/model, which is intended to serve as a consistent foundation for standardized information representation across the cyber security domain/ecosystem.

Specific information representations focused on individual cyber security subdomains (cyber investigation, computer/network defense, threat intelligence, malware analysis, vulnerability research, offensive/hack-back operations, etc.) can be be based on UCO and defined as appropriate subsets of UCO constructs.

Through this approach not only are domain-focused representations defined consistently but they also can take advantage of shared APIs and information can flow in an automated fashion across subdomain boundaries.

The purpose of this repository is to provide a foundation for broader community involvement in defining what to represent and how.

### Current Release
The current release of UCO is 0.5.0

UCO 0.5.0 is primarily focused on the removal of the investigation namespace from UCO (that namespace now resides in the CASE ontology) and on the renaming of several classes (Observable subclasses, Facet subclasses) in the observable namespace  and a single property (core:facet) to support improved alignment with the CASE ontology and the forthcoming addition of ObservableObject subclasses.

Future versions of UCO will not only expand and refine the ontology itself but will also provide more complete and formalized documentation.
