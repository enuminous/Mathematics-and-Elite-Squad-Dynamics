# The Laplacian Coup: How Neighbors Overthrow the Central Committee
*A pamphlet of spectral graph theory, with insufficient reverence for officials*

**Classification:** standard consensus mathematics plus explicit satire.

Take an undirected, connected graph with symmetric adjacency weights \(A\), degree matrix \(D\), and Laplacian \(L=D-A\). Each vertex knows its neighbors and not the grand strategy printed by headquarters.

Consider
\[
x_{t+1}=(I-\eta L)x_t.
\]
Because \(L\mathbf1=0\), the average state is conserved. Expand \(x_0\) into orthonormal Laplacian eigenvectors. The constant mode survives. Every nonconstant mode is multiplied by \(1-\eta\lambda_i\) at each step.

Hence, for connected graphs, if
\[
0<\eta<\frac{2}{\lambda_{\max}(L)},
\]
all nonconstant modes decay and
\[
x_t\longrightarrow \overline{x}_0\mathbf1.
\]
This is ordinary linear-algebraic consensus, not a machine discovering moral truth.

The slowest surviving nonconstant mode is controlled by the spectral gap \(\lambda_2\) and the chosen step size. Networks with bottlenecks can take an age to agree; adding a well-placed edge may accomplish more than appointing seventeen new deputies.

### The revolution's defect
Consensus can spread a *shared error* perfectly. If every voter is wrong by the same amount, \(L\mathbf1=0\) makes that error invisible to neighbor disagreement. Consensus is a property of a process, not a certificate of reality.

This is why Jonathan Swift's institutional absurdity and Norbert Wiener's cybernetic feedback belong on the same desk. Bierce would demand a definition of *agreement* that mentions whom it serves. Thompson would ask who paid for the graph.

### Experiment
Generate a path, a ring, and a complete graph of equal size. Use the same \(\eta\) selected to satisfy stability in each case, random initial states, and log \(\|x_t-\bar x\mathbf1\|_2\). Check rates against the computed eigenvalues. Do not claim that the fastest graph is automatically the most democratic.

**Verdict:** A great many apparent leaders are merely expensive edges.
