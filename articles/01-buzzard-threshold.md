# The Buzzard Threshold: On the Numerical Superiority of Idiots
*Matthew Chenoweth Wright — Mathematics and Elite Squad Dynamics, Vol. 1 (2026)*

**Classification:** theorem within a toy model; the ornithology and political implications are satire.

## Abstract
The buzzard possesses numbers, confidence, a committee, and a remarkable immunity to the sight of the cliff. A smaller, better-coordinated squad may outperform it. We quantify the insult.

## The model
Let a group's task output be
\[
E(N,c,f)=\frac{Nc}{1+f(N-1)},
\]
where \(N\ge1\) is group size, \(c>0\) is per-agent effective competence and coordination, and \(f\ge0\) is pairwise congestion per additional participant. These are **definitions**, not discovered laws of nature.

For buzzards B and squad S, the squad wins precisely when
\[
\frac{N_Sc_S}{1+f_S(N_S-1)}>
\frac{N_Bc_B}{1+f_B(N_B-1)}.
\]
Thus the required competence multiplier is
\[
\frac{c_S}{c_B}>
\frac{N_B}{N_S}
\frac{1+f_S(N_S-1)}{1+f_B(N_B-1)}.
\]
Take \(N_S=5,N_B=100,f_S=.02,f_B=.20\). Then \(c_S/c_B>1.03846\). A five-person squad needs only about four percent higher per-member effectiveness in this extremely congested toy world.

A minister will call this elitism; a biologist will ask for measurements; a campaign consultant will suggest increasing the flock to 200.

## Theorem: diminishing returns by design
For \(f>0\), regarding \(N\) as continuous,
\[
\frac{\partial E}{\partial N}=
\frac{c(1-f)}{[1+f(N-1)]^2}.
\]
At \(f=1\), output is constant in \(N\); at \(f>1\), adding agents **reduces** output. The absurdity is a feature of the assumed congestion model, not a universal theorem about crowds.

## Editorial dispatch
Ambrose Bierce's *The Devil's Dictionary* supplies the administrative temperament; Hunter S. Thompson's political journalism supplies the appropriate suspicion toward self-congratulating power. Neither was consulted on the algebra. No bird was peer-reviewed.

## Falsification
Measure throughput and interference across team sizes; estimate \(c,f\) on held-out observations. Reject this convenient caricature if it predicts poorly against additive or network-based alternatives.

*Related:* [Residual Republic](02-residual-republic.md) · [The Laplacian Coup](03-laplacian-coup.md).
