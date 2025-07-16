# Proof Theory of Modal Logic
### Course at the [5th Tsinghua Logic Summer School](https://tsinghualogic.net/JRC/toss/), June and July 2025
### [Marianna Girlando](https://www.mariannagirlando.com/Girlando.html)



This webpage contains the slides, handouts and homeowork assignments for the course Proof Theory of Modal Logic, which will take place within the [5th Tsinghua Logic Summer School](https://tsinghualogic.net/JRC/toss/), organized by the [Tsinghua University - University of Amsterdam Joint Research Centre for Logic](https://tsinghualogic.net/JRC/). The course will take place at the Tsinghua University, from 14th to 18th July 2025.

This course is based on a [course](https://esslli24-pfthml.github.io/esslli24PfThML.github.io/) taught at [ESSLLI2024](https://2024.esslli.eu/), prepared in collaboration with [Tiziano Dalmonte](https://dev-www.unibz.it/en/faculties/engineering/academic-staff/person/47069-tiziano-dalmonte).


## Table of Contents
- [Practical information](#info)
- [Course material ](#material)
  - [Lecture 1 - Sequent Calculus and Modal Logic ](#lecture-1---sequent-calculus-and-modal-logic-)
  - [Lecture 2 - Nested Sequents ](#lecture-2---nested-sequents-)
  - [Lecture 3 - Labelled Proof Systems ](#lecture-3---labelled-proof-systems-)
  - [Lecture 4 - Semantic Completeness of Labelled Calculi  ](#lecture-4---semantic-completeness-of-labelled-calculi--)
  - [Lecture 5 - Beyond the S5-cube ](#lecture-5---beyond-the-s5-cube-)
- [Homework and Exam ](#homework-assignments-)
- [Prerequisites ](#prerequisites-)
- [References ](#references-)

## Practical information <a name="info"></a>
- **Time:** 09:50-12:15, 14th -18th July 
- **Location:** Room 5105, Teaching Building No. 5
- **Lecturer:** [Marianna Girlando](https://www.mariannagirlando.com/Girlando.html) (m.girlando _at_ uva _dot_ nl)
- **Teaching Assistants:** Sisi Yang (yangss23 _at_ mails _dot_ tsinghua _dot_ edu _dot_ cn), Xin Li (lixin24 _at_ mails _dot_ tsinghua _dot_ edu _dot_ cn)


## Course material <a name="material"></a>
The material will be regularly updated throughout the course.

### Lecture 1 - Sequent Calculus and Modal Logic <a name="l1"></a>
In this lecture we will introduce Gentzen-style sequent calculus for classical propositional logic, using the proof system G3cpl presented in Section 3.5 of (Troelstra and Schwichtenberg, 2000). We will use the calculus to illustrate the main proof-theoretical properties which we will be focusing on in the course, including *invertibility* of the rules, *cut-admissibility* and *termination* of proof search. We will then (quickly) introduce the classical modal logics in the S5-cube, and discuss the available proof systems for the logics. In particular, we will see that the Gentzen-style formalism is not enough to define cut-free calculi for modal logic. This motivates the introduction to *nested* and *labelled* proof systems, which enrich Gentzen-style sequent calculus in different ways.


**Slides**: [Slides Lecture 1](lectures/lecture_1_toss25.pdf), [Annotated Slides Lecture 1](lectures/lecture_1_toss25_annotated.pdf)

**Typos**: There is a typo in the last slide (exercises), Question 2: the formula is missing a parenthesis. The correct formula is: $ \Box ( p \land (\Box p \rightarrow \bot ) ) \rightarrow \bot $

### Lecture 2 - Nested Sequents <a name="l2"></a>
In this lecture we will focus on nested sequent calculi for modal logics in the S5-cube. Nested sequents enrich the *structure* of Gentzen-style sequent calculus, by introducing an additional structural connective, intrepreted as Box. Nested sequents encode *trees* of Gentzen-style sequents and, thanks to their richer structure, constitute a cut-free proof system for modal logic. We will mostly discuss nested sequents for modal logic K and illustrate its main proof-theorerical properties.
The presentation of nested seqeunts is based on (Brünnler, 2009).


**Slides**: [Slides Lecture 2](lectures/lecture2_toss25.pdf), [Annotated Slides Lecture 2](lectures/lecture2_toss25_annotated.pdf)


### Lecture 3 - Labelled Proof Systems <a name="l3"></a>
Labelled sequent calculi enrich the *language* of  Gentzen-style sequents by introducing *labels*, which are variables representing worlds of a Kripke model. We will discuss labelled proof systems for modal logics in the S5-cube, and illustrate their main proof-theoretical properties. Following (Negri, 2003), we will see how labelled calculi can be defined for any modal logic whose frame conditions can be expressed by *geometric formulas*.  

**Slides**: [Slides Lecture 3](lectures/lecture3_toss25.pdf)



### Lecture 4 - Semantic Completeness of Labelled Calculi  <a name="l4"></a>
In this lecture, we will consider semantic completeness, that is, the method to prove completeness by constructing a countermodel from a failed proof-search tree. We will illustrate this method for labelled calculi, which are particularly well-suited to the purpose. As a case study, we will consider the labelled proof system for modal logic S4.

**Slides** - To be uploaded.



### Lecture 5 - Beyond the S5-cube <a name="l5"></a>
In this lecture we will show how to define labelled sequent calculi for different kinds of modal logics, demonstrating the flexibility and modularity of the labelled formalism. In particular, we will consider labelled calculi for intuitionistic modal logic, whose semantics is defined in terms of bi-relational models, and
and labelled calculi for conditional logic, whose semantics is defined in terms of neighbourood models.

**Slides** - To be uploaded.



### Homework Assignments <a name="homs"></a> 
Each homework will receive a maximum of 10 points, and will amount to 20% of the final grade. Each homework will be published right before the corresponding 
lecture, and is due right before the next lecture. 
The take-home exam will amount to 40% of the final grade, and it is due on Sunday 20 June, at 23:59.  
- [Homework 1](homework/homework-1.pdf)
- [Homework 2](homework/homework-2.pdf)
- [Homework 3](homework/homework-3.pdf)
- Take-home exam - To be uploaded.


### Prerequisites <a name="pre"></a>
We only assume some basic familiarity with sequent calculus and modal logics. We will briefly introduce both topics, recalling the main notions used throughout the course, in Lecture 1. In particular, we will be using versions of G3cpl, the sequent calculus for classical propositional logic presented in Section 3.5 of (Troelstra and Schwichtenberg, 2000).


### References <a name="refs"></a>
There are several textbooks and resources that introduce modal logics. You could have a look at one of the following:
- The Stanford Encyclopedia entry for "Modal logics" ([link](https://seop.illc.uva.nl/entries/logic-modal/)).
- van Benthem, Modal logic for open minds, Stanford: Center for the Study of Language and Information, 2010.
- Blackburn, de Rijke and Venema, Modal Logic, Cambridge University Press, 2001 (only the first chapters will be relevant for the course).

For an introduction to proof theory, you can refer to:
- Mancosu, Galvan and Zach, An introduction to proof theory, Oxford University Press, 2021.
- Troelstra and Schwichtenberg, Basic proof theory, Cambridge University Press, 2000 (only chapters 3 and 4 are relevant for the course).

On nested sequent calculi:
- Brünnler, Deep sequent systems for modal logic, Arch. Math. Logic 48, 551–577, 2009 ([doi](https://link.springer.com/article/10.1007/s00153-009-0137-3)).
- Brünnler, Nested sequents, Habilitationsschrift, Institut für Informatik und angewandte Mathematik Universität Bern, 2010 ([arXiv](https://arxiv.org/abs/1004.1845)).
- Lellmann, Poggiolesi, Nested Sequents or Tree-hypersequents-A survey Saul Kripke on Modal Logic, 2022 ([arXiv](https://hal.science/hal-03590537/)).
- Marin, Straßburger, Label-free modular systems for classical and intuitionistic modal logics, Advances in Modal Logic 10, 2014 ([pdf](http://www.aiml.net/volumes/volume10/Marin-Strassburger.pdf)).


On labelled sequent calculi:
- Negri, Contraction-free sequent calculi for geometric theories with an application to Barr's theorem, Arch. Math. Logic 42, 2003 ([doi](https://link.springer.com/article/10.1007/s001530100124)).
- Negri, Proof analysis beyond geometric theories: from rule systems to systems of rules, Journal of Logic and Computation 26.2, 2016 ([doi](https://academic.oup.com/logcom/article-abstract/26/2/513/2579508?login=false)).
- Negri, Proof analysis in modal logic, Journal of Philosophical Logic 34.5, 2005 ([doi](https://link.springer.com/article/10.1007/s10992-005-2267-3)).
- Garg, Genovese, Negri, Countermodels from sequent calculi in multi-modal logics, 27th Annual IEEE Symposium on Logic in Computer Science, IEEE, 2012 ([pdf](https://people.mpi-sws.org/~dg/papers/lics12.pdf)).
- Negri, Kripke completeness revisited, Acts of Knowledge: History, Philosophy and Logic: Essays Dedicated to Göran Sundholm, 2009 ([pdf](https://www.mv.helsinki.fi/home/negri/gkcrev.pdf)).
- Negri, Proofs and Countermodels in Non-Classical Logics, Log. Univers. 8, 25–60, 2014 ([doi](https://link.springer.com/article/10.1007/s11787-014-0097-1)).
