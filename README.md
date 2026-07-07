# A hierarchical model to evaluate pest treatments from prevalence and intensity data
Armand Favrot, David Makowski
2024-01-09

### Citation

Armand Favrot and David Makowski (January 2024). A hierarchical model to evaluate pest treatments from prevalence and intensity data. Computo.
<https://doi.org/10.57750/6cgk-g727>

### Badges

[![build and
publish](https://github.com/computorg/published-202312-favrot-hierarchical/actions/workflows/build.yml/badge.svg)](https://github.com/computorg/published-202312-favrot-hierarchical/actions/workflows/build.yml)
[![reviews](https://img.shields.io/badge/review-report-blue)](https://github.com/computorg/published-202312-favrot-hierarchical/issues?q=is%3Aopen+is%3Aissue+label%3Areview)
[![SWH](https://archive.softwareheritage.org/badge/origin/https://github.com/computorg/published-202312-favrot-hierarchical)](https://archive.softwareheritage.org/browse/origin/?origin_url=https://github.com/computorg/published-202312-favrot-hierarchical)
[![DOI:10.57750/6cgk-g727](https://img.shields.io/badge/DOI-10.57750%2F6cgk--g727-034E79.svg)](https://doi.org/10.57750/6cgk-g727)
[![Creative Commons
License](https://i.creativecommons.org/l/by/4.0/80x15.png)](http://creativecommons.org/licenses/by/4.0/)

### Authors’ affiliations

- [Armand Favrot](https://fr.linkedin.com/in/armand-favrot-469014150) (MIA Paris-Saclay, INRAE AgroParisTech Université Paris-Saclay, France)
- [David Makowski](https://mia-ps.inrae.fr/david-makowski) (MIA Paris-Saclay, INRAE AgroParisTech Université Paris-Saclay, France)

### Abstract

In plant epidemiology, pest abundance is measured in field trials using
metrics assessing either pest prevalence (fraction of the plant
population infected) or pest intensity (average number of pest
individuals present in infected plants). Some of these trials rely on
prevalence, while others rely on intensity, depending on the protocols.
In this paper, we present a hierarchical Bayesian model able to handle
both types of data. In this model, the intensity and prevalence
variables are derived from a latent variable representing the number of
pest individuals on each host individual, assumed to follow a Poisson
distribution. Effects of pest treaments, time trend, and between-trial
variability are described using fixed and random effects. We apply the
model to a real data set in the context of aphid control in sugar beet
fields. In this data set, prevalence and intensity were derived from
aphid counts observed on either factorial trials testing different types
of pesticides treatments or field surveys monitoring aphid abundance.
Next, we perform simulations to assess the impacts of using either
prevalence or intensity data, or both types of data simultaneously, on
the accuracy of the model parameter estimates and on the ranking of
pesticide treatment efficacy. Our results show that, when pest
prevalence and pest intensity data are collected separately in different
trials, the model parameters are more accurately estimated using both
types of trials than using one type of trials only. When prevalence data
are collected in all trials and intensity data are collected in a subset
of trials, estimations and pest treatment ranking are more accurate
using both types of data than using prevalence data only. When only one
type of observation can be collected in a pest survey or in an
experimental trial, our analysis indicates that it is better to collect
intensity data than prevalence data when all or most of the plants are
expected to be infested, but that both types of data lead to similar
results when the level of infestation is low to moderate. Finally, our
simulations show that it is unlikely to obtain accurate results with
fewer than 40 trials when assessing the efficacy of pest control
treatments based on prevalence and intensity data. Because of its
flexibility, our model can be used to evaluate and rank the efficacy of
pest treatments using either prevalence or intensity data, or both types
of data simultaneously. As it can be easily implemented using standard
Bayesian packages, we hope that it will be useful to agronomists, plant
pathologists, and applied statisticians to analyze pest surveys and
field experiments conducted to assess the efficacy of pest treatments.
