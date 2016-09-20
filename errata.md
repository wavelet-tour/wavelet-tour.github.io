---
layout: page
title: "Errata"
description: "of the book"
header-img: "img/wave1.jpg"
---
Here is a list of errors detected in the third edition of the book.

If you find an error, please [let us know about it](gabriel.peyre at ens.fr).

- Images 13.6 (a) and 13.6 (b) should be swapped.
- On page 22, bellow eq. 1.15, the right inequalities should read
\sum_{m \in Gamma} |<f,\tilde{\phi_{p}}>|^2 <= A^(-1) ||f||^2
- The Gradient Pursuit algorithm (reference [115], page 672) does not, as stated in the book, "solve the l1 Lagrangian minimisation (12.97)". The algorithm described in the reference is a fast approximation to OMP and the reference would be better in the OMP section of the book.
- Exercise 6.4(a): on the right hand side of the equation, it should be $\cos(w_0 u)$ rather than $\cos(w_0 t)$.
Follow-up to the current second item on the errata list: On page 22, Below and above eq. 1.15, ${m \in Gamma}$ should be ${p \in Gamma}$
- On page 112, Example 4.11, 2nd to the last line: "quadratic chirp" should be "linear chirp"
- On page 114, top line: Current: This discrete wavelet has $Ka^j$ nonzero values... Correct: This discrete wavelet has $N/(K a^j)$ nonzero values...
- On page 114, above eq. 4.65: two places in the equation for $\phi_J$: $a^j$ should be $a^J$.
- On page 115, 3rd line from top: ${a^j}$ should be ${a^j}_{j \in [I,J]}$.
- On page 171, equation at top: leading factor on right has $1/2^j$ should be the square root of this. (or else the norm has to change in eq. 5.54 and elsewhere).
- On page 267, below eq. 7.12: in the numerator of phi on the right: Current numerator: $t - n$, Correct numerator: $t - n 2^j$ (since this is for the orthonormal basis, not the time-invariant version).
Theorem 7.1 on p.267: The argument in $\phi_{j,n}(t)$ is written as $\phi[(t-n)/2^j]$. It should be $\phi( [t - 2^j n] / 2^j)$.
- On page 677, the iteration for the sparse analysis resolution should read $\tilde F_{k+1} = S_{\mu T}( \tilde F_k + \mu U^*(Y-U\tilde F_k) )$, i.e. $\gamma$ should be replaced by $\mu$.
It is in Eq. (8.106), p. 423, one should replace [n-a_p] with [n-a_p-1/2].
- On page 739, paragraph "Restricted Isometry and Incoherence", the sentence
  _"If the vectors are normalized vectors then $A_\La \leq 1 \leq B_\La$, and it is equivalent to impose that $\delta_\La = \max(1 - A_\La, B_\La - 1)$ is not too small. To get a stable recovery of all sparse signals, compressive sensing imposes a uniform bound on all sufficiently sparse sets $\La$:
    $\delta_\La \geq \delta_M(\DU) > 0 ~~\mbox{if}~~~|\La| \leq M ,$ "_
should be replaced by:
  _"If the vectors are normalized vectors then $A_\La \leq 1 \leq B_\La$, and it is equivalent to impose that $\delta_\La = \max(1 - A_\La, B_\La - 1)$ is not too CLOSE TO 1. To get a stable recovery of all sparse signals, compressive sensing imposes a uniform bound on all sufficiently sparse sets $\La$: $\delta_\La \leq \delta_M(\DU) < 1 ~~\mbox{if}~~~|\La| \leq M,$"_
- On page 739, 8 lines before the end of the page:
  _"A simple geometric interpretation explains why random measurement operators define incoherent dictionaries with $\delta_M (\DU) > 0$ for relatively large $M$."_
should be replaced by
  _"A simple geometric interpretation explains why random measurement operators define incoherent dictionaries with $\delta_M (\DU) < 1$ for relatively large $M$."_
