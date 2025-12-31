# Integers Modulo n

## Definition and Notation

- ℤₙ = {0, 1, 2, …, n − 1}, with n ∈ ℕ, n ≥ 2

## Properties

- Addition (+) and multiplication (×) work as in ℤ, but the **result is taken modulo n**  
  - Example in ℤ₅:  
    - 3 + 3 ≡ 1 (mod 5)  
    - 3 × 3 ≡ 4 (mod 5)  
- ℤₙ is **closed under + and ×**  
- ℤₙ is a **commutative ring with unity**  
- Under special conditions (see later), ℤₙ can even be a **field**

## Example ℤ₈ — Addition and Multiplication Tables

### Addition Table (mod 8)

| +   | 0   | 1   | 2   | 3   | 4   | 5   | 6   | 7   |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 0   | 0   | 1   | 2   | 3   | 4   | 5   | 6   | 7   |
| 1   | 1   | 2   | 3   | 4   | 5   | 6   | 7   | 0   |
| 2   | 2   | 3   | 4   | 5   | 6   | 7   | 0   | 1   |
| 3   | 3   | 4   | 5   | 6   | 7   | 0   | 1   | 2   |
| 4   | 4   | 5   | 6   | 7   | 0   | 1   | 2   | 3   |
| 5   | 5   | 6   | 7   | 0   | 1   | 2   | 3   | 4   |
| 6   | 6   | 7   | 0   | 1   | 2   | 3   | 4   | 5   |
| 7   | 7   | 0   | 1   | 2   | 3   | 4   | 5   | 6   |

### Multiplication Table (mod 8)

| ×   | 0   | 1   | 2   | 3   | 4   | 5   | 6   | 7   |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 0   | 0   | 0   | 0   | 0   | 0   | 0   | 0   | 0   |
| 1   | 0   | 1   | 2   | 3   | 4   | 5   | 6   | 7   |
| 2   | 0   | 2   | 4   | 6   | `0` | 2   | 4   | 6   |
| 3   | 0   | 3   | 6   | 1   | 4   | 7   | 2   | 5   |
| 4   | 0   | 4   | `0` | 4   | `0` | 4   | `0` | 4   |
| 5   | 0   | 5   | 2   | 7   | 4   | 1   | 6   | 3   |
| 6   | 0   | 6   | 4   | 2   | `0` | 6   | 4   | 2   |
| 7   | 0   | 7   | 6   | 5   | 4   | 3   | 2   | 1   |

> Observe the **zeros in the multiplication table**, which indicate **zero divisors**.  
> Hence, ℤ₈ is **not a field**.

