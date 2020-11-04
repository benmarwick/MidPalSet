
<!-- README.md is generated from README.Rmd. Please edit that file -->

# The spatial patterning of Middle Paleolithic human settlement in westernmost Iberia

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh///master?urlpath=rstudio)

This repository contains the data and code for our paper:

> Cascalheira, J., Gonçalves, C. and Maio D. (2020). *The spatial
> patterning of Middle Paleolithic human settlement in westernmost
> Iberia*. Quaternary International
> <https://doi.org/10.1016/j.quaint.2020.08.027>

### How to cite

Please cite this compendium as:

> Cascalheira, J., Gonçalves, C. and Maio D., (2020). *Compendium of R
> code and data for The spatial patterning of Middle Paleolithic human
> settlement in westernmost Iberia*. Accessed 04 Nov 2020. Online at
> <https://doi.org/10.17605/OSF.IO/456EG>

## Contents

The **analysis** directory contains:

  - [:file\_folder: paper](/analysis/paper): R Markdown source document
    for manuscript. Includes code to reproduce the figures and tables
    generated by the analysis. It also has a rendered version,
    `paper.docx`, suitable for reading (the code is replaced by figures
    and tables in this file)
  - [:file\_folder: data](/analysis/data): Data used in the analysis.
  - [:file\_folder: figures](/analysis/figures): Plots and other
    illustrations
  - [:file\_folder:
    supplementary-materials](/analysis/supplementary-materials):
    Supplementary materials including notes and other documents prepared
    and collected during the analysis.

## How to run in your broswer or download and run locally

This research compendium has been developed using the statistical
programming language R. To work with the compendium, you will need
installed on your computer the [R
software](https://cloud.r-project.org/) itself and optionally [RStudio
Desktop](https://rstudio.com/products/rstudio/download/).

The simplest way to explore the text, code and data is to click on
[binder](https://mybinder.org/v2/gh///master?urlpath=rstudio) to open an
instance of RStudio in your browser, which will have the compendium
files ready to work with. Binder uses rocker-project.org Docker images
to ensure a consistent and reproducible computational environment. These
Docker images can also be used locally.

You can download the compendium as a zip from from this URL:
[master.zip](/archive/master.zip). After unzipping: - open the `.Rproj`
file in RStudio - run `devtools::install()` to ensure you have the
packages this analysis depends on (also listed in the
[DESCRIPTION](/DESCRIPTION) file). - finally, open
`analysis/paper/paper.Rmd` and knit to produce the `paper.docx`, or run
`rmarkdown::render("analysis/paper/paper.Rmd")` in the R console

### Licenses

**Text and figures :**
[CC-BY-4.0](http://creativecommons.org/licenses/by/4.0/)

**Code :** See the [DESCRIPTION](DESCRIPTION) file

**Data :** [CC-0](http://creativecommons.org/publicdomain/zero/1.0/)
attribution requested in reuse

### Contributions

We welcome contributions from everyone. Before you get started, please
see our [contributor guidelines](CONTRIBUTING.md). Please note that this
project is released with a [Contributor Code of Conduct](CONDUCT.md). By
participating in this project you agree to abide by its terms.
