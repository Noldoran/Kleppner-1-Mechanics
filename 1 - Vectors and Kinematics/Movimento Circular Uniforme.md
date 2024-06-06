O caso mais simples de movimento circular, onde $r$ e $\omega$ são constantes (distância da origem e velocidade angular, respectivamente)

Define-se o vetor posição $\vec{r}$ como a soma dos componentes vertical e horizontal:
$$\vec{r} = r \cos(\omega t)\hat{i} + r \sin(\omega t)\hat{j}$$
![[Movimento Circular Uniforme 2024-03-06 13.47.11.excalidraw]]
%%[[Movimento Circular Uniforme 2024-03-06 13.47.11.excalidraw.md|🖋 Edit in Excalidraw]]%%

Podemos calcular sua [[velocidade tangencial]] $\vec{v}$ como
$$\vec{v} = \frac{d\vec{r}}{dt} = r\omega(-\sin(\omega t)\hat{i} - \cos(\omega t)\hat{j})$$
Similarmente, sua [[aceleração centrípeta]] $\vec{a}$
$$\begin{align}
\vec{a} = \frac{d\vec{v}}{dt} &= \omega^2 \overbrace{r(-\cos(\omega t)\hat{i} - \sin(\omega t)\hat{j})}^{-\vec{r}} \\
&= -\vec{r} \omega^2
\end{align}$$
