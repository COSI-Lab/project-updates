---
layout: post
title: Type Theory Study Group: First Meeting
author: Corey Richardson
---

The type theory study group met for the first time today. We talked about chapters 1 through
3 of [TaPL]. This covered the history and motivation of type systems, some mathematical
preliminaries, and the first formal language that we'll be studying. In terms of the math, we
reviewed set theory, relations, and various forms of induction. The first formal language is
a very simple language ("NB") consiting of booleans and natural numbers. Our next meeting will
be Thursday at 18:30 in SC334 or SC336 depending on how occupied/loud the labs are. For next
time, the assignment is to finish the exercises from chapter 3 and implement an interpreter for
NB (which is the subject of chapter 4). I'll write a tutorial for how to do this in Rust on Monday.

Recommended exercises for Thursday:

- 3.5.5 (more practice with induction principles, 5 minutes)
- 3.5.9 (practice with inference rules, 5 minutes)
- 3.5.13 (analyzing the consequences of language changes on existing proofs, 10 minutes)
- 3.5.14 (first proof about a language! try and get the structure of the proof, if not necessarily the details. 30 minutes)
- 3.5.16 (makes the evaluation relation total, by formalizing error states, 45 minutes)
- 3.5.17 (a proof about the equivalence of two different ways to model the language, 45 minutes)
- 3.5.18 (practice changing the evaluation relation to reflect language changes, 20 minutes)
- Implement NB (2 hours, possibly more if you do fancy parsing)

3.5.16 and 3.5.17 are challenging, but form the core of what many later proofs will look like.
If any particular problem takes you longer than the estimate, you should stop and either ask
for help or try again after some sleep. Doing all of this should take no longer than 5 hours.
And, of course, we'll go over all of it on Thursday.

[TaPL]: https://www.cis.upenn.edu/~bcpierce/tapl/
