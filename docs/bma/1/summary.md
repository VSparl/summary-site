# Trigonometry & Logarithms

### Trigonometric identities

These laws apply in every triangle; It doesn't have to be a right-angled triangle.

$(\sin(\phi))^2 + (\cos(\phi))^2 = 1$

$\tan(\phi) = \frac{\sin(\phi)}{\cos(\phi)}$

#### Recap of the usage of trigonometric functions

$\sin(x) = \frac{\text{opp}}{\text{hyp}}$

$\cos(x) = \frac{\text{adj}}{\text{hyp}}$

$\tan(x) = \frac{\text{opp}}{\text{adj}}$

> You can remember the pairings using the phrase **_soh-cah-toa_**. The letters in each syllable represent the sides of the triangles that make up the fraction.

### Laws of sines / cosines

These laws apply in every triangle; It doesn't have to be a right-angled triangle.

#### Laws of sines

$\frac{a}{b} = \frac{\sin(\alpha)}{\sin(\beta)}$

$\frac{a}{c} = \frac{\sin(\alpha)}{\sin(\gamma)}$

$\frac{b}{c} = \frac{\sin(\beta)}{\sin(\gamma)}$

#### Laws of cosines

$a^2 = b^2 + c^2 - 2bc \cdot \cos(\alpha)$
$b^2 = a^2 + c^2 - 2ac \cdot \cos(\beta)$
$c^2 = a^2 + b^2 - 2ab \cdot \cos(\gamma)$

### Exact values of common trigonometric calculations

#### Domains and ranges

- **domain** ($\mathbb{D}$): All values that a function accepts as input
- **range** ($\mathbb{W}$): All values that a function can return

$\sin(\phi) \to \mathbb{D} = \mathbb{R}; \quad \mathbb{W} = [-1, 1]$
$\cos(\phi) \to \mathbb{D} = \mathbb{R}; \quad \mathbb{W} = [-1, 1]$
$\tan(\phi) \to \mathbb{D} = \mathbb{R} \backslash \left\{ (2k+1) \cdot \frac{\pi}{2};\ k \in \mathbb{Z} \right\} ;\quad \mathbb{W} = \mathbb{R}$

> _The domain of $\tan(\phi)$ includes all real numbers, except those that are an odd multiple of $\frac{\pi}{2}$ radians, which corresponds to 90 degrees. This is due to the angle going straight up or straight down in the unit circle, thus never crossing the $\tan(\phi)$ line._

#### Exact values

| degrees      | $0°$ | $30°$                | $45°$                | $60°$                | $90°$           | $180°$ | $270°$           | $360°$ |
| ------------ | ---- | -------------------- | -------------------- | -------------------- | --------------- | ------ | ---------------- | ------ |
| radians      | $0$  | $\frac{\pi}{6}$      | $\frac{\pi}{4}$      | $\frac{\pi}{3}$      | $\frac{\pi}{2}$ | $\pi$  | $\frac{3\pi}{2}$ | $2\pi$ |
| $\sin(\phi)$ | $0$  | $\frac{1}{2}$        | $\frac{\sqrt{2}}{2}$ | $\frac{\sqrt{3}}{2}$ | $1$             | $0$    | $-1$             | $0$    |
| $\cos(\phi)$ | $1$  | $\frac{\sqrt{3}}{2}$ | $\frac{\sqrt{2}}{2}$ | $\frac{1}{2}$        | $0$             | $-1$   | $0$              | $1$    |
| $\tan(\phi)$ | $0$  | $\frac{\sqrt{3}}{3}$ | $1$                  | $\sqrt{3}$           | _nd_            | $0$    | _nd_             | $0$    |

### Graphs of trigonometric functions

#### Graph properties

$\sin(\phi)$:

- amplitude $= 1$
- periodicity $= 2\pi$
- asymptotes: none

$\cos(\phi)$:

- amplitude $= 1$
- periodicity $= 2\pi$
- asymptotes: none

$\tan(\phi)$:

- amplitude: none
- periodicity $= \pi$
- asymptotes: $x = \left\{(2k + 1) \cdot \frac{\pi}{2}; \ k \in \mathbb{Z}\right\}$
  > _The asymptotes of $\tan(\phi)$ are all odd multiples of $\frac{\pi}{2}$_, because they don't fit into the domain ($\mathbb{D}$).

#### Graph manipulation

| Change in term                           | resulting change of trigonometric graph | example                                    |
| ---------------------------------------- | --------------------------------------- | ------------------------------------------ |
| multiplication with $a > 1$              | increase in amplitude                   | $f(x) = 3 \cdot \sin(x)$                   |
| multiplication with $0 < a < 1$          | decrease in amplitude                   | $f(x) = \frac{1}{2}\cdot\sin(x)$           |
| substitute $x$ for $ax$ with $a > 1$     | higher frequency (shorter waves)        | $f(x) = \sin(3x)$                          |
| substitute $x$ for $ax$ with $0 < a < 1$ | lower frequency (longer waves)          | $f(x) = \sin(\frac{1}{2}x)$                |
| addition / subtraction of $a$            | translation along $y$-axis              | $f(x) = \sin(x) + 3 \\ f(x) = \sin(x) - 3$ |
| substitute $x$ for $(x + a)$             | translation along $x$-axis              | $f(x) = \sin(x + 3) \\ f(x) = \sin(x - 3)$ |

> When you translate the graph along the $x$-axis, a $-$ moves the graph to the right, while a $+$ moves the graph to the left.

## Logarithms

### Definition

The logarithm of a **positive real number** $b$ with base $a$ is the exponent by which $a$ must be raised to get $b$.
In other words, the logarithm as the question "What do I need to put on $a$ to get $b$?"

Or in mathematical notation:
$x = \log_a(b) \iff a^x = b; \ (a, b \in \mathbb{R}^+ \text{ and } a \neq 1)$

### Rules

!!! note
    Logarithm rules are also found in the *Mathematics formulary* (by Adrian Wetzel) on **page 5**.

> If the logarithm doesn't have a specified base (such as below), it is valid for any base $a$ for which $a \in \mathbb{R}^+$ and $a \neq 1$ are true.

$\log(p \cdot q) = \log(p) + \log(q)$

$\log(\frac{p}{q}) = \log(p) - \log(q)$

$\log(p^x) = x \cdot \log(p)$
