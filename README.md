ShinyVaccine
Shiny app to show the SIR model with an additional vaccine compartment

You can run the English language version locally on your computer with

shiny::runGitHub("fjgoro88/Vaccines")
it requires that you have the following packages installed:

library("shiny")
library("deSolve")
library("cowplot")
library("ggplot2")
library("tidyverse")
library("ggrepel")
library("shinydashboard")
