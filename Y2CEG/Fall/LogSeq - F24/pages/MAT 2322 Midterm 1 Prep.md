### [[Relative Minimums and Maximums]]
- ### [[Absolute Extrema]]
- ### [[Lagrange Multipliers]]
- ### [[Double Integrals]]
- ### [[Double Integrals over General Regions]]
- ### [[Double Integrals in Polar Coordinates]]
- ## Topics Covered:
	- ## Maximum and Minimum Values
		- Suppose that $(a,b)$ is a critical point of $f(x,y)$ and that the second order partial derivatives are continuous in some regions that contain $(a,b)$, therefore
			- $$D = D(a,b) = f_{xx} (a,b) f_{yy} (a,b) - [f_{xy} (a,b)^2]$$
		- This provides the following classifications of the critical point
			- If $D > 0$ and $f_{xx}(a,b) > 0$ then there is a relative minimum at $(a,b)$
			  logseq.order-list-type:: number
			- If $D > 0$ and $f_{xx} (a,b) < 0$ then there is a relative maximum at $(a,b)$
			  logseq.order-list-type:: number
			- If $D<0$ then the point $(a,b)$ is a saddle point
			  logseq.order-list-type:: number
			- If $D = 0$ then the point $(a,b)$ may be a relative minimum, relative maximum or a saddle point
			  logseq.order-list-type:: number
	- ## Lagrange Multipliers
		- ### Method of Lagrange Multipliers
			- Solve the following system of equations
			  logseq.order-list-type:: number
				- $$\nabla f(x,y,z) = \lambda \nabla g(x,y,z) \\g(x,y,z) = k$$
			- Plug in all solutions $(x,y,z)$ from the first step into $f(x,y,z)$ and identify the minimum and maximum values, provided they exist and $\nabla g \ne \vec{0}$
			  logseq.order-list-type:: number
			- The constant $\lambda$ is called the **Lagrange Multiplier**
	- ## Double Integrals over Rectangles
		- ### Properties of Double Integrals
			- logseq.order-list-type:: number
			  $$\iint_D f(x,y) + g(x,y) \ dA = \iint_D f(x,y) \ dA + \iint_D g(x,y) \  dA$$
			- logseq.order-list-type:: number
			  $$\iint_D cf (x,y) \ dA = c \iint_D f(x,y) \ dA$$ where $c$ is constant
			- I the region $D$ can be split into two separate regions $D_1$ and $D_2$ then the integral can be written as
			  logseq.order-list-type:: number
				- $$\iint_D f(x,y) \ dA = \iint_{D_1} f(x,y) \ dA + \iint_{D_2} f(x,y) \ dA$$
	- ## Double Integrals in Polar Coordinates
		- ### Formula for Double Integral in Terms of Polar Coordinates
			- $$\iint_D f(x,y) \ dA = \int_{\alpha}^{\beta} \int_{h_1 (\theta)}^{h_2(\theta)} f(r \cos \theta, r \sin \theta) r \ dr \ d\theta$$
	- ## Applications of Double Integrals
		- ### Volume of Solids Under a Surface
			- Let $z = f(x,y) , (x,y) \in \mathbb{R}$ define a surface $S$
				- where $f(x,y) \ge 0 \forall (x,y) \in D$
			- Then the volume $V$ of solid above $D$ is:
				- $$V = \iint_D f(x,y) \ dA$$
		- ### Mass of the Lamina
			- Let $z = p(x,y), (x,y) \in D$ define the density of the lamina occupies the region $D$
			- The mass $m$ of the lamina is:
				- $$m = \iint_D \rho (x,y) \ dA$$
		- ### Moments and Centres of Mass
			- Find centre of mass of lamina with $p(x,y)$
			- Moments of the entire lamina about $x$ and $y$ axis are
				- $$M_x = \iint_D y \rho(x,y) \ dA \qquad M_y = \iint_D  x \rho (x,y) \ dA$$
			- Centre of Mass of Lamina are
				- $$(\overline{x}, \overline{y}) = \biggl( \frac{M_y}{m}, \frac{M_x}{m} \biggr)$$
		- ### Surface Area
			- For a differentiable surface $S$: $z = f(x,y), (x,y) \in D$, the area of the surface is
				- $$\iint_S \ dS = \iint_D \sqrt{(f_x )^2 + (f_y)^2 + 1} \ dA$$
				-