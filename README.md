# SmoothedHuber
This repository provides a modification to the Huber loss function proposed in (reference to Huber 1964.

\begin{align*}
\rho_{k}(x)=\left\{\begin{matrix}
\frac{1}{2}x^{2} & \left | x \right | \leq k\\ 
k  \left | x \right | -\frac{1}{2}c^{2}&  \left | r \right | > c
\end{matrix}\right.\\
\frac{\mathrm{d} }{\mathrm{d} x} \rho_{k}(x)=\psi_{k}(r)=\left\{\begin{matrix}
 -k &x<-k \\ 
 x &\left |x \right | \leq k\\ 
 k & x>k
\end{matrix}\right.
\end{align*}
