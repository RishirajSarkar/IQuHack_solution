# IQuHack_solution
Logic-wise we need to build:

1.   Input N from file/user
2.   Find the required qubits by 2 * bitsize of number
3.   Take a value of a, such that a and N are co-prime. (Write a gcd func)
4.   Classical register of the total bit size.
5.   Auto-initialize first register with H gate
6.   Placement of x and cx gates as required.
7.   Building that circuit
8.   Figuring out the state by IQFT and plot. *(This should remain the same as the current code)*
9.   Extract the value of r.
10.  Find the factors by using gcd.
---

Grateful mention for simplified explanation: https://kaustubhrakhade.medium.com/shors-factoring-algorithm-94a0796a13b1

---
