# Exercises 1A

---

**1. Show that $\alpha + \beta = \beta + \alpha$ for all $\alpha, \beta \in \mathbf{C}$.**

Let $\alpha = x + yi$, $\beta = p + qi$, where $x, y, p, q \in \mathbf{R}$, then

$$
\begin{aligned}

\alpha + \beta

&= (x + p) + (y + q)i \\

&= (p + x) + (q + y)i \\

&= \beta + \alpha

\end{aligned}
$$

---

**2. Show that $(\alpha + \beta) + \lambda = \alpha + (\beta + \lambda)$ for all $\alpha, \beta, \lambda \in \mathbf{C}.$**

Let $\alpha = x + yi$, $\beta = p + qi$, $\lambda = a + bi$, where $x, y, p, q, a, b \in \mathbf{R}$, then

$$
\begin{aligned}

(\alpha + \beta) + \lambda

&= [(x + p) + (y + q)i] + a + bi \\

&= (x + p) + a + [(y + q) + b]i \\

&= x + (p + a) + [y + (q + b)]i \\

&= x + yi + [(p + a) + (q + b)i] \\

&= \alpha + (\beta + \lambda)

\end{aligned}
$$

---

**3. Show that $(\alpha \beta)\lambda = \alpha(\beta \lambda)$ for all $\alpha, \beta, \lambda \in \mathbf{C}$.**

Let $\alpha = x + yi$, $\beta = p + qi$, $\lambda = a + bi$, where $x, y, p, q, a, b \in \mathbf{R}$, then

$$
\begin{aligned}

(\alpha \beta) \lambda

&= [(x + yi)(p + qi)](a + bi) \\

&= (xp + xqi + ypi - yq)(a + bi) \\

&= xpa + xpbi + xqai - xqb + ypai - ypb - yqa - yqbi \\

&= (x + yi)pa + (x + yi)pbi + (x + yi)qai - (x + yi)qb \\

&= (x + yi)(pa + pbi + qai - qb) \\

&= (x + yi)[(p + qi)a + (p + qi)bi] \\

&= (x + yi)[(p + qi)(a + bi)] \\

&= \alpha (\beta \lambda)

\end{aligned}
$$

---

**4. Show that $\lambda (\alpha + \beta) = \lambda \alpha + \lambda \beta$ for all $\lambda, \alpha, \beta \in \mathbf{C}$.**

Let $\alpha = x + yi$, $\beta = p + qi$, $\lambda = a + bi$, where $x, y, p, q, a, b \in \mathbf{R}$, then

$$
\begin{aligned}

\lambda (\alpha + \beta)

&= (a + bi)[(x + p) + (y + q)i] \\

&= ax + ap + bxi + bpi + ay i + aqi - by - bq \\

&= (ax + ayi + bxi - by) + (ap + bpi + aqi - bq) \\

&= (ax + ayi + bxi + bi yi) + (ap + bpi + aqi + bi qi) \\

&= [a(x + yi) + bi(x + yi)] + [a(p + qi) + bi(p + qi)] \\

&= [(a + bi)(x + yi)] + [(a + bi)(p + qi)] \\

&= \lambda \alpha + \lambda \beta

\end{aligned}
$$

---

**5. Show that for every $\alpha \in \mathbf{C}$, there exists a unique $\beta \in \mathbf{C}$ such that $\alpha + \beta = 0$.**

Let $\alpha = x + yi$, where $x, y \in \mathbf{R}$, then $-x$ and $-y$ are the additive inverses of $x$ and $y$, respectively.

Let $\beta = (-x) + (-y)i$, then

$$
\begin{aligned}

\alpha + \beta

&= x + yi + (-x) + (-y)i \\

&= [x + (-x)] + [y + (-y)]i \\

&= 0

\end{aligned}
$$

Assume there exists another $\beta' \in \mathbf{C}$ such that $\alpha + \beta' = 0$, then 

$$
\begin{aligned}

\beta

