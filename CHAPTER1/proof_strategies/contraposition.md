# Proof Strategy 3 — Proof by Contraposition

**To prove:** `p ⇒ q`

**Proof idea:**
- Prove `¬q ⇒ ¬p`

This relies on the logical equivalence  
`p ⇒ q ≡ ¬q ⇒ ¬p`  
(which can be verified using a truth table).

**Advantages:**
- The proof can be simpler, especially when `¬q` is more general or easier to handle than `p`

**Disadvantage:**
- Less intuitive than a direct proof

---

## Example 1 — Proof by Contraposition

**To prove:**  
`∀ n ∈ ℕ : 3n + 2 is odd ⇒ n is odd`

**Proof:**  
The consequent (`n is odd`) is more general and easier to work with than the antecedent.  
Therefore, we use contraposition and prove:

`n is even ⇒ 3n + 2 is even`

Assume `n` is even.

> `n is even`  
> ⇒ `∃ k ∈ ℕ : n = 2k`  
> ⇒ `3n + 2 = 3(2k) + 2`  
> `= 6k + 2`  
> `= 2(3k + 1)`  
> ⇒ `3n + 2` is even

**Conclusion:**  
Since the contrapositive holds,  
`∀ n ∈ ℕ : 3n + 2 is odd ⇒ n is odd`

## Example 2 — Proof by Contraposition

**To prove:**  
∀ n ∈ ℕ : n² is even ⇒ n is even

**Proof:**  
We use **contraposition** and prove the equivalent statement:  
n is odd ⇒ n² is odd

Assume n is odd.  
Then:
∃ k ∈ ℕ such that n = 2k + 1

Compute:
n² = (2k + 1)²  
   = 4k² + 4k + 1  
   = 2(2k² + 2k) + 1

This is of the form 2m + 1, which is odd.

**Conclusion:**  
Since the contrapositive is true, the original statement holds:  
∀ n ∈ ℕ : if n² is even, then n is even.
