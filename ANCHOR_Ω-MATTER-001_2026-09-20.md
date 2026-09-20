# MATTER ANCHOR — Ω-MATTER-001

**Date:** 2026-09-20  
**Status:** FIXED CHECKPOINT / RESEARCH ANCHOR

## FACT

Ω-Math defines typed relations:

`EntityState={0,1}`  
`RelationState={-1,+1}`

The mathematical extension layer has established a conditional two-field conservative structure:

`∂t E = ω C B`  
`∂t B = -ω C E`

and a Hamiltonian/Poisson-like representation under explicit domain and boundary conditions.

The Re/Im decomposition of the Schrödinger equation,

`iħ ∂t ψ = Hψ`,

with `ψ=E+iB`, has the same two-channel antisymmetric structure:

`ħ ∂t E = H B`  
`ħ ∂t B = -H E`.

## CHECK

This is a structural mathematical correspondence, **not** a derivation of quantum mechanics.

The missing bridge is the operator:

`RELATIONS → H_R`

such that a relation-defined operator produces the required spectral dynamics without inserting quantum mechanics by hand.

The following are also OPEN:

`|ψ|² → physical probability`

and

`relational density → gravitational contribution`.

## RESULT

Current verified chain:

`±1 relation → operator → conservation/constraint → spectrum → mode → propagation`

A candidate extended chain is:

`relation structure → H_R → ψ_R → |ψ_R|² → ρ_R → effective dynamics → observable`

The physical interpretation of each new bridge remains unproven.

## DECISION

Do not claim that matter is a wave function of relations or that dark matter is relational matter.

Next decisive test:

1. construct minimal `H_R` directly from the typed relation structure;
2. calculate its spectrum;
3. evolve `ψ_R`;
4. test norm conservation;
5. compare topology/sign controls;
6. only then test whether a stable coarse-grained `ρ_R` exists;
7. only after that test any gravitational observable.

## FIXATION

This anchor preserves the state reached on 2026-09-20.  
Previous results remain historical and are not overwritten.

**Rule:** FACT → CHECK → RESULT → DECISION → FIXATION.


---

## ADDENDUM — Ω-MATTER-001 → H_R BRIDGE COMPLETED

The decisive mathematical bridge `RELATIONS → H_R` has now been tested and fixed in:

`SmartVoltISA/--Math-A-New-Language-of-Mathematics/EXPERIMENT_MATTER_HR_BRIDGE_001.md`

### RESULT

Preferred operator:

`H_R = D - A_R`

where `A_R` contains the typed relation signs `r_ij ∈ {-1,+1}` and `D` is the ordinary degree matrix of the declared graph.

Verified:

- `H_R = H_R^T`;
- real spectrum;
- Schrödinger-type evolution `i dψ/dt = H_R ψ` preserves norm;
- maximum norm error in the finite spectral run: `4.44×10^-16`;
- 1D analytic dispersion agreement: `2.22×10^-15`;
- relation-sign organization changes spectrum and localization;
- 2D random-sign control increased median IPR from `0.00656` to `0.01545` in the tested 20×20 model.

### NEGATIVE RESULT

The alternative `H=B R B^T` was tested and rejected as the canonical operator because its spectrum is not invariant under the natural node-sign gauge transformation.

### CURRENT CHAIN

`typed relation → signed operator H_R → spectrum → ψ_R → norm-preserving dynamics`

### STILL OPEN

`|ψ_R|² → physical probability`

`ρ_R → physical matter density`

`ρ_R → gravitational contribution`

No physical quantum or dark-matter claim is promoted by this result.

**Rule preserved:** FACT → CHECK → RESULT → DECISION → FIXATION.


### ADDENDUM 2 — FINITE-SIZE SCALING

Follow-up scaling on 1D cycles `n={20,40,80,160}` was executed.

Odd signed topology produced:

`λ₀ = {0.0246233, 0.00616533, 0.00154193, 0.000385519}`

with

`λ₀ n² → 9.8693 ≈ π²`

and fitted exponent approximately `-2.000`.

Therefore the signed-cycle spectral shift survives at finite size but its lowest mode closes as `n^-2`.

**Decision:** no size-independent gap in this construction. Proceed to `ψ_R → |ψ_R|² → ρ_R` rather than interpreting the finite spectral shift as mass.
