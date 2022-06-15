## Highlighted visualizations

<img src="https://raw.githubusercontent.com/Jon-Does-Stats/project-thesis-multinomial/main/figures/marginal_covariate_effects_beta.png" width=675>

<img src="https://raw.githubusercontent.com/Jon-Does-Stats/project-thesis-multinomial/main/figures/reflectance_surface_aspen.png" width=675>

<img src="https://raw.githubusercontent.com/Jon-Does-Stats/project-thesis-multinomial/main/figures/reflectance_surface_locust.png" width=675>

<img src="https://raw.githubusercontent.com/Jon-Does-Stats/project-thesis-multinomial/main/figures/reflectance_surface_oak.png" width=675>

<img src="https://raw.githubusercontent.com/Jon-Does-Stats/project-thesis-multinomial/main/figures/spatial_process_aspen.png" width=675>

<img src="https://raw.githubusercontent.com/Jon-Does-Stats/project-thesis-multinomial/main/figures/spatial_process_locust.png" width=675>

<img src="https://raw.githubusercontent.com/Jon-Does-Stats/project-thesis-multinomial/main/figures/spatial_process_oak.png" width=675>

<img src="https://raw.githubusercontent.com/Jon-Does-Stats/project-thesis-multinomial/main/figures/zoom_spat_process_aspen.png" width=675>

<img src="https://raw.githubusercontent.com/Jon-Does-Stats/project-thesis-multinomial/main/figures/zoom_spat_process_locust.png" width=675>

<img src="https://raw.githubusercontent.com/Jon-Does-Stats/project-thesis-multinomial/main/figures/zoom_spat_process_oak.png" width=675>

<img src="https://raw.githubusercontent.com/Jon-Does-Stats/project-thesis-multinomial/main/figures/reflectance_surface_day_slice_uncertainty.png" width=675>


## Abstract

Accurate information on the existing distribution of tree species is used as proxy for the health of an ecosystem, as a currency of international environmental treaties, and as a necessary planning tool for forest preservation and rehabilitation, to name just a few of its applications. However, obtaining timely species-level detail across large geographic regions is prohibited by practical challenges and costs to data collection.  The extensive coverage and short revisit interval of remote sensing data collected by airborne or satellite instruments could be a critical component of a solution to this problem.  In recent years, the public availability of remote sensing data from moderate resolution satellites like the European Space Agency's Sentinel-2 system has also increased dramatically, making the prospect of utilizing these data more appealing. These remote sensing data sources are measured at a spatial resolution that is inadequate for accurate species-level classification, but ecologists have already begun exploring methods to augment their analyses with the incorporation of moderate-resolution remote sensing data from across different dates or by considering environmental covariates suspected to have relationships with the distributions of species.  This thesis introduces a species classification model that facilitates these augmentations and many others.  A Bayesian hierarchical model framework enables the separate specification of the observed reflectance process and the species occurrence process. Measurement error and temporal autocorrelation are accounted for in the reflectance sub-model, and its form allows for between-site heterogeneity in measurement dates; a rare freedom in existing research.  The species sub-model takes inspiration from ecological joint species distribution models (JSDMs) and estimates the probabilities of all species occurring at each site, preserving between-species relationships inside the model. The specification of the species sub-model also allows covariate effects and the features of the spatial autocorrelation process to vary by species.   To demonstrate the elevated process-level understanding facilitated by such a model, it is applied to a dataset consisting of every cloud-free pixel corresponding to 60 known reference sites in a small study area measured by the Sentinel-2 imaging constellation and collected in the calendar year 2020.  The dataset was sourced from 132 different daily remote sensing images with an average revisit time of 2.8 days at the site level, qualifying it as the most temporally rich time series analyzed within the existing research focused on tree species classification using remote sensing data.  My results confirm the existence of spatial autocorrelation in forest-occupied landscapes, they illustrate how the effect of an abiotic variable on species membership probabilities can vary by species and affect some species but not others, and they reveal that late autumn and winter images hold identifiable spectral profiles when analyzed as a time series.  These results feature both novel and familiar visualizations to demonstrate model output for prospective adopters, and as an application of Bayesian modeling, use draws from the posterior distributions of parameters to more clearly communicate the uncertainty associated with a selection of estimates. 
