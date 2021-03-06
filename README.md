# Joint Models Workshop Cincinnati 2018


This repository consist of all the material (slides, practicals and app) for the workshop on **"Joint Modelling of Longitudinal 
and Survival Data: Tools to Evaluate Exposures and Predict Outcome Across the Lifespan"**.
\
The packages that are needed for this workshop are: 
- [survival](http://cran.r-project.org/package=survival)
- [nlme](http://cran.r-project.org/package=nlme)
- [JMbayes](http://cran.r-project.org/package=JMbayes)
- [lattice](http://cran.r-project.org/package=lattice)
- [splines](http://cran.r-project.org/) 
- [shiny](http://cran.r-project.org/package=shiny)


These packages can be installed using the following function call (this needs to be done only once):

```r
install.packages(c("survival", "nlme", "JMbayes", "lattice", "splines", "shiny", "shinyWidgets"), 
                    dependencies = TRUE)
```

Then they can be loaded with:
```r
lapply(c("survival", "nlme", "JMbayes", "lattice", "splines", "shiny", "shinyWidgets"), 
          library, character.only = TRUE)

```

To run the app you will need to run the following:

```r
runGitHub("JointModelsWorkshopCincinnati2018", "ERandrinopoulou", subdir = "shiny app/")
 ```

You can also get the app from: https://emcbiostatistics.shinyapps.io/Joint_Models_Workshop_Cincinnati2018/