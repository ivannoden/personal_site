---
title: "Notes on Elliptic Curves with Complex Multiplication"
tags: ["notes", "files", "number theory", "algebraic geometry", "algebraic curves"]
date: "2024-10-02"
---

Over the summer of 2024, I was funded by UCL to undertake a research project
under the supervision of Assoc. Prof. Cecilia Busuioc. I am very grateful to
UCL for funding this and especially thankful for all the work Cecilia did in
helping me with the project. She was a brilliant supervisor and I am very glad
to have been able to work with her.

The project was on elliptic curves with complex multiplication. Below is
attached a set of explanatory notes on the topic and I have pasted the
introduction here for convenience.

The study of algebraic number theory is primarily the study of
algebraic number fields, that is finite extensions of the rationals.
When studying field extensions, one of the most indispensable tools is
that of the Galois group of the extension and the famous result of
Kronecker-Weber tells us that every finite extension of \( \mathbb{Q} \) with
an abelian Galois group is contained in a field of the form \(
\mathbb{Q}(\zeta_n) \) where \( \zeta_n \) is a primitive \( n \)th root of
unity. One may then ask, given some number field \( K \), does there
exist a field \( L \) such that every abelian extension of \( K \) is a
subfield of \( L \)? This explanatory note aims to partially answer
that question in the case where \( K = \mathbb{Q}(\sqrt{-m}) \) for some
square-free \( m \in \mathbb{Z}_{>0} \), that is an imaginary quadratic field.
To do so, we will develop the theory of elliptic curves with complex
multiplication which provides us with a correspondence between certain
sets of elliptic curves over \( \mathbb{C} \) and the class group of an order 
in an imaginary quadratic field. This correspondence relies on values
of the miraculous \( j \)-invariant, and it is \( j(\tau) \), for some
\( \tau \) in the upper half plane that will generate the field \( L \)
we are after. This result requires the machinery of class field theory,
which we will not go into detail on. We will, however, build up enough
understanding to motivate and grasp the statement of the theorems.
Along the way, we will give a detailed account of the uniformisation
theorem; delve into the study of modular functions; and end by proving
some remarkable facts about the \( j \)-invariant, in particular that,
if \( \tau \) is an algebraic integer in an imaginary quadratic field,
then \( j(\tau) \) is also an algebraic integer.

The structure of this note is as follows. We open with
*2. Elliptic Curves* which very briefly recaps key definitions
relating to elliptic curves, mainly to cement definitions and
conventions. With *3. Elliptic Functions*, we study elliptic
functions, in particular, the Weierstrass \( \wp \)-function, which we
will show can be used to parameterise an elliptic curve isomorphic to a
complex torus. The content of *4. Uniformisation Theorem* then shows
that every elliptic curve is one of this form and hence isomorphic to a
complex torus. To prove this, we introduce modular functions and the \(
j \)-invariant. We then take a brief aside in *5. Some Ideas from Class Field Theory*
to recap basic ideas of algebraic number theory and then cover some of
the main results of class field theory, including the answer to the
problem of abelian extensions of imaginary quadratic fields. These
results are very useful in *6. Complex Multiplication* where we
introduce the notion of elliptic curves with complex multiplication and
use them to show that \( j(\tau) \) is an algebraic integer when \(
\tau \) is an algebraic integer in an imaginary quadratic field.
*7. Calculating Examples* is then devoted to finding explicit values
of \( j(\tau) \) in these cases.

Whilst we aim to explain the majority of the theory needed, there are a
few prerequisites required for understanding this text. Primarily, we
recommend the reader be comfortable with the fundamentals of Galois
theory, specifically the fundamental theorem. Also, it would be helpful
if the reader were somewhat already familiar with the basic ideas of
elliptic curves and algebraic number theory as we make extensive use of
both and the recaps given do not go into a lot of detail.

[Download](/files/elliptic_curves_with_cm.pdf)
