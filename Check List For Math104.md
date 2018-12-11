## Check List For Math104

- __DEF__: 

  - operation
  - field
    - 9 axioms ($4 +  4 + 1$)
  - ordered field
    - 6 properties

- prove: 1>0

- __DEF__: completeness of ordered field

  - $(\mathbb{Q}, +, \cdot, >)$ is not complete

- __Def__: bounded, bounded above, bounded below

- __DEF__: $Sup_A$

- __Consequences of completeness of $(\real, +, \cdot, >)$__

  - Archimedian property (zoom in & out)
  - Existence of integer part of every real & proof
  - __proof__: Denseness of $\mathbb{Q}$
  - __proof__: Denseness of $\real \setminus \mathbb{Q}$  

- __Triangular inequality__

  - with its two corollaries

- __Bernoulli's__

- __Binomial expansion__

- __Cauchy inequality__

- __A-G-H mean__:

  - harmonic mean
  - geometric mean
  - arithmetic mean

- **Def**: 

  - __neighborhood__ of $a$ for $a \in \real$
  - __Sequnce__
  - $(a_n)_n \rightarrow a, a \in \mathbb{R}$     (2 ways) 

- __Proof__: Uniqueness of limits

- __Every convergent Sequence is bdd & proof__ 

- __Algebra of Limits__

  - $a_n \rightarrow a  \iff a_n - a \rightarrow 0 $

  - $a_n \to 0 \iff |a_n| \to 0 $

  - $a_n \to 0, b_n $ bounded $\implies$ $a_n \cdot b_n \to 0$    

    - & proof 

  - $a_n \to a, b_n \to b $  $\implies a_n + b_n \to a + b$   

    - & proof 

      (*i.e. we can multiply $\epsilon$ by any constant in $\real$*)

  - $a_n \to a, b_n \to b \implies a_n \cdot b_n \to a \cdot b$ 

    - & proof 
    - ($-a \cdot b_n + a \cdot b_n$) 

  - $k \in \mathbb{N}, a_n \to a \implies a_n^{k} \to a^k$

  - $b_n \neq 0, b_n \to b \implies \frac{1}{b_n} \to \frac{1}{b}$

    - & proof (*note: hard)

  - $(a_n)_n \geq 0, k \geq 0, a_n \to a \implies \sqrt[k]{a_n} \to \sqrt[k]{a}$

  - $a > 0$, when $n \to +\infin$, $\sqrt[n]{a} \to 1$

  - when $n \to +\infin$, $\sqrt[n]{n} \to 1$

- __Squeeze Thereom & Proof__

- __Monotone Sequence $(a_n)_n$ converges $\iff$__ 

  - increasing & bdd above 	*or*
  - decreasing & bdd below
  - & proof

- __$(a_n)_n = (1+ \frac{1}{n})^n$ converges__ 

  - proof
  - definition of $e$

- __DEF__:    $+\infty, -\infty$ as limit

  - i.e. as $n \to +\infty, (a_n)_n \to +\infty$
  - 2 ways  

- __ratio test, root test__

  - & proof

