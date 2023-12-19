# Solving viscous Burger's Equation using Spectral method with Fourier transforms
This project was my final project of AMATH 581, Scientific Computing, at the University of Washington.
The goal of this project was to get a numerical solution to the viscous Burger's equation. The viscous Burger's equation is a nonlinear partial differential equation. While such an equation had previously forced me to use 
Newton's method, I can now simply use the Spetral method with Fourier series. Using Fourier transforms I got a value for the partial derivative with respect to time. From there I used Forward Euler and compared the numerical solution
to the analytic one and determining the order of the method. The method ended up being 1st order which is what I wanted since Forward Euler is 1st so that showed that our partial derivative was very accurate.

All coding was done with Python, using Numpy and matplotlib.
