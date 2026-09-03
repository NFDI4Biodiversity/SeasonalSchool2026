# Accounts and Installations

## Accounts

During the course, we will use several services that require personal accounts. Please register with the following services and organizations:

### Necessary

* [GitHub](https://github.com) - version control, make your code available
* [QFieldCloud](https://app.qfield.cloud/accounts/login/) - collect data with [QField](https://qfield.org/) app

### (Highly) recommended

* [ORCID](https://orcid.org/) - self-curated unique researcher ID
  * use ORCID to sign in to Zenodo
  * use ORCID to identify in GBIF
* [GBIF](https://www.gbif.org/) - access and download biodiversity data
  * [How to set up R package *rgbif* with your GBIF account](https://www.erikkusch.com/courses/gbif/setup/#gbif-account)
  * alternative: use your GitHub account to sign in to GBIF
  * recommended: connect your ORCID account to your GBIF account
* [Zenodo](https://zenodo.org/) - publish your code with a doi
  * alternative 1: use your ORCID account to sign in to Zenodo
  * alternative 2: use your GitHub account to sign in to Zenodo

## Installations

This is a selection of installation instructions for the tools we use in this course. Please make sure to install these tools in time, i.e. **well before** the course starts. Some institutions restrict your ability to install programs on their computers, so you may have to find a solution.

### Necessary

#### OpenRefine

* [How to install and use OpenRefine on various OS (English)](https://openrefine.org/docs)

#### QField App (on your mobile phone!)

* [How to install the QField App on various OS on your mobile phone](https://qfield.org/)

#### QGIS

* [How to install and use QGIS on various OS (English)](https://www.qgis.org/resources/installation-guide/)

#### Rightfield

* [How to install and use RightField on various OS (English)](https://rightfield.org.uk/guide.html)

#### Spreadsheet software

* e.g. [LibreOffice](https://www.libreoffice.org)
* e.g. Windows Excel

### Recommended

We will use a cloud version of **JupyterLab** including both **R** and **Python** kernels. If you prefer to set up Jupyter on your own device, please make sure to prepare a suitable version with all necessary libraries (see below).

#### Git

* [Introduction to version control with Git, using the command line (English, Carpentries)](https://swcarpentry.github.io/git-novice/)
* [Optional (!) Windows shell for Git](https://tortoisegit.org/)

#### Jupyter

* [How to re-use Jupyter Notebooks from the Seasonal School](https://sojwolf.github.io/Jupyter_Workshop_Winterschool_2022/3.1_Reuse_Course_Material.html#)
* [How to install Jupyter on your local computer](https://jupyterlab.readthedocs.io/en/latest/getting_started/installation.html)

#### Python

* [How to install Python on various OSs (English)](https://realpython.com/installing-python/)
* [Installing Python with Packages using Anaconda (English, Carpentries)](https://datacarpentry.org/python-ecology-lesson/index.html#setup)
* [Video Guide to install Python on Windows (English)](https://www.youtube.com/watch?v=kRkkPIA-yEU)
* [Video Guide to install Python on MacOS (English)](https://www.youtube.com/watch?v=nhv82tvFfkM)
* [direct link to python.org (English)](https://www.python.org/downloads/)
* [list of tutorials for beginners on python.org (English)](https://wiki.python.org/moin/BeginnersGuide/NonProgrammers)
* Python library [openpyxl](https://pypi.org/project/openpyxl/)

#### R

* [How to install R and RStudio on various OSs (English)](https://rstudio-education.github.io/hopr/starting.html)
* [Installing R and RStudio (English, Carpentries)](https://datacarpentry.org/R-ecology-lesson/#preparations)
* [Video Guide to install R and RStudio on Windows (English)](https://www.youtube.com/watch?v=9SzKJH93t5o)
* [Video Guide to install R and RStudio on MacOS (English)](https://www.youtube.com/watch?v=I5WIMX4LK8M)
* [direct link to RStudio, contains link to R](https://posit.co/download/rstudio-desktop/)
* R packages:
  * pkgs <- c( <br>
              "rgbif",             		                  ## access species data <br>
	             "data.table", "doSNOW",			 		            ## taxonomic harmonization (incl. rgbif) <br>
            	)<br>
install.packages(pkgs, dependencies = TRUE)
