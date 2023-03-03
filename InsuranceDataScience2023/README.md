# Py-shiny for Reinsurance: ready or not, here we come

### Roland A. Schmid, Mirai Solutions
### Paula K. Ando, Mirai Solutions

--------

<!-- Many of us have gotten accustomed to the ease and flexibility of Shiny apps over the past several years. For Python lovers it has often been a tough choice between a preferred framework like Shiny but having to use R, as opposed to being able to use Python but having to work with a framework less appealing than Shiny. -->

**Abstract**: Shiny for Python has been launched, and while it is officially still in **alpha** stage, many people are experimenting with it and we can expect rapid progress.

With corporate reinsurance clients interested in extending and modernizing solutions to **explore, accumulate and manage risks in interactive and responsive ways**, we decided to develop a freely available open-source service through a Py-Shiny app. This could serve as a basis and hopefully provide some common functionality out-of-the-box, while raising and solving current shortcomings of Py-Shiny along the way and thus helping to accelerate its development and maturing process. Python is typically the first-choice language for scalable enterprise-grade solutions in the GIS-domain as well as when it comes to working with large simulation data in a framework like (Py-)Spark.

We show that even now Shiny for Python is already in a very useable state, although there is still a lot of more specific functionality and tooling available in Shiny for R, which hasn't been provided to Python yet.

The core functionality of our initial **Risk Explorer** app / service shall help to visualize, assess, communicate and understand risks and exposure, covering the following features:

- interactively create and modify (reshape) custom (ad-hoc) hazard footprints, download footprint data
- upload scenario (footprint) data and visualize
- upload exposure (location) data and visualize
- calculate and download distances to center of footprints / scenarios
- associate / amend details: define intensities, vulnerabilities / damage ratios, probabilities

In addition we aim to provide and integrate a direct connection to the data of the United States Geological Survey (USGS).

During this talk we introduce **Risk Explorer** illustrating an **effective use-case based on the US terrorism scenarios relevant under ORSA**.

**Keywords**: Reinsurance, Exposure, Scenario, Risk Insight, SolvencyII, ORSA, Shiny, Python, Leaflet

### References

1. Posit Software, PBC (RStudio). https://shiny.rstudio.com/py/.

2. Mirai Solutions GmbH. https://github.com/miraisolutions/PublicTalks/tree/master/InsuranceDataScience2023.  
*Abstract plus screenshots of current work-in-progress version of the app.*
