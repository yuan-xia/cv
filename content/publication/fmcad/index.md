---
title: "Guiding Likely Invariant Synthesis on Distributed Systems with Large Language Models"

authors:
  - Yuan Xia
  - Aabha Pingle
  - Deepayan Sur
  - Jyotirmoy V. Deshmukh
  - Mukund Raghothaman
  - Srivatsan Ravi

author_notes: []

# Use the official conference start date once announced.
date: "2025-10-15T00:00:00Z"          # placeholder (mid-Oct is typical for FMCAD)
publishDate: "2025-08-01T00:00:00Z"   # page visible now, before the event

publication_types: ["paper-conference"]

publication: In *Formal Methods in Computer-Aided Design* (FMCAD 2025) — accepted, to appear
publication_short: In *FMCAD 2025*

abstract: |
  We present a framework that leverages large language models (LLMs) to guide
  the synthesis of inductive invariants for distributed systems.  The approach
  iteratively queries an LLM to propose candidate predicates, integrates them
  into decision-tree learners, and refines the search using counterexample
  feedback from a model checker.  Experiments on classic leader-election,
  mutual-exclusion, and consensus protocols show that our method discovers
  tight invariants with up to a 4× reduction in synthesis iterations compared
  with purely heuristic template-based baselines.

tags:
  - Invariant Learning
  - Distributed Systems
  - Large Language Models

featured: true   

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

doi: ""                                # add DOI when assigned

# External links (fill in when available)
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
Click the _Cite_ button above to import the BibTeX entry once published.
{{% /callout %}}

_Add full text, supplementary notes, or rich content here after publication._