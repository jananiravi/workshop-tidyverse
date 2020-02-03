# Using `Tidyverse` for Genomics
Workshop material: Using R/tidyverse to analyze & visualize processed genomics data!

## Overview

## Learning Objectives
- **Part 1: Getting started**
   - Installation and Setup
   - Loading packages; looking at cheatsheets
   - Data import
   - Knowing your data: _basic data exploration_
- **Part 2: Reshaping data with `tidyr`**
   - Gather, Spread
   - Unite, Separate
- **Part 3: Data wrangling with `dplyr`**
   - Filter
   - Select
   - Mutate
   - Distinct and Arrange
   - Group_by and Summarize
   - More data wrangling
- **Part 4: Visualizing tidy data with `ggplot`**
   - Basics of ggplot
   - Barplots and histograms
   - Scatter plots
   - Boxplots and violin plots
   - Some data sleuthing!
- **Part 5. Export and Wrap-up**
   - Saving your plots
   - Saving your data files
   - Summary of everything that you learnt in the workshop!


## Setup
### Before the Workshop Begins
1. Install the following software if you don’t yet have them. If you do have these installed, skip to #2:
   1. **R** version 3.5+ (Current: 3.6.1) 
   2. **RStudio** version 1.2+ (https://www.rstudio.com/products/rstudio/) OR use RStudio Cloud (https://rstudio.cloud)
2. Ensure that your version of **R** is 3.5+. The latest version is 3.6.1.
   To check your R version, type in your console:
   `version`
3. Check your **RStudio** version. It should be v1.2+
Open RStudio. In the top menu bar click: RStudio > About RStudio > 
4. Install **tidyverse** & **here**: `install.packages(c("tidyverse", "here"))`

**Other Resources: Software Carpentry Video Tutorial for installing R and R Studio**

#### For Windows Users
[Video Tutorial](https://www.youtube.com/watch?v=q0PjTAylwoU) <br>
Install R by downloading and running [this `.exe` file from CRAN](https://cran.r-project.org/bin/windows/base/release.htm).
Also, please install the [RStudio IDE](https://www.rstudio.com/products/rstudio/download/#download).
Note that if you have separate user and admin accounts, you should run the installers as administrator (right-click on .exe file and select "Run as administrator" instead of double-clicking).
Otherwise problems may occur later, for example when installing R packages.

#### For Mac Users
[Video Tutorial](https://www.youtube.com/watch?v=5-ly3kyxwEg)
Install R by downloading and running [this `.pkg` file from CRAN](https://cran.r-project.org/bin/macosx/R-latest.pkg).
Also, please install the [RStudio IDE](https://www.rstudio.com/products/rstudio/download/#download).

#### For Linux Users
You can download the binary files for your distribution from [CRAN](https://cran.r-project.org/index.html).
Or you can use your package manager (e.g. for Debian/Ubuntu run `sudo apt-get install r-base` and for Fedora run `sudo dnf install R`).
Also, please install the [RStudio IDE](https://www.rstudio.com/products/rstudio/download/#download).

## Contact
- Webpage: <https://jananiravi.github.io>
- Email: <janani@msu.edu>
- Other ways to reach us: <https://jananiravi.github.io/#contact>

### Acknowledgements
- [Krishnan Lab](https://thekrishnanlab.org)
- [R-Ladies East Lansing](https://rladies-eastlansing.github.io)
- [R-Ladies Chennai](https://meetup.com/rladies-chennai)

## Additional resources
- You can access all relevant material pertaining to this workshop [here](https://jananiravi.github.io/tidyverse-genomics).
- Other related workshops & useful cheatsheets: On [GitHub](http://github.com/rladies-eastlansing) & [Google Drive](http://bit.ly/rlel-meetup-presentations-gd).

### Some awesome open-source books
- Hands-On Programming with R: Grolemund #HOPR https://rstudio-education.github.io/hopr/
- R for Data Science: Wickham & Grolemund #R4DS https://r4ds.had.co.nz
- R Programming for Data Science: Peng https://leanpub.com/rprogramming
- Learning Statistics with R: Navarro https://learningstatisticswithr.com/book
