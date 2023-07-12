---
title: "On Computability of Data Word Functions Defined by Transducers (FoSSaCS 2020)"
date: 2020-04-25
publishDate: 2020-07-01T10:13:51.519713Z
authors: ["Léo Exibard", "Emmanuel Filiot", "Pierre-Alain Reynier"]
publication_types: ["1"]
abstract: ""
featured: false
publication: "*Foundations of Software Science and Computation Structures - 23rd International Conference, FOSSACS 2020, Held as Part of the European Joint Conferences on Theory and Practice of Software, ETAPS 2020, Dublin, Ireland, April 25-30, 2020, Proceedings*"
url_pdf: "https://doi.org/10.1007/978-3-030-45231-5_12"
doi: "10.1007/978-3-030-45231-5_12"
# Manually added
summary: "We extend the correspondence between computability and continuity over regular functions to the case of data words."
abstract: "In this paper, we investigate the problem of synthesizing computable functions of infinite words over an infinite alphabet (data <nobr>$\\omega$&#x2011;words</nobr>). The notion of computability is defined through Turing machines with infinite inputs which can produce the corresponding infinite outputs in the limit. We use non-deterministic transducers equipped with registers, an extension of register automata with outputs, to specify functions. Such transducers may not define functions but more generally relations of data <nobr>$\\omega$&#x2011;words</nobr>, and we show that it is PSpace-complete to test whether a given transducer defines a function. Then, given a function defined by some register transducer, we show that it is decidable (and again, PSpace-complete) whether such function is computable. As for the known finite alphabet case, we show that computability and continuity coincide for functions defined by register transducers, and show how to decide continuity. We also define a subclass for which those problems are PTime."
tags:
- Data Words
- Register Automata
- Register Transducers
- Functionality
- Continuity
- Computability
url_slides: "slides/dblp-conffossacs-exibard-fr-20/slides.pdf"
url_video: "https://www.youtube.com/watch?v=B349DH2EQOI"
url_poster: "posters/dblp-conffossacs-exibard-fr-20/poster.pdf"
# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: Journal
  url: "publication/dblp-journalslmcs-exibard-flr-21/"
- name: Short video
  url: "https://youtu.be/GmnJXnbyEQA"
---
The work of Vrunda Dave, Emmanuel Filiot, Krishna S and Nathan Lhote, which settles the finite alphabet case and inspired us this research direction, was accepted at [CONCUR 2020](https://concur2020.forsyte.at/accepted/index.html) as [*Synthesis of Computable Regular Functions of Infinite Words*](https://drops.dagstuhl.de/opus/volltexte/2020/12855/pdf/LIPIcs-CONCUR-2020-43.pdf). For the present paper, we refer to the preprint [arXiv version 1](https://arxiv.org/pdf/1906.04199v1.pdf), as it was the one available when we wrote the paper. We have been invited to write an extended version for the LMCS special issue dedicated to FoSSaCS 2020, that has been accepted with minor revisions (more details [here]({{< ref "/publication/dblp-journalslmcs-exibard-flr-21/index.md" >}})). The contributions of both papers are detailed in the [second part](https://hal.archives-ouvertes.fr/tel-03409602/document#page=224) of my manuscript.

Due to the worldwide outbreak of CoViD-19, ETAPS 2020 was postponed; so was my presentation of this work, but I could present it a year later at [ETAPS 2021]({{< ref "/talk/computability-data-word-functions/index.md" >}}). I also got the opportunity to give a longer talk about it at [MOVEP 2020]({{< ref "/talk/computability-data-word-functions-movep/index.md" >}}) and a short one at [HIGHLIGHTS 2020]({{< ref "/talk/computability-data-word-functions-highlights/index.md" >}}).
