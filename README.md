# Source-Grounded Generative Structural Biology Knowledge Base

🔗 **Live Notebook Link:** [Generative Structural Biology: Diffusion, AF3 & Geometric ML](https://gemini.google.com/notebook/786af990-1b4b-44cb-839f-fc91dd0c9423)

## Overview
This repository contains a source-grounded RAG knowledge base and evaluation suite built using Gemini Notebook. Designed at the intersection of **Biophysics, Structural Biology, and Generative Deep Learning**, this project explores how neural diffusion priors and SE(3)-equivariant graph neural networks replace or complement classical physical potential energy functions (like CHARMM/AMBER) in macromolecular design.

## Source Corpus
The knowledge base synthesizes a multi-modal corpus of 7 trusted sources:
1. **AlphaFold 3 Paper** (Abramson et al., *Nature* 2024) - *PDF*
2. **RFdiffusion Paper** (Watson et al., *Nature* 2023) - *PDF*
3. **Geometrically Equivariant GNNs Survey** (Han et al., arXiv:2202.07230) - *Academic Web / ArXiv*
4. **Max Welling Keynote**: Equivariance, Symmetry & Diffusion in AI for Science - *YouTube*
5. **RosettaCommons Lecture**: Diffusion Models for Protein Structure Generation - *YouTube*
6. **OpenFold Technical Documentation & Implementation** - *GitHub / Technical Docs*
7. **Technical Note**: Diffusion Loss vs. Molecular Mechanics Force Fields - *Custom Synthesis*

## Key Evaluations & Stress Testing
* **Cross-Domain Grounding Verification:** Tested hallucination boundaries by querying the notebook on thermodynamic feasibility versus geometric generative priors.
* **Off-Topic Guardrails:** Validated that the notebook correctly rejects queries outside its curated literature corpus (e.g., tabular machine learning benchmarks).
* **Automated Artifact Generation:** Leveraged notebook synthesis engines to generate executive briefing documents, comparative mind maps, and deep-dive technical summaries.