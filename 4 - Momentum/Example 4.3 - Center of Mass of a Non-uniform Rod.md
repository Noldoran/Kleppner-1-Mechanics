> A rod of length $L$ has a non-uniform density. The mass per unit length of the rod, $\lambda$, varies as $\lambda = \lambda_{0} (x/L)$, where $\lambda_{0}$ is a constant and $x$ is the distance from the end marked $0$. Find the center of mass.
> ![[Pasted image 20240531162417.png]]

$dm = \lambda \, dx$
$$\begin{align}
M &= \int_{0}^{L} \lambda_{0} \frac{x}{L} \, dx \\
M &= \frac{\lambda_{0}}{L} \int_{0}^{L} x \, dx \\
M &= \frac{\lambda_{0}}{L} \left( \frac{L^2}{2} - \frac{0^2}{2} \right) \\
M &= \frac{\lambda_{0}L}{2}
\end{align}$$

Estamos integrando em uma única dimensão (o comprimento da vara), portanto nosso vetor posição pode ser expresso como o escalar $x$
$$\begin{align}
R &= \frac{1}{M} \int_{0}^{L} x \, dm \\
R &= \frac{2}{\lambda_{0}L} \int_{0}^{L} \lambda_{0} \frac{x^2}{L} \, dx \\
R &= \frac{2}{L^2} \int_{0}^{L} x^2 \, dx \\
R &= \frac{2}{L^2} \frac{L^3}{3} \\
R &= \frac{2}{3} L
\end{align}$$
