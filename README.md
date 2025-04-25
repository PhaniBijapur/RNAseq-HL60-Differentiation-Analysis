# RNA-Seq Analysis of HL-60/S4 Differentiation

This project presents a full pipeline for RNA sequencing (RNA-Seq) analysis comparing granulocytic and macrophage-differentiated forms of HL-60/S4 cells.  
The workflow includes raw data download, preprocessing, transcript quantification (Salmon), statistical analysis (edgeR, DESeq2), visualization (heatmaps, volcano plots, Venn diagrams), and pathway enrichment analysis.

**Data Source:** [NCBI BioProject PRJNA303179](https://www.ncbi.nlm.nih.gov/bioproject/303179)  
**Organism:** Homo sapiens  
**Platforms:** Illumina HiSeq 2000

---

### 🧪 Methods:
- Data download and conversion (SRA Toolkit)
- Quantification (Salmon)
- Statistical analysis (edgeR, DESeq2)
- Visualization (Boxplots, Heatmaps, Volcano plots)
- Gene Ontology (GO) and KEGG enrichment analysis

---

### 📁 Files Included:
- `IlluminaHiSeq_Phaniraj.Rmd`: Full R Markdown code for the complete analysis pipeline.

---

### 📊 Tools & Packages:
- `tximport`, `DESeq2`, `edgeR`, `limma`, `GO.db`, `org.Hs.eg.db`, `VennDiagram`, `Salmon`, `R`, `NCBI SRA Toolkit`

---

### 🔥 Highlights:
- Compared transcriptomic changes in untreated, RA-treated, and TPA-treated HL-60/S4 cells.
- Identified significant differentially expressed genes and key biological pathways.
- Visualized findings with volcano plots, correlation heatmaps, and enrichment diagrams.

---

> **Author:** Phaniraj Bijapur  
> **Date:** July 2024

