# Reanalysis-Cross-et-al-2012-using-event-history-analysis

We use discrete-time event history analysis to reanalyze the behavioral data (response time and accuracy) reported by 
Emily S. Cross, Nichola Rice Cohen, Antonia F. de C. Hamilton, Richard Ramsey, George Wolford, Scott T. Grafton (2012).
Physical experience leads to enhanced object perception in parietal cortex: Insights from knot tying.
Neuropsychologia, 50, Issue 14, 3207-3217. https://doi.org/10.1016/j.neuropsychologia.2012.09.028.

# What is the easiest way to access this project?

If you want to see and work with the code, then:

1. Clone, fork or download the project from github to your local machine.
See this link for the difference between cloning and forking. https://github.com/orgs/community/discussions/35849

2. Open the Reanalysis-Cross-et-al-2012-using-event-history-analysis.Rproj file and renv() will automatically bootstrap itself.

3. Use renv::restore() to install all of the packages. Say yes.

4. At this point, you can use the project with the same package versions that are stored in the renv.lock file.

Note: you can completely ignore the "install_packages.Rmd" file.

# What are the main project files?

## Preregistration on OSF using simulated data

We preregistered our intended reanalysis using a Bayesian event history analysis on the OSF. The following two files are relevant:

* sim_descriptives.Rmd

In sim_descriptives.Rmd we generate a fake data set with the same structure as the one reported by Cross et al. (2012) and calculate the descriptive statistics for a discrete-time event history analysis, as part of our (pre)registration on the OSF.

* sim_inferential.Rmd

In sim_inferential.Rmd we fit Bayesian hazard models to the simulated data set, and calculate the effects of interest, as part of our (pre)registration on the OSF.

## Analysis of experimental data reported by Cross et al. (2012)

* knot_descriptives.Rmd

Calculates descriptive statistics for the behavioral data of Cross et. al (2012).

* knot_inferential.Rmd

In knot_inferential.Rmd we fit Bayesian hazard models to the (person-trial-bin) data set, and calculate the effects of interest, following our (pre)registration on the OSF.


