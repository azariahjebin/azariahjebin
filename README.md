# 😎 Hey! Nice to see you.

Welcome to my page! 
I am **Azariah Jebin**, an **AI Engineer & Researcher** specializing in Graph Neural Networks (GNNs), multimodal fusion architectures, and deep learning implementations for computational pathology[cite: 1].

I hold a Master of Science in Artificial Intelligence from **The University of Texas at Austin**[cite: 1]. My work bridges the gap between complex structural tissue morphology and geometric deep learning architectures[cite: 1].

---

### 🛠️ Things I code with

<table>
  <tr>
    <td align="center" width="90">
      <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"><br>
    </td>
    <td align="center" width="90">
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch"><br>
    </td>
    <td align="center" width="90">
      <img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white" alt="GCP"><br>
    </td>
    <td align="center" width="90">
      <img src="https://img.shields.io/badge/Apache_Airflow-017CE1?style=for-the-badge&logo=apache-airflow&logoColor=white" alt="Airflow"><br>
    </td>
    <td align="center" width="90">
      <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=chainlink&logoColor=white" alt="LangChain"><br>
    </td>
    <td align="center" width="90">
      <img src="https://img.shields.io/badge/Neo4j-008CC1?style=for-the-badge&logo=neo4j&logoColor=white" alt="Neo4j"><br>
    </td>
  </tr>
</table>

**Other Experience:** SQL, Scikit-learn, CNNs (U-Net, YOLOv5, EfficientNet), LiteLLM, GCP BigQuery, Neo4j, Tableau, Streamlit[cite: 1].

---

### 🔬 Core Research & Publications

#### 🧠 **NeuroGraph: Predicting Pediatric Brain Tumor Biomarkers** *(Master's Thesis)*[cite: 1]
* **Overview:** Developed a computational pathology framework capable of inferring critical molecular alterations directly from routinely available H&E stained Whole Slide Images (WSIs), reducing resource-heavy reliance on IHC or molecular sequencing[cite: 1].
* **Architecture:** Adapted SlideGraph+ concepts to map local cell-patch graph topologies using Delaunay Triangulation and Dynamic Graph CNNs (`EdgeConv`) over dense embeddings from the `UNI2-h` foundation model[cite: 1].
* **Optimization & Performance:** Implemented a masked multi-label binary cross-entropy loss module to successfully handle extreme class imbalance and label sparsity across 5 distinct markers (H3K27M, GFAP, Synaptophysin, INI1, ALK1), achieving a mean AUC of `0.761` and high-tier performance for GFAP (`AUC 0.939`)[cite: 1].
* **Explainability:** Integrated `GNNExplainer` to isolate spatially connected clusters of target nodes, generating interpretable confidence maps and an AI diagnostic dashboard for neuropathologists[cite: 1].

#### 🤖 **NEXUS: A Multi-Agent Architectural Framework for Autonomous Enterprise Workflows**[cite: 1]
* **Overview:** Co-authored a system design position paper outlining the transition from human-default assembly lines to decentralized, AI-native autonomous environments within high-stakes financial and insurance domains[cite: 1, 2].
* **Framework:** Designed a distributed coordination framework utilizing **Google Agent Development Kit (ADK)** and LangChain to manage stateful, multi-turn reasoning loops across specialized sub-agents[cite: 1, 2].
* **Governance Innovation:** Conceptualized a deterministic **Truth Score Engine (TSE)** leveraging evidential deep learning principles to non-linearly calculate epistemic uncertainty and steer automated decisions through a Three-Tiered Confidence Protocol[cite: 1, 2].

#### 📉 **Mitigating Dataset Artifacts in NLI: A Sensitivity Analysis**[cite: 1]
* **Overview:** Evaluated empirical dataset shortcuts and spurious lexical overlap regularities in the Stanford NLI (SNLI) corpus using an ELECTRA-Small encoder backbone[cite: 1, 3].
* **Methodology:** Trained a hypothesis-only baseline revealing an artifact exploitation rate of `60.12%`[cite: 1, 3]. Mitigated it by building an ensemble-based pipeline leveraging a Product-of-Experts strategy and custom penalty loss parameters[cite: 1, 3].
* **Analysis:** Quantified the exact mathematical trade-off between standard leaderboard accuracy constraints and robust, out-of-domain generalized reasoning[cite: 1, 3].

---

### 🚀 Technical Projects

#### 🚗 **Autonomous Driving Planner — SuperTuxKart AI**[cite: 1]
* Implemented deep trajectory prediction networks (MLP, CNN, and Transformers) within the PySuperTuxKart simulation space[cite: 1].
* Applied metric-driven optimization with custom loss constraints to systematically reduce lateral and longitudinal errors, boosting pathing accuracy by `40%`[cite: 1].

#### 🗺️ **Multi-Task Road Scene Segmentation & Depth Estimation**[cite: 1]
* Engineered a Residual U-Net model tasked with simultaneous monocular depth estimation and road scene segmentation in synthetic simulation domains[cite: 1].
* Leveraged joint multi-task loss optimizations and aggressive geometric augmentations to stabilize real-time edge-device inference speeds[cite: 1].

#### 📱 **The Amazing Bible App** *(Google Play Store)*[cite: 1]
* Built and launched an AI-native mobile application incorporating intelligent search semantic features, automated bookmark management, and prayer tracking maps[cite: 1].
* Utilized large language models as core development accelerators, driving structural prompt engineering workflows for rapid code scaffolding and UI layouts[cite: 1].

---

### 📊 Open Source Projects & Metrics

| 🚀 Project Repository | 🛠️ Core Tech Stack | 📊 Live Metrics |
| :--- | :--- | :--- |
| **[NeuroGraph-Pipeline](#)** | `PyTorch Geometric`, `UNI2-h`, `TACC Cluster`[cite: 1] | ![Stars](https://img.shields.io/github/stars/AzariahJebin/NeuroGraph?style=flat-square) |
| **[NEXUS-Framework](#)** | `Google ADK`, `Vertex AI`, `LangChain`[cite: 1] | ![Stars](https://img.shields.io/github/stars/AzariahJebin/NEXUS-framework?style=flat-square) |
| **[CoupGPT-RAG](#)** | `LangChain`, `OpenAI API`, `Streamlit`[cite: 1] | ![Stars](https://img.shields.io/github/stars/AzariahJebin/CoupGPT?style=flat-square) |

---

### 📈 GitHub Status & Activity

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=AzariahJebin&show_icons=true&theme=dark&hide_border=true" alt="Azariah's GitHub Stats" width="48%"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AzariahJebin&layout=compact&theme=dark&hide_border=true" alt="Top Languages" width="48%"/>
</p>

---

📬 **Let's Connect!**
* **Email:** azariahjebin@gmail.com[cite: 1]
* **Location:** Tirunelveli, Tamil Nadu, India[cite: 1]
