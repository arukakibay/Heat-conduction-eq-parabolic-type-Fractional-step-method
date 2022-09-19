# Heat-conduction-eq-parabolic-type-sweep-method
\Heat conduction equation is an equation of parabolic type. To get sufficient answer we need to give right initial and boundary conditions. We said that initial condition for this equation is 0 and boundary conditions were given as in image. In order to put heat we found points where it located and gave boundary condition by Dirichle T=1, so an important moment was to give right outlet of heat by Neumann as u[n - 1][j] = b[n - 1] / (1 - a[n - 1]).
Also we used fractional step method because this method is absolute stable.
