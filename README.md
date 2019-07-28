# Vaccine

Aplicación Shiny para mostrar el modelo SIR con un compartimento adicional para vacunas

Puede ejecutar la versión **en español** localmente en su ordenador con 

```{r}
shiny::runGitHub("fjgoro88/Vaccines")
```

Requiere de los sigueintes paquetes R instalados:

```{r}
install.packages("shiny")
install.packages("deSolve")
install.packages("cowplot")
install.packages("ggplot2")
install.packages("tidyverse")
install.packages("ggrepel")
install.packages("shinydashboard")
```
o los requiere lanzados:

```{r}
library("shiny")
library("deSolve")
library("cowplot")
library("ggplot2")
library("tidyverse")
library("ggrepel")
library("shinydashboard")
```
