# statements

## There Are Infinitely Many Prime Numbers

### Proof by Contradiction

#### Assume that the collection of all prime numbers is **finite**:

P = { p₁, p₂, …, pₙ }

Now define:

m = ∏ᵢ₌₁ⁿ pᵢ

#### Consider the number:

m + 1

The number `m + 1` is **not** in `P`, so it is not among the listed prime numbers.

Therefore, `m + 1` must have at least one **non-trivial divisor**.  
Let `q` be the **smallest non-trivial divisor** of `m + 1`.

#### Then:
- `q` is a prime number  
- hence `q ∈ P`

Since `q ∈ P`, it divides `m`, because `m` is the product of all primes in `P`.

Thus, `q` divides both `m` and `m + 1`, and therefore also their difference:

(m + 1) − m = 1

This is a **contradiction**, because a non-trivial divisor cannot divide `1`.

Hence, our assumption was false.

### Conclusion

The collection of all prime numbers is **infinite**.


## Fundamental Theorem of Arithmetic

Every integer `n > 1` can be written in a **unique way** as a product of prime numbers:

n = p₁ⁿ¹ · p₂ⁿ² · … · pₖⁿᵏ  
= ∏ᵢ₌₁ᵏ pᵢⁿᵢ

where:
- `p₁, p₂, …, pₖ` are **distinct prime numbers**
- `n₁, n₂, …, nₖ` are **strictly positive integers**

### Example

- 162 = 2¹ · 3⁴

## Number of Divisors of an Integer

Let an integer `n` have the prime factorization:

n = p₁ⁿ¹ · p₂ⁿ² · … · pₖⁿᵏ  
= ∏ᵢ₌₁ᵏ pᵢⁿᵢ

Then the **number of (positive) divisors** of `n` is exactly:

(n₁ + 1)(n₂ + 1) … (nₖ + 1)  
= ∏ᵢ₌₁ᵏ (nᵢ + 1)

### Example

162 = 2¹ · 3⁴

Number of divisors:

(1 + 1)(4 + 1) = 2 · 5 = **10**

#### All divisors of 162

These are obtained by choosing powers of 2 and 3:

- 2⁰ · 3⁰ = 1  
- 2¹ · 3⁰ = 2  
- 2⁰ · 3¹ = 3  
- 2¹ · 3¹ = 6  
- 2⁰ · 3² = 9  
- 2¹ · 3² = 18  
- 2⁰ · 3³ = 27  
- 2¹ · 3³ = 54  
- 2⁰ · 3⁴ = 81  
- 2¹ · 3⁴ = 162