- On page 107, before equation (3.35), should be "(Exercise 4.6)".
- Bottom of page 156 "$\lambda$ is also an eigenvector of $\Phi\Phi^*$".
- Page 55, exercise 2.3, references should be (2.18), (2.19) and (2.21).
- Page 57, exercise 2.17, should be "$f(x_1,x_2)=1_{x_1^2+x_2^2 \leq 1}$".
- Page 86, exercise 3.9, should be "recovers $f(t)$ from $\{f(p s)\}_{p \in \ZZ}$."
- Page 86, exercise 3.12, should be "from any $0 \leq k < N$".
- Page 86, exercise 3.16, b), should be "if $h[n]= a \delta[n-p]$ for some $p \in \ZZ$ and $a \in \CC$".
- Page 676, 5th equation, should be $\tilde a_{k+1}[p] = ...$.
- Page 60, before (3.6), should be "the Poisson formula, Theorem 2.4".
- Pages 320-322, the uper-script "pér" should be replaced by "per".
- Exercise 2.9, one needs to impose that $K < M$.
- In p. 676, $\tilde{a}^{k+1}=a^{K}+\gama * b^{k=1}$ should be $\tilde{a}^{k+1}=a^{K}-\gama * b^{k=1}$.
- In p. 156, On the bottome of this page, in the sentence: "Both Statements are proved to be equivalent...", Phi conjugate times Phi" should be "Phi conjugate times Phi" and "Phi times Phi conjugate".
- Exercise 4.4, the result is $O(N^2 log L)$.
- Exercise 4.9, one needs to use $1/2pi$ and not $1/pi$.
- Exercise 4.17, several errors, see corection.
- Exercise 5.1, it is required that $K \geq 1$.
- Exercise 5.6, one needs to impose $||phi_p || = 1$.
- Exercise 5.9, one needs $\hat g = 1_[-\om0/2,\om0/2]$.
- Exercise 5.10, the sum should run in $mM - K/2$ to $mM + K/2-1$.
- Exercise 5.15, several errors, see the correction.
- Exercise 5.18, one needs to impose that $\hat phi (\om)$ tends to 0 when $omega$ tends to infinity.
- On page 218 (paragraph 6.2.1), "See figure 6.5b on page 218 ..." should be "See figure 6.5b on page 220 ...".
- On page 37, before Theorem 2.2, $exp(i t w)$ are the eigenvector of the convolution operator (and not eigenvalues).
- On p.156, "are equal to...":, one should add: "on $Im \Phi$".
- On p.156, last line: "$\Phi \Phi^*^$ with ..." instead of "$\Phi^* \Phi^$ with...".
- On p.157 eq 5.6 one should replace $<\phi_n, \phi_p>$ by $<\phi_m, \phi_p>$.
- On p.36, in the proof of Theorem 2.1 it should read "We cannot apply the Fubini Theorem A.2" instead of "We cannot apply the Fubini Theorem reffubini".
- On page 103 4.3.1 the transform using a real valued wavelet is defined using a capitalized W. However, throughout 4.3.1 a lower case w is used to indicate the real wavelet transform. On the other hand on page 109 the analytic wavelet transform is defined using lower case w, while in the remaining chapter 4.3.2 upper case W is used.
- On page 106: the equation (4.40) lacks the integral from 0 to infinity on the variable s.
- In page 758, for the definition of operator $U$'s image, $Im U$ in line before subsection "Supremum Norm": $H_1$ should be $\mathbf{H}_1$ since $H_2$ is a Hilbert space not a operator.
In page 758, the first equation of "A.4 LINEAR OPERATORS", $\forall f_1,f_2\in\mathbf{H}$should be$\forall f_1,f_2\in\mathbf{H}_1$, since $f_1, f_2$ are defined as vectorss in $H_1$ while $H$ is not defined.
In page 40 before equation (2.31), "applying (2.22) proves that" should be "applying (2.21) proves that", for it used the time derivatives property of Fourier transform.
- On page 129, in the definition of $g_{s,u,\xi}(t)$, $\sqrt(s)$ should be $\frac{1}{\sqrt(s)}$.
- On page 130, in equation(4.109), before the first sign of equality should be $\frac{\eta(u)}{s}$.
- On page 136, the second part of the equation before the last paragraph should be $[-2(u_0-u)-T,-2(u_0-u+T)]$.
- On page 136, the second line of the last paragraph $\abs{u_0-u} \le T$ should be $\abs{u_0-u} \le T/2$.
- On page 137, the last part of (4.129) should be $P_vg(\frac{u}{s},s\xi)$.
- In exercise 2.10, section (b) it should be asked to prove that $\hat{f_r} = H \hat{f_i}$ and $\hat{f_i} = - H \hat{f_r}$.
- At p. 685, in the proof of Theorem 12.15 an argument is missing because one might have that the support of $\tilde a_{\Lambda}$ is strictly included in $\Lambda$. One should use the monoticity of ERC with respect to the support.
- Page 51, equation (2.70), 1/N should be modified to N.
- Table 7.5 " on page 325: The coefficient 0.8705... is listed for the pair (k,l) = (-2,-1), but should be for (k,l) = (-1,-1).
- The negative indices in table 7.5 is not consistent with the remainder of the section where the scaling functions near both the left and the right edge are indexed with non-negative integers. The negative indices are, however, used in the original article of Cohen, Daubechies and Vial.
- On page 324 in the proof of Theorem 7.17 about boundary scaling functions it is mentioned that the support of the functions adapted to the right edge is [-p-n,0]. However, in figure 7.18 on page 326 of these scaling functions for p=2, \phi_0 has support [-3,0] and \phi_1 has support [-2,0]. (In the original article there are similar plots and there the support is as described in the text)
