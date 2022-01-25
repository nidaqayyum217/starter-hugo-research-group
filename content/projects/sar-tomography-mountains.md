+++
# Date this page was created.
date = 2019-12-01T00:00:00

# Project title.
title = "Differential SAR tomography in mountainous areas"

# Project summary to display on homepage.
summary = "This project seeks to facilitate the application of synthetic aperture radar (SAR) tomography as an add-to to persistent scatterer interferometry (PSI) in mountainous areas. A critical issue is to correct the atmosphere-induced phase disturbances alongside tomographic focusing."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "projects/tomography-mountains.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
#tags = ["SAR tomography as an add-on to PSI"]
#tags = [""]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "projects/sar-tomography-swiss-alps.png"
caption = "Scatterers detected with tomography/PSI. The color coding represents the estimated height. Enclosed in the white boundary are single scatterers obtained with tomography on the mountainside, as shown in the left subfigure and a zoom in the right subfigure. The middle figure shows the scatterers obtained with PSI. In this case, no scatterers are detected along the mountainside (the mountain being in layover).  For details, [follow the article: TGARS 2018](https://www.researchgate.net/publication/327314844_A_Case_Study_on_the_Correction_of_Atmospheric_Phases_for_SAR_Tomography_in_Mountainous_Regions)"

+++
*This is an ongoing project in collaboration with [Dr. Othmar Frey](https://eo.ifu.ethz.ch/the-group/people/person-detail.NjQ4Mzc=.TGlzdC8zNTIyLC0zMTYzOTY1OTY=.html). Initial results of the project are part of my doctoral research at [ETH Zurich](http://www.eo.ifu.ethz.ch/forschung/applications.html#par_textimage_1567484257).*

In mountainous areas, such as the Swiss alpine regions, drastic height variations result in frequent layovers in SAR imagery. These layovers are rejected during typical persistent scatterer interferometric (PSI) analyses. This project investigates the use of differential SAR tomography as an add-on to PSI to resolve layovers of temporally coherent scatterers and simultaneously measure their average deformation velocity. Due to the extremely rugged topography, the local atmospheric conditions and propagation paths through the troposphere may strongly vary spatially. This project also investigates the feasibility of advanced interpolation methods for the correction of the atmosphere-induced phase disturbances in the interferometric phase.
