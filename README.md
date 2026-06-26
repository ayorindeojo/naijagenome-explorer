# NaijaGenome Explorer

> Advancing African Genomics Through Open Science, Accessible Software, and Integrated Public Data.

![Status](https://img.shields.io/badge/status-active%20development-brightgreen)
![Python](https://img.shields.io/badge/Python-3.11+-blue)
![FastAPI](https://img.shields.io/badge/FastAPI-Backend-green)
![React](https://img.shields.io/badge/React-Frontend-61DAFB)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## Overview

African populations harbor the greatest genetic diversity in the world, yet researchers studying African genomes often need to navigate multiple databases, publications, and software tools to answer a single biological question. This fragmentation creates barriers to research, education, collaboration, and the translation of genomic discoveries into real-world impact.

**NaijaGenome Explorer** is the flagship application of the **NaijaGenome** platform—an open-source initiative dedicated to advancing African genomics through accessible software, integrated public data, and education. It brings together publicly available genomic variation, clinical annotations, population genetics, pharmacogenomics, and educational resources into a unified, searchable platform focused on Nigerian and African populations.

The platform begins with publicly available Yoruba (YRI) datasets and is designed to expand to additional Nigerian and African populations as high-quality public genomic resources become available. Our long-term vision is to create an ecosystem that supports scientific discovery, education, and collaboration while improving the accessibility and representation of African genomic data.

**Our mission** is to advance African genomics by building open, evidence-based, and accessible software that empowers researchers, educators, clinicians, students, and developers to explore, understand, and apply genomic knowledge.

NaijaGenome Explorer does not seek to replace existing genomic resources. Instead, it builds upon trusted public datasets and databases, integrating them into a cohesive platform that makes African genomic data easier to discover, interpret, visualize, and apply for research, education, and innovation.

---

# Why This Project?

Many existing genomic resources answer questions such as:

> *"What variants exist in this gene?"*

NaijaGenome Explorer aims to answer richer questions such as:

* Which variants are common in Yoruba populations?
* How do Nigerian allele frequencies compare with other populations?
* Which variants are clinically important?
* Which variants influence drug response?
* What diseases are associated with these variants?
* How are these variants distributed across African populations?

Instead of requiring users to search several databases individually, NaijaGenome Explorer brings relevant information together into a single, searchable interface.

---

# Vision

Our long-term vision is to become a comprehensive open-source platform for exploring genomic variation in Nigerian and African populations.

The platform will integrate genomic data, clinical annotations, pharmacogenomic information, population frequencies, scientific literature, and interactive visualizations into one unified experience.

---

# Features

## Current

* Repository setup
* Project architecture
* Documentation
* Development roadmap

## Planned

* Gene Explorer
* Variant Browser
* Population Comparison
* Disease Explorer
* Pharmacogenomics Explorer
* Interactive Genome Browser
* REST API
* Data Download Portal
* Interactive Visualizations

---

# Why Yoruba?

The project begins with the **Yoruba in Ibadan, Nigeria (YRI)** population because it is one of the best-characterized African populations available through public genomic resources.

Starting with YRI allows the project to establish a reproducible analysis pipeline before expanding to additional Nigerian populations such as:

* Igbo
* Hausa
* Esan
* Fulani
* Tiv
* Kanuri
* Ibibio
* Edo
* and other African populations where high-quality public datasets are available.

---

# Target Users

NaijaGenome Explorer is designed for:

* Bioinformatics researchers
* Human geneticists
* Medical researchers
* Graduate students
* University educators
* Public health researchers
* Healthcare professionals
* Students learning genomics

---

# Technology Stack

## Backend

* Python
* FastAPI
* SQLAlchemy
* Pydantic

## Frontend

* React
* Next.js
* TypeScript
* Tailwind CSS

## Bioinformatics

* bcftools
* samtools
* GATK
* Ensembl VEP
* pysam
* pandas
* NumPy

## Database

* SQLite (development)
* PostgreSQL (production)

---

# Project Architecture

```text
                    Public Genomic Resources
                              │
        ┌─────────────────────┼──────────────────────┐
        │                     │                      │
 1000 Genomes             ClinVar              Ensembl
        │                     │                      │
        └─────────────────────┼──────────────────────┘
                              │
                     Data Processing Pipeline
                              │
                   Variant Annotation Pipeline
                              │
                       Application Database
                              │
                        FastAPI REST API
                              │
                     React / Next.js Frontend
                              │
                          End Users
```

---

# Repository Structure

```text
naijagenome-explorer/

├── backend/
│   ├── api/
│   ├── models/
│   ├── services/
│   ├── database/
│   └── utils/
│
├── frontend/
│
├── bioinformatics/
│   ├── scripts/
│   ├── notebooks/
│   └── workflows/
│
├── data/
│   ├── raw/
│   ├── processed/
│   └── reference/
│
├── docs/
│
├── tests/
│
├── README.md
├── LICENSE
└── requirements.txt
```

---

# Roadmap

## Version 0.1 — Foundation

* [ ] Repository architecture
* [ ] Documentation
* [ ] Gene lookup
* [ ] Variant extraction
* [ ] Local database

---

## Version 0.2 — Gene Explorer

* [ ] Search by gene symbol
* [ ] Gene information page
* [ ] Variant list
* [ ] Population frequencies

---

## Version 0.3 — Variant Browser

* [ ] Variant search
* [ ] Clinical annotations
* [ ] Disease associations
* [ ] Functional consequences

---

## Version 0.4 — Population Explorer

* [ ] Population comparison
* [ ] Allele frequency charts
* [ ] PCA visualization
* [ ] Geographic distribution

---

## Version 0.5 — Pharmacogenomics

* [ ] Drug response variants
* [ ] Drug–gene interactions
* [ ] Population-specific frequencies

---

## Version 1.0

* [ ] Interactive Genome Browser
* [ ] Public REST API
* [ ] Docker deployment
* [ ] User authentication
* [ ] Cloud deployment

---

# Development Principles

This project is built around several guiding principles:

* Reproducibility
* Transparency
* Open Science
* Population Representation
* Modern Software Engineering
* Educational Accessibility

---

# Data Sources

NaijaGenome Explorer integrates publicly available datasets, including:

* 1000 Genomes Project
* ClinVar
* dbSNP
* Ensembl
* gnomAD
* PharmGKB (planned)
* H3Africa resources (where publicly available)

---

# Contributing

Contributions are welcome.

Future contribution guidelines will include:

* Bug reports
* Feature requests
* Documentation improvements
* Bioinformatics workflows
* Software development
* Visualization enhancements

---

# Current Status

🟢 **Active Development**

Current milestone:

**Sprint 1 — Gene Search Engine**

The initial focus is building a robust pipeline for querying publicly available Yoruba genomic data and exposing it through a modern API and web interface.

---

# License

This project is released under the **MIT License**.

---

# Author

**Ayorinde Ojo**

M.S. Biotechnology (Bioinformatics), Expected 2026

GitHub: https://github.com/ayorindeojo

---

> *Building accessible genomic tools for African populations through open science and modern software engineering.*
