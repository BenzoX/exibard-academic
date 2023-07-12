---
title: "Church Synthesis on Register Automata over Linearly Ordered Data Domains (STACS 2021)"
date: 2021-03-16
publishDate: 2021-01-29T12:08:37.014471Z
authors: ["Léo Exibard", "Emmanuel Filiot", "Ayrat Khalimov"]
publication_types: ["1"]
abstract: ""
featured: false
publication: "*38th International Symposium on Theoretical Aspects of Computer Science, STACS 2021, March 16-19, 2021, Saarbrücken, Germany*"
url_pdf: "https://arxiv.org/abs/2004.12141.pdf"
doi: "10.4230/LIPIcs.STACS.2021.54"
# Manually added
summary: "The Church game for register automata over $(\\mathbb{N}, \\leq)$ is undecidable, but the one-sided game is, for deterministic ones."
abstract: "<p>Register automata are finite automata equipped with a finite set of registers in which they can store data, i.e. elements from an unbounded or infinite alphabet. They provide a simple formalism to specify the behaviour of reactive systems operating over data <nobr>$\\omega$&#x2011;words</nobr>. We study the synthesis problem for specifications given as register automata over a linearly ordered data domain (e.g. $(\\mathbb{N}, \\leq)$ or $(\\mathbb{Q}, \\leq)$), which allow for comparison of data with regards to the linear order. To that end, we extend the classical Church synthesis game to infinite alphabets: two players, Adam and Eve, alternately play some data, and Eve wins whenever their interaction complies with the specification, which is a language of <nobr>$\\omega$&#x2011;words</nobr> over ordered data. Such games are however undecidable, even when the specification is recognised by a deterministic register automaton. This is in contrast with the equality case, where the problem is only undecidable for nondeterministic and universal specifications.</p><p>Thus, we study one-sided Church games, where Eve instead operates over a finite alphabet, while Adam still manipulates data. We show they are determined, and deciding the existence of a winning strategy is in ExpTime, both for $\\mathbb{Q}$ and $\\mathbb{N}$. This follows from a study of constraint sequences, which abstract the behaviour of register automata, and allow us to reduce Church games to <nobr>$\\omega$&#x2011;regular</nobr> games. Lastly, we apply these results to the transducer synthesis problem for input-driven register automata, where each output data is restricted to be the content of some register, and show that if there exists an implementation, then there exists one which is a register transducer.</p>"
tags:
- Data Words
- Register Automata
- Register Transducers
- Church Synthesis
- Linearly Ordered Data Domains
# url_slides: "slides/dblp-conffossacs-exibard-fr-20/slides.pdf"
# url_video: "https://www.youtube.com/watch?v=oJvEm1wPiWA&feature=youtu.be"
# url_poster: "posters/dblp-conffossacs-exibard-fr-20/poster.pdf"
# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
---
While generalising our results about register-bounded and unbounded synthesis over $(\mathbb{N},=)$ (presented [here]({{< ref "/talk/computability-data-word-functions-highlights/index.md" >}})) to the case of $(\mathbb{Q},<)$ is relatively straightforward, the case of $(\mathbb{N},<)$ is significantly more difficult, as behaviours of register automata over the latter domain cannot be abstracted in an $\omega$&#x2011;regular way. In this paper, we however show that they can be regularly *approximated*. This contribution is detailed in [Chapter 7](https://hal.archives-ouvertes.fr/tel-03409602/document#page=181) of my manuscript (more precisely [Section 7.3.4](https://hal.archives-ouvertes.fr/tel-03409602/document#page=200)), which also features a simpler proof of the key lemma (Lemma 16 in the paper, 7.25 in the manuscript).
<!-- [great talk](https://bbb-lb.math.univ-paris-diderot.fr/playback/presentation/2.0/playback.html?meetingId=eb934df30eaa464f6946e347498fafcdccf672c1-1610716645220) -->

Ayrat [presented](https://www.youtube.com/watch?v=B349DH2EQOI) this work at [STACS 2021](https://stacs2021.saarland-informatics-campus.de/). He also gave a more in-depth talk about it at the [IRIF "Automates" seminar](https://www.irif.fr/seminaires/automates/index). The link is not public, but you might consider contacting the organisers of the seminar to ask for it.
