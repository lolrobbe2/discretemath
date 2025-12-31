# Proof Strategy 1 — Direct Proof

**To prove:** `p ⇒ q`

**Proof outline:**
- `p ⇒ r₁`
- `r₁ ⇒ r₂`
- `…`
- `rₙ ⇒ q`

**Advantage:**
- Simple technique

**Disadvantage:**
- Requires some inventiveness

---

## Example — Direct Proof

**To prove:**  
`∀ n ∈ ℕ : n is odd ⇒ n² is odd`

**Proof:**

> Assume `n` is odd  
> ⇒ `∃ k ∈ ℕ : n = 2k + 1`  
> ⇒ `n² = (2k + 1)²`  
> ⇒ `n² = 4k² + 4k + 1`  
> ⇒ `n² = 2(2k² + 2k) + 1`  
> ⇒ `∃ k ∈ ℕ : n² = 2k + 1`  
> ⇒ `n²` is odd
