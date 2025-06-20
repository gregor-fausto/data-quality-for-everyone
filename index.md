---
site: sandpaper::sandpaper_site
---

### Learning Objectives 
- Describe the importance of efficient and reproducible data QA/QC
-  Identify common data errors and quality issues
-  Develop a QA/QC strategy for a tabular data set
-  Import data into R and QA/QC using default data types 
-  Implement an R script to perform data QA/QC  on a tabular data set
-  Document and communicate data QA/QC steps for data reporting

:::::: prereq

This lesson assumes you have R and RStudio installed on your computer. R and RStudio are two separate pieces of software: 

* **R** is a programming language and software used to run code written in R.
* **RStudio** is an integrated development environment (IDE) that makes using R easier. In this course we use RStudio to interact with R. 
  
If you don't already have R and RStudio installed, follow the instructions for your operating system below.
You have to install R before you install RStudio. 

### Installing R and RStudio

::::::::::::::::: tab

### Windows

* Download R from the [CRAN website](https://cran.r-project.org/bin/windows/base/release.htm).
* Run the `.exe` file that was just downloaded
* Go to the [RStudio download page](https://www.rstudio.com/products/rstudio/download/#download)
* Under *Installers* select **Windows Vista 10/11 - RSTUDIO-xxxx.yy.z-zzz.exe** (where x = year, y = month, and z represent version numbers)
* Double click the file to install it
* Once it's installed, open RStudio to make sure it works and you don't get any error messages.

### Mac

* Download R from the [CRAN website](https://cran.r-project.org/bin/macosx/).
* Select the `.pkg` file for the latest R version
* Double click on the downloaded file to install R
* It is also a good idea to install [XQuartz](https://www.xquartz.org/) (needed by some packages)
* Go to the [RStudio download page](https://www.rstudio.com/products/rstudio/download/#download)
* Under *Installers* select **Mac OS 13+ - RSTUDIO-xxxx.yy.z-zzz.dmg** (where x = year, y = month, and z represent version numbers)
* Double click the file to install RStudio
* Once it's installed, open RStudio to make sure it works and you don't get any error messages.

### Linux

* Download R from the [CRAN website](https://cran.r-project.org/bin/macosx/).
* Select the `.pkg` file for the latest R version
* Double click on the downloaded file to install R
* It is also a good idea to install [XQuartz](https://www.xquartz.org/) (needed by some packages)
* Go to the [RStudio download page](https://www.rstudio.com/products/rstudio/download/#download)
* Under *Installers* select **Your Version of Linux - RSTUDIO-xxxx.yy.z-zzz.dmg** (where x = year, y = month, and z represent version numbers)
* Double click the file to install RStudio
* Once it's installed, open RStudio to make sure it works and you don't get any error messages.

:::::::::::::::::::::::::

::::
