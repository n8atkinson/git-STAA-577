GitHub Repository for STAA 577
-----------
Slides, code, cheat sheets, and RStudio lab notebooks for 
"Applied Machine Learning" course Spring 2018


### Datasets for STAA 577

* **nyflights13**
  + new york city airport flight data from 2013 (**must install**)
  + install with `install.packages("nyflights13", repos="http://cran.rstudio.com")`
* **iris**
  + classic iris flower data set from Fisher (**comes with R installed**)
* **mtcars & mtcars2**
  + mtcars: USA motor trend cannonical data set (**comes with R installed**)
  + mtcars2: An extension of mtcars by Max Kuhn with updated data and more features (**see Labs/data/mtcars2.rda**)
* **Ames Data**
  + An extension of Ames, Iowa housing data set by Max Kuhn (**must install**)
  + install with `install.packages("AmesHousing", repos="http://cran.rstudio.com")`
* **OkC**
  + predicting STEM and other for various predictors (**see Labs/data/okc.rda**)
  + Contains several types of fields:
    - a number of open text essays related to interests and personal descriptions
    - single choice type fields, such as profession, diet, gender, body type, etc.
    - multiple choice data, including languages spoken, etc.
    - We will try to predict whether someone has a profession in the 
    STEM fields (science, technology, engineering, and math) using a 
    random sample of the overall dataset.


### Hadley Wickham Book
[R for Data Science](http://r4ds.had.co.nz/)


### Cheatsheets:
RStudio [cheatsheets](https://www.rstudio.com/resources/cheatsheets/)


### Modeling Framework
![review-resamp-cache](https://user-images.githubusercontent.com/25203086/38456246-cbb2f6f4-3a3f-11e8-8b2e-135b62a07cc0.png)


### Memory Usage and `rsample`:
The [rsample](https://topepo.github.io/rsample/) package is smarter than you might think.


### Vignettes:
  * [dplyr](https://cran.r-project.org/web/packages/dplyr/vignettes/dplyr.html)
  * [tidyr](http://cran.r-project.org/web/packages/tidyr/vignettes/tidy-data.html)


### What is the Tidyverse?
Information about the
  * The [tidyverse](https://www.tidyverse.org/)
  * The tidyverse [packages](https://www.tidyverse.org/packages/)
  * Converting to the [Tidyverse](http://www.significantdigits.org/2017/10/switching-from-base-r-to-tidyverse/)

