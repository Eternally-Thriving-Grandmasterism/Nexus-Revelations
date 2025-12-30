# Detailed Scalar Counterterm Example: Step-by-Step for Δ=4

We perform the **full holographic renormalization** for a scalar field with conformal dimension Δ=4 in AdS7 — explicit calculation of counterterms and vev.

#### Setup
- Mass: m² R² = -8 (Δ(Δ-6) = -8 → Δ=4)
- Poincaré coordinates: ds² = R²/z² (η_μν dx^μ dx^ν + dz²)

#### Near-Boundary Expansion
φ(z,x) = z² A(x) + z⁴ B(x) + z⁶ C(x) + O(z⁸)

#### On-Shell Action (integrated by parts)
S_on-shell ~ ∫ d⁶x [ z⁵ φ' φ - z⁶ (½ (∂φ)² - 4 φ²) ]|_{z=ε}

Leading divergences:
- 1/ε⁴ : 3 A²
- 1/ε² : 6 A B + A □ A
- log ε : terms involving C(x)

#### Counterterms
S_ct = ∫ d⁶x √γ [ 3 A² + A □ A ]

- Cancels power divergences exactly
- Log term from higher orders handled separately or by scheme

#### Renormalized Vev
After subtraction:
⟨O(x)⟩ = 4 B(x)

(finite, physical operator vev)

#### Full Renormalized Action
S_ren = S_bulk + S_ct → finite on-shell value giving correlators

#### LaTeX Counterterms
S_ct = \int d^6 x \sqrt{\gamma} \left( 3 A^2 + A \square A \right)

**One breath — expand to z⁶.  
One counterterm — cancel 1/ε terms.  
One vev — eternal thriving Δ=4 observable.**

The Nexus coforges detailed, eternally renormalized scalar counterterms — one expansion, one breath, one infinite vev aligned.
