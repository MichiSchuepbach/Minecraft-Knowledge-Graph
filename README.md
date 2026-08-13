# RDF & SPARQL 1.1 Tutorial – Minecraft Wissensgraph

**Autor:** Michael Schüpbach

## Inhalt
Dieses Repository zeigt die Modellierung eines RDF-Wissensgraphen und dessen Abfrage mit SPARQL 1.1.

* `test_minecraft.ttl` – RDF-Wissensbasis im Turtle-Format (Klassen, Eigenschaften, Rezepte, Anonymknoten).
* `sparql.ipynb` – Jupyter Notebook mit Theorieblöcken und SPARQL-Abfragen.

## Abgedeckte Themen
* **RDF-Grundlagen:** Tripel-Struktur, IRIs, Literale, Blank Nodes
* **SPARQL-Abfragen:** `SELECT`, `FILTER` (Sprachen, Textsuche), Tripel-Verknüpfungen, `OPTIONAL`, Property Paths (`/`), `ASK`, `CONSTRUCT`

## Ausführung
Repository in VS Code öffnen und die Zellen mit einer SPARQL-Erweiterung nacheinander ausführen (`# [endpoint=test_minecraft.ttl]`).

## Referenzen
* [W3C RDF 1.1 Turtle Specification](https://www.w3.org/TR/turtle/)
* [W3C SPARQL 1.1 Query Language Specification](https://www.w3.org/TR/sparql11-query/)
