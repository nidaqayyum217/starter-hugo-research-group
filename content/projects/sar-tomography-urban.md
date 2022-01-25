+++
# Date this page was created.
date = 2019-12-10T00:00:00

# Project title.
title = "SAR for deformation assessment & infrastructure monitoring in urban areas"

# Project summary to display on homepage.
summary = "The goal of this project is to integrate synthetic aperture radar (SAR) tomography and persistent scatterer interferometry (PSI)  into a combined processing framework, primarily to resolve the layovers that are rejected in the PSI processing."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "projects/torre-agbar.png"

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
image = "projects/diagonal-mar.png"
caption = "3-D plot of scatterers on Torre Agbar tower in Barcelona, detected with SAR tomography. Extended phase models have been used to model scatterer elevation, average displacement in the line of sight and motion correlated with temperature changes (i.e. thermal expansion of the structures)."

+++

*The Principal Investigator (PI) of this project is [Dr. Othmar Frey](https://eo.ifu.ethz.ch/the-group/people/person-detail.NjQ4Mzc=.TGlzdC8zNTIyLC0zMTYzOTY1OTY=.html), from the Chair of Earth Observation & Remote Sensing, [ETH Zurich](http://www.eo.ifu.ethz.ch/forschung/applications.html#par_textimage_1567484257). I worked on this project as part of my doctoral research. The project is in close collaboration with [Gamma Remote Sensing AG](http://www.gamma-rs.ch), Switzerland.*

An accurate assessment of surface or structural deformation — subsidence or uplift — has been the objective of various studies in the field of environmental sciences and engineering geology over the last few decades. It can be caused by various geophysical processes (natural as well as anthropogenic), such as tectonic and volcanic activities, mass movements on unstable slopes, and mining and groundwater pumping, construction-related activities, etc. In each case, a general monitoring and measurement of the deformation is important owing to various environmental, economic and safety considerations. Traditionally, repeated leveling-based methods, and afterwards GPS-based approaches or a combination of both, were used to monitor and measure land deformation in concerned regions. However, leveling and GPS measurements can only be performed locally (for discrete locations), and therefore, they are not suitable for a wide range assessment of land deformation.  

In the context of large-scale and long-term monitoring of deformation in urban areas, PSI with space-borne SAR data stacks has proven to be an invaluable tool. However, an inherent limitation associated with PSI is that, by definition, a PS is a single dominant scatterer within a range–azimuth resolution cell. Therefore, pixels containing backscatter of comparable energy from multiple scatterers, which may individually exhibit point-like behavior, are rejected. This situation arises often in layovers. Urban areas typically have buildings of different heights, and layovers such as those between the ground and the facade of a nearby building, or the rooftop of one building and the facade of a higher building in proximity, occur ubiquitously. A local PSI analysis of such buildings may suffer from poor deformation sampling due to the rejection of such layovers. To overcome this limitation, I am investigating the combined use of PSI and tomography.
