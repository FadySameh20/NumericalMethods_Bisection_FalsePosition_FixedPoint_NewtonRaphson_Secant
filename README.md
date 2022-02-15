# NumericalMethods_Bisection_FalsePosition_FixedPoint_NewtonRaphson_Secant
Comparing and analyzing the behavior of the numerical methods (Bisection, False Position, Fixed Point, Newton Raphson, Secant) by implementing a root finder equation which takes as an input the  equation, the technique to use and its required parameters (e.g. interval for the bisection  method).

* Specification:
The program contains the following features:
1. An interactive GUI that enables the user to enter equations containing different functions such as: {poly, exp, cos, sin}. Reading from files must be available as well.
2. Differentiation and Parsing.
3. A way to choose a method to solve the given equation.
4. A way to enter the precision and the max number of iterations otherwise default values are used, Default Max Iterations = 50, Default Epsilon = 0.00001;
5. The answer for the chosen method indicates the number of iterations, execution time, all iterations, approximate root, and precision.
6. Computing the theoretical bound of the error for the methods.
