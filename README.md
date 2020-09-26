# LabWork-26.09.20-
#Упражение 3 "Построение графиков"
import numpy as np
import matplotlib.pyplot as plt
%matplotlib inline
x=int(input())
x = np.arange(x)
plt.plot(np.log((1+x**2)*np.exp(-np.fabs(x)/10))/np.log(1+np.tan(1/(1+np.sin(x)**2))))
plt.show()
