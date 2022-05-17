---
title: "Attenuation structures using Full Waveform Inversion"
subtitle: 
summary: Based on a time domain complex-valued viscoacoustic wave equation, we present an FWI framework for simultaneously estimating subsurface P wave velocity and attenuation distributions. 
authors:
- Jidong Yang
- Hejun Zhu
doi: "10.1029/2019JB019129"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-05-21"

tags: [Inversion]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

To complement velocity distributions, seismic attenuation provides additional important information on fluid properties of hydrocarbon reservoirs in exploration seismology, as well as temperature distributions, partial melting, and water content within the crust and mantle in earthquake seismology. Full waveform inversion (FWI), as one of the state-of-the-art seismic imaging techniques, can produce high-resolution constraints for subsurface (an)elastic parameters by minimizing the difference between observed and predicted seismograms. Traditional waveform inversion for attenuation is commonly based on the standard-linear-solid (SLS) wave equation, in which case the quality factor (Q) has to be converted to stress and strain relaxation times. When using multiple attenuation mechanisms in the SLS method, it is difficult to directly estimate these relaxation time parameters. Based on a time domain complex-valued viscoacoustic wave equation, we present an FWI framework for simultaneously estimating subsurface P wave velocity and attenuation distributions. Because Q is explicitly incorporated into the viscoacoustic wave equation, we directly derive P wave velocity and Q sensitivity kernels using the adjoint-state method and simultaneously estimate their subsurface distributions. By analyzing the Gauss-Newton Hessian, we observe strong interparameter crosstalk, especially the leakage from velocity to Q. We approximate the Hessian inverse using a preconditioned L-BFGS method in viscoacoustic FWI, which enables us to successfully reduce interparameter crosstalk and produce accurate velocity and attenuation models. 

A detailed introduction can be downloaded and viewed as a pdf, or [click this link.](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2019JB019129)
