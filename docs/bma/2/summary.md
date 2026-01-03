# Differentiation and Polynomials

## Derivatives

$f'(x)$ is the **derivative** of $f(x)$ and graphs its **slope**. This means that for the same $x$ value, $f'(x)$ gives you the _slope of the tangent to $f(x)$ at that point_.

!!! example "How-to"
    For each term in the polynomial, multiply it with the **exponent** of $x$, after which the exponent decreases by 1. If the term is a constant, it just vanishes, as there is no $x$ to have an exponent. Example:

    Initial function: $f(x) = 5x^3 + 2x + 4$

    First derivative: $f'(x) = 15x^2 + 2\qquad$ ($5x^3$ became $15x^2$ ; $2x$ became $2$ ; $4$ vanished)

    Second derivative: $f''(x) = 30x$

    Third derivative: $f'''(x) = 30$

    Fourth derivative: $f''''(x) = 0$

## Special points

- **stationary point**:
    - graph has slope 0
    - **tangent** to the graph is **horizontal** and the graph is flat
    - can be a maximum, minimum or saddle point
    - $f'(x) = 0$

- **saddle point**:
    - graph changes direction in a point with slope 0
    - looks like a saddle ¯\\\_(&#x30C4;)\_/¯
    - $f'(x) = 0$
    - $f''(x) = 0$

- **minimum**:
    - lowest point _(global or local)_ on the graph
    - $f'(x) = 0$
    - $f''(x) \gt 0$

- **maximum**:
    - highest point _(global or local)_ on the graph
    - $f'(x) = 0$
    - $f''(x) \lt 0$

- **point of inflection**[^1]:
    - graph changes direction _(left-hand vs. right-hand curve)_
    - steepest spot between local minima / maxima
    - $f'(x) \neq 0$
    - $f''(x) = 0$

[^1]: Also rarely spelled _"inflexion"_


## Symmetry

- **even** functions:
    - $f(-x) = f(x)$
    - if written in polynomial form &rightarrow; **all** exponents are _positive_ and _even_
    - symmetrical with respect to the **y axis**

- **odd** functions:
    - $f(-x) = -f(x)$
    - if written in polynomial form &rightarrow; **all** exponents are _positive_ and _odd_
    - symmetrical with respect to the **origin**
