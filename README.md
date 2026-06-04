# 🔬 ACTREC — Interview Preparation & Knowledge Bank

> **Advanced Centre for Treatment, Research and Education in Cancer (ACTREC)**
> Tata Memorial Centre, Kharghar, Navi Mumbai
> *A Grant-in-aid Institution of the Department of Atomic Energy, Government of India*

---

## 📌 About This Repository

This repository is a personal knowledge bank built in preparation for the **Project Research Scientist-II (NM)** position at ACTREC, under the project:

> *"Centre for Advanced Research on Innovation in Diagnosis, Prognostication, and Monitoring of Acute Myeloid Leukemia"*

The position requires a computational/ML engineer to build AI-powered diagnostic pipelines for Acute Myeloid Leukemia (AML) using **long-read nanopore sequencing**, **methylation-based classifiers**, and **whole genome transcriptome sequencing**.

This repo documents everything I studied — not as a shortcut to crack an interview, but as a genuine attempt to understand the problem from the ground up as a Machine Learning engineer entering a clinical research domain.

---

## 🗂️ Repository Structure

```
ACTREC-Interview-Prep/
│
├── 📄 advertisements/
│   └── Final_Advt_103-PRS-II_NM.pdf        # Official job advertisement
│
├── 📚 knowledge-bank/
│   ├── Day1_Knowledge_Bank_AML.pdf          # The Problem, Biology, Data & Pipeline
│   ├── Day2_Knowledge_Bank_AML.pdf          # Coming soon
│   ├── Day3_Knowledge_Bank_AML.pdf          # Coming soon
│   ├── Day4_Knowledge_Bank_AML.pdf          # Coming soon
│   ├── Day5_Knowledge_Bank_AML.pdf          # Coming soon
│   ├── Day6_Knowledge_Bank_AML.pdf          # Coming soon
│   └── Day7_Knowledge_Bank_AML.pdf          # Coming soon
│
└── README.md
```

---

## 📢 Official Advertisement

| Field | Details |
|---|---|
| **Position** | Project Research Scientist-II (NM) — 2 Posts |
| **Organisation** | ACTREC, Tata Memorial Centre, Navi Mumbai |
| **Project** | ICMR-funded, 4-year study on AML diagnostics |
| **Application Deadline** | 10th June 2026, 5:00 PM |
| **Mode** | Online (send documents to molhematevent@gmail.com) |
| **Salary** | Up to ₹87,100/month (₹67,000 + HRA @ 30%) |
| **Age Limit** | 40 years (maximum) |
| **Duration** | 6 months, extendable |

### Eligibility

**Option A — Masters Route:**
First Class / CGPA ≥ 7.0 in PG/Masters in Mathematics, Statistics, Physics, Electronic Engineering, Computer Science, or IT — with **3 years post-qualification experience** in:
- Python and DL frameworks (PyTorch preferred), **OR**
- Bioinformatics / Computational Biology

**Option B — PhD Route:**
PhD in Mathematics, Statistics, Physics, Electronic Engineering, Computer Science, IT, Bioinformatics, or Computational Biology — with hands-on experience in:
- Python and DL frameworks (PyTorch preferred), **OR**
- Whole genome transcriptome sequencing

> *Note: Candidates not meeting experience criteria may be considered for Project Research Scientist-I at a lower pay scale.*

---

## 📚 Knowledge Bank — 7-Day Study Plan

The core of this repository is a structured 7-day learning series. Each day covers a distinct layer of the problem — from the clinical background through to the ML engineering specifics. Every document is written to **teach the subject**, not just list facts.

| Day | Topic | Focus |
|---|---|---|
| **Day 1** | The Problem, The Biology, The Data, The Tools | AML disease, genome, DNA methylation, nanopore sequencing, full pipeline, glossary, 7 deep Q&As |
| **Day 2** | Nanopore Toolchain & Bioinformatics in Practice | Dorado, minimap2, samtools, Modkit — hands-on pipeline |
| **Day 3** | PyTorch & DL Model Building for Genomic Data | Architecture design, loss functions, evaluation at small N |
| **Day 4** | Whole Genome Transcriptome Sequencing | RNA-seq pipeline, STAR, DESeq2, multi-modal integration |
| **Day 5** | Bioinformatics Tools Deep Dive | GATK, bcftools, bedtools, variant calling |
| **Day 6** | AML Subtypes, Clinical Context & Interpretability | WHO classification, SHAP, clinical deployment |
| **Day 7** | Synthesis & Mock Interview | Connecting all concepts, reasoning through novel questions |

---

## 🧠 What This Repository Is

Each day's document is structured as:

- **Chapters** that teach each concept from first principles
- **Concept boxes** that connect biology to ML engineering terms
- **Analogy boxes** that build intuition
- **Worked examples** with real data formats and code snippets
- **A full glossary** where every term is explained — not just listed
- **Seven interview questions** answered as reasoning, not scripts

The goal is that after reading, you could explain these concepts to someone else — which is the only real test of understanding.

---

## 🔬 Project Background

The ACTREC project aims to build:

1. **Long-read nanopore sequencing diagnostics** for acute leukemia using methylation-based AI/ML classifiers
2. **Whole genome transcriptome sequencing** capability for leukemia characterisation

The computational role involves building the ML pipeline that takes raw nanopore sequencing data from AML patients and classifies their disease subtype — replacing a multi-day, multi-assay diagnostic process with a single, integrated computational workflow.

---

## 🛠️ Technologies Covered

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![PyTorch](https://img.shields.io/badge/PyTorch-2.x-orange?logo=pytorch)
![Nanopore](https://img.shields.io/badge/Oxford%20Nanopore-ONT-00A98F)
![Bioinformatics](https://img.shields.io/badge/Bioinformatics-minimap2%20%7C%20samtools%20%7C%20Modkit-green)
![ML](https://img.shields.io/badge/ML-XGBoost%20%7C%20DNABERT%20%7C%20Transformers-purple)

**Computational Biology Tools:** Dorado · minimap2 · samtools · Modkit · STAR · DESeq2 · ComBat · featureCounts

**ML / DL:** PyTorch · XGBoost · LightGBM · SHAP · Optuna · scikit-learn

**Data Formats:** POD5 · FASTQ · BAM/SAM · BEDmethyl · VCF · GTF

**Reference Data:** GRCh38 / hg38 human reference genome

---

## 📖 How to Use This Repository

If you are a fellow candidate, researcher, or ML engineer entering the computational biology domain, this repository is structured so you can:

1. Read the **advertisement** to understand the role requirements
2. Work through the **knowledge bank PDFs in order** — Day 1 builds the foundation that every subsequent day depends on
3. Use the **glossary in Day 1** as a reference throughout
4. Treat the **interview questions** as self-assessment exercises — try answering before reading the model answer

---

## ⚠️ Disclaimer

This repository documents personal study material prepared for interview preparation. All clinical and biological information is sourced from peer-reviewed literature and publicly available resources. This is not clinical advice.

---

## 📬 Contact

*Repository maintained as part of personal academic preparation.*
*Field: Machine Learning / Computational Biology*
*Location: Chennai, India*

---

<p align="center">
  <i>Built with the intention of understanding — not just passing.</i>
</p>
