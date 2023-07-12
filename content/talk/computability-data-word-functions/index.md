---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "On Computability of Data Word Functions Defined by Transducers @ ETAPS 2021"
event: "FoSSaCS 2020 @ ETAPS2021"
event_url: "https://www.etaps.org/2021/fossacs"
location: Online
address:
  street:
  city:
  region:
  postcode:
  country:

summary: "We extend the correspondence between computability and continuity over regular functions to the case of data words."
abstract: "In this talk, we investigate the problem of synthesizing computable functions of infinite words over an infinite alphabet (data $\\omega$-words). The notion of computability is defined through Turing machines with infinite inputs which can produce the corresponding infinite outputs in the limit. We use non-deterministic transducers equipped with registers, an extension of register automata with outputs, to specify functions. Such transducers may not define functions but more generally relations of data $\\omega$-words, and we show that it is PSpace-complete to test whether a given transducer defines a function. Then, given a function defined by some register transducer, we show that it is decidable (and again, PSpace-complete) whether such function is computable. As for the known finite alphabet case, we show that computability and continuity coincide for functions defined by register transducers, and show how to decide continuity. We also define a subclass for which those problems are PTime."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2021-04-01T18:00:00+01:00
# date_end: 2020-02-25T16:37:19+01:00
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2021-03-27T11:00:00+01:00

authors: ["Léo Exibard"]
tags:
- Data Words
- Register Automata
- Register Transducers
- Functionality
- Continuity
- Computability

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
  url: "publication/dblp-conffossacs-exibard-fr-20/"

# Optional filename of your slides within your talk's folder or a URL.
url_slides: "talk/computability-data-word-functions/slides.pdf"

url_code:
url_pdf: "https://arxiv.org/pdf/2002.08203.pdf"
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

Due to the worldwide outbreak of CoViD-19, ETAPS 2020 has been cancelled. I thus presented this work at the 2021 edition of the conference.

The recording is unfortunately not available, but I presented [a previous version of this work]({{< ref "talk/computability-data-word-functions-movep/_index.md" >}}) at [MOVEP 2020](http://projects-verimag.imag.fr/movep2020/) that has been recorded.

I also gave a [shorter version]({{< ref "talk/computability-data-word-functions-highlights/_index.md" >}}) of this talk at [Highlights 2020](http://highlights-conference.org/).
