import numpy as np
import matplotlib.pyplot as plt

# Inputs
h = 0.01       # Distance between plates (m)
U = 1.0        # Top plate velocity (m/s)
mu = 0.001     # Dynamic viscosity (Pa·s)
y = np.linspace(0, h, 100)  # Position array

# Solution
u = (U / h) * y  # Linear velocity profile
tau = mu * (U / h) * np.ones_like(y)  # Constant shear stress

# Plot
plt.figure(figsize=(10, 4))
plt.subplot(1, 2, 1)
plt.plot(u, y, 'b-', linewidth=2)
plt.xlabel('Velocity (m/s)')
plt.ylabel('Height (m)')
plt.title('Velocity Profile')

plt.subplot(1, 2, 2)
plt.plot(tau, y, 'r-', linewidth=2)
plt.xlabel('Shear Stress (Pa)')
plt.title('Stress Distribution')
plt.tight_layout()
plt.show()
