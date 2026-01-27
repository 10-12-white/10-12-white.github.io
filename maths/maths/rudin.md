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

## Let $f : [0,1] \in \mathbb{R}$such that it is continuous, and then let $(0,1)$ be an area in which it is differentiable.  We know that the area is $f(0) = f(1) == 0$.

We also know that the deriviate of the integral from the area of 0 to 1 is also 0.

Now, prove, that there exists $c_1, c_2 \in (0,1)$ such that $f'(c_1)$ and $f'(c_2) = 0$

### Step 1, Draw Graph

Step 1 - first, I wanted to draw a graph because otherwise it was going to be too hard for me to understand.

Then, it was easy to see how the area under the graph couldn't be equal to zero, if both sides were positive.  Therefore, one component had to be positive, and the other had to be negative.

### Step 2, Positive and Negative

So, it could be something like a sine curve, something to equal both components out.

Because we now have a concept of area being equivalent in magnitude but opposite, this is useful for us.  We can use this to break the areas under the curves for a few sections.

### Step 3, Differentiable over two areas

Because it is differentiable over the whole area, there is two points where the function must cross over the x-axis (first, to make the positive area) and then second, to make the negative area.

We do not know the value of x is to make this happen.

But, we can say that at this stage, we can see that there are two periods for which there is differentiability, continuity, and we can verify that the function will equal 0 in 3 places.

### Step 4, Rolle Theorem

Rolle Theorem says that in the area $(0,c_a), f'(0) = 0$, and $f'(c_a) = 0$ also.  Since the two extremum values in the set equal the same thing, then there is a $c_1$ such that $f'(c_1) = 0$.

Since $f(0) = 0$, which is verified, and $f(1) = 0$, and these are known.  We also know $f(c_a) = 0$ also, since function must cross over the x-axis (first, to make the positive area) and then second, to make the negative area.

Rolle Theorem says that in the area $(c_a,1)$, $f'(c_a) = 0$, and $f'(1) = 0$ also.  Since the two extremum values in the set equal the same thing, then there is a c_2 such that f'(c_2) = 0.

Therefore, there are two values $c_1$, and $c_2$, such that $f'(x) = 0$ for the interval $(0,1)$ given that $f : [0,1] \in \mathbb{R}$ such that it is continuous, and then let $(0,1)$be an area in which it is differentiable.  We know that the area is $f(0) = f(1) == 0$.

### Working on Legrange Theorem, genenrate the rules for the change and give reasons using the Rolle Theorem why the rules exists

For some function, we have that over the curve of an area, we have that 

$f'(c) = \frac{f(a) - f(b)}{ a - b}$

This is useful because we will then relate it to the function's gradiant at any point in this range, $f'(x)$.

## Theorem

Let f be continuous and $[a,b]$ and differentiable in $(a,b)$.  Prove that there is such a c that exists in (a,b) where the $f'(c) = \frac{f(a) - f(b)}{a - b}$.

If we have this, then we have that: $ f'(c) = \frac{f(a) - f(b)}{a - b} $.

Assume that $f'(c) = \frac{f(a) - f(b)}{a - b}$

$ f(c) = \integral \frac{f(a) - f(b)}{a - b}. dc $

Then we have that:

Then, consider how to make it for a particular area.  At any point in the function, you would have an f'(x).  And the gradient between two points would be $ f'(x) = \frac{(f(h) - f(x))}{h - x} $

## Theorem (Mean Value Theorem)

Let $f$ be continuous on $[a, b]$ and differentiable on $(a, b)$. Prove that there exists a point $c \in (a, b)$ such that:
$$f'(c) = \frac{f(b) - f(a)}{b - a}$$

### Proof Strategy

To prove this, we construct an auxiliary function $g(x)$ that satisfies the conditions of **Rolle's Theorem** (where $g(a) = g(b)$).

1. **Define the eligibility:** We need a function $g(x)$ such that $g(a) = g(b)$.
2. **Apply Rolle's Theorem:** This ensures there exists a $c$ where $g'(c) = 0$.
3. **Construct $g'(x)$:** We define the derivative based on the difference between the function's slope and agreeing function slope:
   $$g'(x) = f'(x) - \frac{f(b) - f(a)}{b - a}$$
4. **Find $g(x)$:** By integrating $g'(x)$, we get:
   $$g(x) = f(x) - \left( \frac{f(b) - f(a)}{b - a} \right)x + C$$

### Verification

To confirm $g(a) = g(b)$, we substitute the endpoints:
$$g(a) = f(a) - \left( \frac{f(b) - f(a)}{b - a} \right)a + C$$
$$g(b) = f(b) - \left( \frac{f(b) - f(a)}{b - a} \right)b + C$$

By setting $g(a) = g(b)$ and simplifying, we confirm that the constant $C$ cancels out, and the relationship holds, proving that such a $c$ must exist where $g'(c) = 0$, which implies:
$$f'(c) = \frac{f(b) - f(a)}{b - a}$$

Because, taking the derivative, we find:

$g'(x) = f'(x) - \frac{f(b) - f(a)}{b - a}$

If we work backwards from the derivative to find $g(x)$ via integration:

$g(x) = \int \left( f'(x) - \frac{f(b) - f(a)}{b - a} \right) dx$
$g(x) = f(x) - \frac{f(b) - f(a)}{b - a} \cdot x + C$

### Evaluating at the Endpoints

Since we require $g(a) = g(b)$, we substitute the values:

$f(a) - \frac{f(b) - f(a)}{b - a} \cdot a + C = f(b) - \frac{f(b) - f(a)}{b - a} \cdot b + C$

By subtracting $C$ from both sides and gathering the slope terms, we prove that the construction is valid, ensuring there exists a $c \in (a,b)$ where $g'(c) = 0$, thus proving:

$f'(c) = \frac{f(b) - f(a)}{b - a}$

