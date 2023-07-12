---
title: "Computability of Data-Word Transductions over Different Data Domains (LMCS Special Issue dedicated to FoSSaCS 2020)"
date: 2021-01-08
publishDate: 2021-01-29T12:08:37.012956Z
authors: ["Léo Exibard", "Emmanuel Filiot", "Nathan Lhote", "Pierre-Alain Reynier"]
publication_types: ["2"]
summary: "We extend the correspondence between computability and continuity over regular functions to the case of data words."
abstract: "<p>In this paper, we investigate the problem of synthesizing computable functions of infinite words over an infinite alphabet (data <nobr>$\\omega$&#x2011;words</nobr>). The notion of computability is defined through Turing machines with infinite inputs which can produce the corresponding infinite outputs in the limit. We use non-deterministic transducers equipped with registers, an extension of register automata with outputs, to describe specifications. Being non-deterministic, such transducers may not define functions but more generally relations of data <nobr>$\\omega$&#x2011;words</nobr>. In order to increase the expressive power of these machines, we even allow guessing of arbitrary data values when updating their registers.</p>
<p>For functions over data <nobr>$\\omega$&#x2011;words</nobr>, we identify a sufficient condition (the possibility of determining the next letter to be outputted, which we call next letter problem) under which computability (resp. uniform computability) and continuity (resp. uniform continuity) coincide.</p>
<p>We focus on two kinds of data domains: first, the general setting of oligomorphic data, which encompasses any data domain with equality, as well as the setting of rational numbers with linear order; and second, the set of natural numbers equipped with linear order. For both settings, we prove that functionality, i.e. determining whether the relation recognized by the transducer is actually a function, is decidable. We also show that the so called next letter problem is decidable, yielding equivalence between (uniform) continuity and (uniform) computability. Last, we provide characterizations of (uniform) continuity, which allow us to prove that these notions, and thus also (uniform) computability, are decidable. We even show that all these decision problems are PSpace-complete for $(\\mathbb{N},\\leq)$ and for a large class of oligomorphic data domains, including for instance $(\\mathbb{Q},\\leq)$. "
featured: false
publication: "*Logical Methods in Computer Science*"
url_pdf: "https://lmcs.episciences.org/9861/"
url_slides: "slides/dblp-conffossacs-exibard-fr-20/slides.pdf"
tags:
- Data Words
- Register Transducers
- Functionality
- Continuity
- Computability
- Oligomorphic Data Domains
- Linearly Ordered Data Domains
links:
- name: Conference
  url: "publication/dblp-conffossacs-exibard-fr-20/"
---
This work has been submitted to the LMCS Special Issue dedicated to FoSSaCS 2020, and has been accepted with minor revisions. The preprint is available on [arXiv](https://arxiv.org/abs/1905.03538.pdf). [Nathan Lhote](https://pageperso.lis-lab.fr/~nathan.lhote/) joined us to extend the results presented in [On Computability of Data Word Functions Defined by Transducers (FoSSaCS 2020)]({{< ref "/publication/dblp-conffossacs-exibard-fr-20/index.md" >}}) in the following ways:
- Extension of our study of $(\\mathbb{N},=)$ to the setting of *oligomorphic* data domains. This includes $(\\mathbb{Q},\\leq)$ in particular.
- Study of the case of $(\\mathbb{N},\\leq)$, which is not oligomorphic.
- Characterisation of uniform continuity in the case of oligomorphic domains[^fn:case-N].
These contributions are the topic of the [second part](https://hal.archives-ouvertes.fr/tel-03409602/document#page=224) of my thesis.

To obtain those generalisations, we shifted to a more abstract presentation of the problem. The reader who is mainly interested in the $(\\mathbb{N},=)$ case can consult the [conference version](https://arxiv.org/abs/2002.08203.pdf), where the proofs use more concrete objects, although they are arguably less elegant. They might also have a look at [Section 12.1](https://hal.archives-ouvertes.fr/tel-03409602/document#page=248) of my manuscript, where the presentation of the concepts and the proofs have been rewritten and detailed[^fn:test-free].

[^fn:case-N]: We also obtained a characterisation of uniform continuity in the case of $(\\mathbb{N},\\leq)$ but did not include it in the paper so as not to clutter the argument.
[^fn:test-free]: The case of test-free transducers has been knowingly omitted, so as not to make the document lengthier than it already is.

