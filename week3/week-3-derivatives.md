# Derivatives - Tangent Lines - Slope of a Graph at a Point

Take graph of function y = f(x) and pick a point for x (x=a)
How fast is f(x) is changing at x=a
Slope of f(x) at x=a gives rate of chagne of f(x) at x=a
Also called the derivative of f(x) at x=a or f′(a)
Only have one point, normally need 2 points to calculate slope
f′(a) = lim h->0

## Simple Example
graph of y=3x
x = price
y = revenue
x = a dollars

simple solution with a simple straight line
(a, 3a)
(a+1, 3(a+1))

Calculate slope using slope formula
3(a+1) - 3a / (a+1) - a = 3

## Realistic Model
y = f(x)
x = price
y = revenue
more natural curve - not a straight line

rate of change varies based on each point along x, can even be negative
slope of tangent line changes based on location of a
f′(a) - the derivative of the function f at x=a

a and a+h - h is notional but means a little bit
corrdinates of each point
(a, f(a))
(a+h, f(a+h))
Slope = (f(a+h) - f(a)) / ((a+h) - a) or just (f(a+h) - f(a)) / h

Calculus says f′(a) = lim h-> 0 as h moves to 0 the line segment gets closer to the tangent line 

# Tangent Lines - The Derivative Function
graph of f(x) = x²

f′(a) = lim		((a + h)² - a²) / h
		h->0

= lim	a² + 2ah + h² - a² / h = h(2a+h) / h = 2a+h (these are all basic algebra steps)
  h->0

### Algebra from above
((a + h)² - a²) / h
	(a+h)² = (a+h) * (a+h) = (a*a) + (a*h) + (h*a) + (h*h) = a² + 2ah * h²
a² + 2ah + h² - a² / h - a² cancel out (a² - a² = 0) = 2ah + h² / h
	2ah + h² = 2ah + h² -> take out common factors (only h) h(2a + h)
h(2a+h) / h = h/h cancels out leaving 2a+h

As h approaches to 0 then equals 2a
f′(a) = 2a - is derivative function - take in value x and f′(a) is the derivative