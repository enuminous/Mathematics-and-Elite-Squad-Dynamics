# Goodhart's Gallows: A Peer-Reviewed Metric Eats Its Own Tail
*Department of Administrative Witchcraft*

**Classification:** exact optimization in a toy model; satire. Historical attribution: Goodhart's law is associated with economist Charles Goodhart, and the widespread slogan has several later formulations.

Let true social value be
\[
V(x)=a x-bx^2,\qquad a,b>0.
\]
Let the politically rewarded dashboard show \(M(x)=x\). An agent maximizing value chooses
\[
x^*=\frac{a}{2b}.
\]
A bureaucrat maximizing the metric on \(0\le x\le K\) chooses \(x=K\). If \(K>a/b\), its true value is negative, while the graph in the quarterly slide deck continues heroically upward.

A second form makes the incentives plain:
\[
U(x)=V(x)+\rho M(x)
=(a+\rho)x-bx^2,
\]
so its unconstrained optimum is
\[
x_\rho^*=\frac{a+\rho}{2b}.
\]
Relative to the value optimum, the shift is \(\rho/(2b)\); the loss in genuine value is
\[
V(x^*)-V(x_\rho^*)=\frac{\rho^2}{4b}.
\]
The damage grows quadratically with the reward for bragging.

This is the mathematical career of a target measure: first an indicator, then a shrine, then a police department.

### The Swift Protocol
In *A Modest Proposal*, Swift exposes the monstrosity of treating human beings as accounting entries. Our parody takes the warning literally: a model should report the human meaning of its objective before somebody optimizes it.

### The EFMW/Zoo veto
A TORTOISE-style referee should ask whether the variable described as *success* was selected independently of its optimization. A HEDGEHOG-style skeptic should ask what was omitted. A CROCODILE-style adversary should try to game the score. These are suggested audit roles, not claims of verified Zoo execution.

### Counterargument
Metrics are often useful. The theorem says only that **misaligned** metrics can invite predictable misoptimization; it does not say that measuring things is always corrupt.

*With apologies to Bierce, who would surely have filed the dashboard under "Progress."*
