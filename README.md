# Comparative Trends in Life Expectancy and Life Satisfaction in Europe and Asia (2011–2023)

This repository contains a reproducible report analyzing trends in **life expectancy** and **life satisfaction** in **Europe** and **Asia** from **2011 to 2023**. The analysis leverages population-weighted averages and compares patterns between the two regions.

## Members

- TingTing Wu
- Yilin Zhang
- James Gray

## 📄 Report Overview

- **Key questions**: Are there similar trends in life expectancy and life satisfaction between Europe and Asia?
- **Data source**: [Our World in Data](https://ourworldindata.org/grapher/life-satisfaction-vs-life-expectancy)
- **Methodology**: Data cleaning, population-weighted aggregation, and visualization.
- **Results**: Europe shows more consistent improvements, while Asia displays more variability and a turning point in 2019.
- **Recommendations**: Consider using happiness indices in policy, expanding research scope, and including more socioeconomic variables.

## 📊 Key Visualizations

- Distribution curves of life expectancy and life satisfaction (2023)
- Density map comparing Europe and Asia (2023)
- Trajectories of weighted regional averages (2011–2023)

## 📦 Folder Structure

```
.
├── report.qmd                                                                # Quarto source file for the main report
├── report.pdf                                                                # Rendered PDF report
├── life-satisfaction-vs-life-expectancy.csv                                  # Raw data
├── ETC5513_Assignment3_Slides.qmd                                            # Quarto source file for slides
├── ETC5513_Assignment3_Slides.html                                           # Rendered HTML slides
├── ETC5513_Assignment3_Slides_files/                                         # Generated slide figures and assets
│   ├── figure-revealjs/
│   ├── libs/
├── europe_asia.csv                                                           # Filtered dataset for Europe and Asia
├── images/                                                                   # Additional images used in slides
│   ├── meme.jpg
├── assignment-3-reproducible-reporting-often-imitated-never-duplicated.Rproj # RStudio project file
├── renv/                                                                     # renv environment files for reproducibility
├── renv.lock                                                                 # Exact R package versions for reproducibility
├── .Rprofile                                                                 # R session configuration (e.g., renv activation)
├── .gitignore                                                                # Files and directories to exclude from version control
├── LICENSE                                                                   # Project license 
└── README.md                                                                 # This README file
```

## ⚙️ Prerequisites

Before running this project, ensure that you have the following installed on your system:

- R (version 4.x or later): The main programming language used for data analysis and visualization.

- Quarto: To render the .qmd files into PDF and HTML outputs.

- LaTeX distribution (e.g., TeX Live, MacTeX, MikTeX): Required for rendering the PDF report.

- renv: Used to manage and restore the R package environment.

To install R packages managed by renv, run:

```
renv::restore()
```

## 📜 License

This project is licensed under the terms of the MIT License. You are free to use, modify, and distribute the materials in this repository, provided you include proper attribution and the license terms in derivative works.