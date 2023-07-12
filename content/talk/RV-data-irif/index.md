---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Runtime Monitoring for Hennessy-Milner Logic with Recursion over Systems with Data @ Séminaire Automates"
event: "Séminaire Automates"
location: IRIF, Université Paris Cité
address:
  street: Bâtiment Sophie Germain, 8 Place Aurélie Nemours
  city: Paris
  region:
  postcode: 75013
  country: France

summary: "Runtime verification consists in monitoring the execution of a system to determine if it satisfies a property. We extend this to systems over data."
abstract: "<p>Runtime verification consists in checking whether a program satisfies a given specification by observing the trace it produces during its execution. In the regular setting, Hennessy-Milner logic with recursion (recHML), a variant of the modal &mu-calculus, provides a versatile back-end for expressing linear- and branching-time specifications. In this talk, I will discuss an extension of this logic that allows to express properties over data values (i.e. values from an infinite domain) and examine which fragments can be verified at runtime. Data values are manipulated through equality tests in modalities and through first-order quantification outside of them. They can also be stored using parameterised recursion variables.</p><p> I then examine what kind of properties can be monitored at runtime, depending on the monitor model. A key aspect is that the logic has close links with register automata with non-deterministic reassignment, which yields a monitor synthesis algorithm, and allows to derive impossibility results. In particular, contrary to the regular case, restricting to deterministic monitors strictly reduces the set of monitorable properties.</p><p> This is joint work with the MoVeMnt team (Reykjavik University): Luca Aceto, Antonis Achilleos, Duncan Paul Attard, Adrian Francalanza, Karoliina Lehtinen.</p>"

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2022-12-02T14:00:00+02:00
# date_end: 2020-02-25T16:37:19+01:00
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2021-03-27T11:00:00+01:00

# authors: ["Luca Aceto","Antonis Achilleos","Duncan Paul Attard","Léo Exibard","Adrian Francalanza","Anna Ingólfsdóttir","Karoliina Lehtinen"]
authors: ["Léo Exibard"]
tags:
- Hennessy-Milner Logic
- Modal mu-Calculus
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
url_slides: slides/RV-data-ligm/slides.pdf

url_code:
url_pdf:
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
