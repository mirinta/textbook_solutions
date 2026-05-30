# Exercises 1B

---

**1. Prove that $-(-v) = v$ for every $v \in V$.**

$-v$ is the additive inverse of $v$, meas $v + (-v) = 0$.

$-(-v)$ is the additive inverse of $(-v)$, meas $(-v) + [-(-v)] = 0$.

Therefore,

$$
\begin{aligned}

-(-v) = -(-v) + 0 = -(-v) + [v + (-v)] = [-(-v) + (-v)] + v = v

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

&= v + 3[\frac{1}{3}(w - v)] \\

&= v + (w - v) \\

&= v + (w + (-v)) \\

&= (v + (-v)) + w \\

&= w

\end{aligned}
$$

Suppose $x'$ also satisfies $v + 3x' = w$, then

$$
\begin{aligned}

x

&= \frac{1}{3} (w - v) \\

&= \frac{1}{3} [(v + 3x') - v] \\

&= \frac{1}{3} [(v + (-v)) + 3x'] \\

&= \frac{1}{3} (3x') \\

&= x'

\end{aligned}
$$

---

**4. The empty set is not a vector space. The empty set fails to satisfy only one of the requirements listed in the definition of a vector space (1.20). Which one?**

The empty set does not have an additive identity.

---

**5. Show that in the definition of a vector space (1.20), the additive inverse condition can be replaced with the condition that $$0v = 0 \text{ for all } v \in V.$$ Here the $0$ on the left side is the number $0$, and the $0$ on the right side is the additive identity of $V$.**
