# Lecture-6-L-Hospital-s-rule.-Continuation-of-investigation-of-functions
Lecture VI. L`Hospital`s rule. Continuation of investigation of functions


![](https://github.com/AM-PJATK/Lecture-6-L-Hospital-s-rule.-Continuation-of-investigation-of-functions/blob/main/6.4.png?raw=true)

# Convexity and Concavity of Curves, Inflection Points

## Definition
We say that a function \( f \) is **convex** in an interval \( P \) if for any numbers \( x_1, x_2 \in P \) and for any number \( \Delta \) where \( 0 < \Delta < 1 \), the following condition is satisfied:
\[ f \big( (1 - \Delta)x_1 + \Delta x_2 \big) \leq (1 - \Delta) f(x_1) + \Delta f(x_2). \]

Geometrically, a function \( f \) is convex if each point of a secant segment is located above or at the graph of the function.

## Definition
We say that a function \( f \) is **strictly convex** in an interval \( P \) if for any numbers \( x_1, x_2 \in P \) and for any number \( \Delta \) where \( 0 < \Delta < 1 \), the following condition is satisfied:
\[ f \big( (1 - \Delta)x_1 + \Delta x_2 \big) < (1 - \Delta) f(x_1) + \Delta f(x_2). \]

Geometrically, a function \( f \) is strictly convex if each point of a secant segment connecting the points \( (x_1, f(x_1)) \) and \( (x_2, f(x_2)) \) is located above the graph of the function.

Examples of convex and strictly convex functions are shown in figures 6.1 and 6.2, respectively.

![fig 6.1](url)
![fig 6.2](url)

## Definition
We say that a function \( f \) is **concave** in an interval \( P \) if for any numbers \( x_1, x_2 \in P \) and for any number \( \Delta \) where \( 0 < \Delta < 1 \), the following condition is satisfied:
\[ f \big( (1 - \Delta)x_1 + \Delta x_2 \big) \geq (1 - \Delta) f(x_1) + \Delta f(x_2). \]

Geometrically, a function \( f \) is concave if each point of a secant segment is located below or at the graph of the function.

## Definition
We say that a function \( f \) is **strictly concave** in an interval \( P \) if for any numbers \( x_1, x_2 \in P \) and for any number \( \Delta \) where \( 0 < \Delta < 1 \), the following condition is satisfied:
\[ f \big( (1 - \Delta)x_1 + \Delta x_2 \big) > (1 - \Delta) f(x_1) + \Delta f(x_2). \]

Geometrically, a function \( f \) is strictly concave if each point of a secant segment connecting the points \( (x_1, f(x_1)) \) and \( (x_2, f(x_2)) \) is located below the graph of the function.

Examples of concave and strictly concave functions are shown in figures 6.3 and 6.4, respectively.

![fig 6.3](url)
![fig 6.4](url)

## Theorem
Let \( f \) be a function, continuous in an interval \( P \), and differentiable in the interior of \( P \). The function \( f \) is:
- **convex** in \( P \) if its derivative \( f' \) is a nondecreasing function in \( P \).
- **strictly convex** in \( P \) if its derivative \( f' \) is an increasing function in \( P \).
- **concave** in \( P \) if its derivative \( f' \) is a nonincreasing function in \( P \).
- **strictly concave** in \( P \) if its derivative \( f' \) is a decreasing function in \( P \).

## Theorem
Assume a function \( f \) is continuous in an interval \( P \) and two-fold differentiable in its interior \( P' \). The function \( f \) is:
- **convex** in an interval \( P' \) if \( f''(x) \geq 0 \) for every \( x \in P' \).
- **strictly convex** in an interval \( P' \) if \( f''(x) > 0 \) for every \( x \in P' \), and \( f'' \) is not a null-function on any subinterval of \( P' \) of finite length.
- **concave** in an interval \( P' \) if \( f''(x) \leq 0 \) for every \( x \in P' \).
- **strictly concave** in an interval \( P' \) if \( f''(x) < 0 \) for every \( x \in P' \), and \( f'' \) is not a null-function on any subinterval of \( P' \) of finite length.

## Corollary
- If \( f''(x) > 0 \) for every \( x \in (a, b) \), then \( f \) is strictly convex in \( (a, b) \). If additionally \( f \) is continuous in the interval \( [a, b] \), then it is also strictly convex in the interval \( [a, b] \).
- If \( f''(x) < 0 \) for every \( x \in (a, b) \), then \( f \) is strictly concave in \( (a, b) \). If additionally \( f \) is continuous in the interval \( [a, b] \), then it is also strictly concave in the interval \( [a, b] \).

## Definition
Let a function \( f \) be defined on some neighborhood of a point \( x_0 \). We say that a point \( (x_0, f(x_0)) \) is an **inflection point** of the function \( f \) if there exists a number \( \delta > 0 \) such that on one of the intervals \( (x_0 - \delta, x_0) \) or \( (x_0, x_0 + \delta) \) the function \( f \) is strictly convex, and on the second one it is strictly concave.

## Remark
Instead of saying that \( (x_0, f(x_0)) \) is an inflection point of a function \( f \), one often says: \( x_0 \) is an inflection point of \( f \).

## Theorem
Assume a function \( f \) is continuous in some neighborhood of a point \( x_0 \):
1. \( x_0 \) is an inflection point of \( f \), then \( f''(x_0) = 0 \) or \( f''(x_0) \) does not exist.
2. If \( f''(x) \) changes its sign by passing through the point \( x_0 \), then \( x_0 \) is an inflection point of \( f \).
3. If \( f''(x) = g(x)h(x) \), where \( g(x_0) \neq 0 \) and \( h(x_0) = 0 \), and the function \( f \) is continuous at \( x_0 \), then:
   - \( x_0 \) is an inflection point of \( f \) if \( h(x) \) changes its sign at \( x_0 \).
   - \( x_0 \) is not an inflection point of \( f \) if \( h(x) \) does not change its sign at \( x_0 \).

## Example
We will determine intervals of convexity and inflection points of the function \( f(x) = e^{x^2} \).

The domain of \( f \) is \( \mathbb{R} \). The function has derivatives of any order in the entire domain. Let us compute the second derivative of \( f \):
\[ f''(x) = e^{x^2} \big( 4x^2 + 2 \big). \]

Roots and the sign of the second derivative are of exactly the same sign of \( 2x^2 + 1 \), since the exponential function is always positive.

By the above theorems, \( f \) is strictly convex in the intervals \( (-\infty, -\frac{1}{\sqrt{2x^2 - 1}}) \) and \( (\frac{1}{\sqrt{2x^2 - 1}}, \infty) \), and is strictly concave in \( (-\frac{1}{\sqrt{2x^2 - 1}}, \frac{1}{\sqrt{2x^2 - 1}}) \).