- __bolzano-Weierstrasss__ (or whatever it's called)

  - 2 ways of proof
    - peak point
    - nested interval

- __DEF__: Cauchy Sequence

- __Converge $\implies$Cauchy__

  - converse does not hold unless in $\real$ 

- __In any metric space, $(b_n)_n$ cauchy with a subsequence: __

  __$(b_{k_n})_n \to b \in \real \implies b_n \to b$ __

  - & proof

---

#####11. Metric Space

- __DEF__: 

  - topology
  - open / closed set
  - neighborhood
  - basis
  - metric  (distance)
    - 3 properties
    - prove the triangular eqaulity in $d_p$
    - Minkowski's inequality

---

##### 12. Topology Induced by a Metric

- topology induced by a metric $T_d$  ($\{ \empty$, union of ... $\}$)  

- characterisation
- open ball  / open set w.r.t $d$ 
- __proof__: finite intersections of sets in $T_d$ are also in $T_d$ 
- closed ball / closed set
- discrete topology (all subsets are open and closed)

---

#####13. Open Sets and Closed Sets

- Properties of unions and intersections:

  - __finite intersections__ of __open__ sets (def)

  - __arbitrary unions__ of __open__ sets (def)

    $\implies$(due to de morgan's law) 

  - __finite unions__ of __closed__ sets

  - __arbitrary intersections__ of __closed__ set 

    $\implies$

  - all __finite__ sets are __closed__

---

#####14. Closure

- __DEF__: closure
- $\overline{F} = F \iff$ F closed
- proof: $\overline{F}$ is closed (w.r.t d)
- $\overline{F}$ is the smallest closed set containing F
  - proof 

---

#####15. Normed Space

- __DEF__: norm($||\cdot||$)
  - nonnegativity
  - sacalar multiplication
  - triangle inequality
- $||\cdot||_p$ for $p \geq 1$, Minkawski's Inequality
- __def__: memtric induced by norm
- Restrictions of normed space

  - $X$ must be vector space 
  - translation invariant
  - $d_{||\cdot||}$ takes all non-negative values in $\real$
    - a result of $\lambda$ multiplication 

---

#####16. Sequence in Metric Space

- __def__: 

  - Sequence in a metric space
  - Convergence: $(x_n)_n \to x_0 \in X$,  w.r.t d  (3 ways)
- 3 properties for convergent Sequence (say, $\to x_o$)in metric spaces
  - unique limit
  - every subsequence converge
  - bounded w.r.t d(meaning ..?) 
- Extra 3 properties in normed spaces (normed space gives us addition, zero, etc.)
- __DEF__: characterisation of closures / closed sets via sequences 
- 2 techniques to prove $F \subset X$ is closed / not closed 

####_MIDTERM ENDS HERE_ 

----

##### 17. Accumulation Points

- __Def__: accumulation point
- __Proof__: $\overline{A}  = A \cup A'$ ,wher $A' :=$ accumulation points of A,
  - prove: $A \cup A' \sub \overline{A}$
  - prove: $\overline{A} \sub A \cup A'$
- ex: $\overline{(a, b) \cup \{c\}} = ((a, b) \cup \{c\}) \cup ((a, b) \cup \{c\})' = (a, b) \cup \{\} \cup [a, b] = [a b] \cup \{c\}$

---

##### 18. Cauchy Sequences In Metric Space

- __Def__: Cauchy sequence in metric space
- cauchy and convergence
  - the key is to note the difference: cauchy only concerns $d$ and all the elements in the squence, while convergence will also need one extra point: the limit. i.e. we need to think about the ambient space
-  __Def__: Complete metric space (now we include the extra point)
- __proof__: Complete $\implies$ closed

---

##### 19. Limits of Functions

- __Def__: accumulation point $x_0$ of $A$, for $x_0 \in \R, A \subset \R$  
  - 3 ways
- __Def__: $x_0$ isolated point of A, for $A \sub R, x_0 \in A$
- __Def__: $\lim_{x \to x_0} f(x) = l$, for $f: A \to \R$, and $ x_0$ a.c point of $A$. 
  - 3 ways
- $+\infty, -\infty$ as limits
- $+\infty, -\infty$ as A.C. points

---

##### 20. Characterisation of Accumulation Points

- The following three are equivalent
  - $x_0$is an A.C points of A
  - Every neighbourhood of $x_0$ contains infinitely many elements of A, different from $x_0$
  - there exits a sequence $(x_n)_{n \in \N} $in $A$, all of whose terms are pairwise distinct, such that $x_n \to x_0$ 

---

##### 21. Characterisation of Limits via Limits of Sequences

- $\lim_{x \to x_0} f(x) = l$  vs  $f(x_n) \to l $, when $x_n \to x_0$ 
- Corollary: Algebra of limits

---

##### 22. Continuity

- __Def__: $f$ is continuous at $x_0$
  - 3 ways
  - Compare to limits, we now really care about $f(x_0)$
  - consider $x_0$ to be an isolated point 

- Proof continuity
  - by $\epsilon$ definiton 
  - by limit of sequence (i.e. when not an isolation point) 

- __Def__: Continuity via limits of Sequence
- __Thm__: Continuity of algebra of functions ($f + g, \lambda \cdot f, f \cdot g, \frac{f}{g}$)
- __Thm__: Composition of functions, $g \circ f$, peserves  continuity

---

##### 23. Continuity as a Local Property

- Continuity is a local property
- if $f$ is cont. at $x_0$, then $f$ is bounded in a neighbourhood of $x_0$
- Local preservation of sign and points of continuity

---

##### 25. Continuous functions on closed intervals

- Every continuous function $f:[a, b] \to \R$ is bounded.
- (Stronger) Every continuous function $f:[a, b] \to \R$ has a maximal value and minimal value.

---

#####26. IVT

- IVT
  - __Def__: IVT
  - __proof__: IVT
    - 2 ways
  - 3 other forms

---

#####27. Applications of IVT

- Every positive number has a unique n-th root

- Each polynomial of odd degree has a root  in $\R$

- Fix point theorem

- __Def__: Interval

- Continuous images of intervals are intervals

- Continuous on $I$  +  1 to 1 $\implies$ strictly monotone

- $f: I \to \R$ continuous and 1-1

  $\implies$ $f^{-1}: f(I) \to I$  is continuous, and has the same kind of monotonicity

---

##### 28. Continuous functions on metric spaces

- __Def__: Let ($X, d_x$),  ($Y, d_y$) be metric spaces, let $f: X \to Y$, $f$ is continuous at $x_0 \in X$
  - 2 ways

- __Def__: $f^{-1}(A), A \sub Y$
  - $f^{-1}(A)$ is well defined $\forall  A \sub Y$,whether the function $f^{-1}: Y \to X$ is well defined or not  
  - $B \sub f^{-1}(A) \iff f(B) \sub A$
- $f$ continuous  $\iff$$f$ inverts open sets to open sets (i.e. $f^{-1}(U)$ open in ($X, d_x$), for every $U \sub Y,$ open in $(Y, d_y)$) .
  - proof

---

##### 29. Compact Sets

- __Def__: open cover of $K$, $K \sub X$ in  $(X, d)$
  - __Def__: subcover $A' \sub A$
- __Def__: $(X, d)$compact
  - __Def__: compact subset
-  $K \sub X, K$ compact $\implies$ $K$ closed and bounded in $(X, d)$
  - the converse is not always true
  - proof
- Thm: Continuous Functions send compact sets to compact sets.

---

##### 30. Sequentially Compactness

- __Def__: $(X, d)$ Sequentially compact
- Sequentially compact $\implies$closed
  - not closed $\implies$not sequentially compact

---

##### 31. Differentiability

- __Def__: $f$ dfferentiable at $x_0$
  - __def__: derivative of $f$ at $x_0$  
- __Proof__: differentiable $\implies$continuous
- Rules of differentiation
  - 4 
- __Proof__: Chain rule

---

##### 32. Local Extrema

- Thm: $f \uparrow$  $\implies f'(x) \geq 0, \forall x \in (a, b) $; .....
  - $f'(x)$ can be zero even strictly  increasing, consider $x^3, x= 0 $
    - however, $f'(x) > 0 \implies f$ strictly increasing...
- __def__: local extremum
- Fermat's Prop: local extremum at $x_0$  and  $f'(x_0)$ exists $\implies f'(x_0) = 0$
- __def__: critical point

---

##### 33. Rolle's, MVT, L' Hopital

- Rolle's Theorem
  - proof
- Mean Value Theorem
  - proof
- L ' Hopistal
  - __Def__: Cauchy's Generalised Mean Value Theorem 

---

##### 34. Uniform Continuity

- __Def__: Uniform Continuity
- $f: (X, d_x) \to (Y, d_y)$ continuous, $(X, d_x)$ compact $\implies f$ uniformly continuous

---

#####35. Riemann Integration

- $X_I$characteristic function

- $\int X_I :=$ length of $I$ 

- __Def__: step function $\phi$

  - equivalence: $\phi(x) = \sum c_i X_{(x_{i-1, } x_i)}$

  - observation:

    - bounded support
    - continuity

  - $\int\phi$

  - observation: adding subset $\{y_0, y_1, ... y_m\}$ to $\{x_o, x_1, .. x_n\}$ of $\phi$ 

  - Linearity of integral for step function

  - $\phi(x) \geq \phi(x), \forall x \in \R $

    $\iff  \int \phi \geq \int \psi$ 

- __def__: Riemann Integrable (R.I.)

  - prop: step functions are R.I.
  - 2 properties of R.I $f$:
    - f bounded
    - f has bounded support 
  - Theorem: R.I. $f$  with  bounded support $\iff$
  - $\int f​$

---

#####36. R.I. Proof & Corollary

- 2 criterions 

- 2 corollary
- 4 basic properties
- Thm: Any monotone function $f: [a, b] \to \R$ is Riemann Integrable.  
- Thm: Any continuous function $f: [a, b] \to \R$ is Riemann Integrable.  