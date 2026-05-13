<h1 align="center">Namaste 🙏 | I'm Anubhav Kaphle</h1>

<p align="center">
  <b>Research Scientist · Statistical Genomics · AI for Healthcare · Digital Health</b><br>
  <i>PhD | CSIRO Australian e-Health Research Centre | Melbourne, Australia</i>
</p>

<p align="center">
  <a href="https://twitter.com/KaphleAnubhav"><img src="https://img.shields.io/badge/Twitter-@KaphleAnubhav-1DA1F2?style=flat&logo=twitter&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/anubhav-kaphle/"><img src="https://img.shields.io/badge/LinkedIn-Anubhav%20Kaphle-0A66C2?style=flat&logo=linkedin&logoColor=white"/></a>
  <a href="https://scholar.google.co.in/citations?user=B2vwpDoAAAAJ&hl=en"><img src="https://img.shields.io/badge/Google%20Scholar-Publications-4285F4?style=flat&logo=google-scholar&logoColor=white"/></a>
  <a href="https://orcid.org/0000-0002-1972-6819"><img src="https://img.shields.io/badge/ORCiD-0000--0002--1972--6819-A6CE39?style=flat&logo=orcid&logoColor=white"/></a>
  <a href="https://people.csiro.au/k/a/anubhav-kaphle"><img src="https://img.shields.io/badge/CSIRO%20Profile-AEHRC-00A9CE?style=flat"/></a>
  <a href="mailto:anubhavkaphle@gmail.com"><img src="https://img.shields.io/badge/Email-Contact%20Me-D14836?style=flat&logo=gmail&logoColor=white"/></a>
</p>

---

## 🧬 About Me

I am a computational scientist and researcher passionate about **unlocking the power of genomics and other health data to understand and prevent human disease**. My work sits at the intersection of **statistical genetics**, **AI/machine learning**, and **digital health infrastructure** — building tools and methods that translate genomic insights into real-world clinical impact.

Currently at the **CSIRO Australian e-Health Research Centre (AEHRC)** in Melbourne, I develop cloud-native genomic platforms, privacy-preserving analytics methods, and scalable bioinformatics pipelines for population-scale datasets.

> *"The genome is one of the most complex and beautiful datasets in existence — I build the methods and infrastructure to make it speak."*

---

## 🔬 Research Focus


---

### 🔐 Genomic Data Governance & Privacy-Preserving Analytics
Genomic data is uniquely sensitive — it is immutable, inherited, and identifies not just individuals but entire families. Responsible genomic research demands infrastructure that is **ethical by design**. I architect and build frameworks that embed data sovereignty, dynamic consent, and access control directly into genomic data platforms.

Key contributions include:

- **GeneGuardian** — A cloud-native dynamic consent and genomic information management platform, deployed to support Australia's first newborn genomic screening trial (TRAIL). Built on AWS (Cognito · Lambda · DynamoDB · API Gateway · SES) with a ReactJS/NodeJS frontend and Terraform IaC. Implements self-sovereign identity principles, giving participants real-time control over how their genomic data is used.
- **GA4GH Standards Alignment** — Active involvement in the Global Alliance for Genomics and Health (GA4GH) consortiums, including alignment with Beacon v2 protocols, data access frameworks, and newborn screening genomic standards.
- **Privacy-Preserving Analytics** — Research into **federated learning** and **secure multiparty computation** approaches that allow genomic analyses to be conducted across institutions without raw data leaving its source — a critical requirement for sensitive clinical genomic data.

**Stack & Standards:** AWS · Terraform · ReactJS · GA4GH Beacon v2 · Federated Learning · SOC2 · FHIR · HL7

---

### 🤖 AI Agents & Machine Learning for Omics Data Analysis
The scale and complexity of modern omics data — genomic, transcriptomic, proteomic, and clinical — demands AI systems that go beyond static pipelines. I am actively developing and exploring **agentic AI frameworks** that can autonomously orchestrate multi-step genomic workflows, reason over heterogeneous data types, and interact with genomic data infrastructure through structured APIs.

**Agentic Genomics Infrastructure:**
- Designing AI agent systems (using frameworks such as CrewAI and Claude-based agents) to automate tasks like variant QC, cohort curation, phenotype harmonisation, and report generation
- Exploring "agentification" of GA4GH Beacon — replacing static client-initiated query APIs with stateful, reasoning agents capable of multi-hop data discovery across federated genomic nodes
- Building consent governance agents that dynamically interpret participant preferences and enforce access policies in real time

