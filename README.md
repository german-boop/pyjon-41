# pyjon-41
pyjon-41


# Simple Mathematical Diagram Example

import matplotlib.pyplot as plt  # Import matplotlib for plotting
import numpy as np  # Import numpy for mathematical operations

# Create x values from -10 to 10
x = np.linspace(-10, 10, 400)

# Define a mathematical function, e.g., quadratic
y = x ** 2  # y = x^2

# Plot the function
plt.plot(x, y, color="blue", label="y = x^2")

# Add labels and title
plt.xlabel("X-axis")
plt.ylabel("Y-axis")
plt.title("Simple Mathematical Diagram")

# Show grid
plt.grid(True)

# Show legend
plt.legend()

# Display the diagram
plt.show()
