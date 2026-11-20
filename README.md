# Testing functional phylosymbiosis in EHI data

Analyses testing functional phylosymbiosis using Earth Hologenome Initiative data.

## Analysis procedures

The raw code used for data analysis is in the **Rmd** files stored in the root directory of this repository, while the bookdown-rendered webbook is available at:

https://irene-martinez-garcia.github.io/testing_functional_phylosymbiosis_ehi/

While the webbook provides a user-friendly overview of the procedures, analyses can be directly reproduced using the Rmd documents. Note that code chunks that require heavy computation can be turned off using 'eval=FALSE'. To re-render the webbook, you can use the following code:

```r
library(bookdown)
library(htmlwidgets)
library(webshot)

render_book(input = ".", output_format = "bookdown::gitbook", output_dir = "docs")
```

Then enable GitHub Pages (Settings > Pages > branch `main`, folder `/docs`).
