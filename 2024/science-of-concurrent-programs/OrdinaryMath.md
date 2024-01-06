# Ordinary Math

Boolean operators vs Mathglish 

$$
\\
 \lnot \quad  negation \: not \qquad \Rightarrow implies
\\
\land \quad conjunction \: and \qquad \equiv \text{if and only if}
\\
\lor \quad disjunction \: or \qquad \forall for all
$$

Negation

$$
\\
\lnot TRUE \equiv FALSE
\\
\not FALSE \equiv TRUE
$$

And

$$
\\
\\ TRUE \land TRUE \equiv TRUE
\\ TRUE \land FALSE \equiv FALSE
\\ FALSE \land TRUE \equiv FALSE
\\ FALSE \land FALSE \equiv FALSE
$$

Definition of other operators $\lor, \Rightarrow, \ and \equiv$ in terms of $\lnot \ and \ \land$.

$$
\\
A \lor B \coloneqq \lnot (\lnot A \land \lnot B)
\\
A \Rightarrow B \coloneqq \lnot A \lor B
\\
A \equiv B \coloneqq (A \Rightarrow B) \land (B \Rightarrow A)
$$

Or

$$
\\
\\ TRUE \lor TRUE \equiv TRUE
\\ TRUE \lor FALSE \equiv TRUE
\\ FALSE \lor TRUE \equiv TRUE
\\ FALSE \lor FALSE \equiv FALSE
$$

Implication

$$
\\
\\ TRUE \Rightarrow TRUE \equiv TRUE
\\ TRUE \Rightarrow FALSE \equiv FALSE
\\ FALSE \Rightarrow TRUE \equiv TRUE
\\ FALSE \Rightarrow FALSE \equiv TRUE
$$

Equivalence (need to represent it better)

$$
\\
\\ TRUE \equiv TRUE \equiv TRUE
\\ TRUE \equiv FALSE \equiv FALSE
\\ FALSE \equiv TRUE \equiv FALSE
\\ FALSE \equiv FALSE \equiv TRUE
$$

Tautologies with names :
Can be derived by substituting $\land, \lor, and \equiv$ for $*, +, and =$. The last one is a special case, this has no counterpart in ordinary arithmetic.

$$
Commutativity :\\
\\ \vDash A \land B \equiv B \land A
\\ \vDash A \lor B \equiv B \lor A
\\
Associativity :\\
\\ \vDash A \land (B \land C) \equiv (A \land B) \land C
\\ \vDash A \lor (B \lor C) \equiv (A \lor B) \lor C
\\
Distributivity : \\
\\ \vDash A \land (B \lor C) \equiv (A \land B) \lor (A \land C)
\\ \text{Special Case.}
\\ \vDash A \lor (B \land C) \equiv (A \lor B) \land (A \lor C)
$$

De Morgan's Laws

$$
\\
\vDash \lnot (A \land B) \equiv \lnot A \lor \lnot B
\\
\vDash \lnot (A \lor B) \equiv \lnot A \land \lnot B
\\
Transitivity : \qquad
\vDash (A \Rightarrow B) \land (B \Rightarrow C) \Rightarrow (A \Rightarrow C)
$$
