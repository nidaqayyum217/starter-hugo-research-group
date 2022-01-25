+++
# Date this page was created.
date = 2019-12-21T00:00:00

# Project title.
title = "Classification of potential oil spills using space-borne SAR"

# Project summary to display on homepage.
summary = "Oil spill is one of the major threats to marine ecosystems. We are working on developing an operational framework to complement early warning systems."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "projects/oilspill.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
#tags = ["SAR tomography as an add-on to PSI"]
tags = ["machine-learning", "deep-learning", "spatial-analytics", "marine-pollution", "arabian-sea", "pakistan", "SAR"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "projects/oilspill.jpg"
caption = "Two SAR images (left), with ground truth labels (center) viz. oil spill (cyan), look-alikes (red), ship (brown), land (green), sea surface (black) and predicted labels (right). Oil spill detection dataset © ITI-CERTH, Greece."

+++
*For inquires, please contact Dr. Adnan Siddique and Mr. Abdul Basit.*
*This is an ongoing project in collaboration with [Dr. Saquib Sarfraz](https://de.linkedin.com/in/saquib-sarfraz-6395783a).*

Oil spill is one of the major threats to marine ecosystems. It is caused by ship accidents, illegal ship discharge (bilge dumping) and natural oil seeps. An accurate monitoring and detection framework is necessary to classify the potential oil spills. Historically, synthetic aperture radar (SAR) data has been used efficiently for classification of oil spills due to its operational capability in all-weather conditions. Oil spill appears as a dark stretch in SAR imagery. Similarly, low wind areas and algae blooms etc. have a similar dark signature, resulting in false positive detections. Research has been conducted on using deep learning techniques for classification of oil spills and look-alikes in SAR imagery, but still it remains a challenging task for researchers. This project is focused on using deep learning techniques and SAR imagery for classification of potential oil spills. We are investigating the deep learning based semantic segmentation of  SAR images for classification of oil spills from look-alikes. Additionally, we are considering detection of coastal areas and ships, because the dark stretch detected near a ship has a greater probability of being an oil spill due to bilge dumping or ship accident. Primarily, our focus is Pakistan territorial waters in the Arabian Sea. Due to lack of any operational framework, the oil spill events in Pakistan Exclusive Economic Zone (EEZ) remain undetected until oil reaches the coastal regions. We are working on developing an operational framework to act to complement early warning systems.
