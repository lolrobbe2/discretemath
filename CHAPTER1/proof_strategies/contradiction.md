# Proof Strategy 4 — Proof by Contradiction

**To prove:** `p ⇒ q`

**Proof idea:**
- Assume `p ∧ ¬q`  
- Show that this assumption leads to a **contradiction**

This method investigates what would happen if `q` were false, ideally resulting in an impossible or false statement.

---

## Example — Proof by Contradiction

**Statement:**  
Prove that √2 is irrational.

**Definitions:**  
- A **rational number** is a number that can be written as a fraction `k/l` with integers `k ∈ ℤ` and `l ∈ ℕ₀`.  
- An **irrational number** is a number that is not rational.

**Proof:**  
Assume, for contradiction, that `s = √2` is **rational**.  
Then we can write:

> s = k / l, with k ∈ ℕ, l ∈ ℕ₀, and k and l having no common divisor.

Squaring both sides:

> (k / l)² = 2  
> ⇒ k² / l² = 2  
> ⇒ k² = 2 l²

This implies k² is even, so k is even.  
Let k = 2m, with m ∈ ℕ. Then:

> (2m)² = 4 m² = 2 l²  
> ⇒ l² = 2 m²

Thus, l² is even ⇒ l is even.

We now see that **both k and l are even**, which contradicts our assumption that they have no common divisor.  

**Conclusion:**  
Therefore, √2 cannot be rational — it is **irrational**.
