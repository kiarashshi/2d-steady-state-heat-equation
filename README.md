# 2d-steady-state-heat-equation


## Introduction
This repository provides a solution to the steady state 2D heat equation using Physics-Informed Neural Networks (PINNs). PINNs leverage the power of deep learning while respecting the underlying physical laws described by partial differential equations (PDEs). This approach allows for the solution of complex PDEs without the need for traditional discretization methods.


## Governing Equation

<p>$$\frac{\partial^2 u}{\partial x^2} + \frac{\partial^2 u}{\partial y^2} = 0$$</p>
where:


**u(x, y)  is the temperature distribution**


**x  and  y  are the coordinates**

## Domain
<p>$$ \Omega = \{ (x, y) \ | \ x \in [0, 1], \ y \in [0, 1] \} $$</p>

where:
- \( x \) and \( y \) are  both ranging from 0 to 1.

## Boundary Conditions

bottom wall = T(x,0) = 0

top wall = T(x,1) = 1

left wall = T(0,y) = 0

right wall = T(1,y) = 0




## Results
**Loss function:**

![Screenshot (657)](https://github.com/user-attachments/assets/e2240596-9b10-4047-9808-b3aab8e83965)

![Screenshot (658)](https://github.com/user-attachments/assets/a3568d3d-e2cc-46da-a2d6-4e024005ca7a)


![Screenshot (659)](https://github.com/user-attachments/assets/0e123da9-ba0d-4732-9f4c-c8fff9f7361b)


![Screenshot (660)](https://github.com/user-attachments/assets/fb2a0753-c3be-4ef8-9676-599b6564106a)


  


