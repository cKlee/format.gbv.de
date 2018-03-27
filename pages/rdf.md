---
title: RDF
wikidata: Q54872
---

Das **Resource Description Framework (RDF)** ist ein Graph-basiertes
Datenformat.  Die Grundeinheit von RDF-Daten sind Tripel bestend aus Subjekt,
Prädikat und Objekt.  Das RDF-Format bildet die Grundlage des so genannten
Semantic Web und von Linked (Open) Data. RDF-Daten können in verschiedenen
*Serialisierungen* vorkommen, die sich verlustfrei ineinander umwandeln lassen.

RDF-Formate basieren auf RDF-Ontologien oder werden mit Ontologien
gleichgesetzt. Eine Besonderheit von RDF ist dass sich Daten verschiedener
Ontologien kombinieren lassen.

Die meisten relevanten Ontologien sind bei [Linked Open Vocabularies
(LOV)](rdf/voc) verzeichnet und können unter `/rdf/voc/{prefix}` mit ihrem
jeweiligen Prefix abgerufen werden. Beispiele:

* [schema.org vocabulary](rdf/voc/schema)
* [BIBFRAME Vocabulary](rdf/voc/bf)
* [RDA Classes](rdf/voc/rdac)

<!-- 
- Ontologien bauen aufeinander auf
- Formate hängen auch von Anwendungsprofilen ab
    - application profiles, data shapes, SHACL, ShEx...
    - implizite profile
-->

[Linked Open Vocabularies (LOV)]: http://lov.okfn.org/

Zur Spezifikation von Ontologien und RDF-Daten eignen sich:

<list-formats for="rdf"/>

Die wichtigsten RDF-Serialisierungen sind:

<list-formats model="rdf" />
