# Simplifying Logical Expressions

Logical expressions can be simplified by applying the **laws of propositional logic**.  
**Note:** No laws are directly provided for `⇒`, `⇔`, or `⊕`.  
To simplify, first rewrite these operators using only `¬`, `∧`, and `∨`:

- `p ⇒ q ≡ ¬p ∨ q`  
- `p ⇔ q ≡ (¬p ∨ q) ∧ (¬q ∨ p)`  
- `p ⊕ q ≡ (p ∧ ¬q) ∨ (¬p ∧ q)`

---

## Step 1 — Rewrite using ¬, ∧, ∨

> p ⇒ (p ⊕ q) ≡ ¬p ∨ ((p ∧ ¬q) ∨ (¬p ∧ q))

## Step 2 — Apply associative and commutative laws

> ¬p ∨ ((p ∧ ¬q) ∨ (¬p ∧ q)) ≡ (¬p ∨ (p ∧ ¬q)) ∨ (¬p ∧ q)

## Step 3 — Apply distributive laws

> ¬p ∨ (p ∧ ¬q) ≡ (¬p ∨ p) ∧ (¬p ∨ ¬q) ≡ true ∧ (¬p ∨ ¬q) ≡ ¬p ∨ ¬q

## Final Simplified Expression

> p ⇒ (p ⊕ q) ≡ ¬p ∨ ¬q
