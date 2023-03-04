## Discrete time martingales
Let $X=\{X_n\}_{n=0}^\infty$ is a discrete-time process that is [[Filtration|adapted]] to $(\mathcal{F_n})_{n=0}^\infty$
Then $X$ is caleed a **martingale** if $X_n$ is [[Measurability|integrable]] for each $n$ and 
$$
\text{E}[X_{n+1}|\mathcal{F_n}] = X_n\,\,\, a.s.
$$
if $\geq$ we call it a **submartingale**
if $\leq$, **supermartingale**
