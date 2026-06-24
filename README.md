# Industrial Foundry Platform

Industrial data platform inspired by the Palantir Foundry ecosystem for manufacturing and operational environments.

The goal of this project is to build a realistic end-to-end industrial platform capable of integrating operational data, implementing business logic, modeling business entities through Ontology, and delivering operational applications that support industrial decision-making.

---

## Vision

This project progressively demonstrates how Palantir Foundry concepts can be applied in a realistic manufacturing and supply chain environment.

Rather than building isolated demos, the objective is to create a shared industrial data foundation that supports multiple business modules, operational workflows, and future applications.

---

## Platform Architecture

Current industrial data foundation:

* Suppliers
* Components
* Plants
* Shipments
* Work Orders
* Incidents

All datasets are connected through realistic business relationships and support a shared industrial Ontology.

![Ontology Overview](images/ontology/ontology-overview.png)

---

## Current Module: Supplier Risk Management

The first business module focuses on Supplier Risk Management.

A complete Pipeline Builder workflow aggregates operational data from multiple industrial sources and calculates supplier-level risk and performance metrics.

Key capabilities:

* Multi-source data integration
* Business KPI calculation
* Data quality handling
* Null management
* Operational risk scoring
* Production-style transformations

![Pipeline Builder Workflow](images/pipeline-builder/supplier-risk-pipeline.png)

---

## Ontology

A business-oriented Ontology has been implemented to model industrial entities and operational metrics.

Current implementation includes:

* Supplier Object Type
* Business-friendly properties
* Risk indicators
* Quality metrics
* Supply chain metrics
* Object View configuration
* Relationship modeling

![Supplier Object Type](images/ontology/supplier-object-type.png)

---

## Workshop Application

A first operational application has been built on top of the Ontology.

### Supplier Risk Management Application

Features:

* Supplier risk distribution analysis
* KPI monitoring
* Supplier explorer
* Supplier detail view
* Top-risk supplier identification
* Interactive filtering and exploration

![Supplier Risk Management Application](images/workshop/supplier-risk-app.png)

![Supplier Risk Management Application](images/workshop/supplier-risk-app-2.png)

---

## Roadmap

The platform evolves module by module while reusing the same industrial data foundation and shared Ontology.

Current roadmap:

* ✅ Supplier Risk Management
* ⏳ Supplier Performance Analytics
* ⏳ Manufacturing Operations Monitoring
* ⏳ Logistics & Shipment Intelligence
* ⏳ Quality Management
* ⏳ Shared Enterprise Ontology
* ⏳ Additional Workshop Applications
* ⏳ Actions & Operational Workflows
* ⏳ AIP-Powered Use Cases

---

## Tech Stack

Palantir Foundry • Pipeline Builder • Ontology • Workshop • PySpark • SQL • Data Lineage

---

## Status

🚧 Active development.

This is a long-term portfolio project that incrementally expands into a complete industrial data platform.

---

## Disclaimer

This is a personal portfolio project created for learning and professional development.

It does not contain confidential company information or proprietary business data.