&= \beta + 0 \\

&= \beta + (\alpha + \beta') \\

&= (\alpha + \beta) + \beta' \\

&= \beta'

\end{aligned}
$$

---

**6. Show that for every $\alpha \in \mathbf{C}$ with $\alpha \neq 0$, there exists a unique $\beta \in \mathbf{C}$ such that $\alpha \beta = 1$.**

Let $\alpha = x + yi$, where $x, y \in \mathbf{R}$.

Since $\alpha \neq 0$, then $x$ and $y$ are not both zero, means $x^2 + y^2 \neq 0$.

Let $\beta = \frac{x}{x^2 + y^2} - \frac{y}{x^2 + y^2}i$, then

$$
\begin{aligned}

\alpha \beta

&= (x + yi)(\frac{x}{x^2 + y^2} - \frac{y}{x^2 + y^2}i) \\

&= \frac{x^2}{x^2 + y^2} - \frac{xy}{x^2 + y^2}i + \frac{xy}{x^2 + y^2}i + \frac{y^2}{x^2 + y^2} \\

&= \frac{x^2 + y^2}{x^2 + y^2} \\

&= 1

\end{aligned}
$$

Assume there exists another $\beta' \in \mathbf{C}$ such that $\alpha \beta' = 1$, then

$$
\begin{aligned}

\beta'

&= \beta' 1 \\

&= \beta' (\alpha \beta) \\

&= (\alpha \beta') \beta \\

&= \beta

\end{aligned}
$$

---

**7. Show that $\frac{-1 + \sqrt{3}i}{2}$ is a cube root of 1 (meaning that its cube equals 1).**

$$
\begin{aligned}

(\frac{-1 + \sqrt{3}i}{2})^3

&= \frac{(-1 + \sqrt{3}i)^2 (-1 + \sqrt{3}i)}{8} \\

&= \frac{(-2 - 2\sqrt{3}i)(-1 + \sqrt{3}i)}{8} \\

&= \frac{2 - 2\sqrt{3}i + 2\sqrt{3}i + 6}{8} \\

&= 1

\end{aligned}
$$

---

**8. Find two distinct square roots of $i$.**

Let $(a + bi)^2 = i$, where $a, b \in \mathbf{R}$, then

$$(a + bi)^2 - i = (a^2 - b^2)+ (2ab - 1)i = 0$$

We have $a^2 = b^2$ and $2ab = 1$.

Let $a = b$, then $a = b = \frac{1}{\sqrt{2}}$, means $z_1 = \frac{1}{\sqrt{2}} + \frac{1}{\sqrt{2}}i$ is a square root of $i$.

Let $z_2 = -z_1 = -\frac{1}{\sqrt{2}} - \frac{1}{\sqrt{2}}i$, then ${z_2}^2 = {z_1}^2 = i$, means $z_2 = -\frac{1}{\sqrt{2}} - \frac{1}{\sqrt{2}}i$ is another square root of $i$.

---

**9. Find $x \in \mathbf{R^4}$ such that $(4, -3, 1, 7) + 2x = (5, 9, -6, 8)$.**

Let $x = (a, b, c, d)$, where $a, b, c, d \in \mathbf{R}$, then

$$
\begin{aligned}

(4, -3, 1, 7) + 2(a, b, c, d) &= (5, 9, -6, 8) \\

(4 + 2a, -3 + 2b, 1 + 2c, 7 + 2d) &= (5, 9, -6, 8) \\

\end{aligned}
$$

We have

$$
\left \{
\begin{aligned}
  
a &= \frac{1}{2} \\

b &= 6 \\

c &= -\frac{7}{2} \\

d &= \frac{1}{2}

\end{aligned}
\right.
$$

Hence, $x = (\frac{1}{2}, 6, -\frac{7}{2}, \frac{1}{2}).$

---

**10. Explain why there does not exist $\lambda \in \mathbf{C}$ such that $\lambda (2 - 3i, 5 + 4i, -6 + 7i) = (12 - 5i, 7 + 22i, -32 - 9i)$.**

Assume there exists a $\lambda \in \mathbf{C}$, then

$$
\begin{aligned}

\lambda (2 - 3i) &= 12 - 5i \\

\lambda &= \frac{12 - 5i}{2 - 3i} \\

\lambda &= \frac{(12 - 5i)(2 + 3i)}{(2 - 3i)(2 + 3i)} \\

\lambda &= \frac{39 + 26i}{13} \\

\lambda &= 3 + 2i

\end{aligned}
$$

However,

$$
\begin{aligned}

\lambda (-6 + 7i) &= (3 + 2i)(-6 + 7i) = -32 + 9i \neq -32 - 9i

\end{aligned}
$$

Assumption fails, means the original statement is true.

---

**11. Show that $(x + y) + z = x + (y + z)$ for all $x, y, z \in \mathbf{F^n}$.**

Let $x = (x_1, ..., x_n), y = (y_1, ...., y_n), z = (z_1, ..., z_n)$, where $x_i, y_i, z_i \in \mathbf{F}$ for $i = 1, 2, ..., n$, then

$$
\begin{aligned}

(x + y) + z

&= ((x_1 + y1) + z_1, ..., (x_n + y_n) + z_n) \\

&= (x_1 + (y_1 + z_1), ..., x_n + (y_n + z_n)) \\

&= (x_1, ..., x_n) + (y_1 + z_1, ..., y_n + z_n) \\

&= x + (y + z)

\end{aligned}
$$

---

**12. Show that $(ab)x = a(bx)$ for all $x \in \mathbf{F^n}$ and all $a, b \in \mathbf{F}$.**

Let $x = (x_1, ..., x_n)$, where $x_i \in \mathbf{F}$ for $i = 1, 2, ..., n$, then

$$
\begin{aligned}
(ab)x

&= ((ab)x_1, ..., (ab)x_n) \\

&= (a(bx_1), ..., a(bx_n)) \\

&= a(bx_1, ..., bx_n) \\

&= a(bx)

\end{aligned}
$$

---

**13. Show that $1x = x$ for all $x \in \mathbf{F^n}$.**

Let $x = (x_1, ..., x_n)$, where $x_i \in \mathbf{F}$ for $i = 1, 2, ..., n$, then

$$
1x = 1(x_1, ..., x_n) = (x_1, ..., x_n) = x
$$

---

**14. Show that $\lambda (x + y) = \lambda x + \lambda y$ for all $\lambda \in \mathbf{F}$ and all $x, y \in \mathbf{F^n}$.**

Let $x = (x_1, ..., x_n), y = (y_1, ..., y_n)$, where $x_i, y_i \in \mathbf{F}$ for $i = 1, 2, ..., n$, then

$$
\begin{aligned}

\lambda(x + y)

&= \lambda (x_1 + y_1, ..., x_n + y_n) \\

&= (\lambda x_1 + \lambda y_1, ..., \lambda x_n + \lambda y_n) \\

&= (\lambda x_1, ..., \lambda x_n) + (\lambda y_1, ..., \lambda y_n) \\

&= \lambda (x_1, ..., x_n) + \lambda (y_1, ..., y_n) \\

&= \lambda x + \lambda y

\end{aligned}
$$

---

**15. Show that $(a + b)x = ax + bx$ for all $a, b \in \mathbf{F}$ and all $x \in \mathbf{F^n}$.**

Let $x = (x_1, ..., x_n)$, where $x_i \in \mathbf{F}$ for $i = 1, 2, ..., n$, then

$$
\begin{aligned}

(a + b)x

&= ((a + b)x_1, ... ,(a + b)x_n) \\

&= (ax_1 + bx_1, ..., ax_n + bx_n) \\

&= (ax_1, ..., ax_n) + (bx_1, ..., bx_n) \\

&= ax + bx

\end{aligned}
$$

---
