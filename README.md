# An intro to `Tidyverse`

## Overview
This repo contains the workshop material for using R/tidyverse to analyze & visualize diverse datasets, _e.g.,_ [genomics](https://github.com/jananiravi/workshop-tidyverse/tree/master/genomics), [gapminder](https://github.com/jananiravi/workshop-tidyverse/tree/master/gapminder). <br>
[Cheatsheets](https://github.com/jananiravi/cheatsheets) | [Setup instructions](/README.md/#Setup) | [Videos](https://github.com/jananiravi/workshop-tidyverse/tree/master/videos)

- **Part 1: Getting started w/ `readr`**
   - Installation and Setup | Cheatsheets
   - Loading packages
   - Data import
   - Knowing your data: _basic data exploration_
- **Part 2: Reshaping data w/ `tidyr`**
   - Gather, Spread
   - Unite, Separate
- **Part 3: Data wrangling w/ `dplyr`**
   - Filter, Select
   - Mutate
   - Distinct and Arrange
   - Group_by and Summarize
   - More data wrangling
- **Part 4: Visualizing tidy data w/ `ggplot`**
   - Basics of ggplot
   - Barplots and histograms
   - Scatter plots
   - Boxplots and violin plots
   - Some data sleuthing!
- **Part 5. Export and Wrap-up w/ `rmarkdown`**
   - Saving your plots
   - Saving your data files
   - Summary of everything that you learnt in the workshop!

## Learning Objectives
By the end of this workshop, you will be able to load your genomic dataset, perform basic data tidying & wrangling, data visualization, and save/export your results using `tidyverse`! Hopefully, you will also have a newfound appreciation for reproducible research and R!

<img src="https://github.com/jananiravi/workshop-tidyverse/blob/master/tidyverse-overview.png" alt="" width="50%" height="50%">

## Setup
### Before the Workshop Begins
1. Install the following software if you don’t yet have them. If you do have these installed, skip to #2:
   1. **R** version 3.6+ (Current: 4.0.5) 
   2. **RStudio** version 1.2+ (https://www.rstudio.com/products/rstudio/) OR use RStudio Cloud (https://rstudio.cloud)
2. Ensure that your version of **R** is 3.6+. The latest version is 4.0.5.
   To check your R version, type in your console:
   `version`
3. Check your **RStudio** version. It should be v1.3+
Open RStudio. In the top menu bar click: RStudio > About RStudio > 
4. Install **tidyverse**, **here**, **gapminder**, **gganimate**: <br> `install.packages(c("tidyverse", "here", "gapminder"))` <br> `devtools::install_github(‘thomasp85/gganimate’)`

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

## Credits
[Arjun Krishnan](https://thekrishnanlab.org) and [I](https://jravilab.github.io) co-developed the content for the genomics part for this workshop; [R-Ladies East Lansing](https://rladies-eastlansing.github.io) members (Kayla J, Nafiseh H, Veronica F, Cara F, Camille A) and I helped with the gapminder material.

### Acknowledgements
- [Krishnan Lab](https://thekrishnanlab.org) | [JRaviLab](https://jravilab.github.io)
- [R-Ladies East Lansing](https://rladies-eastlansing.github.io), incl. Nafiseh Haghtalab, Kayla Johnson, Veronica Frans, Cara Feldscher, Camille Archer
- [R-Ladies Chennai](https://meetup.com/rladies-chennai) | [R-Ladies Bangalore](https://meetup.com/rladies-bangalore) | [R-Ladies Tunis](https://meetup.com/rladies-tunis)

### Contact
- Webpage: <https://jravilab.github.io> | <https://thekrishnanlab.org> | <https://rladies-eastlansing.github.io>
- Email: <janani@msu.edu> | <arjun@msu.edu> | <eastlansing@rladies.org>
- Twitter: [@janani137](https://twitter.com/janani137) | [@compbiologist](https://twitter.com/compbiologist) | [@RLadiesELansing](https://twitter.com/RLadiesELansing)
- GitHub: [@jananiravi](https://github.com/jananiravi) | [@arjunkrish](https://github.com/arjunkrish) | [@RLadies-EastLansing](https://github.com/rladies-eastlansing)

## Additional resources
- You can access all relevant material pertaining to this workshop [here](https://jananiravi.github.io/workshop-tidyverse).
- Other related [RLEL workshops](http://github.com/rladies-eastlansing/meetup-presentations) & useful [cheatsheets](http://github.com/jananiravi/cheatsheets).
- [Computational Biology/Bioinformatics Resources](https://github.com/jananiravi/compbio-gists) collated by Arjun and me.
- [Data-to-viz.com](https://www.data-to-viz.com) & [R Graph Gallery](https://www.r-graph-gallery.com)

### Some awesome open-source books
- R for Data Science: Wickham & Grolemund #R4DS https://r4ds.had.co.nz
- Hands-On Programming with R: Grolemund #HOPR https://rstudio-education.github.io/hopr/
- R Programming for Data Science: Peng https://leanpub.com/rprogramming
- Learning Statistics with R: Navarro https://learningstatisticswithr.com/book
