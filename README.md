# O3PO: A domain ontology for offshore petroleum production plants

The **Offshore Petroleum Production Ontology (O3PO)** is a bilingual, BFO‑aligned domain ontology that formally represents knowledge about offshore oil and gas production systems.  
It was introduced in the paper:

> **Santos, N. O., Rodrigues, F. H., Schmidt, D., Romeu, R. K., Nascimento, G., & Abel, M. (2024).**  
> *O3PO: A domain ontology for offshore petroleum production plants.*  
> **Expert Systems with Applications**, 238 (Part F), 122104.  
> <https://doi.org/10.1016/j.eswa.2023.122104>

O3PO supports semantic data integration, interoperability, and reasoning over industrial asset information.  
It provides a structured vocabulary for modeling production systems, equipment, processes, and information artifacts found in offshore petroleum facilities.

---

## 🧭 Overview

- **Ontology IRI:** <https://www.inf.ufrgs.br/ontologies/o3po>  
- **Current version IRI:** <https://www.inf.ufrgs.br/ontologies/o3po/2.0>  
- **License:** [MIT License](LICENSE)  
- **Code repository:** [BDI-UFRGS/O3POntology](https://github.com/BDI-UFRGS/O3POntology)  
- **Primary language tags:** `@en`, `@pt-BR`

---

## 📚 Imported Ontologies

O3PO directly imports the following foundational ontologies:

| Ontology | Version / IRI | Purpose |
|-----------|----------------|----------|
| **BFO** – Basic Formal Ontology | <http://purl.obolibrary.org/obo/bfo/2020/bfo.owl> | Upper-level ontology providing core categories (Object, Process, Quality, etc.) |
| **IAO** – Information Artifact Ontology | <http://purl.obolibrary.org/obo/iao/2022-11-07/iao.owl> | Metadata and information content entities |
| **IOF-Core** | <https://spec.industrialontologies.org/ontology/202401/core/Core/> | Common industrial foundation for Artifact, Process, and Function |
| **GeoCore** | <https://www.inf.ufrgs.br/bdi/ontologies/geocore/releases/2024-04-06/geocore.owl> | Spatial and geoscientific extensions |

---

## 🧩 Structure

This repository maintains only the **current canonical ontology version** for public use:

- `o3po.ttl` – canonical OWL 2 DL version (bilingual, normalized IRIs)

All entities use the base namespace:  

```
https://www.inf.ufrgs.br/ontologies/o3po#
```

---

## 🧠 Reasoning Compatibility

O3PO conforms to the **OWL 2 DL** profile and is compatible with reasoners such as **HermiT**, **Pellet**, and **FaCT++**.  
Datatype usage (`xsd:dateTime`, `xsd:decimal`, `xsd:boolean`, etc.) follows OWL 2 DL constraints.

---

## 🌐 Citation

If you use O3PO in academic or industrial work, please cite:

> **Santos, N. O., Rodrigues, F. H., Schmidt, D., Romeu, R. K., Nascimento, G., & Abel, M. (2024).**  
> *O3PO: A domain ontology for offshore petroleum production plants.*  
> *Expert Systems with Applications*, 238 (Part F), 122104.  
> <https://doi.org/10.1016/j.eswa.2023.122104>

---

## 📬 Contact

For questions, collaborations, or ontology contributions:

- **Maintainer:** [Nicolau Oyhenard dos Santos](mailto:nicolau.santos@inf.ufrgs.br)  
- **Research group:** [BDI‑UFRGS – Ontologies and Knowledge Graphs Lab](https://www.inf.ufrgs.br/bdi/)  
- **Institution:** Federal University of Rio Grande do Sul (UFRGS)

---

## 🇧🇷 Sobre (Português‑BR)

**O3PO: Ontologia de domínio para plantas de produção de petróleo offshore** é uma ontologia bilíngue, alinhada à **Basic Formal Ontology (BFO)**, desenvolvida para representar o conhecimento sobre sistemas, equipamentos e processos de produção de petróleo e gás offshore.  

O trabalho foi apresentado no artigo:

> **Santos, N. O.; Rodrigues, F. H.; Schmidt, D.; Romeu, R. K.; Nascimento, G.; Abel, M. (2024).**  
> *O3PO: A domain ontology for offshore petroleum production plants.*  
> *Expert Systems with Applications*, 238 (Part F), 122104.  
> <https://doi.org/10.1016/j.eswa.2023.122104>

---
