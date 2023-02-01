**Definition**
1. A family $\{X_t\}$ of _random variables_ on a [[Measurability|probability space]] $(\Omega, \mathcal{F},\mathbb{P})$ is called a **stochastic process.**
2. **Continuity** of a stochastic process: if for almost all $\omega \in \Omega$, $X(\omega): t\mapsto X(t)(\omega)$ is continuous on $T=[0,T], T>0$
3. $X(\omega)$ is called a **sample path**
Note that due to measuring, there appears several degrees of _sameness_ between X and X':
4. If $\mathbb{P}(X(t)=X'(t))=1,\,\forall t\in T$  we say that $X'$ is a **modification** of $X$.
5. **The same distribution** if for all partition $\{t_i\}$ of $[0,\infty)$ and $A \in \mathcal{B}(R^{nd})$ $\mathbb{P}((X_{t_1},...,X_{t_n}) \in A) = \mathbb{P}((X'_{t_1},...,X'_{t_n}) \in A)$ 
6. **Indistinguishable**(we also say that almost all pahts agree) $\mathbb{P}(X_t=X'_t; \forall t)=1$

**Remark**
* modification and indistinguishability needs the processes to be in the same probability space
* sameness through distribution is quite powerful way to define stochastic processes because it does not depend on the construction of the underlying probability space

#### Predictable process
A stochastic process $(f_n)$ is called **predictable** if $f_n$ is $\mathcal{F_{n-1}}$-measurable for all n.


**Kolmogorov's continuity theorem**