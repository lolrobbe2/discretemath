# Prime Numbers

A **prime number** `p` has **exactly two distinct divisors**, namely its trivial divisors:
- `1`
- `p`

## Examples

- `97` is a prime number because it is divisible only by `1` and `97`
- `1` is **not** a prime number

## Sieve of Eratosthenes

The **Sieve of Eratosthenes** is an algorithm used to find all prime numbers less than or equal to `n`.

## Sieve of Eratosthenes — n = 100

We determine all prime numbers **≤ 100** step by step.

### Step 1 — Write down the numbers
List all integers from **2 to 100**.  
(1 is not prime.)

### Step 2 — Start with the first prime (2)
- Keep **2**
- Cross out all multiples of 2 greater than 2  
  (4, 6, 8, 10, …, 100)

### Step 3 — Next uncrossed number: 3
- Keep **3**
- Cross out all multiples of 3 greater than 3  
  (6, 9, 12, 15, …, 99)

### Step 4 — Next uncrossed number: 5
- Keep **5**
- Cross out all multiples of 5 greater than 5  
  (10, 15, 20, …, 100)

### Step 5 — Next uncrossed number: 7
- Keep **7**
- Cross out all multiples of 7 greater than 7  
  (14, 21, 28, …, 98)

### Step 6 — Stop condition
We stop when the square of the current prime exceeds 100:
- 11² = 121 > 100  

So no further steps are needed.

### Step 7 — Remaining numbers
All numbers that are **not crossed out** are prime.

**Primes ≤ 100:**

2, 3, 5, 7, 11, 13, 17, 19, 23, 29,  
31, 37, 41, 43, 47, 53, 59, 61, 67, 71,  
73, 79, 83, 89, 97

### Final Answer

There are **25 prime numbers** less than or equal to **100**.
