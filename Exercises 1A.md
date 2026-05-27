# Exercises 1A

## 1. Show that $\alpha + \beta = \beta + \alpha$ for all $\alpha, \beta \in \mathbf{C}$. 

Let $\alpha = x + yi$, $\beta = p + qi$, where $x, y, p, q \in \mathbf{R}$, then

$$
\begin{aligned} 

\alpha + \beta 

&= (x + p) + (y + q)i \\ 

&= (p + x) + (q + y)i \\ 

&= \beta + \alpha

\end{aligned}
$$

## 2. Show that $(\alpha + \beta) + \lambda = \alpha + (\beta + \lambda)$ for all $\alpha, \beta, \lambda \in \mathbf{C}.$

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

## 3. Show that $(\alpha \beta)\lambda = \alpha(\beta \lambda)$ for all $\alpha, \beta, \lambda \in \mathbf{C}$.

Let $\alpha = x + yi$, $\beta = p + qi$, $\lambda = a + bi$, where $x, y, p, q, a, b \in \mathbf{R}$, then

$$
\begin{aligned}


\end{aligned}
$$ 

## 4. Show that $\lambda (\alpha + \beta) = \lambda \alpha + \lambda \beta$ for all $\lambda, \alpha, \beta \in \mathbf{C}$.

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

## 5. Show that for every $\alpha \in \mathbf{C}$, there exists a unique $\beta \in \mathbf{C}$ such that $\alpha + \beta = 0$.

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

## 6. Show that for every $\alpha \in \mathbf{C}$ with $\alpha \neq 0$, there exists a unique $\beta \in \mathbf{C}$ such that $\alpha \beta = 1$.

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

## 7. Show that $$\frac{-1 + \sqrt{3}i}{2}$$ is a cube root of 1 (meaning that its cube equals 1).

$$
\begin{aligned}

(\frac{-1 + \sqrt{3}i}{2})^3

&= \frac{(-1 + \sqrt{3}i)^2 (-1 + \sqrt{3}i)}{8} \\

&= \frac{(-2 - 2\sqrt{3}i)(-1 + \sqrt{3}i)}{8} \\

&= \frac{2 - 2\sqrt{3}i + 2\sqrt{3}i + 6}{8} \\

&= 1

\end{aligned}
$$

## 8. Find two distinct square roots of i.
