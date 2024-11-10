---
title: "Statistical Verification using Surrogate Models and Conformal Inference and a Comparison with Risk-Aware Verification"
authors:
- Xin Qin
- Yuan Xia
- Chuchu Fan
- Jyotirmoy Deshmukh
author_notes:
- "Equal contribution"
date: "2023-05-14T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-05-14T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Source Themes, 1*(1)"
publication_short: ""

abstract: Uncertainty in safety-critical cyber-physical systems can be modeled using a finite number of parameters or parameterized input signals. Given a system specification in Signal Temporal Logic (STL), we would like to verify that for all (infinite) values of the model parameters/input signals, the system satisfies its specification. Unfortunately, this problem is undecidable in general. Statistical model checking (SMC) offers a solution by providing guarantees on the correctness of CPS models by statistically reasoning on model simulations. We propose a new approach for statistical verification of CPS models for user-provided distribution on the model parameters. Our technique uses model simulations to learn surrogate models, and uses conformal inference to provide probabilistic guarantees on the satisfaction of a given STL property. Additionally, we can provide prediction intervals containing the quantitative satisfaction values of the given STL property for any user-specified confidence level. We compare this prediction interval with the interval we get using risk estimation procedures. We also propose a refinement procedure based on Gaussian Process (GP)-based surrogate models for obtaining fine-grained probabilistic guarantees over sub-regions in the parameter space. This in turn enables the CPS designer to choose assured validity domains in the parameter space for safety-critical applications. Finally, we demonstrate the efficacy of our technique on several CPS models.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://dl.acm.org/doi/full/10.1145/3635160
#url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
