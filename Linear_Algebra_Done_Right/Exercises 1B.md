# Exercises 1B

---

**1. Prove that $-(-v) = v$ for every $v \in V$.**

We have

$$
\begin{aligned}

-(-v) + (-v) = (-1)(-v) + 1(-v) = 0(-v) = 0

\end{aligned}
$$

Add $v$ to both sides, we have

$$
\begin{aligned}

-(-v) + (-v) + v &= v \\

-(-v) + ((-v) + v) &= v \\

-(-v) &= v

\end{aligned}
$$

---

**2. Suppose $a \in \mathbf{F}$, $v \in V$, and $av = 0$. Prove that $a = 0$ or $v = 0$.**

If $a = 0$, then $av = 0v = 0$.

If $a \neq 0$, then there exists a unique $b \in \mathbf{F}$ such that $ab = 1$, then

$$
\begin{aligned}

v = 1v = (ab)v = b(av) = 0

\end{aligned}
$$

---

**3. Suppose $v, w \in V$. Explain why there exists a unique $x \in V$ such that $v + 3x = w$.**

Let $x = \frac{1}{3}(w - v)$, then

$$
\begin{aligned}

v + 3x

&= v + 3(\frac{1}{3}(w - v)) \\

&= v + (w - v) \\

&= v + (w + (-v)) \\

&= v + ((-v) + w) \\

&= (v + (-v)) + w \\

&= w

\end{aligned}
$$

Assume there is another $x' \in V$ such that $v + 3x' = w$, then

$$
\begin{aligned}

x

&= \frac{1}{3} (w - v) \\

