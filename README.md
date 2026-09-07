# ⛏️ Minecraft Knowledge Graph

Ein semantisches Wissensgraph-Projekt auf Basis von Minecraft: von SPARQL-Abfragen über OWL-Inferenz bis zur SHACL-Validierung[cite: 2, 8].

## 📁 Repository-Struktur

```text
Minecraft-Knowledge-Graph/
├── data/
│   ├── test_minecraft.ttl             # Basis-Graph (Klassen, Eigenschaften, Rezepte)[cite: 2]
│   ├── test_minecraft_inferred.ttl    # Mit HermiT-Reasoner abgeleiteter Graph[cite: 8]
│   ├── minecraft_shapes.ttl           # W3C SHACL-Validierungsregelwerk[cite: 8]
│   └── test_minecraft_invalid.ttl     # Testgraph mit 12 gezielten Violations[cite: 8]
├── notebooks/
│   ├── 01_sparql_basics.sparqlbook    # SPARQL 1.1 Grundlagen & Abfragen[cite: 2]
│   ├── 02_rdfs_owl_reasoning.sparqlbook # RDFS- und OWL-Inferenz[cite: 8]
│   └── 03_shacl_validation.sparqlbook # SHACL-Validierung & Gegenbeweise[cite: 8]
├── images/shacl/                      # Screenshots der Validierungsberichte[cite: 8]
├── .gitignore
└── README.md
```

## 🚀 Ausführung
* **Notizbücher:** In VS Code / Posit Workbench öffnen und die Zellen mit einer SPARQL-Erweiterung nacheinander ausführen (`# [endpoint=test_minecraft.ttl]`)[cite: 2].
* **Reasoning:** Inferenz-Materialisierung via ROBOT CLI und HermiT (`test_minecraft_inferred.ttl`)[cite: 8].
* **Validierung:** Prüfung der Shapes gegen die Datengraphen via SHACL Play![cite: 8].

## Referenzen
* [W3C RDF 1.1 Turtle Specification](https://www.w3.org/TR/turtle/)
* [W3C SPARQL 1.1 Query Language Specification](https://www.w3.org/TR/sparql11-query/)
* [W3C OWL 2 Web Ontology Language Overview](https://www.w3.org/TR/owl2-overview/)
* [W3C Shapes Constraint Language (SHACL) Specification](https://www.w3.org/TR/shacl/)
