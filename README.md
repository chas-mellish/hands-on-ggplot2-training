# “Hands–On Data Visualization with ggplot2”

### Material for the Material for the Pearson Live Training Session for O’Reilly

To get a copy of all the material, clone this repository to a directory of your choice.  
If you are not familiar how to clone a repository, have a look [here](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository-from-github/cloning-a-repository) or download and unpack [this zip folder]().  
  
To run any of the materials locally on your own machine, you will need the following:

#### Installation

- A recent version of **R** (download from [here](https://cloud.r-project.org/)) 
- A recent version of **RStudio**, (download from [here](https://rstudio.com/products/rstudio/download/#download))
- The following R packages: 
  + [`tidyverse`](https://www.tidyverse.org/) (includes [`ggplot2`](https://ggplot2.tidyverse.org/))
  + [`ggrepel`](https://ggrepel.slowkow.com/)
  + [`ggtext`](https://wilkelab.org/ggtext/)
  + [`patchwork`](https://patchwork.data-imaginist.com/)
  + [`ggforce`](https://ggforce.data-imaginist.com/)
  + [`ragg`](https://ragg.r-lib.org/)
  + [`magick`](https://docs.ropensci.org/magick/)

You can install all required R packages at once by running the following code in the R command pane:

```{r install, eval=FALSE, echo=TRUE}
# Package names
packages <- c("tidyverse", "ggrepel", "ggtext", "patchwork", "ragg", "magick")
install.packages(packages)
```

To run the code, open up Rstudio and copy–paste the code in **console windonw** and hit enter. Several messages should pop up. Scan these messages that are returned for errors and troubleshoot them if necessary. Warnings and other informational messages can be ignored.

#### Starting with the Training

Double-click on the `hands-on-ggplot2.Rproj` file. Rstudio opens up with the working directory set to the same folder. Now, you can open any script in the files pane—we start with `01-grammar.Rmd`.
