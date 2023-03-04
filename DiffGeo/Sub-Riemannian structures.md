Let $M$ be a connected smooth manifold.
A **sub-Riemannian structure** on $M$ is a pair $(U,f)$ where
1) $U$ is a Euclidean bundle with base space $M$ and Euclidean fibers $U_q$
2) $f:U\to TM$ is a morphism of vector bundles and is fiber-wise linear such that the following diagram commutes
$$
\begin{CD}
U @>{f}>> TM\\
@VVV @V{\pi}VV \\
 @>{\pi_U}>> M
\end{CD}
$$
3) The set of horizontal vector fields $\mathcal{D}:=\{f(\sigma);\sigma:M\to U \text{ is a smooth section}\}$ is a bracket-generating family of vector fields