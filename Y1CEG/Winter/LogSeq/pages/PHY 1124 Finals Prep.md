# Collisions
collapsed:: true
	- Gobber hours
	  collapsed:: true
		- ### Momentum and Impulse
			- Momentum is the mass in motion
				- Vid
				  collapsed:: true
					- {{video https://www.youtube.com/watch?v=NIVNfI0RN2k}}
				- $p = mv$
			- Impulse is the change of momentum of the particle
				- Magnitude of impluse is equal to the area under the Force-Time curve $F \Delta t$
			- ### Elastic Collisions
				- Momentum and Kinetic Energy are conserved
					- $$m_1v_{1i} + m_2v_{2i} = m_1v_{1f}+ m_2 v_{2f}$$
					- $$\frac{1}{2}m_1v_{1i}^2 +\frac{1}{2} m_2v_{2i}^2 = \frac{1}{2}m_1v_{1f}^2+ \frac{1}{2}m_2 v_{2f}^2$$
					- $$v_{1f} = \Big( \frac{m_1 - m_2}{m_1 + m_2} \Big)v_{1i} + \Big (\frac{2m_2}{m_1+m_2} \Big)v_{2i}$$
					- $$v_{2f} = \Big( \frac{2m_1}{m_1 + m_2} \Big)v_{1i} + \Big (\frac{m_2 - m_1}{m_1+m_2} \Big)v_{2i}$$
				- ### Inelastic Collsion
					- Kinetic energy is not conserved although momentum is still conserved, where the objects stick together
					- $$m_1 v_{1i} = m_2v_{2i} = (m_1 + m_2)v_f$$
			- Vido
				- {{video https://www.youtube.com/watch?v=9YRgHikdcqs}}
		- ## Centre of Mass
		  collapsed:: true
			- The **centre of mass** is the point that moves if all of the mass of the system is concentrated at that point
			  collapsed:: true
				- {{video https://www.youtube.com/watch?v=2uszSnvzBEU}}
			- $$P_{cm} \frac{\sum m_i x_i}{\sum m_i}$$
	- ## Linear Momentum and Impulse
		- **Linear momentum** is defined as the ^^product of mass and velocity of an object^^
			- Momentum is a vector measured in $\text{kg} \cdot \text{m/s}$
				- $$\vec{P} = m \vec{v}$$
			- If a force is applied to an object, Newton's Second Law
				- $$\vec{F} = \frac{\Delta \vec{P}}{\Delta t}$$
		- **Impulse** is defined as the ^^change in momentum^^ of the object if a ^^constant^^ external force of F is applied to the object
			- $$\vec{J} = \Delta \vec{P} = \vec{F} \Delta t$$
			- For a **net external force which is changing with time**, impulse is defined as:
				- $$\vec{J} = \Delta \vec{P} = \int_{t_i}^{t_f} \vec{F}(t) \ dt$$
		- ^^**Note:**^^
			- If a Force vs Time plot is provided, **Impulse** is the area under the curve
			- When **net external force** is ^^zero^^, momentum remains ^^conservered^^
		- Example:
		  background-color:: blue
			- A soccer player applied an average force of 180 N during a kick. The kick accelerates a 0.45 kg soccer ball from rest to a speed of 18m/s. What is the impulse measured on the ball
				- ![ImpulseQ1.png](../assets/ImpulseQ1_1712030746620_0.png){:height 263, :width 423}
			- A 2.5 kg Dodge ball hits the back wall of a school gym at 15 m/s at an angle of 50º to the wall. The ball is in contact with the wall for 0.15s before bouncing back at 12 m/s at an angle of 60º to the wall.  What average force was exerted by the ball on the wall? ![Screenshot from 2024-04-02 12-18-01.png](../assets/Screenshot_from_2024-04-02_12-18-01_1712075295478_0.png){:height 271, :width }
				- ![ImpulseQ2.png](../assets/ImpulseQ2_1712076261024_0.png)
		- A force $F  = (2t^2 -5)N$ is acting on a moving object with mass of 2*kg* in the direction of its motion for 5 seconds. If the initial speed of the particle is 5*m/s.*
			- ![ImpulseQ3.png](../assets/ImpulseQ3_1712076610999_0.png)
	- ## Conservation of Momentum
		- **Conservation of momentum** means that the change in momentum (^^impulse^^) is zero
			- $$\Delta \vec{p} = 0 \qquad \rightarrow \qquad \vec{p}_f = \vec{p}_i$$
		- If the **net external force on a system of objects is zero**, the impulse of the system will be zero and the total **momentum of the system remains constant**
		- Note that ^^sum of all internal forces^^ between elemetns of a system should be ^^zero^^ because of Newton's third law
	- ## Collisions
		- ### **Elastic Collision**
			- In a **perfectly elastic collision**, two objects completely bounce off each other
				- Assume there is ^^no loss of energy^^ in this collision because there is **no deformation**
			- ^^**Note:**^^
				- During this collision, **total momentum** and **total kinetic energy** of the two objects are **conserved**, from before and after the collision
			- **Conservation of Kinetic Energy:**
			  background-color:: green
				- $$\frac{1}{2}m_Av^2_{A1} + \frac{1}{2}m_Bv^2_{B1} = \frac{1}{2}m_Av^2_{A2} + \frac{1}{2}m_Bv^2_{B2}$$
			- **Conservation of Total Momentum**
			  background-color:: green
				- $$m_A\vec{v}_{A1} + m_B\vec{v}_{B1} = m_A\vec{v}_{A2} + m_B\vec{v}_{B2}$$
		- ### **Elastic Collision with One Object Intitially at Rest**
			- It is very commom to have **one of the objects initially at rest**
				- Since we still have elastic collision, both kinetic energy and total momentum are conserved
			- **Equation for One Moving Object**
			  background-color:: green
				- $$v_{A2} = \frac{m_A - m_B}{m_A + m_B} v_{A1}$$
		- ### **Perfectly Inelastic Collision**
			- In a **perfectly inelastic collision**, the two objects ^^stick together^^ after collision
				- The **kinetic energy** is not ^^conserved^^ because part of the energy is lost due to **deformation**
				- **Total momentum** is ^^conserved^^
			- **Kinetic Energy**
			  background-color:: green
				- $$\frac{1}{2}m_Av^2_{A1} + \frac{1}{2}m_Bv^2_{B1} > \frac{1}{2}m_Av^2_{A2} + \frac{1}{2}m_Bv^2_{B2}$$
			- **Conservation of Total Momentum**
				- $$m_A\vec{v}_{A1} + m_B\vec{v}_{B1} = (m_A + m_B)\vec{v}_{2}$$
		- Example:
		  background-color:: blue
			- A 3000 kg truck traveling at 50 km/hr strikes a stationary 1000 kg car, locking the two vehicles together. (a) What is the final velocity of the two vehicles? (b) How much of the initial kinetic energy is lost to the collision?
			- Two carts on a friction less surface collide and stick to each other. What is the velocity of the two carts after collision?
				- ![Screenshot from 2024-04-02 13-56-44.png](../assets/Screenshot_from_2024-04-02_13-56-44_1712080625125_0.png)
			- A cart with mass 340 g moving on a frictionless linear air track at an initial speed of 1.2 m/s undergoes an elastic collision with an initially stationary cart of unknown mass. After the collision, the first cart continues in its original direction at 0.66 m/s.
			- A firework explodes and forms three fragments of equal mass. One fragment travels directly upward at 14 m/s and the second fragment moves at 25 m/s at 25° below the horizontal to the right. Determine the velocity of the third fragment immediately after the explosion.
			- Two objects slide over a frictionless horizontal surface. The first object, m1=5m1​=5 kg, is propelled with a speed of $v_{1i}=4.5 \text{m/s}$ toward the second object, $m_2=2.5\text{kg}$ which is initially at rest. After the collision, both objects have velocities which are directed at $θ=30°$ on either side of the original line of motion of the first object. What are the final speeds of the two objects? Is the collision elastic or inelastic?
	- ### Shell Explosion
		- **Momentum Conservation in the Centre of Mass Frame**
			- The centre of mass behaves as if it were a **single particle of combined mass** $M$ located at an imaginary point, where that net external foce would be applied
			- Location of centre of mass is where the mass of the entire system would be concentrated
			- The motion of the center of mass depends only on the **net external force** acting on the entire system
			- If there is **no external force**, momentum is conserved
			- If there is **external force**, there will be ^^impulse^^ on the centre of mass
- # Rotational Kinematics and Dynamics
	- ## Dynamics of Rotational Motion
	  collapsed:: true
		- ## Torque
			- **Torque** is simply tendency of rotation
			- It is a rotational equivalent of force defined as
				- $$\tau = |\vec{r} \times \vec{F}| = rF \sin \theta$$ where
					- $r$ is the magnitude of vector $\vec{r}$ which is deifned from **centre of rotation** (^^ref. point^^) to **point of exertion of force** (^^point of action^^)
					- $\theta$ is the angle
			- Forces that cause NO torque are
				- Parallel to axis of rotation $(\sin \theta = 0)$
				- Acting at centre of rotation $(r=0)$
			- Example:
				- You and your friend are trying to push open a gate that has a single hinge on one side. The gate starts opening if you apply a force of 60N perpendicular to the gate, at a point that is 60cm horizontally away from the hinge, parallel to the ground. If your friend is only able to push the gate with a force of 40N perpendicular to the door, where should they apply the force in order to open the gate?
				- Seven forces are applied to a beam supported at the center as shown. Rank the torques produced by each force about the hinge from greatest to least, labeling the forces from 1-7 starting left to right (2F forces make an angle of 45 °45 °respect to the beam)
					- ![Screenshot from 2024-04-02 14-10-39.png](../assets/Screenshot_from_2024-04-02_14-10-39_1712081522298_0.png){:height 206, :width 523}
		- ## Rotational Kinematics
			- The parameters describing the translational motion have an analogue in rotational mtion
				- **Kinematic Equations for Rotational Motion**
				  background-color:: green
					- $$\theta_f = \frac{1}{2}\alpha t^2 + \omega_i t + \theta_i$$
					- $$\omega_f = \alpha t + \omega_i$$
					- $$\omega_f^2 - \omega_i^2 = 2 \alpha \Delta \theta$$
					- $$\frac{1}{2} (\omega_f + \omega_i)t = \Delta \theta$$
				- ^^**Note:**^^ For **uniform circular motion**, $\alpha - 0$
			- Example:
			  background-color:: blue
				- A flywheel turns through 60 revolutions as it slows from an angular speed of 2 rad/s to a stop.
					- Assuming a constant angular acceleration, find the time for it to come to rest.
					- What is its angular acceleration?
					- How much time is required for it to complete the first 20 of the 60 revolutions
		- ## Moment of Inertia
			- ### Moment of Inertia of Discrete partices
				- The **moment of inertia** of an object is a measure of the ^^resistance^^ of the object to ^^changes^^ in **rotational motion**
					- The quanity shows how the mass of an object is distributeed about its *axis of rotation*
				- For point masses $m_i$ at distances $r_i$ from axis of rotation, the moment of inertia is
					- $$I = \sum m_i \cdot r_i^2$$
						- with units $\text{kg} \cdot \text{m}^2$
				- ^^**Note:**^^ The value of $I$ changes if the axis of rotation changes
			- ### Moment of Inertia of Objects with a Continuous Mass
				- When there is an extended object with a **continuous mass distribution**, the the moment of inertia can be found with:
					- $$I = \int r^2 \ dm$$
			- Example:
			  background-color:: blue
				- Calculate the moment of inertia of a rotating disk with radius of R and mass M about an axis which is passing through its center and it is perpendicular to the disc.
		- ## Parallel Axis Theorem
			- If the object is rotating about an unknown axis, **Parallel Axis Theorem** to calculate the moment of inertia about this new axis
			- If we know that the moment of inertia about an axis that extends through the body's **centre of mass** $(I_{COM})$, the moment of inertia about an axis that is ^^parallel^^ to this axis is
				- $$I = I_{COM} + M \cdot h^2$$
				- where $h$ is the **distance between the axes** and the $M$ is the total mass of the object
					- ![Screenshot from 2024-04-02 14-31-52.png](../assets/Screenshot_from_2024-04-02_14-31-52_1712082732282_0.png)
			- ### Moment of Inertia in Composite Shapes
				- For **composite shapes**, you can use the moment of inertia of their sub-components to the moment of inertia, as long as you are **careful with the axis of rotation** for each ^^sub-component^^
			- Example:
				- Tom and Jerry decide to build a snowmen at the edge of a cliff.  The snowman consists of three spheres with radii 90 cm, 60 cm and 30 cm, and the density of snow is $300\text{kg/m}^3$.  They fight and Tom pushes the snowman over the cliff.  The snowman begins to rotate around its center of mass as it falls.  What is the moment of inertia of the snowman as it’s falling?
					- For a solid sphere, $I_{cm} = \frac{2}{5} MR^2$ and $V = \frac{4}{3}\pi R^3$
						- ![Screenshot from 2024-04-02 14-47-53.png](../assets/Screenshot_from_2024-04-02_14-47-53_1712083691984_0.png)
				- Two thin Hoops each of mass M and radius of R are joined together as shown in the figure. What is the moment of inertia for rotations in the plane of the page about pint *O*?
				- (The moment of inertia of a hoop with mass M and Radius R about an axis perpendicular to it and passing through its center is equal to $MR^2$)\
					- ![Screenshot from 2024-04-02 14-48-41.png](../assets/Screenshot_from_2024-04-02_14-48-41_1712083743778_0.png)
		- ## Rotational Analog of Newton's Second Law
			- Torque is the rotational analog for force
			- When torque is applied, the angular acceleration changes
				- This change is given by **Newton's Second Law for rotations**:
					- $$\sum \tau = I \cdot \alpha$$
					- where $\alpha$ is in $\text{rad/s}^2$
			- Example:
			  background-color:: blue
				- A thin uniform rod (length=1m, mass = 5kg) is pivoted about a horizontal, frictionless pin through one end of the rod. The rod is released when it makes an angle of 60° above the horizontal. What is the angular acceleration of the rod at the instant it is released? (The moment of inertia of a rod with length of L and mass of m about one of its ends is $I = \frac{1}{3} mL^2$)
					- ![Screenshot from 2024-04-02 14-51-41.png](../assets/Screenshot_from_2024-04-02_14-51-41_1712083959771_0.png)
				- A 10 kg mass is hanging from a rope wrapped around a cylindrical pulley. The falling mass causes the pulley to rotate. The mass of the pulley is 3 kg.  (The moment of inertia of a solid cylinder with radius R and mass of M about its axis of symmetry is $I = \frac{1}{2}MR^2$
		- ## Rotational Kinetic Energy
			- When an object is rotating, we have **rotational kinetic energy** from all the mass elements rotating
				- $$K = \frac{1}{2} I \cdot \omega^2$$
				- The kinetic energy of a rigid body with **both translation and rotation**
					- $$K = \frac{1}{2}I \omega^2 + \frac{1}{2}Mv^2_{cm}$$
			- ### Conservation of Energy
				- Similar to translational motion, if there is no friction or other non-conservative forces, total mechanical energy is conserved
			- Example:
			  background-color:: blue
				- A stone with a mass of 9.5kg is hung vertically from the end of a rope that is wound around a pulley on a boat. The moment of inertia of the pulley is 0.47kg $\text{m}^2$ and the radius is 0.25m. The stone is released from rest and falls toward the water, causing the pulley to rotate. After the stone has fallen 2.5 m, what is the angular velocity of the pulley? (Mass of the rope is negligible)
				- A thin rod with mass of M and length of L is hinged to the wall at one end. The rod is held horizontally and then released. What is the speed of the tip of the rod as it hits the wall? Assume the hinge is frictionless. The moment of inertia for a thin rod about one of its ends is $\frac{1}{3}ML^2$
		- ## Rotational Work and Torque
			- When torque is applied to an object, work is beign performed
				- Work done by a torque caused by a force which is along the angular displacement is:
					- $$W = \tau (\theta_f - \theta_i)$$
				- or integral
					- $$W = \int \vec{\tau} \cdot d\vec{\theta}$$
				- If the force is opposite the direction of angular displacement, then the torque is doing negative work; if in the same direction, then positive work
			- Example:
			  background-color:: blue
				- A wheel whose rotational inertia is 10 $\text{kg} \cdot \text{m}^2$  starts from rest and accelerates under a constant torque of 3.0 $\text{N} \cdot \text{m}$ for 8.0 seconds. What is the wheel's rotational kinetic energy at the end of the 8 seconds?
		- ## Rolling Motion
			- Roling without slipping is a combination of two mtions
				- A ^^translational motion^^ of the centre of the mass with the velocity:
					- $$v_{cm} = R \cdot \omega$$
				- A ^^rotational motion^^ of all points on the object
			- In rolling without slipping, the **point of contact** is instananeously at rest
				- All points of the rolling object are rotating about this point of contact
				- ![Screenshot from 2024-04-02 15-12-19.png](../assets/Screenshot_from_2024-04-02_15-12-19_1712085155531_0.png)
			- The rolling without slipping motion is usually caused by the static friction between the point of contact and surface
			- For rolling without slipping:
			  background-color:: green
				- $v_{cm} = R \omega$
				- $a_{cm} = R \alpha$
				- $d_{cm} = R \theta$
				- Since a rolling object has **both translational and rotational motion**, the total kinetic energy for an object rolling without slipping is:
					- $$K =  \frac{1}{2}mv^2 + \frac{1}{2}I_{cm} \omega^2 $$
					- First term is translational kinetic energy of centre of mass, and second is rotational kinetic energy of the object
			- Example:
			  background-color:: blue
				- Show that the friction for a round object of radius R rolling (without slipping) down an incline of angle $\theta$ has magnitude given by
					- $$f = \frac{mg \sin \theta}{1+ \frac{mR^2}{I}}$$![Screenshot from 2024-04-02 15-17-03.png](../assets/Screenshot_from_2024-04-02_15-17-03_1712085441850_0.png){:height 226, :width 429} $\\$ Let clockwise rotation be positive, and let the x and y directions be along the slope and perpendicular to the slope. Positive is up for y, and downward along the slope for x.
				- A marble starts from rest and rolls without slipping on the loop-the-loop track in the figure. Find the minimum starting height h from which the ball will remain on the track throughout the loop. Assume the marble's radius is small compared with R. The moment of inertia for a solid sphere is $\frac{2}{5}Mr^2$ Enter your answer by using R = 70 cm (radius of the loop) and r = 1.0 cm (radius of the marble). Your answer should be in meters with three significant figures
					- ![Screenshot from 2024-04-02 15-19-24.png](../assets/Screenshot_from_2024-04-02_15-19-24_1712085580095_0.png)
		- ## Angular Momentum
			- **Angular momentum** is a vector the cross product of position vector and momentum vector
				- $$\vec{L} = \vec{r} \times \vec{P}$$
			- **Magnitude** of this vector is equivalent to $|\vec{L}| = |\vec{r}||\vec{p}| \sin \theta$
			- For rigid bodies rotating around an axis with angular frequency $\omega$, the magnitude of angular momentum in analogy to  linear momentum can be represented by
				- $$L  = I \omega$$
			- ### Angular Momentum and Torque
				- $$\vec{\tau} =  \vec{r} \times \vec{F} =  \vec{r} \times \frac{\vec{dP}}{dt} = \frac{\vec{dL}}{dt}$$
				- If the **net externl torque** about an axis acting on a rotating body is **zero**, the **angular momentum about the same axis remains constant**
					- $$L_f = L_i$$
			- Example:
			  background-color:: blue
				- An object of mass $m$ and speed $v_0$ strikes a bob pendulum with mass $M$ and length of $l$ which is hanging from the ceiling and sticks to it and they both move (oscillate) to the right. Find the size and direction of the angular momentum with respect to where the rope is attached to the ceiling .
				- In an isolated system, the moment of inertia of a rotating object is halved. What happens to the angular velocity of the object?
				- You're sitting on a rotating stool, initially rotating at 3.0 radians per second. You're holding a 5.0 kg dumbbell very close to you, 0.05 meters away from your center of rotation. You then extend your arms 1.0 meters away from you with the dumbbell. The moment of inertia of you and the stool is 4.0 $\text{kg} \cdot \text{m}^2$. Neglect the mass of your arms and any rotational friction in the seat. What is your new angular velocity?
	- ## Periodic Motion
- # Electrostatics
  collapsed:: true
	- Goober Hours (does have videos)
	  collapsed:: true
		- ### Electric Charge
		  collapsed:: true
			- Carried by certain subatomic particles (protons, newtons)
			- The fundamental charge is $\pm1.602 \times 10^-{19} \text{C}$ (all charges are multiples of this)
		- ### Coulombs Law
		  collapsed:: true
			- Opposite charges attract because of the **electric force**
			- **Point charge** refers to a particle of zero size thtat carries an electric charge
			- #### Coulombs Law
				- $$F = k \frac{q_1 q_2}{r^2}$$
					- where $k = 8.99 \times 10^9 \text{N m}^2 / \text{C}^2$
				- The magnitude of electric force between two objects is equal to the constant times the charge on the objects divided by the distance between (squared)
				- Electric force increases as charge increases
		- ### Electric Fields
		  collapsed:: true
			- The electric force arises from an electric field
			- Region of space around a charged object
			- When another charged object enters the electric field, an electric force acts on it
			- #### Electric Field
				- $$E = K_c \frac{q}{r^2}$$
					- Constant times charge divided by distance from some object generating field to other object
			- **Electric dipole** on two charges equal in magnitude, but opposite in sign
			- {{video https://www.youtube.com/watch?v=PSlnlXjaHA4}}
				- $$E = k_e \frac{2 qa}{(y^2 + a^2)^{3/2}}$$
			- {{https://www.youtube.com/watch?v=Mt9Rn2Ek0SU&t=282s}}
		- ### Electric Flux
		  collapsed:: true
			- The rate of flow of the electric field through a given surface (vid)
			  collapsed:: true
				- {{video https://www.youtube.com/watch?v=yOv4xxopQFQ&t=393s}}
			- The product of magnitude of the electric field adn the surface area $A$, perpendicular to the field
				- Electric Flux through open surface
					- $\phi_E = EA\cos\theta$
				- Electric Flux through closed surface
					- $\phi = \int \vec{E} \cdot d\vec{A}$
		- ### Gauss's Law
		  collapsed:: true
			- The electric flux going through a closed surface, is the sum of all charges Q inside the closed surface divided by permitivity of free space $E_0$
			- $$\phi_e = \frac{q}{\varepsilon_0}$$
			-
			-
	-