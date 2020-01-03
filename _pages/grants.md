---
title: "Grants"
permalink: /grants/
author_profile: true

---

{% include base_path %}    

Further info on my research grants can be found at my [ORCID profile](http://orcid.org/0000-0002-0732-9154).

Deep Learning and likelihood-free Bayesian inference for intractable stochastic models
======
For years 2020-2024 I have received a combined 8.7 million SEK from [CHAIR](https://www.chalmers.se/en/centres/chair/news/Pages/Five-PhD-student-positions-funded-within-deep-neural-networks-and-machine-learning.aspx) (Chalmers AI Research Centre) and the Swedish Research Council (Vetenskapsrådet 2019-03924) to research on possibilities offered by deep neuronal networks to facilitate approximate Bayesian inference, such as approximate Bayesian computation (ABC). An initial motivating work is [published here](http://proceedings.mlr.press/v97/wiqvist19a.html). We plan to extend the methodology to accommodate state-space modelling, and generally non iid data, with particular emphasis on inference for stochastic differential equations.
    
Likelihood-free methods, approximate Bayesian computation and stochastic modelling of protein folding
======

For years 2014-2018 I have been granted 3,360,000 SEK (euro 380,000) from the Swedish research council for the interdisciplinary project 
"Statistical Inference and Stochastic Modelling of Protein Folding" ([here is an accessible description](http://www.maths.lu.se/index.php?id=85411)) for which I am the principal investigator. This is a collaboration with [Kresten Lindorff-Larsen](http://www1.bio.ku.dk/english/research/bms/research/sbinlab/groups/kll/) (Dept. Biology, Copenhagen University) 
and [Julie Lyng Forman](http://biostat.ku.dk/staff_/?pure=en/persons/164838) (Dept. Biostatistics, Copenhagen University).
In a preliminary work with Julie Forman we have considered the problem of estimating folding rates for some protein having a coordinate 
switching between the folded and unfolded state. We have proposed a new dynamical model (expressed as sum of two diffusions) and a 
fast computational strategy based on Approximate Bayesian Computation (ABC). ABC could be used in place of 
exact Bayesian inference, when large datasets do not allow for the latter. See also my [research page](/research) for further details.

Study Group in Bayesian Methods
======

In 2015 I have been principal investigator for the creation of a [study group in Bayesian methods](http://www.maths.lth.se/matstat/staff/umberto/bayes-asg.html) at Lund University (SEK 100,000). 
The study group has organized a number of well attended acivities during year 2016 for the promotion and understanding of Bayesian modelling. 
    

A software for fitting general state–space multidimensional models
======

In 2013 the Faculty of Science at Lund University awarded me 100,000 SEK (euro 12,000) for the project 
“A software for fitting general state–space multidimensional models”. I coded [abc-sde](http://sourceforge.net/projects/abc-sde/) which 
is a MATLAB package performing Approximate Bayesian Computation to estimate parameters in stochastic models having dynamics defined by 
stochastic differential equations (SDEs). Both one- and multi-dimensional SDE systems are supported and partially observed systems are 
easily accommodated. Variance components for the "measurement error" affecting the data/observations can be estimated. 
A 50-pages Reference Manual is provided with two case-studies implemented and discussed. See also [my software page](/software). 
