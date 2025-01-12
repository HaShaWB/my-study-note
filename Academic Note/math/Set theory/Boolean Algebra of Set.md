## Boolean Algebra
세 [[Set|sets]] $A, B, C$를 subsets으로 갖는 set $U$에 대해, 다음과 같은 Boolean algebra가 성립한다
1. **Minimal Elements**: 
   $$ A \cup \varnothing = A, \;\; A \cap \varnothing = \varnothing $$
2. **Maximal Elements**:
   $$ A \cup U = U, \;\; A \cap U = A $$
3. **Identity**:
   $$ A \cup A = A, \;\; A \cap A = A $$
4. **Commutativity**:
   $$ A \cup B = B \cup A, \;\; A \cap B = B \cap A $$
5. **Associativity**:
   $$ \begin{align} (A \cup B) \cup C = A \cup (B \cup C) \\ (A\cap B)\cap C = A \cap (B\cap C) \end{align} $$
6. **Distributivity**:
   $$
\begin{align}
A \cap (B \cup C) = (A \cap B) \cup (A \cap C)\\
A \cup (B \cap C) = (A \cup B) \cap (A \cup C)
\end{align}
 $$
7. **Partition**:
   $$ A \cup (U \backslash A) = U \; \land \; A \cap (U\backslash A) = \varnothing $$
8. **De Morgan's Law**:
   $$ (A\cup B)^c = A^c \cup B^c, \;\; (A\cap B)^c = A^c \cap B^c $$