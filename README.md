<div align="center">

<img width="1983" height="793"
     alt="AI-driven computational biology and precision medicine"
     src="https://github.com/user-attachments/assets/029f7106-3c12-4491-abd7-2a615666f169" />

# 🧬 AI-Driven Computational Biology for Precision Medicine

**Bioinformatics · Cancer Genomics · Healthcare Data Engineering · Scientific Machine Learning**

[![Profile Views](https://komarev.com/ghpvc/?username=mtariqi&style=for-the-badge&color=0F766E)](https://github.com/mtariqi)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mdtariqulscired)
[![ORCID](https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white)](https://orcid.org/0009-0009-6545-8040)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mtiumea@gmail.com)
[![Portfolio](https://img.shields.io/badge/Research_Portfolio-000000?style=for-the-badge&logo=githubpages)](https://mtariqi.github.io)

</div>

---

## About Me

I am a **Research Scientist, Bioinformatician, and Data Scientist** working at the intersection of **computational biology, cancer genomics, artificial intelligence, biostatistics, and precision medicine**.

My research combines genomics, transcriptomics, multi-omics integration, machine learning, and large language models to transform complex biological and health data into evidence for:

- Biomarker discovery
- Therapeutic-target prioritization
- Precision oncology
- AI-assisted drug discovery
- Reproducible biomedical research

I currently contribute to cancer-genomics research as a **Bioinformatician at the University of Arkansas for Medical Sciences (UAMS)**, developing scalable NGS workflows and analyzing TCGA and CPTAC datasets. I am also pursuing an **MSc in Bioinformatics at Northeastern University**, strengthening my expertise in translational bioinformatics, machine learning, and trustworthy biomedical AI.

Beyond biomedical research, I independently reproduced and extended machine-learning workflows for streamflow prediction and National Water Model bias correction. My **HYDRO-FLOW-AI** project builds on open workflows from the Alabama Water Institute’s NWM-ML project and research involving a University of West Florida researcher, while remaining an independent project with no claim of institutional affiliation.

My long-term goal is to build trustworthy computational systems that connect biological evidence, clinical data, and artificial intelligence to accelerate scientific discovery and improve patient outcomes.

---

## Research Interests

- 🧬 Computational biology and bioinformatics
- 🎗️ Cancer genomics and precision oncology
- 🧪 NGS analysis and variant interpretation
- 🔗 Multi-omics integration
- 💊 Computational drug discovery
- 🤖 Artificial intelligence and deep learning
- 📚 Biomedical large language models
- ⚡ Agentic AI and retrieval-augmented generation
- ☁️ Cloud-based scientific computing
- 🏥 Healthcare data engineering
- 🌊 Scientific machine learning for hydrology

---

## Featured Research Projects

| Project | Research focus | Repository |
|---|---|---|
| **RTK/NRTK TNBC** | Patient-level kinase alterations and drug-target prioritization in triple-negative breast cancer | [View project](https://github.com/mtariqi/rtk_nrtk_tnbc) |
| **HYDRO-FLOW-AI** | Extreme-aware streamflow prediction and National Water Model bias correction | [View project](https://github.com/mtariqi/HYDRO-FLOW-AI) |
| **NIH Clinical Trials Lakehouse** | Reproducible healthcare data engineering for clinical-trial analytics | [View project](https://github.com/mtariqi/nih-clinical-trials-lakehouse-pipeline) |
| **CDC Healthcare Streaming ETL** | Streaming ingestion, validation, transformation, and public-health analytics | [View project](https://github.com/mtariqi/cdc-healthcare-streaming-etl-pipeline) |
| **TCGA–CPTAC Kafka Platform** | Event-driven processing of large-scale cancer multi-omics data | [View project](https://github.com/mtariqi/tcga-cptac-kafka-bioinformatics) |
| **Synthetic Variant Calling Benchmark** | Reproducible benchmarking of NGS variant-calling workflows | [View project](https://github.com/mtariqi/synthetic-variant-calling-benchmark) |
| **Genomic Foundation Models** | Transformer-based representation learning for genomic sequences | [View project](https://github.com/mtariqi/genomic-foundation-models) |
| **USAG1 Validation** | Computational evidence synthesis and therapeutic-target validation | [View project](https://github.com/mtariqi/USAG1-Validation) |

---

## 🌊 HYDRO-FLOW-AI

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/mtariqi/HYDRO-FLOW-AI)
[![Python 3.10+](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://www.python.org/)
![Stage 1](https://img.shields.io/badge/Stage%201-Reconstruction%20Complete-2D6A4F.svg)

**HYDRO-FLOW-AI** is an independent, extreme-aware machine-learning framework for streamflow prediction and site-specific National Water Model bias correction at USGS gauges.

### Current capabilities

- Leakage-safe temporal training, validation, and testing
- Historical USGS streamflow and climate-data integration
- Site-specific model-performance diagnostics
- Evaluation using RMSE, MAE, bias, and NSE
- Q95 and Q99 high-flow evaluation
- Peak-magnitude error analysis
- Extreme-event detection and threshold-based assessment

### Planned extensions

- XGBoost residual bias correction
- Quantile-regression uncertainty intervals
- LSTM and Transformer-based forecasting
- River-network graph neural networks
- Explainability and model-drift monitoring

---

## My Current Research

### Wnt/β-Catenin Signaling, Craniofacial Development, and Skeletal Biology

I am currently conducting collaborative computational biology research with **Professor Wei Hsu**, focusing on the role of **Wnt/β-catenin signaling in craniofacial development, skeletal biology, epithelial differentiation, and osteogenic regulatory programs**.

Professor Hsu's research program is based at the **ADA Forsyth Institute** and is connected with Harvard-affiliated biomedical and stem-cell research activities. My contribution to this collaboration centers on **bioinformatics, RNA-seq analysis, pathway biology, transcription-factor regulation, network analysis, and reproducible computational workflows**.

The current project analyzes RNA-seq data from a **4-control vs. 4-mutant mouse experimental design** to characterize transcriptional changes associated with perturbation of Wnt-related developmental biology.

### RNA-seq and Differential-Expression Analysis

The processed DESeq2 dataset contains:

| Measure | Result |
|---|---:|
| Total rows in the differential-expression dataset | 22,444 |
| Genes retained for analysis after missing-value filtering | 21,730 |
| Unique genes in the current testing universe | 21,715 |
| Genes with nominal `p < 0.05` | 1,334 |
| Downregulated nominal DEGs | 994 |
| Upregulated nominal DEGs | 340 |

The project intentionally distinguishes between:

- **nominal DEG selection**, used for exploratory biological characterization and sensitivity analyses, and
- **multiple-testing-adjusted enrichment statistics**, used where appropriate for pathway and transcription-factor analyses.

This distinction is particularly important because the biological interpretation is being developed under several DEG thresholds rather than relying on a single arbitrary cutoff.

### Wnt and Epithelial Biology

A prominent feature of the transcriptional profile is the strong reduction of epithelial, junctional, and cell-adhesion-associated genes.

Examples identified during the analysis include:

- `Krt5`
- `Krt14`
- `Dsp`
- `Pkp1`
- `Dsg2`
- `Cdh1`

These changes are being investigated in the context of:

- canonical Wnt/β-catenin signaling,
- non-canonical Wnt signaling,
- planar cell polarity,
- epithelial differentiation,
- cell-cell junction organization,
- craniofacial morphogenesis,
- and tissue-composition effects.

Pathway enrichment analyses have highlighted downregulated programs related to:

- Cell-Cell Junction
- Apical Junction Complex
- Tight Junction
- Cornified Envelope

These results suggest substantial remodeling of epithelial-associated transcriptional programs in the mutant condition.

### Canonical and Non-Canonical Wnt Signaling

The project separately interrogates several branches of Wnt biology:

- **β-catenin-dependent / canonical Wnt signaling**
- **TCF/LEF-dependent transcription**
- **β-catenin-independent signaling**
- **planar cell polarity (PCP)**
- **Wnt/Ca²⁺ signaling**

This branch-specific analysis is important because changes in Wnt biology cannot necessarily be interpreted from a single pathway score or a small group of canonical markers.

The analysis therefore combines differential expression with ranked gene-set approaches and mechanistic pathway interrogation to determine whether different Wnt branches show distinct transcriptional responses.

### Transcription-Factor Regulatory Analysis

I developed a transcription-factor target-set enrichment workflow using curated regulatory resources including:

- **TRRUST**
- **ChEA**
- **Gene Ontology**
- **WikiPathways**

TF target-set over-representation is evaluated using **one-sided Fisher exact tests** followed by **Benjamini-Hochberg correction for multiple testing**.

Only TF target sets meeting:

`FDR < 0.05`

are included in the current pathway-focused TF network analysis.

Importantly, the underlying DEG pools in this analysis are selected using nominal p-values, so gene-level significance and TF-enrichment significance are treated as separate statistical concepts.

### TF–Wnt Regulatory-Association Network

I developed a regulatory-association network connecting significantly enriched TF target sets with downregulated Wnt-associated DEGs.

Current network summary:

| Measure | Result |
|---|---:|
| Wnt annotation genes in testing universe | 412 |
| Wnt TF–DEG edges displayed | 48 |

The Wnt network contains several transcriptional programs, including Polycomb-associated regulators such as:

- `BMI1`
- `EZH2`
- `JARID2`
- `SUZ12`
- `RING1B`

Additional TF-associated programs include regulators such as:

- `SOX2`
- `ZNF217`

The connected Wnt-associated genes include candidates such as:

- `WNT6`
- `APC2`
- `SFRP5`
- `CDH1`
- `CELSR1`
- `CELSR2`
- `CTNND2`
- `FGF10`
- `FOXD3`
- `ITGA3`
- `CAV1`

The Polycomb factors are visually highlighted as a prespecified biological annotation rather than being assigned greater statistical weight.

These networks are interpreted as **regulatory-association networks**, not direct causal models. An edge indicates that a DEG belongs to an enriched TF target set and overlaps the pathway annotation; it does not by itself establish direct TF-DNA binding, regulatory direction, interaction strength, or causal regulation.

### Osteogenesis Regulatory Network

A complementary analysis investigates TF programs associated with **upregulated osteogenesis-related genes**.

Current network summary:

| Measure | Result |
|---|---:|
| Osteogenesis annotation genes in testing universe | 319 |
| Osteogenesis TF–DEG edges displayed | 23 |
| TF programs shared with the Wnt network | 2 |

TF-associated programs identified in this network include candidates such as:

- `SP7`
- `EP300`
- `PPARG`
- `IRF8`
- `PBX`
- `NUCKS1`
- `SUZ12`
- `RING1B`

Associated osteogenic genes include candidates such as:

- `BGLAP`
- `SPP1`
- `COL1A2`
- `COL2A1`
- `COL11A2`
- `PDGFRA`
- `LRP4`
- `NOTUM`
- `SGMS2`

The objective is not simply to identify isolated differentially expressed genes, but to determine whether the mutant transcriptome contains coordinated regulatory programs linking Wnt perturbation with skeletal and osteogenic biology.

### Wnt/PCP Mechanistic Analysis

The project also contains a focused mechanistic interrogation of non-canonical Wnt and planar-cell-polarity biology.

One signal identified during this analysis was **Bmp6**, which remained significant after multiple-testing correction in the relevant pathway analysis.

The broader goal is to distinguish:

- pathway-level enrichment,
- regulatory-program enrichment,
- individual gene-level differential expression,
- and experimentally testable mechanistic hypotheses.

### Craniofacial and Skeletal Gene Prioritization

In response to the biological focus of the collaboration, I developed dedicated analyses for genes involved in:

- craniofacial morphogenesis,
- skeletal development,
- osteoblast differentiation,
- extracellular-matrix organization,
- epithelial-mesenchymal biology,
- Wnt pathway regulation,
- and developmental signaling.

This enables the RNA-seq findings to be interpreted specifically in relation to Professor Hsu's research interests in craniofacial and skeletal development rather than relying only on generic pathway enrichment.

### Network and Regulatory Visualization

I am also developing publication-oriented visualization approaches, including:

- TF-centered star networks
- TF-DEG regulatory-association networks
- pathway-specific regulatory maps
- DEG volcano plots
- pathway enrichment figures
- ranked gene-set analyses
- TF-target spider maps
- source-audited regulatory networks

For the TF-Wnt and osteogenesis networks:

- squares represent TF target programs,
- circles represent pathway-associated DEGs,
- node size reflects network degree,
- edges have constant width,
- and visual styling is kept separate from statistical evidence.

This prevents graphical properties from being misinterpreted as biological interaction strength.

### Reproducibility and Validation

A major objective of this project is to make the analysis reproducible and publication-ready.

Current validation and sensitivity work includes:

- reconstruction and verification of DEG pools,
- comparison of nominal-p-value and adjusted-p-value thresholds,
- ranked GSEA,
- canonical versus non-canonical Wnt analyses,
- β-catenin-dependent versus β-catenin-independent signatures,
- TF enrichment across TRRUST and ChEA,
- orthology verification,
- source auditing of TF-target relationships,
- epithelial-composition sensitivity analysis,
- and network robustness assessment.

Planned and ongoing validation includes recovery of the original count matrix and re-evaluation of the DESeq2 design, normalization, and experimental metadata.

### Research Objective

The overarching goal of this collaboration is to develop a mechanistically interpretable model connecting:

**Wnt pathway perturbation → transcription-factor programs → epithelial and developmental changes → craniofacial/skeletal and osteogenic phenotypes**

while carefully separating statistical association from experimentally established causality.

The project is being developed as a reproducible computational biology framework that can support future mechanistic experiments and, following completion and collaborator approval, peer-reviewed publication.
## 🧪 Selected Scientific Contributions

### Hybrid-CORE

Computational framework for rational drug-combination prioritization using complementary biological and pharmacological evidence.

### RTK/NRTK Network Analysis

Identification of compensatory kinase alteration patterns and potential drug-target combinations using TCGA cancer-genomics data.

### Biomedical Agentic RAG

LLM-supported retrieval, evaluation, and synthesis of biomedical evidence for research decision support.

### Genomic Foundation Models

Transformer-based representation-learning approaches for genomic sequences and downstream biological prediction.

### Healthcare Data Engineering

Reproducible lakehouse and streaming architectures for clinical-trial, public-health, and biomedical data.

---

## ⚙️ Technology Stack

### Programming and Analytics

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

### Artificial Intelligence

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square)
![Amazon Bedrock](https://img.shields.io/badge/Amazon_Bedrock-232F3E?style=flat-square&logo=amazonaws)

### Bioinformatics

![GATK](https://img.shields.io/badge/GATK-2E8B57?style=flat-square)
![BWA](https://img.shields.io/badge/BWA-006699?style=flat-square)
![DeepVariant](https://img.shields.io/badge/DeepVariant-0F9D58?style=flat-square)
![Snakemake](https://img.shields.io/badge/Snakemake-039475?style=flat-square)
![Nextflow](https://img.shields.io/badge/Nextflow-24C8DD?style=flat-square)

### Cloud and Infrastructure

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

---

## 📈 Current Research Focus

- AI for precision oncology
- Computational drug discovery
- Cancer multi-omics
- Biomedical large language models
- Genomic foundation models
- Agentic AI for scientific discovery
- Trustworthy and explainable AI
- Scalable scientific computing
- Extreme-aware streamflow forecasting

---

## 🎓 Education

- **MSc Bioinformatics** — Northeastern University *(in progress)*
- **MSc Molecular Biology (Bioinformatics)** — Umeå University
- **BSc Biotechnology and Genetic Engineering** — Khulna University
- **Advanced Diploma in Data Science and Data Engineering**
- **Graduate Certificate in Project Management**

---

## 📜 Professional Development

- Health Informatics — Johns Hopkins University
- Business Analytics and Data-Driven Decision-Making — University of Toronto
- Project Management
- Cloud Computing
- Machine Learning and Data Science

---

## 🌱 Currently Learning

- Trustworthy and causal AI
- Agentic and multi-agent systems
- Biomedical large language models
- Genomic foundation models
- Scalable multi-omics analytics

---

## 📊 GitHub Statistics

<div align="center">

<img
  width="49%"
  alt="GitHub profile statistics"
  src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=mtariqi&theme=github"
/>

<img
  width="49%"
  alt="Most-used programming languages"
  src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=mtariqi&theme=github"
/>

</div>
---

## 🤝 Collaboration

I welcome research and open-source collaboration in:

- Computational biology and bioinformatics
- Cancer genomics and precision medicine
- Biomedical artificial intelligence
- Computational drug discovery
- Healthcare data engineering
- Scientific machine learning
- Reproducible research software
- Regenerative medicine and stem cell research

---

<div align="center">

## 🧬 Research and Open-Source Activity

<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/mtariqi/mtariqi/output/github-contribution-grid-snake-dark.svg"
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/mtariqi/mtariqi/output/github-contribution-grid-snake.svg"
  />
  <img
    alt="Animated GitHub contribution graph"
    src="https://raw.githubusercontent.com/mtariqi/mtariqi/output/github-contribution-grid-snake.svg"
  />
</picture>

</div>

---

<div align="center">

<a href="https://git.io/typing-svg">
  <img
    alt="Research mission"
    src="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=20&duration=3500&pause=1000&color=0F766E&center=true&vCenter=true&repeat=true&width=900&height=50&lines=Transforming+biological+data+into+therapeutic+evidence;Building+trustworthy+AI+for+precision+medicine;Advancing+reproducible+computational+biology"
  />
</a>

[LinkedIn](https://www.linkedin.com/in/mdtariqulscired) ·
[ORCID](https://orcid.org/0009-0009-6545-8040) ·
[Portfolio](https://mtariqi.github.io) ·
[Email](mailto:mtiumea@gmail.com)

<img
  width="100%"
  alt="Profile footer"
  src="https://capsule-render.vercel.app/api?type=waving&color=0:081C15,50:0F766E,100:14B8A6&height=130&section=footer&animation=twinkling"
/>

</div>
