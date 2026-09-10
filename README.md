# Digital Filters &mdash; State, Structure and Stability

Deck 02 of the [Matrix Methods in Engineering](https://github.com/BrendanJamesLynskey/Mathematics#linear-algebra) pair.

**Live presentation:** https://brendanjameslynskey.github.io/Matrix_Concepts_Digital_Filters/

Three matrix ideas do the organising work in digital filter design. Eigenvalues of the
state matrix decide stability, Hermitian positive-semidefinite structure decides the
optimal taps, and paraunitary structure decides whether you can take a signal apart and
put it back together again.

## What's inside

- Three matrix structures in one filter &mdash; and the analogue-to-digital boundary dictionary
- The state matrix $\mathbf{A}$: $|\lambda_k| < 1$, minimal realisations, why FIR cannot blow up
- **Interactive:** pole explorer &mdash; drag $r$ and $\theta$, watch the $z$-plane, the magnitude response and the ringing move together (push $r$ past 1 and watch it go unstable)
- Why tones are the natural language: exponentials are the eigenvectors of an LTI filter
- The shortest possible EQ lesson &mdash; a two-point averager and its zero at $z = -1$
- Hermitian matrices and optimal taps: Wiener&ndash;Hopf, Toeplitz structure, Levinson&ndash;Durbin
- **Interactive:** the eigenfilter bowl &mdash; a Rayleigh quotient over three taps, with snap-to-eigenvector
- Paraunitary matrices and lossless filter banks
- **Interactive:** a rotation once per frequency &mdash; break the paraunitary structure and watch perfect reconstruction fail
- The analogue &harr; digital cross-map
- What the linear theory does not model: quantised coefficients, overflow, limit cycles

## Long-form companion

The same material as a written report:
[Matrix_Concepts_Digital_Filters.pdf](Matrix_Concepts_Digital_Filters.pdf) (7 pp).

## Companion deck

[Matrix Methods in Network Parameters](https://github.com/BrendanJamesLynskey/Matrix_Methods_Network_Parameters)
&mdash; the same structures in continuous time, for RF and high-speed digital networks.

Single-page HTML, KaTeX-rendered maths, no build step. Open `index.html` directly.
