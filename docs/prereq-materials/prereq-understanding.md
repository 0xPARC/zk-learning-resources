---
sidebar_position: 2
---

# Prerequisite Understanding Questions

You should be reasonably confident that you'd be able to solve most of the problems below, given some time and a bit of Googling.

If you're comfortable solving these problems, you should have the necessary background for writing ZK circuits!

[Here](https://crypto.stanford.edu/pbc/notes/numbertheory/) is a good reference for number theory topics.

## Modular arithmetic

1. Without using a calculator, compute the remainder when $20212017^2$ is divided by $20212022$.
2. Cycles
    1. What is the third-smallest positive value of $x$ for which $2^x \equiv 3 \pmod{13}$?
    2. What is the fourth-smallest positive value of $x$ for which $2^x \equiv 8 \pmod{101}$?
3. Chinese Remainder Theorem
    1. Describe all integers $n$ such that $n \equiv 3 \pmod{5}$ and $n \equiv 6 \pmod{7}$.
    2. Describe all integers $n$ such that $n \equiv 5 \pmod{6}$, $n \equiv 6 \pmod{7}$, and $n \equiv 7 \pmod{8}$.
4. Modular inverses
    1. Describe all integers $n$ such that $5n + 7 \equiv 2 \pmod{13}$.
    2. Describe all integers $n$ such that $3n + 9 \equiv 4 \pmod{12}$.
    3. Describe all integers $n$ such that $3n + 9 \equiv 3 \pmod{12}$.
    4. Describe all integers $n$ such that $19n \equiv 1 \pmod{257}$.


## Polynomials

1. Solve for $x$: $(x-1)(x+2)(x-3)(x+4) > 0$.
2. Describe all $n$ such that $(n-2)(n-3) \equiv 0 \pmod{97}$.
3. Describe all $n$ such that $(n-2)(n-3) \equiv 0 \pmod{72}$.
4. Suppose that $f(x)$ is a polynomial with leading coefficient $1$ such that $f(0) = 10$. What is the product of the roots of $f(x)$, if $f(x)$ has an even degree? What if $f(x)$ has an odd degree? If $f(x)$ had leading coefficient $5$, how would this change?
5. Find the sum of the squares of the roots of the polynomial $x^4 - 3x^3 + 12x^2 - x + 15 = 0$.


## Miscellaneous

1. Suppose you had an efficient algorithm to factor arbitrarily large numbers. How could you use such an algorithm to decrypt messages not meant for you, that are encrypted with an [RSA encryption scheme](https://en.wikipedia.org/wiki/RSA_(cryptosystem))?
2. Many online services which require user authentication store hashed passwords, rather than plaintext passwords.
    1. Explain the [rainbow attack](https://en.wikipedia.org/wiki/Rainbow_table): an attack by which an attacker can derive a substantial fraction of plaintext passwords from a leaked table of hashed passwords.
    2. Explain how to use [salting](https://en.wikipedia.org/wiki/Salt_(cryptography)) to prevent a rainbow attack.
3. What is the difference between a [Merkle tree](https://en.wikipedia.org/wiki/Merkle_tree) and a [hash list](https://en.wikipedia.org/wiki/Hash_list)? When would you want to use a Merkle tree instead of a hash list?
