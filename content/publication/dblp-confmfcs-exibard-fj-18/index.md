---
title: "The Complexity of Transducer Synthesis from Multi-Sequential Specifications (MFCS 2018)"
date: 2018-08-27
publishDate: 2020-02-25T13:25:19.204307Z
authors: ["Léo Exibard", "Emmanuel Filiot", "Ismaël Jecker"]
publication_types: ["1"]
featured: false
publication: "*43rd International Symposium on Mathematical Foundations of Computer Science, MFCS 2018, August 27-31, 2018, Liverpool, UK*"
url_pdf: "https://doi.org/10.4230/LIPIcs.MFCS.2018.46"
doi: "10.4230/LIPIcs.MFCS.2018.46"
# Manually added
summary: "Multi-sequential specifications are recognised by unions of sequential transducers. Their synthesis problem is PSpace-complete."
abstract: "<p>The transducer synthesis problem on finite words asks, given a specification $S \\subseteq I \\times O$, where $I,O$ are sets of finite words, whether there exists a function $f$ which (1) fulfils the specification, i.e. $(i,f(i))\\in S$ for all $i\\in I$, and (2) can be defined by some input-deterministic (aka sequential) transducer $\\mathcal{T}$. If such an $f$ exists, the procedure should also output $\\mathcal{T}$. For specifications given by synchronous transducers (which read and write alternately one symbol), this problem is the finite variant of the classical synthesis problem on <nobr>$\\omega$&#x2011;words</nobr>, solved by Büchi and Landweber in 1969, and is known, in both finite and <nobr>$\\omega$&#x2011;word</nobr> settings, to be ExpTime-complete.</p>
<p>In the asynchronous setting (where a transducer can write a batch of symbols, or none, in a single step), this problem is known to be undecidable. We consider here the class of multi-sequential specifications, defined as finite unions of sequential transducers (over possibility incomparable domains). In both settings, asynchronous and synchronous, we provide optimal decision procedures by showing the problem to be PSpace-complete.</p>"
tags:
- Transducers
- Multi-Sequentiality
- Synthesis
url_slides: "slides/dblp-confmfcs-exibard-fj-18/slides.pdf"
---