&= \frac{1}{3} ((v + 3x') - v) \\

&= \frac{1}{3} ((v + (-v)) + 3x') \\

&= \frac{1}{3} (3x') \\

&= x'

\end{aligned}
$$

---

**4. The empty set is not a vector space. The empty set fails to satisfy only one of the requirements listed in the definition of a vector space (1.20). Which one?**

The empty set does not have an additive identity.

---

**5. Show that in the definition of a vector space (1.20), the additive inverse condition can be replaced with the condition that $$0v = 0 \text{ for all } v \in V.$$ Here the $0$ on the left side is the number $0$, and the $0$ on the right side is the additive identity of $V$.**

If the additive inverse of 1.20 is replaced with the given condition, we need to show that for every $v \in V$, there exists $w \in V$ such that $v + w = 0$.

For any $v \in V$, let $w = (-1)v$, then,

$$
\begin{aligned}

v + w = 1v + (-1)v = (1 + (-1))v = 0v = 0

\end{aligned}
$$

---

**6. Let $\infty$ and $-\infty$ denote two distinct objects, neither of which is in $\mathbf{R}$. Define an addition and scalar multiplication on $\mathbf{R} \cup \lbrace \infty, -\infty \rbrace$ as you could guess from the notation. Specifically, the sum and product of two real numbers is as usual, and for $t \in \mathbf{R}$ define**

$$
\begin{aligned}

t\infty =
\begin{cases}
    -\infty & \text{if } t < 0, \\
    0 & \text{if } t = 0, \\
    \infty & \text{if } t > 0, \\
\end{cases}

\qquad

t(-\infty) =
\begin{cases}
    \infty & \text{if } t < 0, \\
    0 & \text{if } t = 0, \\
    -\infty & \text{if } t > 0,
\end{cases}

\end{aligned}
$$

and

$$
\begin{aligned}

t + \infty &= \infty + t = \infty + \infty = \infty \\

t + (-\infty) &= (-\infty) + t = (-\infty) + (-\infty) = -\infty \\

\infty + (-\infty) &= (-\infty) + \infty = 0.

\end{aligned}
$$

**With these operations of addition and scalar multiplication, is $\mathbf{R} \cup \lbrace \infty, -\infty \rbrace$ a vector space over $\mathbf{R}$? Explain.**

$\mathbf{R} \cup \lbrace \infty, -\infty \rbrace$ is not a vector space, because the associativity of addition is not satisfied.

According to the given condition, we have

$$

(1 + \infty) + (-\infty) = \infty + (-\infty) = 0

$$

However,

$$

1 + (\infty + (-\infty)) = 1 + 0 = 1

$$

---

**7. Suppose $S$ is a nonempty set. Let $V^S$ denote the set of functions from $S$ to $V$. Define a natural addition and scalar multiplication on $V^S$, and show that $V^S$ is a vector with these definitions.**

We define the addition and scalar multiplication on $V^S$ according to 1.24:

- For $f, g \in V^S$, the sum $f + g \in V^S$ is the function defined by $$(f + g)(x) = f(x) + g(x)$$ for all $x \in S$.

- For $\lambda \in V$ and $f \in V^S$, the product $\lambda f \in V^S$ is the function defined by $$(\lambda f)(x) = \lambda f(x)$$ for all $x \in S$.

**Commutativity:**

For all $f, g \in V^S$ and for all $x \in S$,

$$
\begin{aligned}

(f + g)(x)

&= f(x) + g(x) \\

&= g(x) + f(x) \text{, according to the commutativity of addition in } V\\

&= (g + f)(x)

\end{aligned}
$$

**Associativity:**

For all $f, g \in V^S$, for all $a, b \in V$ and for all $x \in S$,

$$
\begin{aligned}

((f + g) + h)(x)

&= (f + g)(x) + h(x) \\

&= (f(x) + g(x)) + h(x) \\

&= f(x) + (g(x) + h(x)) \text{, according to the associativity of addition } in V \\

&= f(x) + (g + h)(x) \\

&= (f + (g + h))(x) \\ \\

((ab)f)(x)

&= (ab)f(x) \\

&= a(bf(x)) \text{, according to the associativity of scalar multiplication in } V \\

&= a((bf)(x)) \\

&= (a(bf))(x)

\end{aligned}
$$

**Additive identity:**

Let $0$ be the function in $V^S$ such that $0(x)$ is the additive identity in $V$ for all $x \in S$.

For all $f \in V^S$ and for all $x \in S$, we have

$$
\begin{aligned}

(f + 0)(x) = f(x) + 0(x) = f(x)

\end{aligned}
$$

**Additive inverse:**

For every $f \in V^S$, let $g$ be the function in $V^S$ such that $g(x)$ is the additive inverse of $f(x)$.

$$
\begin{aligned}

(f + g)(x) = f(x) + g(x) = 0

\end{aligned}
$$

for all $x \in S$.

**Multiplicative identity:**

For all $f \in V^S$ and for all $x \in S$,

$$
\begin{aligned}

(1f)(x) = 1f(x) = f(x)

\end{aligned}
$$

**Distributive properties:**

For all $f, g \in V^S$ and for all $a, b \in \mathbf{F}$,

$$
\begin{aligned}

(a(f + g))(x)

&= a((f + g)(x)) \\

&= a(f(x) + g(x)) \\

&= af(x) + ag(x) \text{, according to the distributive properties in } V \\

&= (af)(x) + (ag)(x) \\

&= (af + ag)(x) \\ \\

((a + b)f)(x)

&= (a + b)f(x) \\

&= af(x) + bf(x) \text{, according to the distributive properties in } V \\

&= (af)(x) + (bf)(x) \\

&= (af + bf)(x)

\end{aligned}
$$

Therefore, $V^S$ is a vector space over $\mathbf{F}$.

---

**8. Suppose $V$ is a real vector space.**

- The complexification of $V$, denoted by $V_C$, equal $V \times V$. An element of $V_C$ is an ordered pair $(u, v)$, where $u, v \in V$, but we write this as $u + iv$.

- Addition on $V_C$ is defined by $$(u_1 + iv_1) + (u_2 + iv_2) = (u_1 + u_2) + i(v_1 + v_2)$$ for all $u_1, v_1, u_2, v_2 \in V$.

- Complex scalar multiplication on $V_C$ is defined by $$(a + bi)(u + iv) = (au - bv) + i(av + bu)$$ for all $a, b \in \mathbf{R}$ and all $u, v \in V$.

**Prove that with the definitions of addition and scalar multiplication as above, $V_C$ is a complex vector space.**

**Commutativity:**

$$
\begin{aligned}

(u_1 + iv_1) + (u_2 + iv_2)

&= (u_1 + u_2) + i(v_1 + v_2) \\

&= (u_2 + u_1) + i(v_2 + v_1) \text{, according to the commutativity of addition in } V \\

&= (u_2 + iv_2) + (u_1 + iv_1)

\end{aligned}
$$

for all $u_1, v_1, u_2, v_2 \in V$.

**Associativity:**

$$
\begin{aligned}

((u_1 + iv_1) + (u_2 + iv_2)) + (u_3 + iv_3)

&= ((u_1 + u_2) + i(v_1 + v_2)) + (u_3 + iv_3) \\

&= ((u_1 + u_2) + u_3) + i((v_1 + v_2) + v_3) \\

&= (u_1 + (u_2 + u_3)) + i(v_1 + (v_2 + v_3)) \text{, according to the associativity of addition in } V \\

&= (u_1 + iv_2) + ((u_2 + u_3) + i(v_2 + v_3)) \\

&= (u_1 + iv_1) + ((u_2 + iv_2) + (u_3 + iv_3)) \\

\\

((a_1 + ib_1)(a_2 + ib_2))(u + iv)

&= ((a_1a_2 - b_1b_2) + i(a_1b_2 + b_1a_2))(u + iv) \\

&= ((a_1a_2 - b_1b_2)u - (a_1b_2 + b_1a_2)v) + i((a_1a_2 - b_1b_2)v + (a_1b_2 + b_1a_2)u) \\

&= ((a_1a_2)u - (b_1b_2)u - (a_1b_2)v - (b_1a_2)v) + i((a_1a_2)v - (b_1b_2)v + (a_1b_2)u + (b_1a_2)u) \\

&= (a_1(a_2u) - b_1(b_2u) - a_1(b_2v) - b_1(a_2v)) + i(a_1(a_2v) - b_1(b_2v) + a_1(b_2u) + b_1(a_2u)) \text{, according to the associativity of scalar multiplication in } V \\

&= (a_1(a_2u - b_2v) - b_1(b_2u + a_2v)) + i(a_1(b_2u + a_2v) + b_1(a_2u - b_2v)) \text{, according to the commutativity of addition and the distributive properties in } V \\

&= (a_1 + ib_1)((a_2u - b_2v) + i(b_2u + a_2v)) \\

&= (a_1 + ib_1)((a_2 + ib_2)(u + iv))

\end{aligned}
$$

for all $u, v, u_1, v_1, u_2, v_2, u_3, v_3 \in V$ and for all $a_1, b_1, a_2, b_2 \in \mathbf{R}$.

**Additive identity:**

For all $u, v \in V$,

$$
\begin{aligned}

(u + iv) + (0 + i0)

= (u + 0) + i(v + 0)

= u + iv

\end{aligned}
$$

which means $0 + i0$ is the additive identity in $V_C$.

**Additive inverse:**

For every $u, v \in V$, let $(-u), (-v) \in V$ be the additive inverse of $u$ and $v$, respectively.

We have

$$
\begin{aligned}

(u + iv) + ((-u) + i(-v))

= (u + (-u)) + i(v + (-v))

= 0 + i0 \\

\end{aligned}
$$

which means $(-u) + i(-v)$ is the additive inverse of $u + iv$.

**Multiplication identity:**

For all $u, v \in V$,

$$
\begin{aligned}

(1 + i0)(u + iv)

= (u - 0v) + i(1v + 0u)

= u + iv

\end{aligned}
$$

**Distributive properties:**

$$
\begin{aligned}

(a + ib)((u_1 + iv_1) + (u_2 + iv_2))

&= (a + ib)((u_1 + u_2) + i(v_1 + v_2)) \\

&= (a(u_1 + u_2) - b(v_1 + v_2)) + i(a(v_1 + v_2) + b(u_1 + u_2)) \\

&= (au_1 + au_2 - bv_1 - bv_2) + i(av_1 + av_2 + bu_1 + bu_2) \\

&= ((au_1 - bv_1) + (au_2 - bv_2)) + i((av_1 + bu_1) + (av_2 + bu_2)) \\

&= ((au_1 - bv_1) + i(av_1 + bu_1)) + ((au_2 - bv_2) + i(av_2 + bu_2)) \\

&= (a + ib)(u_1 + iv_1) + (a + ib)(u_2 + iv_2) \\

\\

((a_1 + ib_1) + (a_2 + ib_2))(u + iv)

&= ((a_1 + a_2) + i(b_1 + b_2))(u + iv) \\

&= ((a_1 + a_2)u - (b_1 + b_2)v) + i((a_1 + a_2)v + (b_1 + b_2)u) \\

&= (a_1u + a_2u - b_1v - b_2v) + i(a_1v + a_2v + b_1u + b_2u) \\

&= ((a_1u - b_1v) + (a_2u - b_2v)) + i((a_1v + b_1u) + (a_2v + b_2u)) \\

&= ((a_1u - b_1v) + i(a_1v + b_1u)) + ((a_2u - b_2v) + i(a_2v + b_2u)) \\

&= (a_1 + ib_1)(u + iv) + (a_2 + ib_2)(u + iv)

\end{aligned}
$$

for all $u_1, v_1, u_2, v_2 \in V$ and for all $a, b, a_1, b_1, a_2, b_2 \in \mathbf{R}$.

---

