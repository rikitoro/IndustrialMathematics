# How to show ryama image in Python environment

download ryama.dat then

````python
import numpy as np
import matplotlib.pyplot as plt


org_img = np.loadtxt('./ryama.dat')


plt.figure(figsize=(12,18))
plt.imshow(org_img, "gray")
plt.show()
````

![ryama image (1024x786)](./ryama_gray.png "ryama image (1024x786)")
