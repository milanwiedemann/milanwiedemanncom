---
title: Software
disable_comments: true
---

## [`library(suddengains)`](https://milanwiedemann.github.io/suddengains/)

I designed this R package together with my colleagues [Graham Thew](https://twitter.com/drgrahamthew) and [Richard Stott](https://twitter.com/DrRichardStott) and supervisor [Anke Ehlers](https://www.psy.ox.ac.uk/team/anke-ehlers) to make the research of sudden gains in longitudinal data (see Tang & DeRubeis, [1999](https://doi.org/10.1037/0022-006X.67.6.894)) as easy and **reproducible** as possible.
No more looking into the :crystal_ball: to figure out what was done.
Find out more about this project in our preprint on [PsyArXiv](https://psyarxiv.com/2wa84/) or check out the code on [GitHub](https://github.com/milanwiedemann/suddengains). 

<img src="/gifs/r-suddengains.gif"/>

## [`library(lcsm)`](https://milanwiedemann.github.io/lcsm/)

I started working on this project to better understand how latent change score modeling works. 
This R package combines the strengths of other packages like [lavaan](http://lavaan.ugent.be/), [broom](https://CRAN.R-project.org/package=broom), and [semPlot](https://CRAN.R-project.org/package=semPlot) by generating lavaan syntax that helps these packages work together efficiently. 
The code and some more details about the functionality are available on [GitHub](https://github.com/milanwiedemann/lcsm).


## [`runApp(shinychange)`](https://milanwiedemann.shinyapps.io/shinychange/)

The main aim of this interactive shiny tutorial is to show how different univariate and bivariate latent change score models (lcsm) can be implemented in R using [lavaan](http://lavaan.ugent.be/) syntax (Rosseel, [2012](http://www.jstatsoft.org/v48/i02)).
The underlying functions of this shiny application come from the [`lcsm`](https://milanwiedemann.github.io/lcsm/) R package.
At the moment it is possible to **Generate lavaan Syntax** for different model specifications and varying time points, **Simulate Data** to explore the effect of different parameters, **Fit Models** using example datasets, and create **Longitudinal Plots** and simplified **Path Diagrams** to visualise data and model specifications.

<img src="/gifs/r-shinychange-low.gif"/>
