---
title: CAP — a categorical (re)organization of computer algebra
comments: false
---

###### Talk at [<Q>Topos Institute Colloquium</Q>](https://topos.institute/events/topos-colloquium/) <br/> Topos Institute <br/> Berekely, California <br/> 17 July 2025

###### Abstract:

In this talk I will introduce CAP (Categories, Algorithms and
Programming), a multi-package open-development software project for
algorihmic category theory. CAP is currently loosely organized by the
3-category of doctrines. By a "doctrine" we mean a 2-category of
structured categories, structure-preserving 2-functors, and natural
transformations between them. Compositions of such 2-functors applied
to a specific category give rise to what we call "categorical towers",
a highly economic and modular way to create various computational
contexts in computer algebra. Such modular code cannot be optimized by
hand for comptutational performance as it would require breaking the
modularity: Each layer in the tower treats the layer below merely as a
blackbox. This forced us to develop CompilerForCAP, a
category-theory-aware compiler that is able to get rid of the entire
categorical abstraction and produce efficient low-level code which is
almost impossible to write by hand, let alone error-free.


<https://www.youtube.com/watch?v=t1v13J-P7RE&list=PLhgq-BqyZ7i7gcP-hFVqIqQDpK3e4AsfZ>
