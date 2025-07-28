# AMICA: Agentic Dataset Annotator

[![Release](https://img.shields.io/github/v/release/Cellular-Semantics/amica-agent)](https://img.shields.io/github/v/release/Cellular-Semantics/amica-agent)
[![Build status](https://img.shields.io/github/actions/workflow/status/Cellular-Semantics/amica-agent/main.yml?branch=main)](https://github.com/Cellular-Semantics/amica-agent/actions/workflows/main.yml?query=branch%3Amain)
[![codecov](https://codecov.io/gh/Cellular-Semantics/amica-agent/branch/main/graph/badge.svg)](https://codecov.io/gh/Cellular-Semantics/amica-agent)
[![Commit activity](https://img.shields.io/github/commit-activity/m/Cellular-Semantics/amica-agent)](https://img.shields.io/github/commit-activity/m/Cellular-Semantics/amica-agent)
[![License](https://img.shields.io/github/license/Cellular-Semantics/amica-agent)](https://img.shields.io/github/license/Cellular-Semantics/amica-agent)

**AMICA (Automated Mapping and Integration of Curation Annotations)** is an LLM- and ontology-driven tool for automating cell type annotation in single-cell datasets, especially from HCA and CELLxGENE.

- **Github repository**: <https://github.com/Cellular-Semantics/amica-agent/>

- **Documentation** <https://Cellular-Semantics.github.io/amica-agent/>

---

## 🚀 What It Does

- Maps author annotations to Cell Ontology (CL) terms using:
  - Ontology Lookup Service (OLS) API
  - LLM-powered synonym matching
  - Metadata-aware reasoning (e.g. tissue, stage)
- Flags unmatched terms as potential new ontology entries
- Suggests more specific terms using context and ontology structure
- Validates performance against curated CELLxGENE datasets
