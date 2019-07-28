# Vaccine

Shiny app to show the SIR model with an additional vaccine compartment

You can run the **English** language version locally on your computer with 

```{r}
shiny::runGitHub("fjgoro88/Vaccines")
```

it requires that you have the following packages installed:

```{r}
install.packages("shiny")
install.packages("deSolve")
install.packages("cowplot")
install.packages("ggplot2")
install.packages("tidyverse")
install.packages("ggrepel")
install.packages("shinydashboard")
```
or it requires that they are summoned:
```{r}
library("shiny")
library("deSolve")
library("cowplot")
library("ggplot2")
library("tidyverse")
library("ggrepel")
library("shinydashboard")
```
