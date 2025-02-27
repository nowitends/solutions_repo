# Problem 2

Let's start

![alt text](image.png)

Equation

$$
x^2+y^2=1
$$

```python
import numpy as np
import matplotlib.pyplot as plt

x = np.linspace(-1, 1, 100)
y = np.sqrt(1-x**2)

plt.plot(x, y)
plt.plot(x, -y)
plt.show()
```