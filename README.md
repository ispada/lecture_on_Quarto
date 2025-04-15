# Lecture on Quarto - Scripts and materials for an introductory lecture on Quarto using R.

# Introduction to Quarto with R
This repository contains lecture materials and example scripts for an introductory session on **Quarto** using **R**. 
The session is part of the course *Introduction to Data Science for Engineering*, Bachelor’s Degree in Management Engineering at the **University of Pisa**.

## 📚 About the Lecture
The lecture introduces key concepts in authoring documents with Quarto, a modern scientific and technical publishing system that integrates code and text into elegant, reproducible outputs such as HTML pages, PDFs, and slides. Topics covered include:
- Structure of a Quarto document (YAML, Markdown, and code chunks)
- Output formats (HTML, PDF, RevealJS slides)
- Literate programming principles
- Code execution and display options
- Figures, tables, and cross-referencing
- Visual and source editors
- Tips and tricks using RStudio and Quarto features

## 🛠️ Requirements
Make sure the following are installed:
- **R** (version 4.2 or later): [https://cran.r-project.org](https://cran.r-project.org)  
- **RStudio** (2023.03.1+446 or later): [https://posit.co/download/rstudio-desktop](https://posit.co/download/rstudio-desktop)  
- **Quarto CLI** (version 1.3.354 or later): [https://quarto.org/docs/get-started](https://quarto.org/docs/get-started)  
Install the required R packages:
```r
install.packages(c("tidyverse", "gt", "ggthemes", "palmerpenguins", "quarto", "here"))
```

## 🧑‍💻 Getting Started
Clone this repository or download the files and open the .Rproj file in RStudio.
Learn the basics of Quarto and follow the instruction to render the document and experiment with the code and markdown elements.

## 📦 Materials
- Lecture.qmd: .qdm file for producing a report on introduction on Quarto with instruction for exercises.
- Documents.qmd: .qdm file for producing a RevealJS presentation slides on documents creation.
- images: folder with images used in the report and in the slides

## 🙏 Credits
Based on original teaching materials by:
Mine Çetinkaya Rundel (Duke University + Posit), Andrew Bray (UC Berkeley) and Charlotte Wickham (Posit)
- https://mine.quarto.pub/cincinnati-asa/2-documents-slides/2-documents-slides.html#/title-slide 
- https://mine.quarto.pub/quarto-monash/1-hello-quarto/

## 🔗 Useful Links
Quarto Documentation: https://quarto.org/docs/guide/
