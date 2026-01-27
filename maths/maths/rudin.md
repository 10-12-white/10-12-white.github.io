# Rudin

## Chapter 1 notes

### 2 questions on page 1-10

#### How can you prove that x + r , and xr is an irrational, if x is irrational, and we know r is rational?

To do this, proof by contraditions is best approach.  We know that r is rational, therefore, we have that r = a/b, where a and b have the smallest redcued form possible.  This means that a and b are both not even, and do not equal each other, and crucially, b ≠ 0.  When this is the case, it is possible to write and let x also be a rational number.

If so, then $x + r = \frac{m}{n} + \frac{a}{b} = \frac{am + bn}{bn} $

Once we are able to say this, it is clear this this is a rational number.

But, we know that x is NOT rational, so therefore cannot be stated as a fration, it is NOT possible for x + r to be a fraction, and therefore is not rational.  Proof by contradiction.

For the case of $x*r$, take the example again and state that if $x$and $r$are both rationals, and we assume that x is a rational, and we know r is a rational, then we have:

$x = \frac{m}{n} $for some m and n not equal to each other, both even, or 0, and then we have that

$x * r = \frac{m}{n} * \frac{a}{b} = \frac{am}{nb}$

This is clearly a rational number.  But, we know that x is NOT rational, so therefore cannot be stated as a fration, it is NOT possible for x * r to be a fraction, and therefore is not rational.  Proof by contradiction.

## Prove that these values are 0

# Rolles Theorem 

"This means, that if a function have the same value in the extreme of an interval, then there exist a point in which the derivative is zero in this interval, in other words, there exist point which are maximum or minimum at least local, in the interval."

In other words, you would check a period, say, $[a,b]$

If $f(a) = f(b)$, then this first part of the theorem has been satisfied
If $f'(c)$ exists, then we knowm, as some stage, it will be equal to 0, because of Rolles Theorem.

This is useful to use, because we can use it for powerful rules, see below

For example, two beautiful proofs for some interesting problems are below:

Assume that you have a sequence.  This sequence $\sum_{i=1}^{n} a_i$ is generated from some $a_i$s in such a way that:

$a_1 + \frac{a_2}{2} + ... + \frac{a_n}{n} = 0$

Now, we need to prove that the following is true:

${a_1} + {a_2}*c + a_{3}*c^{2} + a_{4}*c^{3} ... + {a_n}*c^{n-1} = 0$

So this is an interesting question? The first thought, then, is what is the function, and what is the boundary?

The function must have the same value in both cases of the extremum.  So, the sum is not the extremum.  It is a result of adding the different components of the functions.  So I think the best approach is to say something like:

Test f(0) and f(1) for the function, and if they are the saem value, then f'(c) can exist, we can calculate it.

So, this is to be done for the function below:

$f(a) = \frac{a_i}{i}$

By checking the values of f(0) and f(1) for this particular function, we can tell that these values are not the same as eachother, therefore, So then, this is a quick way for us to check that $f(a) = \frac{a_i}{i}$ is NOT the function

Ok, so, lets try something different.  Rolles Theorem, says, find two values for the function.  So, this would be f(0) and f(1) and we would want these to be 0.

If $f'(c)$ is equal to $0$, then we would have to have:

$f'(c) = a_1 + a_2 c + a_3 c^2 + a_4 c^3 + \dots + a_n c^{n-1} = 0$

Then $f(c) = a_1 c + \frac{a_2 c^2}{2} + \frac{a_3 c^3}{3} + \frac{a_4 c^4}{4} + \dots + \frac{a_n c^n}{n}$

Now we can test $f(0)$ and $f(1)$, which we evaluate by substituting values of $c$ into the function:

Since $f(0) = f(1)$, we have that these are equivalent. Therefore, there exists a $c \in (0, 1)$ such that $f'(c) = 0$ for the derivative of the function; that is, there is some $c$ for:

$f'(c) = a_1 + a_2 c + a_3 c^2 + a_4 c^3 + \dots + a_n c^{n-1} = 0$

Rolles Theorem, says, find two values for the function.  So, this would be f(0) and f(1) and we would want these to be 0.

If $f'(c)$ is equal to $0$, then we have:

$f'(c) = a_1 + a_2 c + a_3 c^2 + a_4 c^3 + \dots + a_n c^{n-1} = 0$

Then, by integrating $f'(c)$, we get $f(c)$:

$f(c) = a_1 c + \frac{a_2 c^2}{2} + \frac{a_3 c^3}{3} + \frac{a_4 c^4}{4} + \dots + \frac{a_n c^n}{n}$

Now we can test $f(0)$ and $f(1)$ to see if they satisfy the conditions of Rolle's Theorem by substituting $c=0$ and $c=1$ into the function:

- For $c = 0$: $f(0) = 0$.
- For $c = 1$: $f(1) = a_1 + \frac{a_2}{2} + \frac{a_3}{3} + \dots + \frac{a_n}{n}$.

If $f(0) = f(1)$, then the conditions for Rolle's Theorem are met. This implies there exists some $c \in (0, 1)$ such that the derivative vanishes:

$f'(c) = a_1 + a_2 c + a_3 c^2 + a_4 c^3 + \dots + a_n c^{n-1} = 0$

