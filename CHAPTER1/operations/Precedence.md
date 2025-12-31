# Precedence Rules

How to evaluate complex compound propositions:

1. **Parentheses** have highest priority  
2. Evaluate all **negations (`¬`)**  
3. Then **disjunction (`∨`)**, **conjunction (`∧`)**, and **exclusive disjunction (`⊕`)**  
4. Finally **implication (`⇒`)** and **biconditional (`⇔`)**

Within the same precedence level, always evaluate **from left to right**.

---

## Exercise

Evaluate **¬p ⇒ ¬(p ⊕ q)** given:
- `p` = true
- `q` = false

### Step-by-step evaluation

1. `p ⊕ q` → `true ⊕ false` = `true`  
2. `¬(p ⊕ q)` → `¬true` = `false`  
3. `¬p` → `¬true` = `false`  
4. `¬p ⇒ ¬(p ⊕ q)` → `false ⇒ false` = `true`

### Result

**¬p ⇒ ¬(p ⊕ q) = true**
