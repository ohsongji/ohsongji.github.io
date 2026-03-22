---
title: "Research Toolkit for Cancer Biology (My Practical Guide)"
date: 2026-03-21
categories: [Research, Resources]
tags: [bioinformatics, database, RNA-seq, tools, CRISPR]
---

This post is a curated list of research tools I frequently use in cancer biology, particularly for genomics, transcriptomics, and experimental design.

Rather than listing everything, I focused on tools that are practically useful in real research workflows.

---

## 🔎 1. Literature & Protocol Resources

- **[PubMed](https://pubmed.ncbi.nlm.nih.gov/)**  
  → Primary resource for biomedical literature search  
  → Use filters (review, clinical trial, recent) to refine results  

- **[STAR Protocols](https://www.cell.com/star-protocols/home)**  
  → Step-by-step experimental protocols  
  → Useful for reproducing published experiments or optimizing lab methods
  
---

## 🧬 2. Public Databases

### 📊 Comprehensive Tumor Databases

- **[cBioPortal (MSKCC)](https://www.cbioportal.org/)**  
  → Mutation, copy number, and clinical data exploration  

- **[TCGA (GDC Portal)](https://portal.gdc.cancer.gov/)**  
  → Large-scale genomic datasets  

- **[COSMIC (Sanger Institute)](https://cancer.sanger.ac.uk/cosmic)**  
  → Curated somatic mutation database  

- **[ICGC Data Portal](https://daco.icgc-argo.org/)**  
  → International cancer genome datasets  

---

### 🧬 Variant & Annotation

- **[OncoKB](https://www.oncokb.org/)**  
  → Clinical interpretation of cancer mutations  

- **[ClinVar](https://www.ncbi.nlm.nih.gov/clinvar/)**  
  → Variant pathogenicity information  

- **[gnomAD](https://gnomad.broadinstitute.org/)**  
  → Population frequency filtering  

---

### 🧪 Gene Expression Resources

- **[GEO (NCBI)](https://www.ncbi.nlm.nih.gov/geo/)**  
  → Public gene expression datasets  

- **[GEPIA2](https://gepia2.cancer-pku.cn/#index)**  
  → Quick visualization of TCGA/GTEx  

- **[GTEx Portal](https://www.gtexportal.org/home/)**  
  → Normal tissue expression reference  

---

### 🧫 Protein Expression

- **[Human Protein Atlas](https://www.proteinatlas.org/)**  
  → Protein-level validation  

- **[UniProt](https://www.uniprot.org/)**  
  → Protein sequence and function  

- **[PDB (Protein Data Bank)](https://www.rcsb.org/)**  
  → Protein structure  

---

### 🧬 Cell Line & Functional Genomics

- **[CCLE](https://sites.broadinstitute.org/ccle/)**  
  → Multi-omics cancer cell line data  

- **[DepMap](https://depmap.org/portal/)**  
  → Gene dependency and CRISPR screening  

- **[Single Cell Portal](https://singlecell.broadinstitute.org/single_cell)**  
  → Single-cell RNA-seq datasets  

---

### 💊 Drug Sensitivity

- **[GDSC](https://www.cancerrxgene.org/)**  
  → Drug response in cancer cell lines  

- **[Cancer Therapeutics Response Portal (CTRP)](https://portals.broadinstitute.org/ctrp.v2/)**  
  → Identifying cancer dependencies with small molecules  

---

## 🧪 3. RNA Analysis Tools

### 📈 Differential Expression Analysis

- **R-based analysis (DESeq2, edgeR, etc.)**  
  → Flexible and widely used  

- **[GEO2R](https://www.ncbi.nlm.nih.gov/geo/)**  
  → Quick analysis from GEO  

- **[GenePattern](https://www.genepattern.org/rna-seq-analysis/)**  
  → GUI-based RNA-seq analysis  

---

### 🧬 Pathway Analysis

- **[KEGG](https://www.genome.jp/kegg/)**  
- **[Reactome](https://reactome.org/)**  
- **[Panther](https://pantherdb.org/)**  
- **[GSEA](https://www.gsea-msigdb.org/gsea/index.jsp)**  
- **[DAVID](https://davidbioinformatics.nih.gov/)**  

💡 **Note:** Always consider effect size and biological relevance  

---

## ✂️ 4. Genome Editing Tools

- **[CRISPOR](https://crispor.tefor.net/)**  
  → sgRNA design and off-target prediction  

- **[CHOPCHOP](https://chopchop.cbu.uib.no/)**  
  → Genome editing design  

- **[Addgene](https://www.addgene.org/)**  
  → Plasmid repository  

- **[SnapGene](https://www.snapgene.com/)**  
  → DNA cloning and experiment planning  

---

## 🧬 5. Visualization & Network Analysis

- **[UCSC Genome Browser](https://genome.ucsc.edu/)**  
  → Genome visualization  

- **[IGV](https://software.broadinstitute.org/software/igv/)**  
  → Sequencing data visualization  

- **[STRING](https://string-db.org/)**  
  → Protein interaction networks  

- **[BioGRID](https://thebiogrid.org/)**  
  → Interaction database  

- **[Cytoscape](https://cytoscape.org/)**  
  → Network visualization  

---

## 🎨 6. Figure Design & Idea Organization

- **[BioRender](https://www.biorender.com/)**  
  → Scientific figure design  

- **[Napkin AI](https://napkin.ai/)**  
  → Idea organization and visualization  

---

## 🛠 7. Miscellaneous Useful Tools

- **[GraphPad Molarity Calculator](https://www.graphpad.com/quickcalcs/molarityform/)**  
  → Quick concentration calculations  

- **[MEME Suite](https://meme-suite.org/meme/index.html)**  
  → Motif discovery  

---

## 🧬 Notes & Practical Considerations

- Always define your **biological question first**  
- Use databases for **hypothesis generation**  
- Combine multiple tools for validation  

---
<span style="color: #8b3a3a;">
Please note that these resources may be updated, changed, or integrated over time.  
If you notice any outdated information or have suggestions for improvement, feel free to let me know.
</span>
