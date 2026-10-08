# The Ministry of Percolation: When a Rumor Becomes a Government
*A probabilistic investigation into the sudden dignity of nonsense*

**Classification:** branching-process heuristic, valid in its stated random-network limit; institutional analogies satirical.

Consider a sparse Erdős–Rényi random graph \(G(n,c/n)\) for large \(n\). A locally tree-like neighborhood has approximately Poisson\((c)\) offspring. Let \(q\) denote the probability that a branch dies out. Its fixed-point equation is
\[
q=e^{c(q-1)}.
\]
A giant connected component emerges for \(c>1\). Its asymptotic vertex fraction \(s\) satisfies
\[
s=1-e^{-cs}.
\]
For \(c\le1\) the only nonnegative solution is \(s=0\); for \(c>1\) a positive solution appears.

This is a theorem about random graphs, not a theorem that any specific false rumor or party will go viral. Real social contagion needs adoption rules, heterogeneous networks, correlated behavior, and exposure data.

### Departmental interpretation
A rumor below threshold remains the property of a drunk in a corridor. Above threshold it acquires a letterhead, an advisory council, and a procurement budget. Bierce, Mencken, and Thompson would not need to agree on ideology to recognize the ritual.

### Experiment: the rumor and the evidence
Simulate 1,000 random graphs at increasing mean degree \(c\), measure largest-component fractions, and compare to the positive fixed-point branch. Repeat with strong community structure; document the discrepancy. Then introduce an independently verified signal and ask whether evidence spreads any faster than theater.

### EFMW conjecture
If agents locally revise beliefs in response to residual error, there may be a critical connectivity regime for correction propagation. That is a **new modeling question** requiring an explicit update rule; the percolation result above does not prove it.

**Editorial line:** Everything is connected, except—frequently—the conclusion and the premises.
