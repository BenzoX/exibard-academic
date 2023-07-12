---
title: "Synthesis of Data Word Transducers (LMCS Special Issue dedicated to CONCUR 2019)"

date: 2020-06-09
publishDate: 2021-01-29T12:08:37.013979Z
authors: ["Léo Exibard", "Emmanuel Filiot", "Pierre-Alain Reynier"]
publication_types: ["2"]
summary: "Register automata are a counterpart of finite automata over data words. Synthesis algorithms can (sometimes) be extended to them."
abstract: "<p>In reactive synthesis, the goal is to automatically generate an implementation from a specification of the reactive and non-terminating input/output behaviours of a system. Specifications are usually modelled as logical formulae or automata over infinite sequences of signals (<nobr>$\\omega$&#x2011;words</nobr>), while implementations are represented as transducers. In the classical setting, the set of signals is assumed to be finite. In this paper, we consider data <nobr>$\\omega$&#x2011;words</nobr> instead, i.e., words over an infinite alphabet. In this context, we study specifications and implementations respectively given as automata and transducers extended with a finite set of registers. We consider different instances, depending on whether the specification is nondeterministic, universal or deterministic, and depending on whether the number of registers of the implementation is given or not.</p><p>In the unbounded setting, we show undecidability for both universal and non-deterministic specifications, while decidability is recovered in the deterministic case. In the bounded setting, undecidability still holds for non-deterministic specifications, but can be recovered by disallowing tests over input data. The generic technique we use to show the latter result allows us to reprove some known result, namely decidability of bounded synthesis for universal specifications.</p>"
featured: false
publication: "*Logical Methods in Computer Science*"
doi: "10.4230/LIPIcs.CONCUR.2019.24"
url_pdf: "https://lmcs.episciences.org/7279/pdf"
url_slides: "slides/dblp-confconcur-exibard-fr-19/slides.pdf"
url_poster: "posters/dblp-confconcur-exibard-fr-19/poster.pdf"
tags:
- Register Automata
- Synthesis
- Data Words
- Transducers
links:
- name: Conference
  url: "publication/dblp-confconcur-exibard-fr-19/"
---
This work is an extension of [Synthesis of Data Word Transducers (CONCUR 2019)]({{< ref "/publication/dblp-confconcur-exibard-fr-19/index.md" >}}). It contains full proofs and provides a simplified proof for the unbounded case. The proofs have been further distilled in [Chapters 5-7](https://hal.archives-ouvertes.fr/tel-03409602/document#page=151) of my manuscript.

It also includes a discussion on the relation between synthesis and uniformisation problems, in particular on the aspect of the domain of the specification. Such distinction does not matter much in the finite alphabet case, as $\\omega$&#x2011;regular languages are closed under complement. Thus, any specification can be extended to one with a total domain by allowing any behaviour on the complement of the domain. However, it makes a big difference in the infinite alphabet case, since languages recognised register automata are not closed under complement. This question is explored in more depth in [Chapter 8](https://hal.archives-ouvertes.fr/tel-03409602/document#page=217) of my thesis.
