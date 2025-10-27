# Energy Digital Twin – Training Room

This repository provides the implementation of a **semantic and modular Energy Digital Twin (EDT)** developed for a training room case study within an educational building.
The framework integrates **BIM (IFC4)**, **IoT sensor data**, **BMS operational variables**, and **meteorological information** into a unified semantic architecture based on **Brick/RDF**. It also generates **AI-ready datasets** for predictive modeling, anomaly detection, and energy optimization tasks.

## Project Structure
- `notebooks/`: Jupyter notebooks for data acquisition, fusion, semantic structuring, and machine learning evaluation.
- `graph/`: RDF/TTL files aligned with the Brick ontology and validated with SHACL.
- `data/`: 
  - `raw/`: raw datasets (BIM/IoT/BMS/Weather) 
  - `processed/`: refined, synchronized, and model-ready data 
- `src/edt/`: Python utilities for SPARQL queries, SHACL validation, and data transformation.
- `figures/`: Architecture diagrams, RDF graphs, and evaluation plots.
- `docs/`: Additional documentation.


