<!-- README.md is generated from README.Rmd. Please edit that file -->
FishGraph 2.0
=============

FishGraph is a set of `R` functions that generates diagnostics and data visualizations from stock assessment model output. These functions are designed to process model output from the **Beaufort Assessment Model (BAM)**. Further information on the details of the *BAM* can be found in ([Williams and Shertzer, 2015](http://docs.lib.noaa.gov/noaa_documents/NMFS/SEFSC/TM_NMFS_SEFSC/NMFS_SEFSC_TM_671.pdf))

Installation
------------

The package can be installed using the `install_github()` function from the `devtools` library.

    # To install the devtools package
    install.packages("devtools")

    # Load library and install directly from the repo.
    library(devtools)
    devtools::install_github("rcheshire/FishGraph")

Alternatively, the package can be installed locally from the repository source files.

    install.packages("C://Location of files//FishGraph_2.0.tar.gz, 
                     repos = NULL, type="source")

Application
-----------

Once installed the package offers a series of functions for model diagnostics and evaluations. A full list of available functions can be obtained using:

    library(FishGraph)
    ls(pos = "package:FishGraph")

`FishGraph 2.0` includes several updated functions. Additionally, version 2.0 includes four new functions: `Cohort.plots`, `Phase.plots`, `Parm.plots`, and `Bound.vec.plots`. All functions can be tested using the included data set `data(gag)` which is distributed with the package.

A comprehensive description of all included functions and examples of their graphical output is available in the **NOAA Technical Memorandum NMFS-SEFSC-684** installed in the "doc" folder of the package or online ([Prager et al., 2016](http://docs.lib.noaa.gov/noaa_documents/NMFS/SEFSC/TM_NMFS_SEFSC/NMFS_SEFSC_TM_684.pdf)).

Notice of nonendorsement
------------------------

The National Marine Fisheries Service (NMFS) does not approve, recommend or endorse any proprietary product or material mentioned in this product or related publications. No reference shall be made to NMFS, or to this publication furnished by NMFS, in any advertising or sales promotion which would imply that NMFS approves, recommends, or endorses any proprietary product or proprietary material mentioned herein which has as its purpose any intent to cause directly or indirectly the advertised product to be used or purchased because of this NMFS product.
