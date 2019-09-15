### Global Agricultural Concept Space (GACS) as a Backbone for Interoperability

Tom Baker <br>
Johannes Keizer <br>
2018-03-05

The acronym GACS, which currently stands for Global Agricultural Concept Scheme, can be redefined to mean Global Agricultural Concept Space.  

#### GACS as a Concept Space

By analogy to "RDF namespace" (a set of RDF resources identified with common base URI) a "concept space" is a namespace of SKOS concepts with a common base URI.

The current GACS Beta is called "Global Agricultural Concept Scheme".  Its concepts are identified by URIs starting with http://id.agrisemantics.org/gacs/ and are part of the SKOS concept scheme GACS Core, identified by the URI http://id.agrisemantics.org/gacs-core.

Redefining the acronym GACS to refer to a concept space allows the current GACS Beta, aka GACS Core, to be positioned as just one of potentially many and possibly overlapping concept schemes defined within a broader GACS concept space.

#### GACS as a Backbone for Interoperability

GACS concepts and concept schemes can serve as building blocks, freely available to any interested organization or user, for the construction new concept schemes, lists, classifications, or ontologies outside of GACS.

The GACS concept space is defined with light semantics and in accordance with the SKOS data model, which supports generic interoperability by deliberately avoiding language constructs that might ontologically "overcommit" to an overly specific or precise interpretation of the world.  When pragmatically mapped to or from other, more precisely defined ontologies, GACS can serve as a backbone for binding together clusters of concepts of approximately equivalent meaning.  GACS concepts can be used as building blocks for constructing more precise ontologies, outside of GACS, through customizing the concepts with additional semantic constraints.

The relationship of a GACS concept scheme to concept schemes, lists, classifications, or ontologies based on that concept scheme is analogous to the relationship of an RDF vocabulary to application profiles which use that vocabulary, together with other RDF vocabularies and with customized constraints, to meet the requirements of specific applications.  

#### Governance of GACS concept schemes

The existing GACS Core is but the first of many potential concept schemes to be defined and maintained within the GACS concept space.  GACS Core itself will be maintained as a set of high-level, generic, frequently-used concepts, with high guarantees of quality and semantic stability; its editorial board will involve, at a minimum, the three organizations that collaborated in its creation (FAO, NAL, and CABI), and will periodically verify the continued validity of mappings to AGROVOC, NAL Thesaurus, and CAB Thesaurus.  Other concept schemes, potentially of more specific scope, may be created within GACS by other stakeholders and curated by their own editorial boards.  Communication and cooperation among editorial boards may be facilitated by a lead editor or editorial board for GACS as a whole.

Editorial Boards may need to meet defined criteria of scope, starting with "agriculture and nutrition" and "common applicability".  Editorial Boards will strive to re-use concepts that already exist in GACS, map narrower concepts to broader concepts in GACS Core, and propose salient concepts of a cross-domain nature for inclusion in the Core.  Analytics and machine learning may be used to facilitate the continual evolution of GACS in response to actual usage patterns.  The work of all GACS editorial boards will be supported by an editorial environment with robust versioning and archival preservation.

#### GACS Policies

GACS guarantees the persistence of all GACS URIs (of "stable" status) in perpetuity.  Editorial boards will also strive to ensure the orderly evolution of concept semantics, though as editorial boards disband, their members move on, or as concepts fall under the purview of new editorial boards, GACS will not be able to guarantee their semantic stability over the long term.  Concepts found to be ambiguous or out of date with respect to current knowledge may eventually be deprecated (though never deleted).  GACS concepts and concept schemes will all carry metadata on their provenance and maintenance status.  Information about the status and current activities of their editorial boards will be transparent to users.

GACS aspires to serve as a springboard for the devolution of maintenance responsibility for specific concept types, such as species or chemicals, to external authorities.  Because of the URI persistence principle, GACS URIs will never be abandoned, but some may become maintained "passively", in response to changes in external namespaces.  GACS is seeking funds to deploy and test methods to support distributed editorial processes and a demand-driven evolution of the GACS concept space.

#### GACS in the Agrisemantics framework

GACS is part of the Agrisemantics framework, which delivers semantic services for agricultural research and innovation and to improve the efficiency of food systems generally. The Agrisemantics framework contributes to the European Open Science Cloud but is global in scope.  GACS is currently one of the three pillars of Agrisemantics along with the Agrisemantics Map of Standards, which tracks relevant vocabularies and metadata schemes, and the Agrisemantics Ontology Server, or Agroportal, which provides one-stop access to published, specialized Knowledge Organization Systems. As the third pillar, GACS provides a common space for publishing reusable concepts.
