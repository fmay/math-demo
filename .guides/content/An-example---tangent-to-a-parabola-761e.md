To make things more concrete, suppose that the function we had was $f(x)=x^2$ and that the point was $(1,1)$. The graph of $f$ is of course a parabola. Any line through the point $P(1,1)$ has equation

$$y−1=m(x−1)$$

where $m$ is the slope of the line. So instead of finding the equation of the secant and tangent lines we will find their slopes.

Let $Q$ be the other point on the parabola, with coordinates $(x,x2)$. We can “move $Q$ around on the graph” by changing $x$. Whatever $x$ we choose, it must be different from $1$, for otherwise $P$ and $Q$ would be the same point. 

What we want to find out is how the line through $P$ and $Q$ changes if $x$ is changed (and in particular, if $x$ is chosen very close to $a$). 

Now, as one changes $x$ one thing stays the same, namely, the secant still goes through $P$. So to describe the secant we only need to know its slope. 

By the “rise over run” formula, the slope of the secant line joining $P$ and $Q$ is

$$m_{PQ}= \frac{\Delta y}{\Delta x}
\quad\text{where}\quad
\Delta y=x^2-1
\quad\text{and}\quad
\Delta x = x-1.$$

By factoring $x^2 - 1$ we can rewrite the formula for the slope as follows

$$\begin{equation}
m_{PQ}= \frac{\Delta y}{\Delta x}
=\frac{x^2-1}{x-1}
=\frac{(x-1)(x+1)}{x-1}
= x+1.
\label{eq:secant-slope-simplified}
\end{equation} $$

As $x$ gets closer to $0$, the slope $m_{PQ}$, being $x+1$, gets closer to the value $1+1=2$. We say that

||| definition
the limit of the slope $m_{PQ}$ as $Q$ approaches $P$ is $2$.
|||

In symbols,

$$ \lim_{Q\to P} m_{PQ} = 2, $$

or, since $Q$ approaching $P$ is the same as $x$ approaching $1$,

$$ \begin{equation}
\lim_{x\to 1} m_{PQ} = 2.
\label{eq:tangent-slope-found}
\end{equation} $$

So we find that the tangent line to the parabola $y=x^2$ at the point $(1,1)$ has equation

$$ y-1 = 2 (x-1), \text{~i.e.~} y=2x-1. $$

**A warning**: you cannot substitute $x=1$ in equation (1) to get (2) even though it looks like that's what we did. The reason why you can't do that is that when $x=1$ the point $Q$ coincides with the point $P$ so *the line through $P$ and $Q$* is not defined; also, if $x=1$ then $ \Delta x=\Delta y =0$ so that the rise-over-run formula for the slope gives

$$ m_{PQ} = \frac{\Delta x}{\Delta y} = \frac 00 = \text{~undefined.} $$

It is only after the algebra trick in (1) that setting $x=1$ gives something that is well defined. But if the intermediate steps leading to $m_{PQ}=x+1$ aren't valid for $x=1$ why should the final result mean anything for $x=1$? 

Something more complicated has happened. We did a calculation which is valid for all $x\neq 1$, and later looked at what happens if $x$ gets *very close to 1*. 

This is the concept of a limit and we'll study it in more detail later in this section, but first another example.






















