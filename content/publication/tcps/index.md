---
title: "Statistical Verification using Surrogate Models and Conformal Inference and a Comparison with Risk-aware Verification"

authors:
  - Xin Qin
  - Yuan Xia
  - Aditya Zutshi
  - Chuchu Fan
  - Jyotirmoy V. Deshmukh

author_notes: []

date: "2023-07-01T00:00:00Z"          # adjust to actual publication date if known
publishDate: "2023-07-01T00:00:00Z"

publication_types: ["article-journal"]

publication: In *ACM Transactions on Cyber-Physical Systems* (TCPS 2023)
publication_short: In *TCPS 2023*

abstract: Uncertainty in safety-critical cyber-physical systems can be modeled using a finite number of parameters or parameterized input signals. Given a system specification in Signal Temporal Logic (STL), we would like to verify that for all (infinite) values of the model parameters/input signals, the system satisfies its specification. Unfortunately, this problem is undecidable in general. Statistical model checking (SMC) offers a solution by providing guarantees on the correctness of CPS models by statistically reasoning on model simulations. We propose a new approach for statistical verification of CPS models for user-provided distribution on the model parameters. Our technique uses model simulations to learn surrogate models, and uses conformal inference to provide probabilistic guarantees on the satisfaction of a given STL property. Additionally, we can provide prediction intervals containing the quantitative satisfaction values of the given STL property for any user-specified confidence level. We compare this prediction interval with the interval we get using risk estimation procedures. We also propose a refinement procedure based on Gaussian Process (GP)-based surrogate models for obtaining fine-grained probabilistic guarantees over sub-regions in the parameter space. This in turn enables the CPS designer to choose assured validity domains in the parameter space for safety-critical applications. Finally, we demonstrate the efficacy of our technique on several CPS models.

tags:
  - Statistical Verification
  - Cyber-Physical Systems
  - Surrogate Models
  - Conformal Inference
  - Risk-aware Verification

featured: false                        # switch to true to surface in “Featured Publications”

doi: ""                                # fill in when available

# External links (add real URLs when you have them)
url_pdf: ""
url_code: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""

image:
  caption: ""
  focal_point: ""
  preview_only: false

projects: []

slides: ""
---
{{% callout note %}}
Click the _Cite_ button above to import the BibTeX entry.
{{% /callout %}}

<!-- _Add full text, supplementary materials, or rich content (figures, code) here as desired._ -->


