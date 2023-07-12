---
title: "Synthesis of Data Word Transducers (CONCUR 2019)"
date: 2019-08-27
publishDate: 2020-02-25T13:25:19.203670Z
authors: ["Léo Exibard", "Emmanuel Filiot", "Pierre-Alain Reynier"]
publication_types: ["1"]
featured: false
publication: "*30th International Conference on Concurrency Theory, CONCUR 2019, August 27-30, 2019, Amsterdam, the Netherlands*"
url_pdf: "https://doi.org/10.4230/LIPIcs.CONCUR.2019.24"
doi: "10.4230/LIPIcs.CONCUR.2019.24"
# Manually added
summary: "Register automata are a counterpart of finite automata over data words. Synthesis algorithms can (sometimes) be extended to them."
abstract: "<p>In reactive synthesis, the goal is to automatically generate an implementation from a specification of the reactive and non-terminating input/output behaviours of a system. Specifications are usually modelled as logical formulae or automata over infinite sequences of signals (<nobr>$\\omega$&#x2011;words</nobr>), while implementations are represented as transducers. In the classical setting, the set of signals is assumed to be finite. In this paper, we consider data <nobr>$\\omega$&#x2011;words</nobr> instead, i.e., words over an infinite alphabet. In this context, we study specifications and implementations respectively given as automata and transducers extended with a finite set of registers. We consider different instances, depending on whether the specification is nondeterministic, universal or deterministic, and depending on whether the number of registers of the implementation is given or not.</p>
<p>In the unbounded setting, we show undecidability for both universal and non-deterministic specifications, while decidability is recovered in the deterministic case. In the bounded setting, undecidability still holds for non-deterministic specifications, but can be recovered by disallowing tests over input data. The generic technique we use to show the latter result allows us to reprove some known result, namely decidability of bounded synthesis for universal specifications.</p>"
tags:
- Register Automata
- Synthesis
- Data Words
- Transducers
url_slides: "slides/dblp-confconcur-exibard-fr-19/slides.pdf"
url_poster: "posters/dblp-confconcur-exibard-fr-19/poster.pdf"
links:
- name: Journal
  url: "publication/dblp-journalslmcs-exibard-fr-21/"
---
We have been invited to write an [extended version](https://lmcs.episciences.org/7279/pdf) of this paper, that appeared in the LMCS special issue dedicated to CONCUR 2019. It contains full proofs and provides a simplified proof for the unbounded case; see [this page]({{< ref "/publication/dblp-journalslmcs-exibard-fr-21/index.md" >}}) for more details. The proofs have been further distilled in [Chapters 5-8](https://hal.archives-ouvertes.fr/tel-03409602/document#page=151) of my manuscript.
