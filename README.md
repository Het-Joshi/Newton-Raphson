# Newton-Raphson
---
This method was named after Sir Isaac Newton and Joseph Raphson. 
It begins with a function f defined over real numbers, its derivative f′, and an initial guess x0 for the root of f. The solution comes to a stop when the function satisfies the assumptions made in the derivation of the formula and the initial guess is close.

The *General Newton Raphson Method Formula* is:

---
![download](https://user-images.githubusercontent.com/96608251/187615403-b68a2e05-9063-4e1f-9f5d-70717692cceb.png)

---

### General working algorithm:

1. Compute the values of f(x) and f′(x) for a given initial x.
2. While the ratio of f(x) and f′(x) is greater than allowed error ϵ,xn+1=xn–f(xn)f′(xn)For all values from 0 to n.

---
