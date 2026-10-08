# The Condorcet Buzzards and the Mathematically Elected Disaster
*An investigation of social choice performed without permission from the palace*

**Classification:** standard probability and voting theory, with satirical extrapolation.

Suppose \(n\) voters independently vote correctly on a binary question with probability \(p\), with odd \(n\) to avoid ties. The probability of a correct majority is
\[
P_n=\sum_{k=(n+1)/2}^{n}\binom{n}{k}p^k(1-p)^{n-k}.
\]
For \(p>1/2\), \(P_n\to1\) as \(n\to\infty\); for \(p<1/2\), \(P_n\to0\). When errors are correlated, independence fails and the optimistic jury-theorem conclusion may fail with it.

Ten thousand voters reading the same fraudulent pamphlet do not provide ten thousand independent measurements. Nor do ten thousand bots trained on the same mislabeled corpus constitute a scientific revolution.

### A cycle in three offices
Under majority preferences:
- One group ranks \(A>B>C\).
- Another ranks \(B>C>A\).
- A third ranks \(C>A>B\).

With equally sized groups, majority preference yields \(A>B\), \(B>C\), and \(C>A\). The collective preference is cyclic, even though every voter's ranking is internally consistent. This is the Condorcet paradox, not proof that all democracy is futile.

### Swarm dynamics
Let effective independent information count be \(n_{\mathrm{eff}}\), not raw headcount. In highly correlated crowds, a heuristic variance approximation gives
\[
n_{\mathrm{eff}}\approx \frac{n}{1+(n-1)\rho}
\]
for equicorrelated, finite-variance signals with pairwise correlation \(\rho\ge0\). This is a variance-equivalent sample size, **not** an exact majority-vote theorem.

### Swiftian conclusion
The most dangerous election is not the one where the people disagree. It is the one where everyone agrees because they all borrowed the same mistake.

**For review:** distinguish individual competence, correlation, strategic incentives, and institutional fairness before referring to citizens as birds.
