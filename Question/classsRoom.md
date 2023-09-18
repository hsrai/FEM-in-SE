# Q1. what are the differences between analtical method and numerical method of structural analysis ?

Analytical methods and numerical methods are two different approaches to solve problems in structural analysis. Analytical methods are based on mathematical equations and can provide exact solutions using pencil and paper. Numerical methods, on the other hand, are based on algorithms and provide approximate solutions using computers 

Analytical methods are more rigorous and provide exact solutions, but they become hard to use for complex problems. Numerical methods have become popular with the development of computing capabilities, and although they give approximate solutions, they have sufficient accuracy for engineering purposes 

In structural analysis, analytical methods are best suited for designing calculations and are suitable for checking calculations with certain limitations. Numerical methods, on the other hand, are best suited for checking calculations and are practically ineffective for designing calculations. They are versatile and flexible but need much work to be developed. However, only simple software is required for their application

# Q2. What are the fundamental principles employed in the analysis of indeterminate structure?

In the analysis of indeterminate structures, several fundamental principles are employed to ensure the structure is in equilibrium, maintain continuity, and relate displacement to forces 12. These principles include:

### 1. Equilibrium Equations:
The structure must satisfy the equilibrium equations, which ensure that all forces acting on the structure are balanced.

### 2. Compatibility Equations:
Compatibility equations are necessary to maintain the continuity of the structure without any breaks. They ensure that the structure remains intact and connected.

### 3. Force-Displacement Equations:
Force-displacement equations describe the relationship between displacement and forces in the structure. They help determine how forces affect the deformation and movement of the structure.

# Q3. Solve a 2D portal with one beam and two columns left hand is fixed and the right is hinged with and UDL of 50KN/m. the top left joint has a horizontal force of 200KN height of the frame is 5m and a span is 4m. MOI of the beam is 1.5 times that of the column grade of concrete M30. Any missing data may be assumed. solve by using the element approach and stiffness approach

## SOLUTION

### ELEMENT APPROACH
Assume that the columns are identical and have a cross-sectional area of 0.2m^2 each.

the reactions at the supports :

H_L = H_R = 200kN - 50kN/m * 4m = 100kN

V_L = 50kN/m * 4m = 200kN

V_R = 200kN - 200kN = 0kN

The bending moments and shear forces in the beam :

M_max = 50kN/m * 4m^2 / 8 = 100kNm

V_max = 50kN/m * 4m / 2 = 100kN

The bending moments and shear forces in the columns :

M_max = 200kN * 5m = 1000kNm

V_max = 200kN


Beam deflection:

Delta = 5 * M_u * L^2 / 48 * E * I


Column deflection:

Delta = P_u * L^3 / 3 * E * A


Grade M30 concrete has the following properties:

Young's modulus (E) = 30GPa,
Compressive strength (f_ck) = 30MPa


Assuming that the beam and columns are made of grade M30 concrete, the following checks can be performed:

Beam strength:

M_u = 100kNm

M_c = 0.9 * f_ck * b * d^2 / 6

Since the MOI of the beam is 1.5 times that of the column, we can assume that the beam is wider and deeper than the column. Therefore, we can assume that the beam has a width of 0.4m and a depth of 0.6m.

M_c = 0.9 * 30MPa * 0.4m * 0.6m^2 / 6 = 144kNm


Beam deflection:

Delta = 5 * 100kNm * 4m^2 / 48 * 30GPa * (0.4m * 0.6m^3) = 5.56mm

column strength:

P_u = 200kN

P_c = 0.6 * f_ck * b * d

Assuming that the columns are made of grade M30 concrete and have a cross-sectional area of 0.2m^2 each, the ultimate axial load capacity of each column is

P_c = 0.6 * 30MPa * 0.2m * 1000mm = 36kN




