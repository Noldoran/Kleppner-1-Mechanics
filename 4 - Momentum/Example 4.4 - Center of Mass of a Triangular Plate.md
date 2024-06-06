> Calculating the center of mass is straightforward if the object can be subdivided into parts with known centers of mass. Consider the two-dimensional case of a uniform right triangular plate of mass $M$, base $b$, height $h$, and small thickness $t$.
> Divide the triangle into strips of width $\Delta x$ parallel to the y axis, as shown.
> ![[Pasted image 20240531162534.png]]

$h_{j} = x_{j} (h/b)$ 
$dV = t h_{j} \Delta x$
$\rho = 2M/tbh$
$$\begin{align}
\rho &= \frac{dm}{dV} \\
\frac{2M}{tbh} &= \frac{dm}{th_{j}\Delta x} \\
dm &= h_{j}\frac{2M\cancel{t}\Delta x}{\cancel{t}bh} \\
dm &= \frac{x_{j}\cancel{h}}{b}\frac{2M\Delta x}{b\cancel{h}} \\
dm &= \frac{2Mx_{j}}{b^2}\Delta x = \frac{2Mx}{b^2}dx
\end{align}$$
$\vec{r}_{j}(x) = x\hat{i} + \frac{1}{2} h_{j} \hat{j} = x\hat{i} + xh/(2b) \hat{j}$
$$\begin{align}
\vec{R} &= \frac{1}{M} \int \vec{r} \, dm \\
\vec{R} &= \frac{1}{M} \int \left( x\hat{i} + \frac{h_{j}}{2} \hat{j} \right) \frac{2Mx}{b^2} \, dx \\
\vec{R} &= \frac{1}{\cancel{M}} \frac{2\cancel{M}}{b^2} \int \left( x\hat{i} + \frac{xh}{2b} \hat{j} \right)x \, dx \\
\vec{R} &= \frac{2}{b^2} \int \left( x^2\hat{i} + \frac{x^2h}{2b} \hat{j} \right) \, dx \\
\vec{R} &= \frac{2}{b^2} \left( \hat{i} \int_{0}^{b} x^2 \, dx + \frac{h}{2b} \hat{j} \int_{0}^{b} x^2 \, dx \right) \\
\vec{R} &= \frac{2}{b^2} \left( \hat{i}\left( \frac{b^3}{3} \right) + \frac{h}{2b} \hat{j}\left( \frac{b^3}{3} \right) \right) \\
\vec{R} &= \frac{2}{b^2} \left( \frac{b^3}{3} \hat{i} + \frac{hb^2}{6} \hat{j} \right) \\
\vec{R} &= \frac{2}{3}b \hat{i} + \frac{1}{3} h\hat{j} \\
\end{align}$$