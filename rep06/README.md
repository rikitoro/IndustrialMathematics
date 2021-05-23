# How to show ryama image (Python)

````
import numpy as np
import matplotlib.pyplot as plt


org_img = np.loadtxt('./ryama.dat')


plt.figure(figsize=(12,18))
plt.imshow(org_img, "gray")
plt.show()
````
