# 2d-steady-state-heat-equation


## Introduction
This repository provides a solution to the transient 2D heat equation using Physics-Informed Neural Networks (PINNs). PINNs leverage the power of deep learning while respecting the underlying physical laws described by partial differential equations (PDEs). This approach allows for the solution of complex PDEs without the need for traditional discretization methods.


## Governing Equation
<p>$$ \left( \frac{\partial^2 u}{\partial x^2} + \frac{\partial^2 u}{\partial y^2} \right)$$ </p> 
where:

**u(x, y)  is the temperature distribution**

**x  and  y  are the coordinates**

## Domain
<p>$$ \Omega = \{ (x, y) \ | \ x \in [0, 1], \ y \in [0, 1] \} $$</p>

where:
- \( x \) and \( y \) are  both ranging from 0 to 1.

## Boundary Conditions

bottom wall = T(x,0) = 273K

top wall = T(x,1) = 400k

left wall = T(0,y) = 300k

right wall = T(1,y) = 300k


**when normalized:**


bottom wall = T(x,0) = 273/400 = 0.6825

top wall = T(x,1) = 400/400 = 1

left wall = T(0,y) = 300/400 = 0.75

right wall = T(1,y) = 300/400 = 0.75

## Results
**Loss function:**


  


