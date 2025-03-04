# Problem 2

# Notes on Limits of Sequences and Real Functions

## 19. Limits of Sequences

### 1. Limit of Rational Sequences
For a rational sequence of the form:
$$
\lim_{n \to \infty} \frac{P(n)}{Q(n)}
$$
where $P(n)$ and $Q(n)$ are polynomials, the rule is:
- If $\deg(P) < \deg(Q)$, then the limit is $0$.
- If $\deg(P) = \deg(Q)$, then the limit is the ratio of the leading coefficients.
- If $\deg(P) > \deg(Q)$, then the limit is $\infty$ or does not exist.

Example:
$$
\lim_{n \to \infty} \frac{n^2 + 3n}{2 n^2 - 2n}
$$
Use the highest power of $n$ in both numerator and denominator.

### 2. Squeeze Theorem
If three sequences satisfy:
$$
a_n \leq b_n \leq c_n
$$
and 
$$
\lim_{n \to \infty} a_n = \lim_{n \to \infty} c_n = L,
$$
then 
$$
\lim_{n \to \infty} b_n = L.
$$

Application:
$$
\lim_{n \to \infty} \frac{\sin(n)}{n}
$$
Since $-1 \leq \sin(n) \leq 1$, divide by $n$ and apply the squeeze theorem.

### 3. Exponential Limit (Euler's Number)
A fundamental limit:
$$
\lim_{n \to \infty} \left(1 + \frac{1}{n}\right)^n = e.
$$
This applies to sequences of the form:
$$
a_n = \left(1 + \frac{1}{n}\right)^n.
$$

## 20. Limits of Real Functions

### 1. Limit of Rational Functions
For a rational function:
$$
\lim_{x \to \infty} \frac{P(x)}{Q(x)}
$$
where $P(x)$ and $Q(x)$ are polynomials, apply the same rules as for sequences.

Example:
$$
\lim_{x \to \infty} \frac{x^3 + 2x^2}{x^4 - 3x^3}
$$
Divide by the highest power of $x$ in the denominator.

### 2. Trigonometric Limits
A key formula:
$$
\lim_{x \to 0} \frac{\sin(x)}{x} = 1.
$$
For modified expressions, use substitution or L'Hôpital's rule.

Example:
$$
\lim_{x \to 0} \frac{\sin(3x)}{2x+1}.
$$
Use small-angle approximations or L'Hôpital’s rule.

### 3. Asymptotes of a Function
- **Horizontal asymptote**: 
  $$\lim_{x \to \pm\infty} f(x) = L$$ means $y = L$ is a horizontal asymptote.
- **Vertical asymptote**: Occurs at points where the denominator goes to zero and the function diverges.
- **Oblique asymptote**: If $\lim_{x \to \infty} \frac{f(x)}{x} = m$, then $y = mx + b$ is an oblique asymptote.

Example:
For $f(x) = \frac{x^2 - 1}{x^2 + 1}$, analyze limits as $x \to \pm\infty$.

For $g(x) = \frac{\sin(x)}{x^2+1}$, check behavior for large $x$ and near singularities.

---

These formulas and definitions should help in solving the problems!

