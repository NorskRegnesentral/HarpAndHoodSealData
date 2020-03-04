<img src="Scripts/Fig/Logos.png" align="right" height="50px"/>

# Harp and Hooded seal data for the West Ice and the East Ice

### Updated data on biological parameters, catch data, pup production estimates, and priors

#### T. A. Øigård and M. Biuw

# Overview
This folder contains data which can be analyzed by the `rSPAMM` package.

To download this data install the [rSPAMM](https://www.github.com/NorskRegnesentral/rSPAMM)-package and run:
```{r}
downloadData()
```

When you run this function you can run it as it is and you will be asked to specify a folder where the data is stored. You can even decide to create a new folder if needed. If you already have prepared a folder for where to download the data and has set working directory to this folder you should use the option `chooseFolder = FALSE`, i.e.,
```{r}
downloadData(chooseFolder = FALSE)
```
After downloading the data repository you will have a **Data** folder and a **Scripts** folder. The **Data** folder contains the various harp and hooded seal data and the **Scripts** folder contains useful examples on how to perform a complete assessment.


For details about these data look at the vignette in the `rSPAMM` package.
