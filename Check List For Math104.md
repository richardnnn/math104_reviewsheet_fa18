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





36. Riemann Integration

- $X_I$characteristic function

- $\int X_I :=$ length of $I$ 

- __def__: step function $\phi$

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
  - $\int f$



37. R.I. Proof & Corollary

- 2 criterions 

- 2 corollary
- 4 basic properties
- Thm: Any monotone function $f: [a, b] \to \R$ is Riemann Integrable.  
- Thm: Any continuous function $f: [a, b] \to \R$ is Riemann Integrable.  