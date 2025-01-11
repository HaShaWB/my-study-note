### Truth Table
- 임의의 proposition에 대하여, 해당 proposition의 truth value에 대응되는 다른 proposition의 truth value를 나타낸 표
### Negation (¬)
- proposition의 truth value를 반전
  $$ \begin{array}{c|c} p & \neg p \\ \hline T & F \\ F & T \end{array} $$
  $$ \begin{array}{c|c|p} p & \neg p & \neg(\neg p) \\ \hline T & F & T\\ F & T & F \end{array} $$
### Conjunction ($\land$)
- 'AND': 두 proposition이 동시에 true일 때 만 true인 연산
  $$\begin{array}{cc|c} P & Q & P \land Q \\ \hline T & T & T \\ T & F & F \\ F & T & F \\ F & F & F \end{array}$$
### Disjunction ($\lor$)
- 'OR': 두 proposition 중 하나라도 true면 true인 연산
  $$ \begin{array}{cc|c} P & Q & P \lor Q \\ \hline T & T & T \\ T & F & T \\ F & T & T \\ F & F & F \end{array} $$
### Implication ($\to$)
- 앞선 proposition이 뒤의 proposition을 '함의'하고 있는지를 나타내는 연산
  $$ \begin{array}{cc|c} P & Q & P \rightarrow Q \\ \hline T & T & T \\ T & F & F \\ F & T & T \\ F & F & T \end{array} $$
### Biconditional ($\leftrightarrow$)
- 양 방향으로 implication을 만족하는 두 명제
- 명제의 equivalence를 나타냄 (두 명제가 같은지를 표현)
  $$ \begin{array}{cc|c} P & Q & P \leftrightarrow Q \\ \hline T & T & T \\ T & F & F \\ F & T & F \\ F & F & T \end{array} $$

## Properties
- **Double Negation**: $$\neg(\neg P) \equiv P$$
- **Idempotent Laws**: $$
	\begin{aligned}
	P \land P &\equiv P \\
	P \lor P &\equiv P
	\end{aligned}$$
- **Commutative Laws**: $$
	\begin{aligned}
	P \land Q &\equiv Q \land P \\
	P \lor Q &\equiv Q \lor P
	\end{aligned}$$
- **Associative Laws**:$$
	\begin{aligned}
	(P \land Q) \land R &\equiv P \land (Q \land R) \\
	(P \lor Q) \lor R &\equiv P \lor (Q \lor R)
	\end{aligned}$$
- **Distributive Laws**: $$
	\begin{aligned}
	P \land (Q \lor R) &\equiv (P \land Q) \lor (P \land R) \\
	P \lor (Q \land R) &\equiv (P \lor Q) \land (P \lor R)
	\end{aligned}
	$$
- **Identity Laws**: $$
	\begin{aligned}
	P \land \text{T} &\equiv P \\
	P \lor \text{F} &\equiv P
	\end{aligned}
	$$
- **Domination Laws**: $$
\begin{aligned}
P \lor \text{T} &\equiv \text{T} \\
P \land \text{F} &\equiv \text{F}
\end{aligned}
$$
- **Absorption Laws**: $$
	\begin{aligned}
	P \lor (P \land Q) &\equiv P \\
	P \land (P \lor Q) &\equiv P
	\end{aligned}
	$$
- **De Morgan's Laws**: $$
	\begin{aligned}
	\neg (P \land Q) &\equiv \neg P \lor \neg Q \\
	\neg (P \lor Q) &\equiv \neg P \land \neg Q
	\end{aligned}
	$$

