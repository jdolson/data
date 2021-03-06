---
uid: S000044
slug: nested-interval-topology
name: Nested Interval Topology
---
Let $X$ be the set $(0,1)$ and define a topology on $X$ consisting of all sets $U_n = (0,1-\frac{1}{n})$ for $n \geq 2$ (along with $\emptyset$ and $X$).

See also:

* Steen, L. A.; Seebach, J. A. (1970), [Counterexamples in Topology](http://books.google.com/books/about/Counterexamples_in_Topology.html?id=DkEuGkOtSrUC), Dover, pp 76-77.
* [Nested interval topology](http://en.wikipedia.org/wiki/Nested_interval_topology) on Wikipedia.

[[Proof of Topology]]
1. Note that $X \in N$ by definition and $U_1=(0,1-\frac{1}{1})=(0,0)= \emptyset$ thus $\emptyset \in N$. 

2. Let $I$ be any indexing set of $n \in \mathbb{N}$ where $\bigcup\limits_{n \in I} U_n$ where $U_n \in N$. Thus
\begin{align*}
\bigcup\limits_{n \in I} U_n &= U_{max(n) \in I}, or X
\end{align*}
Which are both open. 

3.  Let $I$ be any finite indexing set of $n \in \mathbb{N}$. Thus 
\begin{align*}
\bigcap\limits_{n \in I} U_n &= U_{min(I)}
\end{align*}
which is an open set so any finite union of open sets is open.

