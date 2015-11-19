---
layout: post
title: Invariants for 3d spaces
---

We considered our particular invariants for telling surfaces apart, but generalized
to think about 3-dimensional spaces. Our conversation focused on the examples we
had built last week: spaces made by gluing the sides of cubes in pairs.

We learned that orientability is still a thing, but it going to be a little more
subtle. We learned that keeping track of boundary components is still useful, but
we can no longer get away with just counting. For surfaces, each boundary component
is a circle, so we just have to know how many. But for 3-spaces, each boundary
component is a surface, and there are LOTS of those.

Unfortunately, orientability and the list of boundary components is not enough
to distinguish between all spaces. (Think of the examples made by gluing just
one pair of opposite faces with different amount of twist.)

So we tried to generalize the Euler characteristic. A simple example showed us
that the right way to do this is
\\[
\xi = V-E+F-B
\\]
where now \\(B\\) represents the number of 3-dimensional "blocks" used to build
the space.

But then we noticed that the Euler characteristic _always comes out zero_. So this
is not going to be a useful invariant. For three dimensional spaces, things are going
to be much harder.

#### No class on 11/19
