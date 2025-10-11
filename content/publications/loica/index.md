---
title: "LOICA: Integrating Models with Data for Genetic Network Design Automation"
authors:
- admin
- Carolus Vitalis
- Timothy Rudge
  
author_notes:

date: "2022-05-04T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-05-04T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "LOICA: Integrating Models with Data for Genetic Network Design Automation"
publication_short: "LOICA"

abstract: Genetic design automation tools are necessary to expand the scale and complexity of possible synthetic genetic networks. These tools are enabled by abstraction of a hierarchy of standardized components and devices. Abstracted elements must be parametrized from data derived from relevant experiments, and these experiments must be related to the part composition of the abstract components. Here we present Logical Operators for Integrated Cell Algorithms (LOICA), a Python package for designing, modeling, and characterizing genetic networks based on a simple object-oriented design abstraction. LOICA uses classes to represent different biological and experimental components, which generate models through their interactions. These models can be parametrized by direct connection to data contained in Flapjack so that abstracted components of designs can characterize themselves. Models can be simulated using continuous or stochastic methods and the data published and managed using Flapjack. LOICA also outputs SBOL3 descriptions and generates graph representations of genetic network designs.

# Summary. An optional shortened abstract.
summary: Logical Operators for Integrated Cell Algorithms (LOICA) is a tool for the design, modeling, and parametrization of synthetic genetic networks.

tags:
- Design
- Modeling
- Simulation
- Genetic Networks
  
featured: true

hugoblox:
  ids:
    arxiv: 1512.04133v1

links:
  - type: DOI
    url: https://doi.org/10.1021/acssynbio.1c00603
  - type: code
    url: https://github.com/RudgeLab/LOICA

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**ACS Synthetic Biology**](https://doi.org/10.1021/acssynbio.1c00603)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""

> [!NOTE]
> Create your slides in Markdown - click the *Slides* button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
