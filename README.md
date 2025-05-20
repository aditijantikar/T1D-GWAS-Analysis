# T1D-GWAS-Analysis

📝 Project Overview

This project focuses on the analysis of Genome-Wide Association Study (GWAS) summary statistics for Type 1 Diabetes (T1D). The data is from a 2021 study by Chiou et al. (Nature). This involves reading and processing the GWAS data (filtered to SNPs with p-values < 0.001 on the hg38 genome assembly), generating Manhattan plots to visualize associations, and investigating significant genomic regions, including the MHC region and other top hits.

## 📁 Files in this Repository

* **`BGGN239_mcvicker_hw1.Rmd`**: The R Markdown file containing the R code, analysis steps, and narrative for the T1D GWAS homework.
* **`BGGN239_mcvicker_hw1.pdf`**: The compiled PDF document showing the results and answers for the homework questions.
* **`t1d_gwas_hg38_pruned2_w_genome_pos.tsv`**: A tab-separated values file containing the pruned T1D GWAS summary statistics (hg38 assembly) used for the analysis.

## 🛠️ Tools & Technologies

* **R:** For statistical analysis and data visualization.
* **R Markdown:** For creating reproducible reports.
* **Key R packages used:** `ggplot2` (for Manhattan plots), `dplyr` or `data.table`
  
## 🚀 How to Run/Use

1.  **Prerequisites:**
    * An R environment with R Markdown support (e.g., RStudio).
    * Required R packages (e.g., `ggplot2`, `data.table` or other data import packages) should be installed.
2.  **To view the completed work:**
    * Open `BGGN239_mcvicker_hw1.pdf`.
3.  **To reproduce the analysis:**
    * Open `BGGN239_mcvicker_hw1.Rmd` in RStudio.
    * Ensure the data file `t1d_gwas_hg38_pruned2_w_genome_pos.tsv` is in the same directory or update the file path within the Rmd script.
    * Run the R code chunks sequentially.

## ✨ Key Concepts Explored

* Reading and processing GWAS summary statistics.
* Generating Manhattan plots to visualize genome-wide associations.
* Identifying and interpreting significant loci in GWAS data.
* Working with genomic coordinates (hg38 assembly) and gene regions (e.g., MHC).

---
