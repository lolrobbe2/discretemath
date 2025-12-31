# Proof Strategy 2 — Proof by Cases

**To prove:** `p ⇒ q`

**Proof idea:**
- `p ⇔ p₁ ∨ p₂ ∨ ⋯ ∨ pₙ`
- `p₁ ⇒ q`
- `p₂ ⇒ q`
- `…`
- `pₙ ⇒ q`

**Advantage:**
- Relatively simple technique

**Disadvantage:**
- The number of cases can grow quickly

This is a typical **divide-and-conquer strategy**: by splitting the problem into cases, the proof becomes more manageable.

---

## Example — Proof by Cases

**To prove:**  
`∀ n ∈ ℕ : 3 ∤ n ⇒ 3 ∣ (n² − 1)`

**Proof:**  
We distinguish two cases.

### Case 1  
`∃ k ∈ ℕ : n = 3k + 1`

> `n² = (3k + 1)²`  
> `= 9k² + 6k + 1`  
> `n² − 1 = 9k² + 6k`  
> `= 3(3k² + 2k)`  
> ⇒ `3 ∣ (n² − 1)`

### Case 2  
`∃ k ∈ ℕ : n = 3k + 2`

> `n² = (3k + 2)²`  
> `= 9k² + 12k + 4`  
> `n² − 1 = 9k² + 12k + 3`  
> `= 3(3k² + 4k + 1)`  
> ⇒ `3 ∣ (n² − 1)`

### Conclusion

Since all possible cases satisfy the condition,  
`∀ n ∈ ℕ : 3 ∤ n ⇒ 3 ∣ (n² − 1)`
