# LabWork-26.09.20-
#Упражение 2 "Построение графиков"
import numpy as np
import matplotlib.pyplot as plt
%matplotlib inline
x=int(input())
x = np.arange(x)
plt.plot(x*x - x - 6)
plt.show()