**ML/AI for Omics:**
- **Random Forest & Gradient Boosting** for genomic feature selection and variant prioritisation
- **Deep Learning** (CNN, Transformer-based models) for sequence-level variant effect prediction and multi-omics integration
- **Federated & Privacy-Aware ML** — training models on distributed genomic datasets without centralising sensitive data
- **Multimodal Data Integration** 

---

### 🌏 Trans-Ethnic & Diverse Population Genomics
Most large-scale GWAS have been conducted predominantly in European-ancestry cohorts, limiting the generalisability of genetic findings and risk models to diverse populations. My research addresses this gap by conducting **large-scale heritability and association analyses across trans-ethnic populations**, including extensive collaboration with researchers in Taiwan on Taiwanese biobank datasets.

This work explores how **linkage disequilibrium (LD) structure**, **allele frequency differences**, and **gene-environment interactions** vary across ancestries — and how these differences affect the transferability of PRS models. Improving cross-population genomic inference is essential for equitable precision medicine.

**Methods & Tools:** Cross-population LD analysis · Ancestry-stratified GWAS · Meta-analysis (METAL) · Admixture modelling · Propensity Score Matching (PSM) · PLINK · REGENIE

---

## 🏗️ Featured Projects

### 🔐 GeneGuardian — Genomic Consent Management Platform
> *Tech Lead | CSIRO × NSW Health Pathology | TRAIL Newborn Genomic Screening Study*

A cloud-native dynamic consent and genomic information management platform supporting Australia's first newborn genomic screening trial.

**Stack:** AWS (Cognito · API Gateway · Lambda · DynamoDB · SES) · ReactJS · MUI · NodeJS · Terraform (IaC)

**Key contributions:**
- Designed and deployed the full-stack platform from architecture to production
- Implemented self-sovereign identity principles for participant-controlled genomic data access
- Integrated future-proof encryption aligned with GA4GH genomic data standards
- Supported deployment under NSW e-Health Pathology cloud infrastructure

---

### 📊 Population-Scale GWAS & Heritability Analysis
Large-scale genome-wide association studies on biobank-sized datasets (UK Biobank, Taiwanese cohorts) using HPC systems.

**Tools:** PLINK · REGENIE · BOLT-LMM · GCTA · R · Python · Bash  
**Methods:** Propensity Score Matching, PCA, SNP annotation, epistasis detection, partitioned LD score regression

---

## 🛠️ Technical Skills

| Domain | Tools & Technologies |
|---|---|
| **Languages** | Python · R · Bash · AWK · SQL ·  LaTeX |
| **Cloud & Infra** | AWS (EC2, Lambda, DynamoDB, Cognito, S3) · Terraform  |
| **Bioinformatics** | PLINK · REGENIE · GCTA · VCF processing · Genome imputation |
| **HPC & Big Data** | SLURM/PBS HPCs · Apache Spark · DNAnexus |
| **ML/AI** | Random Forest · Deep Learning · Federated Learning · Agentic AI (CrewAI, LangChain and LangGraph) |
| **Data & Dev** | Git/GitHub · dbt · R (tidyverse, ggplot2) · ReactJS · NodeJS |

---

## 📚 Interests

- Statistical & Deep Learning in Genomics
- Agentic AI in Healthcare and Bioinformatics
- Genetic Data Privacy & Federated Analytics
- Precision & Preventive Medicine
- Digital Health Infrastructure & Policy
- Trans-ethnic Population Genetics
- Science Outreach & Mentorship

---


## 📬 Get In Touch

| | |
|---|---|
| 📧 Personal | [anubhavkaphle@gmail.com](mailto:anubhavkaphle@gmail.com) |
| 🏛️ CSIRO | anubhav.kaphle [at] csiro [dot] au |
| 🌐 Profile | [CSIRO AEHRC — Anubhav Kaphle](https://people.csiro.au/k/a/anubhav-kaphle) |
| 📍 Location | Melbourne, Victoria, Australia |

---

<p align="center">
  <i>Open to collaborations in genomics, digital health, and AI for precision medicine.</i>
</p>
