# The Doppler-Smith Correspondence 
## Shared Möbius Structure in Impedance and Frequency Ratios

**Series:** Mathematical Foundations for Universal Systems  
**Author:** Carolina Johnson (CJ)  
**Date:** July 2026  
**DOI:** [https://doi.org/10.5281/zenodo.21451980](https://doi.org/10.5281/zenodo.21451980)  
**License:** CC BY 4.0 (Attribution required)

---

## What This Does

Identifies a shared algebraic structure between the Smith chart, a foundational graphical tool in electrical engineering, and the Doppler frequency shift.

We show that both are expressible through the same bilinear (Möbius) form:

$$
\Gamma = \frac{u - 1}{u + 1}
$$

Where $u$ represents normalized impedance $z = Z/Z_0$ or a normalized frequency ratio $1 + \beta$, with $\beta = v/c$. This shared form follows directly from the general identity $(A-B)/(A+B) = T(A/B)$ for any two positive quantities, making it a property of the normalized-ratio construction itself.

---

## The Problem It Solves

The Smith chart is a powerful and well-understood tool for visualizing impedance matching in electrical engineering. The Doppler shift is a ubiquitous phenomenon in wave physics. Although they belong to different physical domains, both are governed by the same underlying functional form.

Recognizing this isomorphism allows the extensive graphical and computational tooling developed for the Smith chart over eight decades to be reused directly for analyzing Doppler-ratio problems and, as demonstrated in this paper, for acoustic cavity resonance analysis.

---

## The Correspondence

For the Smith chart:

$$
\Gamma = \frac{z - 1}{z + 1}, \quad z = \frac{Z}{Z_0}
$$

For a normalized Doppler frequency ratio:

$$
\Gamma_D = \frac{u - 1}{u + 1}, \quad u = \frac{f_{\text{obs}}}{f_0} = 1 + \beta
$$

**Theorem (Shared Möbius Form):**
Let $\Gamma$ be the reflection coefficient for normalized impedance $z$, and let $\Gamma_D$ be the normalized Doppler coefficient for frequency ratio $u$. Then:

$$
\Gamma = T(z), \qquad \Gamma_D = T(u)
$$

where $T(x) = (x-1)/(x+1)$ is the same function in both cases.

The paper proves this theorem, derives the explicit real and imaginary components of the reflection coefficient, and demonstrates the application to a standard acoustic tube resonance calculation.

---

## Repository Contents

- `Doppler-Smith Correspondence.pdf` — Full paper with derivations, worked example, and references.
- `README.md` — This file.

---

## Citation

Johnson, C. (2026). *The Doppler-Smith Correspondence: Shared Möbius Structure in Impedance and Frequency Ratios*. Series: Mathematical Foundations for Universal Systems. SemanticShift. DOI: [https://doi.org/10.5281/zenodo.21451980](https://doi.org/10.5281/zenodo.21451980)  
License: CC BY 4.0

---

## Dependencies

This paper builds upon the following work from the same series:

| Framework | DOI |
|-----------|-----|
| Taylor-Doppler Identity: Frequency Transport on a Phase Manifold | [https://zenodo.org/records/21102010](https://zenodo.org/records/21102010) |

---

## License

© 2026 Carolina Johnson (CJ)  
Licensed under Creative Commons Attribution 4.0 International (CC BY 4.0)  
Attribution required.  
[https://creativecommons.org/licenses/by/4.0/](https://creativecommons.org/licenses/by/4.0/)
