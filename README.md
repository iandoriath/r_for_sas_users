# R for SAS Users

This repository contains a curriculum designed to help SAS users learn R programming. The materials are structured as a series of lessons that build upon each other, introducing R concepts with comparisons to SAS equivalents.

## Installation Instructions

Before starting the lessons, you'll need to install R and RStudio on your computer.

### Installing R

R is the core statistical programming language, while RStudio is an integrated development environment (IDE) that makes working with R much easier.

1. Go to the R Project website: [https://cran.r-project.org/](https://cran.r-project.org/)
2. Select the download link for your operating system (Windows, Mac, or Linux)
3. Follow the installation instructions for your system
   - For Windows: Click "Download R for Windows" → "base" → "Download R x.x.x for Windows"
   - For Mac: Click "Download R for macOS" and select the appropriate version
   - For Linux: Choose your distribution and follow the provided instructions

### Installing RStudio

After installing R, you'll need to install RStudio:

1. Go to the RStudio website: [https://posit.co/download/rstudio-desktop/](https://posit.co/download/rstudio-desktop/)
2. Scroll down to "All Installers" and download the appropriate version for your operating system
3. Run the installer and follow the instructions

> **Note for SAS Users:** Unlike SAS, which is a standalone proprietary program, R is open-source and typically used with an IDE like RStudio. Think of R as the engine and RStudio as the dashboard that makes it easier to use.

### Essential Packages

Once you have R and RStudio installed, you'll need to install some essential packages for the lessons. Open RStudio and run the following commands in the Console:

```r
# Install the tidyverse and haven packages
install.packages("tidyverse")
install.packages("haven")
```

The tidyverse is a collection of packages for data manipulation and visualization, and haven is a package for importing and exporting SAS datasets.

## Curriculum Overview

This repository contains the following lessons:

1. **Lesson 1**: Introduction to RStudio Interface and R Markdown
2. **Lesson 2**: R Basics and Data Structures
3. **Lesson 3**: Data Import and Export
4. **Lesson 4**: Data Manipulation with dplyr
5. **Lesson 5**: Data Visualization with ggplot2
6. **Lesson 6**: Statistical Analysis in R
7. **Lesson 7**: Reporting with R Markdown

Each lesson is provided as an R Markdown (.Rmd) file that you can open in RStudio.

## Getting Started

1. Clone or download this repository
2. Make sure you have R and RStudio installed following the instructions above
3. Open the .Rproj file in the repository to start an RStudio session
4. Open Lesson1_setup.Rmd to begin the first lesson

## Additional Resources

- [R for SAS and SPSS Users](https://r4stats.com/books/r4sas-spss/) by Robert A. Muenchen
- [RStudio Cheatsheets](https://posit.co/resources/cheatsheets/)
- [R Markdown: The Definitive Guide](https://bookdown.org/yihui/rmarkdown/)
- [R for Data Science](https://r4ds.had.co.nz/) by Hadley Wickham & Garrett Grolemund
