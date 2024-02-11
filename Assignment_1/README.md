
<h1><b>ASSIGNMENT</b></h1>
Consider a solid with heat capacity C and an initial temperature T0. The solid is placed in an environment with temperature T_e, and heat is transferred from the environment to the solid over time. The rate of heat transfer, dQ/dt, can be described by the equation:

$$\frac{dQ}{dt} = -kA \frac{(T - T_{e})}{d}$$

***where k is the thermal conductivity of the solid, A is the surface area, d is the thickness of the solid, and T is the temperature of the solid.***

Use a for loop in Python to solve this equation numerically and determine the temperature T of the solid as a function of time ($t$). The simulation should run from $t=0$ to $t=t_{final}$ with a time step dt, and the initial temperature should be $T_0$.

Calculate the specific heat capacity $C_p$ of the solid by running the simulation for a range of heat inputs and plotting the temperature ($T$) versus the heat input ($Q$). Extract the slope of this plot, which will give you $\frac{C_p}{V}$, where $V$ is the volume of the solid.

***Given the parameters*** $ k=0.1$, $A=1$, $d=0.1$, $T_{e}=300$, $T_0=500$, $dt=0.01$, and $t_{final}=100 $.
