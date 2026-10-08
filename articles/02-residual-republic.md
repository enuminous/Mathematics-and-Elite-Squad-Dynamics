# The Residual Republic: A Constitution for Error-Correcting Scoundrels
*An EFMW-inspired field note in the spirit of Swift, Bierce, and H. L. Mencken*

**Classification:** elementary proof for a specified recurrence; political metaphors are satire. This does not establish an EFMW physical law.

A republic whose rulers never admit error is an unstable filter. A filter that forgets everything is a television interview.

## Operational definition
Let observations be \(y_t\), forecasts \(\hat y_t\), and residuals \(r_t=y_t-\hat y_t\). Define a recursive tracker:
\[
m_{t+1}=\lambda m_t+(1-\lambda)r_{t+1},\qquad 0\le\lambda<1.
\]
The name *EFMW-style residual monitor* acknowledges a family resemblance to the Monolithic experimental program; no claim of fundamental physics is implied.

Unrolling the recurrence gives exactly
\[
m_t=\lambda^t m_0+
(1-\lambda)\sum_{k=1}^{t}\lambda^{t-k}r_k.
\]
If \(|r_t|\le R\), then
\[
|m_t|\le\lambda^t|m_0|+R(1-\lambda^t)
\le \max(|m_0|,R).
\]
For constant \(r_t=r\), subtraction gives
\[
m_t-r=\lambda^t(m_0-r),
\]
so the estimator converges geometrically to \(r\).

## The Bierce Amendment
The system is forbidden to describe the vanishing of its residual as proof that its forecast is true. It may merely have learned to conceal dissent inside its measurement process. This is a distinction between **internal consistency** and **external validity**.

## The Thompson Test
Give the filter an abrupt change at time \(\tau\). Compare its detection delay at matched false-positive rate with EWMA, CUSUM, and a robust median baseline. If the avant-garde watchdog merely outperforms a straw man chosen by its own editor, publish the embarrassment in large type.

## Speculative EFMW extension
Couple multiple local residual monitors by a graph Laplacian:
\[
\mathbf m_{t+1}=
\lambda\mathbf m_t+(1-\lambda)\mathbf r_{t+1}-\eta L\mathbf m_t.
\]
Convergence and stability now depend on the spectrum of \(L\), step size \(\eta\), and the input process; these conditions cannot be wished into existence by giving the equation a splendid name.

*The editor's enemies are certainty without calibration and politics without an error bar.*
