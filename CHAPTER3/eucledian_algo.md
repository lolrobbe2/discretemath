# Euclidean Algorithm

One of the **oldest known mathematical algorithms** (circa 300 BC).

It is used to compute the **greatest common divisor** `ggd(a, b)` of two integers `a` and `b`.

## Algorithm (Subtraction Version)

1. Repeat while `a ≠ b`:
   - Subtract the smaller number from the larger one
2. When `a = b`, this value is the **greatest common divisor**

## Example

ggd(35, 126)  
= ggd(35, 91)  
= ggd(35, 56)  
= ggd(35, 21)  
= ggd(14, 21)  
= ggd(14, 7)  
= ggd(7, 7)  
= **7**

## Important Consequence — Bachet–Bézout Theorem

There exist integers `u, v ∈ ℤ` such that:

ggd(a, b) = u · a + v · b

The integers `u` and `v` are called the **Bézout coefficients**  
(and they are **not unique**).
