Locally developed:
E:\Projects\GitHub\tree-height-maps-meta

Code push
D:\GitHub\LinkedIn_Code\tree-height-maps-meta\Python


# R - PACKAGES
#------------

install.packages("devtools")
install.packages("pacman")

devtools::install_github("TESS-Laboratory/chmloader")
devtools::install_github("rstudio/leaflet")

pacman::p_load(
    chmloader,
    terra,
    sf,
    maptiles,
    classInt,
    tidyverse,
    tidyterra,
    leaflet,
    htmlwidgets
)

Python packages
