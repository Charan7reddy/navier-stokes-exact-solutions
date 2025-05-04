# Exact Solutions of Navier-Stokes Equations
Python implementations of analytical solutions for classic fluid flows.

## **Flows Included**
1. **Plane Couette Flow**  
   - Linear velocity profile driven by moving plate.  
   - `Re = ρUh/μ` determines stability.

2. **Plane Poiseuille Flow**  
   - Parabolic profile from pressure gradient.  
   - Max velocity: `u_max = -(h²/2μ)(dp/dx)`.

3. **Hagen-Poiseuille Flow**  
   - Axisymmetric pipe flow solution.  
   - Flow rate: `Q = (πR⁴/8μ)(-dp/dz)`.

4. **Stokes' First Problem**  
   - Unsteady flow due to impulsive plate motion.  
   - Boundary layer grows as `δ ~ √(νt)`.

## **How to Run**
```bash
# Navigate to each flow's directory and execute:
python couette.py
python poiseuille.py
python hagen_poiseuille.py
python stokes.py
