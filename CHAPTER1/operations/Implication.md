- [Implication (IF)](#implication-if)
  - [Truth Table — Implication](#truth-table--implication)
  - [Necessary and Sufficient Conditions](#necessary-and-sufficient-conditions)
    - [Example](#example)

# Implication (IF)

The `implication` of `q` from `p` is *false* if and only if **p is true and q is false**.

`Notation (statement):`
- `p ⇒ q`

> [!NOTE]
> An implication is expressed in sentences as  
> “**if p, then q**”.

- `p` is called the **hypothesis** or **antecedent**
- `q` is called the **conclusion** or **consequent**

## Truth Table — Implication

| p   | q   | p ⇒ q |
| --- | --- | ------ |
| 0   | 0   | 1      |
| 0   | 1   | 1      |
| 1   | 0   | 0      |

## Necessary and Sufficient Conditions

- `q` is a **necessary condition** for `p`  
  This means that `p` can only be *true* if `q` is *true`.  
  Otherwise, the statement `p ⇒ q` would be *false*.

- `p` is a **sufficient condition** for `q`  
  This means that if `p` is *true*, then `q` must also be *true*,  
  but `q` may still be *true* even when `p` is *false*.

### Example

- `p` = “Tobias passes in June”  
- `q` = “Tobias is allowed to go to Pukkelpop”

We then express `p ⇒ q` as:

- “If Tobias passes in June, he is allowed to go to Pukkelpop”
- “Passing in June is sufficient to be allowed to go to Pukkelpop”
- “If Tobias is not allowed to go to Pukkelpop, then he did not pass in June”
