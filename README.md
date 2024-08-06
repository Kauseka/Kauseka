import random
import matplotlib.pyplot as plt  # This library might need installation in some online compilers

# Generate 100 random samples between -5 and 5
signal = []
for i in range(100):
    sample = random.uniform(-5, 5)
    signal.append(sample)

# Plot the signal
plt.plot(signal)
plt.xlabel('Sample Number')
plt.ylabel('Voltage (V)')
plt.title('Random Signal')
plt.grid(True)
plt.show()
