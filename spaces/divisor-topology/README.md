---
uid: S000049
slug: divisor-topology
name: Divisor Topology
---
Let $X = \{x \in \mathbb{N} : x \geq 2\}$ with topology generated by all $U_n = \{x \in X : x$ divides $n\}$ for $n \in X$.

See also:

* Steen, L. A.; Seebach, J. A. (1970), [Counterexamples in Topology](http://books.google.com/books/about/Counterexamples_in_Topology.html?id=DkEuGkOtSrUC), Dover, pp 79-80.
* [Divisor topology](http://en.wikipedia.org/wiki/Divisor_topology) on Wikipedia.

[[Proof of Topology]]
To prove the set $\mathscr{B}=\{B_n : n\in X\}$ is a basis for a topology on $X$, we must prove:
$$\text{ For every } x\in X \text{ there exists some } B_n \text{ such that } x\in B_n$$
$$\text{ If }x\in B_a \cap B_b, \text{ there exists some } B_c \text{ such that } x\in B_c\subset B_a\cap B_b$$
To prove the first condition, note that for every $x\in X$, $x$ divides $x$. So by definition, $x \in B_x$. 
To prove the second, let $x\in B_a\cap B_b$. It follows that $x\in B_a$ and $x\in B_b$ This is to say, $x$ is a common divisor of $a$ and $b$. Note that if $x \in B_n$, it follows that $x$ divides $n$. Therefore, all of the divisors of $x$ divide $n$ and thus are in $B_n$. The set $B_x$ is the set of all divisors of $x$, so $x\in B_x \subset B_a\cap B_b$. We have shown that both conditions hold, so therefore the set $\mathscr{B}$ is a basis for topology on $X$.

