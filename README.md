## Hi there 👋

I'm Loai Eletr, a Bioinformatics researcher specializing in end-to-end transcriptomic workflows—from raw sequencing data to high-level biological systems modeling. My work focuses on building reproducible, scalable pipelines for cancer research, with a particular emphasis on the tumor microenvironment.

---

### 🧬 Featured Projects

#### **[LoaiEletr/rnaseq](https://github.com/LoaiEletr/rnaseq)**
*A comprehensive Nextflow DSL2 pipeline for Bulk RNA-seq analysis.*
- **Architecture:** Built on nf-core standards with a branched design supporting Genomic (HISAT2) and Pseudoalignment (Salmon/Kallisto) routes.
- **Capabilities:** End-to-end processing including UMI handling, contamination removal (BBSplit), and specialized downstream analysis modules:
    - **Genomic:** Differential Gene Expression (DEG), WGCNA, Alternative Splicing (rMATS), Differential Exon Usage (DEXSeq), and Germline Variant Calling (GVC).
    - **Pseudoalignment:** Isoform Switching analysis via IsoformSwitchAnalyzeR.
- **Tech Stack:** Nextflow, Docker/Singularity, Bash, R, Python.

#### **[CRC-SingleCell-Atlas](https://github.com/LoaiEletr/CRC-SingleCell-Atlas)**
*High-resolution transcriptomic landscape of Colorectal Cancer and Liver Metastasis.*
- **Methodology:** Integrated 15 patient samples (Normal, Primary Tumor, Metastasis) using **scVI** and **Harmony** to resolve complex batch effects.
- **Advanced Analysis:**
    - **Systems Biology:** Modeled the Malignant-Myeloid-Stroma axis (SPP1, MIF, and MK signaling) using **CellChat**.
    - **Transcriptomics:** Performed pseudobulk DE analysis using **PyDESeq2** to ensure statistical rigor at the patient level.
    - **Regulatory Networks:** Gene Set Enrichment Analysis (GSEA) and pathway discovery.
- **Tech Stack:** Python (Scanpy, scVI-tools), R (Seurat, CellChat), and Python-R interoperability (rpy2).

---

### 🛠️ Technical Toolkit

- **Languages:** Python (Advanced), R (Advanced), Bash, Nextflow DSL2.
- **Single-Cell:** Scanpy, AnnData, scVI/scArches, DoubletFinder, SoupX, CellChat, PyDESeq2, Decoupler.
- **Bulk RNA-seq:** HISAT2, Salmon, Kallisto, DESeq2, rMATS, DEXSeq, GATK.
- **Workflow & Cloud:** Nextflow, nf-core, Docker, Conda, Linux/Ubuntu.
- **Machine Learning:** Deep learning for single-cell transcriptomics (scVI).

---

### 📝 Research & Publications

- **First-Author Research:** Identified **DNASE1** as a pan-cancer diagnostic biomarker and explored **miR-133b** as a functionally conserved tumor suppressor.
- **Focus Areas:** Tumor Microenvironment (TME), Metastatic Transition, Myeloid-driven Immunosuppression, and Biomarker Discovery.

### 🔍 Peer Review Service

- **Ad Hoc Reviewer:** *Frontiers in Molecular Biosciences* (2026)
---

### 📫 Connect with Me

- **LinkedIn:** [linkedin.com/in/loai-eletr](https://linkedin.com/in/loai-eletr)
- **Email:** loai.eletr65@yahoo.com
