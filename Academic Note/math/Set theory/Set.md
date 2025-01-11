## Set
- **Set**: 순서가 없는 object의 모임
- **Object**: 수학의 대상이 되는 모든 것
- **Element**: Set에 속하는 각각의 object 
  $$ x \in A := \text{x is element of A}$$
### Basic Notation
각 notation에 대한 존재성 등은 뒤의 axioms에서 자세히 규정한다
- **Subset ($\subseteq$)**: 두 sets $A$, $B$에 대해, $A$의 모든 elements가 $B$의 elements일 때, $A$를 $B$의 subset이라 한다
  $$A \subseteq B := \forall a \in A,\; a \in B$$
- **Proper Subset ($\subset$)**: 두 sets $A$, $B$에 대해, $A$는 $B$의 subset이지만, $B$는 $A$의 subset이 아닐 때, $A$를 $B$의 proper subset이라 한다
  $$ A \subset B := A\subseteq B \; \land \; B \nsubseteq B $$
- **Empty Set ($\varnothing$)**: Element가 없는 set
- **Union ($\cup$)**: 두 set $A$, $B$에 대해, $A$ 또는 $B$의 elements를 elements로 하는 set
  $$ A\cup B = \{x: x \in A \; \lor \; x \in B\} $$
  (위와 같이 set의 elements를 [[Proposition#^condition|condition]]을 통해 정의할 수 있으며, 이를 **set-builder notation**라고 한다)
- **Intersection**: 두 set $A$, $B$에 대해, $A$와 $B$의 공통된 elements를 elements로 하는 set
  $$ A\cap B \; = \; \{ x: x \in A \; \land \; x \in B  \}$$
- **Disjoint**: 두 sets의 공통된 element가 없는 한 쌍의 sets
  $$ A\text{ and }B\text{ are disjoint} \Longleftrightarrow A \cap B = \varnothing $$
- **Difference Set ($A \backslash B$)**: 두 set $A$, $B$에 대하여, $A$의 elements이나 $B$의 elements는 아닌 것을 elements로 하는 set
  $$ A \backslash B \; = \; \{ x: x\in A \; \land \; x \not\in B \}$$