# Proof Strategy 5 — Mathematical Induction

**To prove:** ∀ n ∈ ℕ : P(n) is true

**Proof by weak induction:**

1. **Base step**  
   Prove: P(0) (or P(1), depending on convention) is true.

2. **Induction step**  
   Prove: ∀ n ∈ ℕ : P(n) ⇒ P(n + 1)

Although this may appear to be inductive reasoning, it is a **deductive proof technique**.

---

## Example — Mathematical Induction

**Statement:**  
∀ n ∈ ℕ₀ : Sₙ = 1 + 2 + 3 + ⋯ + n = n(n + 1)/2 (this is P(n))

### Step 1 — Base step

Prove P(1) is true:

> S₁ = 1 = 1⋅(1 + 1)/2

True, as the sum of the first positive integer is 1.

---

### Step 2 — Induction step

Assume P(n) is true for some n ∈ ℕ₀:

> Sₙ = n(n + 1)/2  (induction hypothesis)

Prove P(n + 1):

> Sₙ₊₁ = Sₙ + (n + 1)  
> = n(n + 1)/2 + (n + 1)  
> = (n(n + 1) + 2(n + 1))/2  
> = (n + 1)(n + 2)/2

Hence, P(n + 1) is true.

---

**Conclusion:**  
By mathematical induction,  
∀ n ∈ ℕ₀ : Sₙ = 1 + 2 + 3 + ⋯ + n = n(n + 1)/2
