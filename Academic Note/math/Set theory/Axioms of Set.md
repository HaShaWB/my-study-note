## Axioms
### Set is Object
모든 [[Set|set]]은 그 자체로 object이다
### Axiom of Extensionality (Equality of Sets)
두 sets $A$, $B$가 서로 같다는 것은 $A$의 모든 elements가 $B$에 존재하고, $B$의 모든 elements가 $A$에 존재하는 것이다
$$
A = B \Longleftrightarrow  A \subseteq B  \; \land B \subseteq A
$$
### Axiom of Empty Set
Empty set은 존재한다. 이때, empty set은 유일하다
$$ \exists \varnothing \; \forall x, \;\; x \notin \varnothing $$
### Axiom of Singleton Set & Pair Set
- **Singleton Set**: 모든 object $a$에 대해, element가 $a$로 유일한 set $\{a\}$가 존재한다.
  $$ y \in \{a\} \; \Longleftrightarrow y = a $$
- **Pair Set**: 모든 object $a$, $b$에 대해, elements로 $a$, $b$ 만을 갖는 set $\{a, b\}$가 존재한다.
    $$ y \in \{a, b\} \; \Longleftrightarrow y = a \; \lor y = b$$
### Axiom of Specification
임의의 proposition에 대해, 해당 [[Proposition#^condition|condition]]을 만족시키는 objects를 elements고 갖는 set이 존재한다
$$
\exists A, \; y \in A=\{x: P(x)\} \Longleftrightarrow P(y)
$$
### Axiom of Union
임의의 두 sets $A$와 $B$에 대해, 두 sets의 union이 존재한다
$$ \exists (A\cup B) := \{x: x\in A \; \lor \; x \in b\} $$
### Axiom of Replacement
하나의 set $X$의 모든 element $x$에 대하여, $y= φ (x)$가 유일하게 존재한다면, $y$를 elements고 갖는 set이 존재한다
$$
\forall x \in X, \exists!y=φ(x) \Longleftrightarrow \exists Y = {y: φ(s)}
$$

### Axiom of Infinity
Elements가 natural number라고 불리는 Infinite set이 존재한다.
$$ \exists \mathbb{N} $$

## Lemmas
- **Finite Choice**: Empty set이 아닌 set $A$에 대하여, $x \in A$를 만족하는 object $x$가 존재한다
- $\{a, b\} = \{a\} \cup \{b\}$
- **Partial Order of (proper) subset**: for sets $A, B, C$
  $$ \begin{align} 
  A \subseteq B \; \land \; B \subseteq C \; &\Longrightarrow A \subseteq B \\
  A \subseteq B \; \land \; B \subseteq A \; &\Longrightarrow A = B \\
  A \subsetneq B \; \land \; B \subsetneq C \; &\Longrightarrow A \subsetneq C\\
  \end{align}$$
- **Boolean Algebra**: ![[Boolean Algebra of Set]]