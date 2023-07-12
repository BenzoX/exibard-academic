---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Synthesis over Infinite Domains through Machines with Registers @ Journées GT Vérif 2021 (Invited talk)"
event: "Journées du GT Vérif 2021"
event_url: "https://www.benedikt-bollig.org/gt-verif-2021"
location: ENS Paris-Saclay
address:
  street:
  city: Gif-sur-Yvette
  region:
  postcode:
  country: France

summary: "Register automata are a counterpart of finite automata over data words. Synthesis algorithms can (sometimes) be extended to them."
summary: "Synthesis can be lifted to infinite domains through register automata, targeting register transducers implementations."
abstract: "<p>In reactive synthesis, the goal is to automatically generate an implementation from a specification of the reactive and non-terminating input/output behaviours of a system. Specifications are usually modelled as logical formulae or automata over infinite sequences of signals (<nobr>$\\omega$&#x2011;words</nobr>), while implementations are represented as transducers. In the classical setting, the set of signals is assumed to be finite.</p>
<p> The aim of this talk is to investigate the case of infinite alphabets. Correspondingly, executions are modelled as <em>data</em> <nobr>$\\omega$&#x2011;words</nobr>. In this context, we study specifications and implementations respectively given as automata and transducers extended with a finite set of registers, used to store and compare data values. We consider different instances, depending on whether the specification is nondeterministic, universal (a.k.a. co-nondeterministic) or deterministic: contrary to the finite-alphabet case, those classes are expressively distinct.</p>
<p> When the number of registers of the target implementation is unbounded, the synthesis problem is undecidable, while decidability is recovered in the deterministic case. In the bounded setting, undecidability still holds for non-deterministic specifications, but decidability is recovered for universal ones.</p>
<p>The study was initially conducted over data domains with the equality predicate only, but the techniques can be lifted to the dense order $(\\mathbb{Q},<)$ and so-called oligomorphic data domains, over which register automata behave in an <nobr>$\\omega$&#x2011;regular</nobr> way. A further exploration of the problem allows to extend the results to the discrete order $(\\mathbb{N},<)$, where the behaviours can be regularly <em>approximated</em>. Finally, decidability can be transferred to the case of words with the prefix relation $(\\mathbb{\\Sigma}^*,\\prec)$ through a notion of reducibility between domains.</p>"

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2021-11-18T09:30:00+01:00
# date_end: 2020-02-25T16:37:19+01:00
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2021-03-27T11:00:00+01:00

authors: ["Léo Exibard"]
tags:
- Register Automata
- Synthesis
- Data Words
- Transducers

# Is this a featured talk? (true/false)
featured: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: Details
  url: "publication/dblp-journalslmcs-exibard-fr-21/"

# Optional filename of your slides within your talk's folder or a URL.
url_slides: ""

url_code:
url_pdf: "https://lmcs.episciences.org/7279/pdf"
url_video:

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
I have been invited to give a talk at the [Journées du GT Vérif](https://www.benedikt-bollig.org/gt-verif-2021), that will take place at ENS Paris Saclay (Gif-sur-Yvette, France) from the 17<sup>th</sup> to the 19<sup>th</sup> of November 2021. I will be in Paris for the week, do not hesitate to contact me if you want to meet at this occasion. The event simultaneously happens online, so you can also follow the talk via Zoom.
