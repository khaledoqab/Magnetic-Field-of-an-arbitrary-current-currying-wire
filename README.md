# Magnetic-Field-of-an-arbitrary-current-currying-wire
The aim of this project is to solve for the magnetic field of an arbitrary current currying wire by applying the Bio-Savart Law, using simpson's-3/8 rule for integration. The second file dealt with fusion reactors case.
In the attached code (Magnetic Field), the code apply Simpsons-3/8 rule for integration to integrate a vector valued function that is derived from the Bio-Savart rule, and hence, find the magnetic field at a certain point.
The function described above was then applied to find the magnetic field due to a parametrized curve at a given point. And then it was applied to find the magnetic field around an apple shaped curve, a circle, a solenoid (short and long) and a toroid.
Both solenoid and toroid are analytically solvable, however, in order to solve them it was required that some approximations are made, mainly that the adjacent wires are close enough as to make the magnetic field in between equal to zero, and in the case of the solenoid, it should have been long enough as to avoid the "edge" effects. In this project, those approximations were tested using the computational solution.
The results were as follows, the analytical solution ($B\alpha \frac{1}{r}$) converged to the real value, as long as we are far from from the wire's edge. And in the case of the solenoid, it was found that the solenoid should be long(along the axis of the cylender) in order for the field to be uniform, as analytically assumed.

In the second code 
