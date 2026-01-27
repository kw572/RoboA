
This repository contains the code and analysis for our study on:

📄 **[RoboA reinforces planarian stem cell fate through FoxA and Anosmin1a]**  
(https://www.nature.com/articles/s41467-026-68656-1)

🧬 Kuang-Tse Wang, Fu-Yu Tsai, Yu-Chia Chen, , Catherine P Judy,  Indya E. Weathers, Engin Özkan, Carolyn E Adler

---

## 📁 Repository Structure

| Folder                      | Description |
|----------------------------------|-------------|
| `Analysis_of_FoxARNAi`              | Analysis of foxA(RNAi) scRNAseq data generated in this study. Refer to Fig6 and FigS5 |
| `Reanalysis_of_Fincher_2018`  | Reanalyze data from [Fincher et al., 2018](https://pubmed.ncbi.nlm.nih.gov/29674431/); Determine pharynx cell types; Compare head and pharynx neurons. Refer to FigS1, Fig2, Fig5 |


---

## 🔧 Requirements

- R (>= 4.2)
- R packages:
  - `Seurat`
  - `tidyverse`
  - `patchwork`
  - `ggplot2`

---

## 🚀 How to Run

Each `.Rmd` file can be knitted or executed in sequence:

```r
rmarkdown::render("00_Preprocess.Rmd")
rmarkdown::render("01_FigS1_cell_composition.Rmd")
...
