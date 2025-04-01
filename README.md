
This repository contains the code and analysis for our study on:

📄 **Pluripotent Stem Cell Plasticity is Fine-Tuned by a Slit-Independent Robo Pathway in a Regenerative Animal**  
🧬 Kuang-Tse Wang, Yu-Chia Chen, Fu-Yu Tsai, Catherine P Judy, Carolyn E Adler

---

## 📁 Repository Structure

| Folder                      | Description |
|----------------------------------|-------------|
| `Analysis_of_FoxARNAi`              | Analysis of foxA(RNAi) scRNAseq data generated in this study. Refer to Fig6 and FigS5 |
| `Reanalysis_of_Fincher_2018`  | Determine pharynx cell types; Compare head and pharynx neuorns. Refer to FigS1, Fig2, Fig5 |


---

## 🔧 Requirements

- R (>= 4.2)
- R packages:
  - `Seurat`
  - `tidyverse`
  - `patchwork`
  - `ggplot2`
  - Your custom theme function: `scTheme.R`

---

## 🚀 How to Run

Each `.Rmd` file can be knitted or executed in sequence:

```r
rmarkdown::render("00_Preprocess.Rmd")
rmarkdown::render("01_FigS1_cell_composition.Rmd")
...
