---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "History-deterministic Register Automata @ NWPT 2021"
event: "NWPT 2021"
event_url: "http://icetcs.ru.is/nwpt21/"
location: Reykjavik University
address:
  street:
  city: Reykjavík
  region:
  postcode:
  country: Iceland

summary: "History-deterministic register automata form a promising class for synthesis and runtime verification applications."
abstract: "Recently, reactive synthesis, which asks to generate a system that guarantees correctness regardless of the behaviour of its environment, has been generalised to infinite alphabets. In this setting, specifications can be formalised as register automata. As is often the case, nondeterminism in the specification automaton leads to the synthesis problem being undecidable, yet deterministic register automata are much less expressive.
  History-determinism is a restricted form of nondeterminism which combines some of the algorithmic properties of deterministic automata with some of the succinctness and expressivity of nondeterministic ones. In particular, the synthesis problem for history-deterministic automata tends to be no harder than for deterministic ones, which makes this an interesting class to consider for reactive synthesis.
   In this extended abstract, we study the expressivity and succinctness of history-deterministic register automata, as well as their whether membership to the class is decidable. We also examine whether history-determinism coincides with good-for-gameness."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2021-11-05T16:40:00+00:00
# date_end: 2020-02-25T16:37:19+01:00
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2021-03-27T11:00:00+01:00

authors: ["Léo Exibard","Karoliina Lehtinen"]
tags:
- Register Automata
- History-determinism
- Good-for-Gameness
- Data Words

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

# Optional filename of your slides within your talk's folder or a URL.
url_slides: slides/nwpt-21/slides.pdf

url_code:
url_pdf: "http://icetcs.ru.is/nwpt21/abstracts/paper24.pdf"
url_video: "https://youtu.be/subw_yUwbhI"

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
History-determinism was introduced by Henzinger and Piterman in *Solving Games without Determinisation* [(CSL 2006)](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.118.9837&rep=rep1&type=pdf) as a means to reduce the complexity of reactive synthesis algorithms, and independently discovered by Colcombet in the context of cost functions (*The theory of stabilisation monoids and regular cost function*, [ICALP 2009](https://www.irif.fr/~colcombe/Publications/ICALP09-colcombet.pdf)). At the 32nd Nordic Workshop on Programming Theory [(NWPT 2021)](http://icetcs.ru.is/nwpt21/), I gave a talk to present some preliminary results obtained together with [Karoliina Lehtinen](http://www.pageperso.lif.univ-mrs.fr/~karoliina.lehtinen/) about the class of history-deterministic register automata. As of today, this is work in progress, and we hope to understand more about them in the months to come, as they offer promising perspectives to further the study of reactive synthesis over infinite alphabets (see [this article]({{< ref "/publication/dblp-journalslmcs-exibard-fr-21/index.md" >}}) for our contribution to this line of reasearch).
