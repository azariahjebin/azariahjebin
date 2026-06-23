😎 Hey! Nice to see you.

Welcome to my page! I am **Azariah Jebin**, an **AI Engineer & Researcher** specializing in Graph Neural Networks (GNNs), multimodal fusion architectures, and deep learning implementations for computational pathology and agentic systems.

I hold a **Master of Science in Artificial Intelligence** from **The University of Texas at Austin**. My work bridges the gap between complex structural tissue morphology and geometric deep learning architectures — with a long-term focus on building AI systems that democratize diagnostic access in resource-constrained healthcare settings.

---

## 🛠️ Things I code with

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Airflow-017CEE?style=for-the-badge&logo=apache-airflow&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?style=for-the-badge&logo=neo4j&logoColor=white)

**Other Experience:** SQL, Scikit-learn, CNNs (U-Net, YOLOv5, EfficientNet), LiteLLM, GCP BigQuery, Tableau, Streamlit, Google ADK, QGIS, PyTorch Geometric

---

## 🔬 Core Research & Publications

### 🧠 NeuroGraph: Predicting Pediatric Brain Tumor Biomarkers *(Master's Thesis, UT Austin)*

- **Overview:** Developed a computational pathology framework capable of inferring critical molecular alterations directly from routinely available H&E stained Whole Slide Images (WSIs), reducing resource-heavy reliance on IHC or molecular sequencing.
- **Architecture:** Adapted SlideGraph+ concepts to map local cell-patch graph topologies using Delaunay Triangulation and Dynamic Graph CNNs (`EdgeConv`) over dense embeddings from the `UNI2-h` foundation model.
- **Optimization & Performance:** Implemented a masked multi-label binary cross-entropy loss module to successfully handle extreme class imbalance and label sparsity across 5 distinct markers (H3K27M, GFAP, Synaptophysin, INI1, ALK1), achieving a mean AUC of `0.761` and high-tier performance for GFAP (AUC `0.939`).
- **Interpretability:** Integrated GNNExplainer to surface biomarker-specific tissue subgraphs and built a clinical interpretability dashboard for pathologist-facing visualization of prediction confidence and graph topology.
- **Dataset:** 182 IRB-approved pediatric CNS tumor cases (Protocol STUDY00007710) in collaboration with Dell Medical School neuropathologists.
- **Infrastructure:** High-throughput feature extraction on TACC HPC clusters; GNN training on NVIDIA A100 (Google Colab Pro+).

---

### 🤖 NEXUS: A Multi-Agent Framework for Autonomous Enterprise Workflows *(Preprint — Preprints.org)*
> DOI: [10.20944/preprints202602.0493.v1](https://doi.org/10.20944/preprints202602.0493.v1)

- **Overview:** Architectural position paper proposing a transition from human-default insurance processing to AI-native, agent-orchestrated lifecycle management.
- **Core Innovation:** Designed the **Truth Score Engine (TSE)** — a weighted, penalty-adjusted consensus aggregation mechanism that synthesizes outputs from specialized AI agents and routes decisions across three confidence tiers: AUTO (>90%), REVIEW (60–90%), MANUAL (<60%).
- **Stack:** Google Agent Development Kit (ADK), LangChain, Vertex AI, evidential deep learning for uncertainty quantification.
- **Generalization:** Framework is domain-agnostic; demonstrated across medical, auto, and property insurance verticals via swappable specialist agent modules.

---

### 📊 Mitigating Dataset Artifacts in NLI: A Sensitivity Analysis of Ensemble-Based Debiasing *(Course Research, UT Austin)*

- Trained a hypothesis-only ELECTRA-Small baseline on SNLI, exposing a `60.12%` accuracy rate driven by spurious lexical correlations.
- Implemented a Product-of-Experts (PoE) ensemble debiasing pipeline with a tunable penalty weight `α`.
- Conducted sensitivity analysis across `α ∈ {0.2, 0.5, 0.8}`, quantifying the accuracy-robustness trade-off: light debiasing improved out-of-distribution robustness; aggressive debiasing degraded in-domain accuracy from `89.6% → 87.9%`.

---

### 🎥 Real-Time Video Analytics via Cascaded YOLOv5 + EfficientNet *(Technical Report, UT Austin)*

- Designed a cascaded two-stage computer vision pipeline: YOLOv5 for spatial detection, EfficientNet for deep feature classification.
- Applied geometric and photometric augmentations; evaluated inference performance against FPS and memory constraints for edge-device deployment.

---

## 💼 Experience

**Analyst — Capgemini** *(Feb 2023 – Dec 2025, Bengaluru)*
- Built an LLM-powered NL-to-Cypher/SQL metadata assistant using LangChain + Gemini with a Streamlit + Neo4j frontend.
- Migrated legacy Teradata SQL pipelines to GCP BigQuery; orchestrated staging data loads via Airflow DAGs on Cloud Composer.
- Maintained production ETL pipelines (Ab Initio, SQL) with data quality checks and incident resolution at scale.

**Data & GIS Analyst Intern — Thazhal Geospatial Analytics** *(Oct 2021 – Dec 2021, Nov 2022 – Dec 2022, Tirunelveli)*
- Built Flask REST APIs to process raster map data and categorize spatial datasets by elevation and coordinate logic.
- Developed automated Selenium-based web scraping engines for geographic and environmental data aggregation.
- Utilized QGIS and Pandas for land record digitization and government project validation; received a **Certificate of Appreciation from the Tirunelveli District Collector** for data-driven public planning contributions.

---

## 🎓 Education

| Degree | Institution | Year | GPA |
|---|---|---|---|
| M.S. in Artificial Intelligence | University of Texas at Austin | Dec 2025 | 3.7 / 4.0 |
| B.E. in Computer Science Engineering | SCAD College of Engineering and Technology, Tamil Nadu | Jul 2022 | 8.25 / 10 |

---

## 📫 Get in Touch

- 📧 azariahjebin@gmail.com
- 🔗 [LinkedIn](https://linkedin.com/in/azariahjebin)
- 📍 Tirunelveli, Tamil Nadu, India
