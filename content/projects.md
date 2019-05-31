---
title: Projects
disable_comments: true
---

I'm interested in the processes of change in evidence-based psychological therapies for mental health problems.
In my PhD I'm looking at processes of treatment effects in cognitive therapy for Posttraumatic Stress Disorder. 
To learn more about how the treatment works I analyse changes in variables that are thought to drive symptom change according to cognitive theories of PTSD.
My two main projects are looking at *sudden gains* and *mediation of clinical improvement* during treatment.

During the course of my PhD I started to feel the superpowers of R Studio :rocket: and now use it for all my analyses and most of my writing.
As a results I've designed R packages to make my life a bit easier. 

### *suddengains*

I designed this package together with my colleagues [Graham Thew](https://twitter.com/drgrahamthew) and [Richard Stott](https://twitter.com/DrRichardStott) and supervisor [Anke Ehlers](https://www.psy.ox.ac.uk/team/anke-ehlers) to make the research of sudden gains as easy and **reproducible** as possible.
No more looking into the :crystal_ball: to figure out what was done.
Below you see an illustration of how to use the package to identify sudden gains and create a plot from scratch in real time, sit back and :popcorn:. 
We describe more about the background and why we think this package might be useful in our preprint on [PsyArXiv](https://psyarxiv.com/2wa84/). 
You can check out the code on [GitHub](https://github.com/milanwiedemann/suddengains). 

<img src="/gifs/r-suddengains.gif"/>

### *lcsm*

While learning about latent change score (LCS) models for one of my research projects I was quite confused initially and didn't know where to start.
Fortunately there are great papers (e.g., Grimm et al. ([2012](https://doi.org/10.1080/10705511.2012.659627)), books (e.g., Grimm, Ram & Estabrook ([2017](https://www.guilford.com/books/Growth-Modeling/Grimm-Ram-Estabrook/9781462526062)), and online tutorials (e.g., [here](https://quantdev.ssri.psu.edu/tutorials/growth-modeling-chapter-17-multivariate-latent-change-score-models)) that helped me understand some of the details.

I've created some functions to make it easier for me to use LCS models and avoid mistakes writing the [lavaan](http://lavaan.ugent.be/) syntax.
I'm also working on tools that combine the strengths of other R packages like [broom](https://CRAN.R-project.org/package=broom) and [semPlot](https://CRAN.R-project.org/package=semPlot) when using LCS models.
At the moment I'm writing a short tutorial on how I use these packages together in a simple workflow that worked great for me.
You can find the code and some more details on [GitHub](https://github.com/milanwiedemann/lcsm).

<img src="/gifs/r-lcsm-uni.gif"/>
