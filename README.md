# Pluripotent Stem Cell Plasticity is Fine-Tuned by a Slit-Independent Robo Pathway in a Regenerative Animal 
This repository contains the code and analysis for our study on:
📄 _"Pluripotent Stem Cell Plasticity is Fine-Tuned by a Slit-Independent Robo Pathway in a Regenerative Animal "_  
🧬 _Kuang-Tse Wang, Yu-Chia Chen, Fu-Yu Tsai, Catherine P Judy, Carolyn E Adler_
_

---

## 📁 Repository Structure

| File/Folder                      | Description |
|----------------------------------|-------------|
| `00_Preprocess.Rmd`              | Preprocessing of Seurat object (normalization, PCA, UMAP). |
| `01_FigS1_cell_composition.Rmd`  | Cell type composition visualization and UMAPs. |
| `01_FigS1_pharynx_epithelium.Rmd`| Pharynx-specific cell analysis. |
| `02_Fig5_Head_vs_pharynx.Rmd`    | Differential expression and comparison of head vs. pharynx neural cells. |

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
