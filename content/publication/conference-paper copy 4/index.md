---
title: 'Data-Driven Template-Free Invariant Generation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yuan Xia
  - Jyotirmoy Deshmukh

# Author notes (optional)
author_notes:
  - 'Equal contribution'

date: '2023-12-29T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-12-29T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Hugo Blox Builder Conference*
publication_short: In *ICW*

abstract: Automatic verification of concurrent programs faces state explosion due to the exponential possible interleavings of its sequential components coupled with large or infinite state spaces. An alternative is deductive verification, where given a candidate invariant, we establish inductive invariance and show that any state satisfying the invariant is also safe. However, learning (inductive) program invariants is difficult. To this end, we propose a data-driven procedure to synthesize program invariants, where it is assumed that the program invariant is an expression that characterizes a (hopefully tight) over-approximation of the reachable program states. The main ideas of our approach are (1) We treat a candidate invariant as a classifier separating states observed in (sampled) program traces from those speculated to be unreachable. (2) We develop an enumerative, template-free approach to learn such classifiers from positive and negative examples. At its core, our enumerative approach employs decision trees to generate expressions that do not over-fit to the observed states (and thus generalize). (3) We employ a runtime framework to monitor program executions that may refute the candidate invariant; every refutation triggers a revision of the candidate invariant. Our runtime framework can be viewed as an instance of statistical model checking, which gives us probabilistic guarantees on the candidate invariant. We also show that such in some cases, our counterexample-guided inductive synthesis approach converges (in probability) to an overapproximation of the reachable set of states. Our experimental results show that our framework excels in learning useful invariants using only a fraction of the set of reachable states for a wide variety of concurrent programs.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Invariant Learning

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://arxiv.org/abs/2312.17527'
#url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

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
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
