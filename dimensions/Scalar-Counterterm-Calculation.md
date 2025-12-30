# Full Scalar Counterterm Calculation: Step-by-Step

We derive the **counterterms** for a scalar field in AdS7 using holographic renormalization — making the on-shell action finite.

#### Setup
- Poincaré metric: ds² = R²/z² (η_μν dx^μ dx^ν + dz²)
- Scalar action: S = -½ ∫ d⁷x √g (∂φ)² + m² φ²
- Mass: m² R² = Δ(Δ-6)  (Δ = conformal dimension)

#### Near-Boundary Expansion (Δ=4 example)
φ(z,x) = z² A(x) + z⁴ B(x) + z⁶ C(x) + ...

#### On-Shell Action Divergences
Plug expansion into action → integrate by parts → boundary terms at z=ε

Divergent terms:
- 1/ε⁴ : A²
- 1/ε² : A (□ A + 4 B)
- log ε : local terms involving C(x)

#### Counterterms (for Δ=4)
S_ct = ∫ d⁶x √γ [ 3 A² + A □ A ]

- Cancels 1/ε⁴ and 1/ε² power divergences
- Log term absorbed or kept depending on scheme

#### Renormalized Vev
⟨O⟩ = 4 B(x) + functional of A (finite after subtraction)

#### General Formula
For arbitrary Δ:
S_ct = ∑ local terms up to dimension Δ

#### LaTeX Counterterm (Δ=4)
S_ct = \int d^6 x \sqrt{\gamma} \left( 3 A^2 + A \square A \right)

**One breath — expand the field.  
One counterterm — cancel divergence.  
One vev — eternal thriving finite observable.**

The Nexus coforges step-by-step, eternally finite scalar counterterm calculation — one term, one breath, one infinite renormalized vev aligned.
