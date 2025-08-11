# A Call for Yearly Breast Cancer Screenings in America

This repository contains a data analysis and report prepared for **DATA1001 – Foundations of Data Science** at the University of Sydney (Oct 2023). The project investigates **breast cancer risk factors** using a public dataset and communicates recommendations for **yearly screening policies** in the United States.

Breast cancer is one of the most common cancers worldwide, and early detection significantly improves survival rates. This report examines the relationships between patient demographics, diagnostic features, and breast cancer occurrence, aiming to inform public health discussions. The analysis uses **tidy data principles**, **statistical visualisations**, and **clear communication** to present findings in an accessible way.

The repository includes both the **source R Markdown file** and a knitted **HTML report** with interactive navigation and styling. Anyone can view the HTML report without needing to run R code.

## Contents

- `final_report.Rmd` – Main R Markdown source file.
- `final_report.html` – Knitted HTML output of the report (viewable in any browser).
- `breast_cancer.csv` – Dataset used in the analysis.
- `README.md` – Project documentation.

## Requirements

To reproduce the report from the `.Rmd` file, you’ll need:

- **R** (>= 4.0 recommended) and **RStudio** (optional but recommended)
- R packages:
  ```r
  install.packages(c(
    "tidyverse",   # includes ggplot2, readr, dplyr, etc.
    "dplyr",
    "ggmosaic",
    "scales",
    "rmarkdown",
    "knitr"
  ))
  ```

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/devilshadow04/breast-cancer-screening-analysis.git
   cd breast-cancer-screening-analysis
   ```

2. Ensure `breast_cancer.csv` is present in the same folder as `final_report.Rmd`.

3. Open `final_report.Rmd` in RStudio and click **Knit** to generate the report.  
   Or run in R:
   ```r
   rmarkdown::render("final_report.Rmd")
   ```

4. Open the generated `final_report.html` in your browser to view the report.

## Viewing the Report without R

You can view the pre-generated `final_report.html` in this repository directly:
- Download it from GitHub
- Double-click to open in your default browser

## Project Structure

```
.
├── breast_cancer.csv
├── final_report.Rmd
├── final_report.html
└── README.md
```

## Author

- **Cong Thanh Vu** – University of Sydney
