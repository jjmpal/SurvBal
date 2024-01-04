# SurvBal

## Overview
SurvBal enables the selection of microbiome balances in relation to censored
    survival and time-to-event outcomes which are of considerable
    interest, particularly in many biomedical studies. The most common Cox
    proportional hazards and standard parametric survival (including
    accelerated failure time) models are included in the package, which
    are used in combination with step-wise selection procedures to
    identify the optimal associated ratio of the geometric means of two
    groups of taxa’s relative abundances.

## Installation Guide

You can install SurvBal from GitHub by:

```
# install.packages("devtools")
devtools::install_github("yinglia/SurvBal")
```

## Resources


All functions in `SurvBal` are described in the manual: 

https://github.com/yinglia/SurvBal/blob/main/SurvBal_0.1.0.pdf

The vignette of `SurvBal` includes the instructions to run the method on the example dataset, with the input and output clearly described, which can be found at: 

https://yinglia.github.io/SurvBal-Vignette/

A Shiny app of `SurvBal`: 

https://yinglistats.shinyapps.io/shinyapp-survbal/
