---
title: "Automatic Synthesis of Systems with Data"
subtitle: "Synthèse automatique de systèmes avec données"
date: 2021-09-20
publishDate: 2021-01-29T12:08:37.012956Z
authors: ["Léo Exibard"]
publication_types: ["7"]
summary: "We lift synthesis to infinite domains through register automata, targeting register transducers or computable implementations."
featured: false
links:
- name: Manuscript
  url: "manuscript/Exibard_ASSD_SASD.pdf"
- name: Slides
  url: "slides/phd-21/slides.pdf"
- name: Video
  url: "https://youtu.be/uJpR63RSpZc"

tags:
- Register Automata
- Register Transducers
- Reactive Synthesis
- Church Problem
- Data Words
- Data Domains
- Asynchronous Transducers
- Computability
- Continuity
---
This thesis was conducted under the joint direction of [Emmanuel Filiot](http://www.ulb.ac.be/di/ssd/filiot/) (at [Département d'Informatique](http://www.ulb.ac.be/facs/sciences/info/), [Université Libre de Bruxelles](http://www.ulb.ac.be/)) and [Pierre-Alain Reynier](http://pageperso.lif.univ-mrs.fr/~pierre-alain.reynier/) (at [LIS](http://www.lis-lab.fr/), [Aix-Marseille Université](https://www.univ-amu.fr/)). I studied extensions of synthesis methods to systems operating with an infinite alphabet. The manuscript is available [here](../../files/Exibard_ASSD_SASD.pdf).

Following the Belgian conventions, it was first defended with the sole jury on the 6<sup>th</sup> of September 2021 in Brussels, and was then publicly defended on the 20<sup>th</sup> of September in Marseille. The public defence opened with a non-technical introduction in French  and was [recorded](https://youtu.be/uJpR63RSpZc), while the private one was fully in English with a more technical content. Most readers are probably interested in the latter, so the [default slides](../../slides/phd-21/slides.pdf) are those of the "private" defence. The slides of the public defence are available [here](../../slides/phd-21/slides_publique.pdf).

# Summary
We often interact with machines that react in real time to our actions (robots, websites etc). They are modelled as reactive systems, that continuously interact with their environment. The goal of reactive synthesis is to automatically generate a system from the specification of its behaviour so as to avoid a long, costly and error-prone design process.

In the classical setting, the set of signals available to the machine is assumed to be finite. However, this assumption is not realistic to model systems which process data from a possibly infinite set (e.g. a client id, a sensor value, etc.). The goal of this thesis is to extend reactive synthesis to the case of data words. We study a model that is well-suited for this more general setting, and examine the feasibility of its synthesis problem(s). We also explore the case of non-reactive systems, where the machine does not have to react immediately to its inputs.
# Abstract
A reactive system is a system that continuously interacts with its environment. The environment provides an input signal, to which the system reacts with an output signal, and so on ad infinitum. In reactive synthesis, the goal is to automatically generate an implementation from a specification of the reactive and non-terminating input/output behaviours of a system. In the classical setting, the set of signals is assumed to be finite. however, this assumption is not realistic to model systems which process sequences of signals accompanied with data from a possibly infinite set (e.g. a client id, a sensor value, etc.), which need to be stored in memory and compared against each other.

The goal of this thesis is to lift the theory of reactive system synthesis over words on a finite alphabet to data words. The data domain consists in an infinite set whose structure is given by predicates and constants enriched with labels from a finite alphabet. In this context, specifications and implementations are respectively given as automata and transducers extended with a finite set of registers that they use to store data values. To determine the transition to take, they compare the input data with the content of the registers using the predicates of the domain.


In a first part, we consider both the bounded and unbounded synthesis problem; the former additionally asks for a bound on the number of registers of the implementation, along with the specification. We do so for different instances, depending on whether the specification is a nondeterministic, universal (a.k.a. co-non-deterministic) or deterministic automaton, for various domains.
While the bounded synthesis problem is undecidable for non-deterministic specifications, we provide a generic approach consisting in a reduction to the finite alphabet case, that is done through automata-theoretic constructions. This allows to reprove decidability of bounded synthesis for universal specifications over $(\\mathbb{N},=)$, and to obtain new ones, such as the case of a dense order, or the ability of data guessing, all with a 2-ExpTime complexity.
We then move to the unbounded synthesis problem, which is undecidable for specifications given by non-deterministic and universal automata, but decidable and ExpTime-complete for deterministic ones over $(\\mathbb{N},=)$ and $(\\mathbb{Q},<)$. We also exhibit a decidable subclass in the case of $(\\mathbb{N},<)$, namely one-sided specifications.


In a second part, we lift the reactivity assumption, considering the richer class of implementations that are allowed to wait for additional input before reacting, again over data words. Specifications are modelled as non-deterministic asynchronous transducers, that output a (possibly empty) word when they read an input data. Already in the finite alphabet case, their synthesis problem is undecidable.

A way to circumvent the difficulty is to focus on functional specifications, for which any input sequence admits at most one acceptable output. Targeting programs computed by input-deterministic transducers is again undecidable, so we shift the focus to deciding whether a specification is computable, in the sense of the classical extension of Turing-computability to infinite inputs. We relate this notion with that of continuity for the Cantor distance, which yields a decidable characterisation of computability for functional specifications given by asynchronous register transducers over $(\\mathbb{N},=)$ and for the superseding class of oligomorphic data domains, that also encompasses $(\\mathbb{Q},<)$. The study concludes with the case of $(\\mathbb{N},<)$, that is again decidable. Overall, we get PSpace-completeness for the problems of deciding computability and refined notions, as well as functionality.
