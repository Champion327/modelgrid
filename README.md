
<!-- README.md is generated from README.Rmd. Please edit that file -->
modelgrid <img src="man/figures/mglogo.png" align="right" />
============================================================

[![Travis-CI Build Status](https://travis-ci.org/thomasp85/scico.svg?branch=master)](https://travis-ci.org/thomasp85/scico) <!-- [![AppVeyor Build Status](https://ci.appveyor.com/api/projects/status/github/thomasp85/scico?branch=master&svg=true)](https://ci.appveyor.com/project/thomasp85/scico) --> <!-- [![CRAN_Release_Badge](http://www.r-pkg.org/badges/version-ago/scico)](https://CRAN.R-project.org/package=scico) --> <!-- [![CRAN_Download_Badge](http://cranlogs.r-pkg.org/badges/scico)](https://CRAN.R-project.org/package=scico) -->

This is a small package to provide access to the colour palettes developed by Fabio Crameri and published at <http://www.fabiocrameri.ch/colourmaps.php>. It uses more or less the same api as [`viridis`](https://github.com/sjmgarnier/viridis) and provides scales for [`ggplot2`](https://github.com/tidyverse/ggplot2) without requiring `ggplot2` to be installed.

Installation
------------

<!-- `scico` can be installed from CRAN with `install.packages('scico')`. If you want -->
<!-- the development version then install directly from GitHub: -->
<!-- ```{r, eval=FALSE} -->
<!-- # install.packages("devtools") -->
<!-- devtools::install_github("thomasp85/scico") -->
<!-- ``` -->
<!-- ## Palettes -->
<!-- `scico` provides 17 different palettes, all of which are perceptually uniform  -->
<!-- and colourblind safe. An overview can be had with the `scico_palette_show()` -->
<!-- function: -->
<!-- ```{r} -->
<!-- library(scico) -->
<!-- scico_palette_show() -->
<!-- ``` -->
<!-- Once you've decided on a palette you can generate colour values using the  -->
<!-- `scico()` function: -->
<!-- ```{r} -->
<!-- scico(30, palette = 'lapaz') -->
<!-- ``` -->
<!-- ## ggplot2 support -->
<!-- `scico` provides relevant scales for use with `ggplot2`. It only suggests  -->
<!-- `ggplot2` in order to stay lightweight, but if `ggplot2` is available you'll  -->
<!-- have access to the `scale_[colour|fill]_scico()` functions: -->
<!-- ```{r, message=FALSE} -->
<!-- library(ggplot2) -->
<!-- volcano <- data.frame( -->
<!--   x = rep(seq_len(ncol(volcano)), each = nrow(volcano)), -->
<!--   y = rep(seq_len(nrow(volcano)), ncol(volcano)), -->
<!--   height = as.vector(volcano) -->
<!-- ) -->
<!-- ggplot(volcano, aes(x = x, y = y, fill = height)) +  -->
<!--   geom_raster() +  -->
<!--   scale_fill_scico(palette = 'davos')  -->
<!-- ``` -->
