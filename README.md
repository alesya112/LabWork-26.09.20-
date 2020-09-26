# LabWork-26.09.20-
#Упражнение 6 "график функции Вейерштрасса"
import numpy as np
import matplotlib.pyplot as plt
%matplotlib inline
x=int(input())
a=int(input())
b=int(input())
n=int(input())
n=0
x = np.arange(x)
np.cos(np.pi*x*a**n)*b**n
plt.plot(np.cos(np.pi*x*a**n)*b**n)
plt.show()
