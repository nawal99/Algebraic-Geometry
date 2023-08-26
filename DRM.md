# Dominant Rational Maps
## Let $X\subseteq {\mathbb{A}_k}^n, Y\subseteq {\mathbb{A}_k}^m$. A rational map $\varphi:X\to Y$ is said to be dominant if $\varphi(X)$ is dense in $Y$. 

Let $U$ be the domain of definition of $\varphi\equiv(\varphi_1,\varphi_2,\dots,\varphi_m)$. Now, we can define ${\varphi}^{\*} :\Gamma[Y]\to k(X)$ such that for any $f\in \Gamma[Y]$, $\varphi^{\*}(f)=f(\varphi_1,\varphi_2,\dots,\varphi_m).$ Since $f$ is a polynomial we can see that $\varphi^{\*}(f)\in k(X)$. 

$\varphi^{\*}$ is a ring homomorphism from $\Gamma[Y]$ to $k(X)$. If $\varphi^{\*}(u)=0$ for some $u\in \Gamma[Y]$ then $u(\varphi_1,\varphi_2,\dots,\varphi_m)=0$ on $U$ and hence $u=0$ in $k(X)$. Let if possible $u$ is not identically zero on $Y$ i.e., $V(u)\subsetneq Y$. Since $u$ is zero on $\varphi(X)$ we have $\varphi(X)\subseteq V(u)$. Taking closure in the both sides and using the fact that $V(u)$ is a closed set we get $\overline{\varphi(X)}\subseteq V(u)$ i.e., $\overline{\varphi(X)}\subsetneq Y$. Contradicting $\varphi(X)$ is dense in Y.
