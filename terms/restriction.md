---
comments: true
cards-deck: terms
---

# Restriction []()

If polynomial $q$ is a restriction of a polynomial $f$ to a line $l$, then for every random point $r$, we have $q(r) = f(l(r))$.

[](1724488973336)

**Example**:

$l(t) = (t + 2,4 - 2t)$\
$f(x, y) = 3xy + 2y$\
$q = 3(t+2)(4-2t) + 2(4-2t) = -6t^2 - 4t + 32$

Random point: $r = 5 \rightarrow l(r) = (7, -6)$

$q(r)=q(5)$
$\iff q(r)=(-6) * 5^2-4 * 5+32 = -138$

$f(l(r))= f(l(5)) = f(7,-6)$
$\iff f(l(r)) =3 * 7 * (-6)+2 * (-6)=-138$


